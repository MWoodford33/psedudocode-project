START

INIT()
//initialize objects and variables

FILL_KETTLE(desiredamount.water)
//fill the kettle with the desired amount of water

HEAT_KETTLE()
//heat kettle until it whistles

PREPARE_FRENCH_PRESS
//add coffee1, coffee2, and cinnamon

IF (kettle is whistling) THEN
  ADD_WATER_TO_FRENCH-PRESS(desiredamount.coffee)
//add hot water to your french press

PUT_LID_ON_FRENCH_PRESS()
//put the lid on your french press

SET_TIMER(4 minutes)
//set a timer for 4 minutes

WHEN_TIMER_GOES_OFF()
//wait for timer to go off

PRESS_FRENCH_PRESS_LID(down)
//press down on french press lid handle to seperate grounds from coffee

POUR_FIRST_CUP_COFFEE
//into chosen coffee cup

TRANSFER_COFFEE_TO_SECOND_RECEPTICAL()
//transfer the remaining coffee into a seperate receptical so it doesn't become bitter

IF (remainingamount.coffee is desired.hot)
    USE_THERMOUS()
    //use thermous if you want remaining coffee to stay hot
ELSE IF (remainingamount.coffee is desire.tepid use glass jar >64 fl ounces)
    USE-GLASS-JAR()
    //use glass jar if you want remaining coffee to become tepid

ENJOY_COFFEE
//if you bad then drink it black, otherwise add milk and sugar
  
END