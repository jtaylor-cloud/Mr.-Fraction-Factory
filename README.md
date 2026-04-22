🏭 Mr. Fraction's Factory
An interactive fractions website for middle school students, built as a single HTML file with a factory theme. Designed to be dyslexia-friendly using the Atkinson Hyperlegible font with high contrast, generous spacing, and clear visual explanations.

📁 File Structure
Your repository should look exactly like this:
your-repo/
├── index.html
├── README.md
├── Gear.png
├── Pizza.png
├── Pie.png
├── Mr__Fraction_Front.png
├── Mr__Fraction_Back.png
├── Mr__Fraction_Left_Side.png
├── Mr__Fraction_Right_Side.png
├── Mr__Fraction_Ladder.png
└── Mr__Fraction_GIF.png

⚠️ All image files must be in the same folder as index.html. The names are case-sensitive — do not rename them.


🚀 Hosting on GitHub Pages
Step 1 — Create a GitHub Repository

Go to github.com and sign in
Click the + button (top right) → New repository
Give it a name, e.g. mr-fractions-factory
Set it to Public
Click Create repository

Step 2 — Upload Your Files

On your new repository page, click Add file → Upload files
Drag and drop ALL files into the upload area:

index.html
README.md
All 9 PNG image files


Scroll down, add a commit message like Initial upload, and click Commit changes

Step 3 — Enable GitHub Pages

Go to your repository's Settings tab
In the left sidebar, click Pages
Under Source, select Deploy from a branch
Set the branch to main and the folder to / (root)
Click Save

Step 4 — Get Your URL
GitHub will show you a URL like:
https://your-username.github.io/mr-fractions-factory/
It may take 1–2 minutes to go live after the first deploy. Refresh the Pages settings screen until you see the green "Your site is published" banner.

🖥️ Testing Locally (Before Uploading)
You cannot just double-click index.html — browsers block local images for security reasons. Use one of these options instead:
Option A — VS Code Live Server (Recommended)

Install VS Code
Install the Live Server extension (search in the Extensions panel)
Open your project folder in VS Code
Right-click index.html → Open with Live Server
Your browser will open automatically at http://localhost:5500

Option B — Python (Mac / Linux)
Open Terminal in your project folder and run:
bashpython -m http.server 8000
Then go to http://localhost:8000 in your browser.
Option C — Python (Windows)
Open Command Prompt in your project folder and run:
bashpython -m http.server 8000
Then go to http://localhost:8000 in your browser.

📚 What's Inside
StationDescription🏠 Landing PageModule selection with Mr. Fraction and the factory theme📖 Station 01 — Lesson8 interactive steps covering fraction basics, types, equivalence, comparing, and real-life uses. Includes quizzes and clickable activities.🔧 Station 02 — SimplifyEnter any fraction to see step-by-step GCF calculation with pie chart and bar model visuals⚙️ Station 03 — OperateAdd, subtract, multiply, and divide fractions using visual rectangle builders🔄 Station 04 — ConvertExplore how fractions, decimals, and percentages represent the same value

♿ Accessibility & Dyslexia-Friendly Design

Atkinson Hyperlegible font throughout — designed specifically for low-vision and dyslexic readers
Minimum 18px body text
High contrast dark theme with warm off-white text (no pure white on dark)
Extra line spacing (1.7)
No italics used for instructions
Large, clearly labelled buttons
Visual representations alongside every mathematical concept


🌐 Moving to Another Platform
The site is a single self-contained HTML file. To move it to any other hosting platform (Netlify, Vercel, a school server, etc.):

Upload index.html and all PNG files to the new platform
Keep all files in the same directory
Make sure index.html is set as the entry point

No build tools, no dependencies, no server-side code required.

🛠️ Dependencies
All loaded from CDN — no installation needed:

Atkinson Hyperlegible — Google Fonts
Bebas Neue — Google Fonts (display headings)


📡 An internet connection is required to load the fonts. If hosting in an offline environment, download the fonts and update the <link> tag in index.html to point to local copies.


👨‍🏫 For Teachers

No login or accounts required
Works on tablets and desktops
Students can use it independently or alongside classroom instruction
Each station is self-contained — you can assign specific stations without students needing to complete others first
