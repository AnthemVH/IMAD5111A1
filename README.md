# README IMAD5111A1

## Detailed Report

### UI
The provided code for an Android app which was written in Kotlin, takes a users age as an input and returns famous people who died at similar ages. 

The UI consists of multiple elements,
- An Edit Text Field for the age input with an "age" 
- Two buttons(Clear and Generate), which are used to clear the output box and to generate the text from the calculations.
- TextView to display the historical figure that matches the age input.
- Graphical Images and a custom background to make the UI easier to understand and access.

### Code Breakdown
![onCreate](https://github.com/AnthemVH/IMAD5111A1/assets/113454977/75520022-853c-4b41-9030-1a6a7fb798f5)
The initialization and UI Setup
- The **'onCreate'** method sets up the UI elements by finding and setting up buttons, EditText and the TextView
- **'btnClear'** and **'btnGenerateText'** correspond to the Clear and Generate buttons, respectively
- **'edtText'** refers to the EditText element for age input and **'txtHistory'** is the TextView for displaying the historical figures

![btnGenerateText](https://github.com/AnthemVH/IMAD5111A1/assets/113454977/3d2d65b8-c2c6-44e8-8fb4-c3c4bd0c455c)
GenerateText Button Click Listener
- When the Generate button is clicked the listener is triggered
- It fetches the age input from the EditText field and checks if its a valid integer
- If the age is not valid, it notifies the user to enter a number. Otherwise, it proceeds to process the age Input

![AgeCheck](https://github.com/AnthemVH/IMAD5111A1/assets/113454977/c42ec3e3-cb7d-4503-83a1-31bdce2f7ea8)
Age Validation and Historical Figure Selection
- Validates the age to be within the specific range(20 to 100, inclusive)
- Uses a **'when'** expression to determine the age range and assign the corresponding historical figure to **'ageRange'**.
- Updates the TextView(**'txtHistory'**)to display the age and the matched historical figure.

![btnClear](https://github.com/AnthemVH/IMAD5111A1/assets/113454977/a5c5f863-a73c-47e8-b06e-5f44babec418)

Clear Button Click Listener
- Clears the TextView(**'txtHistory'**) when the Clear button is clicked.

### Historical Figures and Age Ranges
- My app returns specific historical figures with age ranges as follows:
- Ages 20-29: Brian Jones
- Ages 30-39: Aaron Carter
- Ages 40-49: Verne Troyer
- Ages 50-59: Bob Ross
- Ages 60-69: Marie Curie
- Ages 70-75: Ray Charles
- Ages 76-79: Galileo Galilei
- Ages 80-85: Joe Flaherty
- Ages 86-89: Louis Gossett Jr.
- Ages 90-100: Nelson Mandela

### Conclusion

My provided Kotlin code demonstrates a simple Android app which takes an age input and matches it with historical figures who passed away at similar ages. It uses some basic UI elements, basic input validation, and some basic logic to associate ages with the relevant figures. This functionality can be expanded to include more historical figures, and possibly integrate it with some external API`s for a better user experience.

# Video Tutorial
https://youtu.be/vsgA0_CWVLU

### References

Pixlr(2024)(https://pixlr.com) 
- For the images in the app

ElevenLabs(2024)(https://elevenlabs.io/)
- For the voice during the video


