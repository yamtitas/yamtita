SEND 'Please enter the temperture." TO DISPLAY
RECEIVE temperature FROM KEYBOARD
IF temperature < 18°C THEN
  SEND 'Cold, the perfect temperature for sleep is 18-21 degrees.' TO DISPLAY
ELSE
  IF temperature > 21°C THEN
    SEND 'Perfect' TO DISPLAY
  ELSE
    SEND 'No!, the perfect temperature for sleep is 18-21 degrees.' TO DISPLAY 
  END IF
END IF
