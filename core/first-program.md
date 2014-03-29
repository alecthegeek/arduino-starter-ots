---

layout: ots
title: Your first Arduino program

---

# Working at the IDE

1. Open the IDE on your personal computer
2. Use the IDE meu to open `File`->`Examples`->`01.Basics`->`Bklink`


You should now have a new window open with the blink program source code

3. Use the upload button to make sure you can compile and load it into the Arduino

If you look at the program code you can see a distinct structure to the way the code is orderd

`int led = 13;`

This line sets up an alias `led` to refer to the number 13. As each input or ouput pin on the Arduino
is referred by only a number it can be quite confusing trying to remember which pin is which.
By creating a name, like `led` we can make it a lot less confusing.
Even better is that if we move the LED device to a different connection pin on the board we
only need to remember to change one line of code. This can save a LOT of mistakes!

`void setup() {
  // initialize the digital pin as an output.
  pinMode(led, OUTPUT);
}`

Every sketch has to have a setup function. It is responsible for setting up the board into the correct configuration
before we start doing anything. In this case it sets the pin to output mode.

Next we have the main part of the program

'// the loop routine runs over and over again forever:
void loop() {
  digitalWrite(led, HIGH);   // turn the LED on (HIGH is the voltage level)
  delay(1000);               // wait for a second
  digitalWrite(led, LOW);    // turn the LED off by making the voltage LOW
  delay(1000);               // wait for a second
}'

This must be a function called loop which does one cycle of our program. This will be repeated until the head death of the universe or occurs,
or the Arduino loses power, or a new program is loaded (whichever comes first).


