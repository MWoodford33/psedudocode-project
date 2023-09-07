START 
//begin the prgram

INIT()
  fill kettle with desiredamount.water
  put kettle on selected stove burner
  turn knob to turn on selected stove burner
  take lid off french press
  add 2 scoops coffee1 and coffee2 to french press
  add 3 dashes cinnamon to french press
  if kettle whistling add water to french press
  put lid on french press
  press handle of french press lid down 50% length of french press
  set timer to 4 minutes
  when timer goes off 

// objects

Stove
  has knobs with array of temps to set burner to
  has set of burners that heat up when knob is turned
  has display with array of function buttons
   INIT()
    displays timer 
    heats kettle of water

Kettle
  holds amount of fl ounces = number of cups of coffee desired
  heats water while atop burner
   INIT()
    whistles when water is ready (ready is nearly boiling)

French Press
  holds scoops of coffee grounds
  hold dashes of cinnamon 
  steeps coffee grounds in nearly boilng water

French Press Lid
  has handle mechanism on top
   INIT()
    when top handle is pressed down seperates coffee grounds from coffee

Second Receptical
  holds liquid from french press after steeping for 4 minutes so coffee isn't bitter
    IF desiredamount.coffee is hot use thermous
      ELSE IF use glass jar > 64 fl oz

coffee1
  holds ground espresso beans
  is cafe bustello

coffee2 
  holds whole coffee beans to be ground
  is starbucks french roast

coffeeSwill
  holds inferior ground coffee, use if coffee1 or coffee2 are unavailable
  is any brand

scoops 
  is 2 tablespoons

scoop
  removes coffee from receptical

Grinder
  IF button is depressed grinds whole beans into coarse ground coffee

Person
  INIT
    turns knob on stove to heat burner
    fills kettle with desiredamount.water
    put kettle on stove
    scoop whole beans into grinder
    depress button to grind coffee beans to coarse ground (coffee1)
    IF enough add 2 scoops coffee1 and 2 scoops coffee2 into french press
        ELSE IF add 4 scoops coffee2 into french press
        ELSE IF add 4 scoops of coffeeSwill into french press
    add desiredmount.cinnamon to french press
    if kettle is whistiling remove from stove
    add water from kettle to french press = desiredamount.coffee
    set timer for 4 minutes and let coffee steep
    pour contents of french press into second receptical after 4 minutes so coffee does not 
     become bitter
    enjoys coffee
    
desiredamount.coffee is 8 cups

desiredamount.water is 64 fl ounces

desiredamount.cinnamon is 3 dashes 

dash is the amount of cinnamon that comes out when receptical is turned upside down and shaken





  
  
