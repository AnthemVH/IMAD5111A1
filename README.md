# README IMAD5111A1

## Detailed Report

### UI
The provided code for an android app which was written in Kotlin, takes a users age as an input and returns famous people who died at similar ages. 

The UI consists of multiple elements,
- An Edit Text Field for the age input with an "age" hint
- Two buttons(Clear and Generate), which are used to clear the output box and to generate the text from the calculations.
- TextView to display the historical figure that matches the age input.
- Graphical Images and a custom background to make the UI easier to understand and access.

### Code Breakdown

The initialization and UI Setup
- The **'onCreate'** method sets up the UI elements by finding and setting up buttons, EditText and the TextView
- **'btnClear'** and **'btnGenerateText'** correspond to the Clear and Generate buttons, respectively
- **'edtText'** refers to the EditText element for age input and **'txtHistory'** is the TextView for displaying the historical figures

GenerateText Button Click Listener
- When the Generate button is clicked the listener is triggered
- It fetches the age input from the EditText field and checls if its a calid integer
- If the age is not valid, it notifies the user to enter a number. Otherwise it proceeds to process the age Input

Age Validation and Historical Figure Selection
- Validates the age to be withing the specific range(20 to 100, inclusive)
- Uses a **'when'** expression to determine the age range and assign the corresponding historical figure to **'ageRange'**.
- Updates the TextView(**'txtHistory'**)to display the age and the matched historical figure.

Clear Button Click Listener
- Clears the TextView(**'txtHistory'**) when the Clear button is clicked.

### Historical Figures and Age Ranges
-My app returns specific historical figures with age ranges as follows:
-Ages 20-29: Brian Jones
-Ages 30-39: Aaron Carter
-Ages 40-49: Verne Troyer
-Ages 50-59: Bob Ross
-Ages 60-69: Marie Curie
-Ages 70-75: Ray Charles
-Ages 76-79: Galileo Galilei
-Ages 80-85: Joe Flaherty
-Ages 86-89: Louis Gossett Jr.
-Ages 90-100: Nelson Mandela

### Conclusion

My provided Kotlin code demonstrates a simple Android app which takes an age input and matches it with historical figures who passed away at similar ages. It uses some basic UI elements, basic input validation, and some basic logic to associate ages with the relevant figures. This functionality can be expanded to include more historical figures, and possibly integrate it with some external API`s for a better user experience.


