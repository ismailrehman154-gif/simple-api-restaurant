# Recommended Meals

Enter a max calorie count and it finds recipes that fit, with macros and a photo for each. Hit "something else" to cycle through the results.

![Recommended Meals screenshot](screenshot.jpg)

Two fiddly bits: the API ignores you unless the key rides along in the headers, and the switch button has to wrap the index back to zero at the end of the list, or it tries to display a meal that doesn't exist.

Spoonacular API, vanilla JavaScript. My code is on the `answer` branch.
