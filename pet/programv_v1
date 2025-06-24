// Область кода

FOR i := 1 TO c_iMeasurePointsCount DO

   astMeasurePoints[i].xAlarm := IsValueOutOfLimits(astMeasurePoints[i].rValue, 
      astMeasurePointsMemData[i].rLowAlarmValue, astMeasurePointsMemData[i].rHighAlarmValue);

   astMeasurePointsMemData[i].fbAlarmCounter(CU := astMeasurePoints[i].xAlarm);
		
   astMeasurePoints[i].wsStatus := Mx210Assistant.ANALOG_SENSOR_ERROR_TO_WSTRING(astMeasurePoints[i].eStatus);

END_FOR
