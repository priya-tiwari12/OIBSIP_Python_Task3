# OIBSIP_webdevlopment_Task3
📖 Objective
The goal of this project is to create a user‑friendly temperature converter web page using pure HTML, CSS, and JavaScript. It enables users to input a temperature and convert it seamlessly between Celsius, Fahrenheit, and Kelvin.

🔧 Tools & Technologies Used

HTML: Defines the structure of the page (input field, dropdown, button, and result display).

CSS: Styles the page for a clean, readable layout (fonts, spacing, block elements).

JavaScript (vanilla): Implements core logic to parse user input, perform unit conversions, and update the display dynamically.

🚀 Steps Performed

Page Structure (HTML)

Added an <input type="number"> for temperature entry.

Added a <select> dropdown letting users choose the source unit: Celsius, Fahrenheit, or Kelvin.

Added a button that triggers convertTemperature() on click.

Included a <div> with id="result" to show the converted values.

Styling (CSS)

Applied a readable Arial font, centralized 50px margin, and max width of 400px for readability.

Ensured form elements (label, select, input, button) are stacked and full-width for a clean mobile-friendly UI.

Styled the output .result div with bold, larger font for emphasis.

Conversion Logic (JavaScript)

Fetch & validate input: Read temperature and unit, use parseFloat() to convert input string to a number, and check for NaN.

Declare intermediate variables: c, f, k for Celsius, Fahrenheit, Kelvin values.

Switch logic based on selected unit:

Celsius → Fahrenheit & Kelvin

𝐹
=
(
C
×
9
/
5
)
+
32
,
𝐾
=
C
+
273.15
F=(C×9/5)+32,K=C+273.15
Fahrenheit → Celsius & Kelvin

𝐶
=
(
𝐹
−
32
)
×
5
/
9
,
𝐾
=
𝐶
+
273.15
C=(F−32)×5/9,K=C+273.15
Kelvin → Celsius & Fahrenheit

𝐶
=
𝐾
−
273.15
,
𝐹
=
(
𝐶
×
9
/
5
)
+
32
C=K−273.15,F=(C×9/5)+32
Display: Inject the results into the .result div using template literals and format numeric values to two decimal places using .toFixed(2).

✅ Outcome
This web app empowers users to effortlessly convert temperatures across three units with instant feedback. It showcases:

Efficient handling of user input validation

Clear conversion math

Dynamic DOM manipulation—all packaged in a clean UI.

It’s a practical example of how HTML, CSS, and JavaScript work together to build interactive, real‑world utilities.

my code link is:-https://www.linkedin.com/posts/priya-tiwari-bb86b7365_webdevelopment-html-javascript-activity-7349417801570230272-WDbH?utm_source=share&utm_medium=member_android&rcm=ACoAAFqxyPwBicuDiH0INFhdt_h3ZyCSZ_Z-E8s
