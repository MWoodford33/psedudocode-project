START

INIT()
//initialize objects and variables

FILL_KETTLE(desiredamount.water)
//fill the kettle with the desired amount of water

HEAT_KETTLE()


PREPARE_FRENCH_PRESS


IF (kettle is whistling) THEN
  ADD_WATER_TO_FRENCH-PRESS(desiredamount.coffee)


PUT_LID_ON_FRENCH_PRESS()


SET_TIMER(4 minutes)


WHEN_TIMER_GOES_OFF()


PRESS_FRENCH_PRESS_LID()


POUR_FIRST_CUP_COFFEE


TRANSFER_COFFEE_TO_SECOND_RECEPTICAL()


IF (remainingamount.coffee is desired.hot)
    USE_THERMOUS()
ELSE IF (remainingamount.coffee is desire.tepid use glass jar >64 fl ounces)
    USE-GLASS-JAR()

ENJOY_COFFEE

END