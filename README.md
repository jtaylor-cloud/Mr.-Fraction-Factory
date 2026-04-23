🏭 Mr. Fraction's Factory
An interactive, self-contained web application for middle school students to explore, practice, and master fractions — guided by Mr. Fraction himself.

What It Is
Mr. Fraction's Factory is a single HTML file that runs entirely in any web browser with no installation, no internet connection required after loading, and no external dependencies. Every image, font reference, and tool is embedded directly in the file.
The app is designed to be dyslexia-friendly — using Atkinson Hyperlegible as the primary font, a warm cream background, high-contrast colours, large readable text, and visual representations alongside every concept.

How to Use

Download index.html
Open it in any modern web browser (Chrome, Edge, Firefox, Safari)
That's it — no server, no setup, no login required

To host it for students, upload the single index.html file to any web host, Google Drive (share as link), OneDrive, or a school LMS. Nothing else is needed.

The Four Stations
📖 Station 01 — What Are Fractions? (Lesson)
An 8-step interactive lesson that walks students through fraction fundamentals from scratch.

Interactive pizza model — click to eat slices and watch the fraction change in real time
Fraction types explorer — tap cards to reveal proper fractions, improper fractions, and mixed numbers with explanations
Equivalent fractions table — use a slider to multiply a fraction and see the pattern build
Comparison tool — two side-by-side bar models with sliders to compare any two fractions visually
Number line — drag a slider to place any fraction on a number line between 0 and 10
Real-world matching game — match everyday scenarios (pizza slices, clock time, basketball shots) to their fraction
Built-in quizzes — multiple-choice questions at key steps with instant feedback

🔧 Station 02 — Simplify Fractions
Students enter any fraction and see it simplified step by step.

Step-by-step Euclidean algorithm — every division step shown with remainders
GCF verification — confirms the Greatest Common Factor divides evenly into both parts
Division walkthrough — visual breakdown of dividing numerator and denominator by the GCF
Circle model — pie chart visuals comparing the original and simplified fraction
Bar model — segmented bar visuals for both fractions side by side
Random fraction button — generates a random unsimplified fraction instantly
"Already simplified" detection — tells students when GCF = 1 and no simplification is needed

⚙️ Station 03 — Fraction Operations
A visual manipulative tool for adding, subtracting, multiplying, and dividing fractions.

Rectangle builders — students use sliders to set the number of rectangles and cuts, then click cells to select a fraction
Four operations — add (+), subtract (−), multiply (×), divide (÷)
LCD guidance — when adding or subtracting, the tool detects mismatched denominators, calculates the GCF and LCD, and prompts students to align them before solving
Colour-coded results — each operation uses distinct colours to show which parts of the result came from which fraction
Grid model for multiplication — overlapping rows and columns show the product as an intersection area
Division grouping arrows — animated arrows show how many times Fraction B fits inside Fraction A

🔄 Station 04 — Convert Fractions
A live converter that links fractions, decimals, and percentages — change any one and all three update instantly.

Fraction inputs — numerator and denominator number fields
Decimal slider and input — values from 0 to 10, synced to the fraction
Percentage slider and input — 0% to 1000%, synced to the fraction
Pie chart model — circle divided into slices matching the denominator
Number line — shows the decimal value on a segmented line, with overflow rows for values over 10
Percentage bar — fills a rectangle proportionally, with overflow rows for values over 100%
Reset button — returns everything to 3/4 as a clean starting point


Mr. Fraction — Your Guide
Mr. Fraction is a cartoon character who appears throughout the app as a floating guide in the bottom-right corner of every station. He:

Greets students when they enter each station with station-specific dialogue
Reacts to interactions — correct quiz answers, wrong answers, simplifying fractions, clicking the pizza, switching tabs, changing the converter, solving operations
Changes pose depending on the station — climbing a ladder in the Lesson, facing sideways in the Simplifier, front-facing in Operations
Can be dismissed by clicking him — he'll stay quiet for 8 seconds before responding again
Speaks again if clicked when silent — he'll offer an encouragement or hint

The animated GIF version of Mr. Fraction appears on the loading screen.

Loading Screen
When the app first opens, a factory-themed loading screen plays for approximately 3 seconds:

Animated spinning gears in the corners
Mr. Fraction's animated GIF bouncing in the centre
A progress bar with cycling status messages
A scrolling conveyor belt at the bottom


Technical Notes
PropertyDetailFile typeSingle .html fileFile size~4.3 MB (all images embedded as base64)DependenciesNone — fully self-containedFontsAtkinson Hyperlegible, Bebas Neue (loaded from Google Fonts — requires internet on first load; cached after)Browser supportAll modern browsers (Chrome 80+, Firefox 75+, Safari 13+, Edge 80+)MobileResponsive — works on tablets and phones
To make it fully offline
The only external dependency is Google Fonts. To remove it, open the file in a text editor, find the <link> tag near the top that references fonts.googleapis.com, and replace it with locally-hosted font files. Everything else already works offline.

Images
All images in the app are of Mr. Fraction — a cartoon character created for this project — along with prop images (pizza, pie, gear). They are embedded directly in the HTML as base64-encoded PNG data, so no separate image files are needed.

Accessibility

Atkinson Hyperlegible font — designed specifically for readers with dyslexia and low vision
Cream background (#f5eed8) — reduces visual stress compared to pure white
High contrast text — dark brown on cream throughout
Large font sizes — 18px base with generous line height
Keyboard support — Enter key triggers simplification in the Simplifier station
No time limits — students can work at their own pace


Credits
Character design: Mr. Fraction — original cartoon character
Educational content: Aligned with middle school fraction curriculum
Built with: HTML, CSS, JavaScript — no frameworks or libraries
Font: Atkinson Hyperlegible by the Braille Institute
Display font: Bebas Neue
