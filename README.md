🚀 GitForge

<div align="center">

Turn JSON Patterns Into GitHub Contribution Art

Generate custom GitHub contribution patterns, pixel art, text designs, and activity visualizations using real Git commits and configurable commit timelines.

Developed by Mrinal Kanth Padhi

🌐 Portfolio: https://mrinal-devfolio.vercel.app

🐙 GitHub: https://github.com/MinalKanth

</div>

⸻

🧠 What is GitForge?

GitForge is a lightweight Python utility that converts a visual pattern stored inside a pattern.json file into actual Git commits.

GitHub’s contribution graph is essentially a grid of days distributed across weeks. GitForge maps your pattern onto that grid and automatically creates commits for the corresponding dates.

This allows developers to:

* Create contribution art
* Experiment with Git history visualization
* Learn how contribution graphs work
* Generate custom patterns
* Build creative profile designs

The project focuses on understanding Git commit history mechanics through hands-on experimentation.

⸻

✨ Features

✅ Pattern-based contribution generation

✅ Custom text and pixel art support

✅ Year selection support

✅ Configurable commit density

✅ Real Git commit generation

✅ Private and public repository compatible

✅ Cross-platform support

✅ Lightweight Python implementation

✅ JSON-based configuration

✅ Fast execution

⸻

📸 How GitHub Contribution Graphs Work

A GitHub contribution graph is structured as:

7 Rows   → Days of the Week
52 Weeks → Columns
365 Days → One Full Year

GitForge reads your pattern and translates it into commit dates.

Each active position in the pattern becomes one or more commits on the corresponding date.

GitHub then displays those commits as contribution squares on your profile.

⸻

📂 Project Structure

GitForge/
│
├── script.py
├── pattern.json
├── info.txt
├── README.md
└── requirements.txt

⸻

🚀 Getting Started

1. Clone the Repository

git clone https://github.com/MinalKanth/GitForge.git
cd GitForge

⸻

2. Install Python

macOS

brew install python

Windows

Download and install Python:

https://www.python.org/downloads/

Verify Installation

python3 --version

Expected output:

Python 3.x.x

⸻

3. Create a GitHub Repository

Create a new repository where commits will be generated.

Example:

git init
git remote add origin <your-repository-url>

Push an initial commit:

git add .
git commit -m "Initial repository setup"
git push -u origin main

⸻

🎨 Creating a Pattern

Edit the file:

pattern.json

Example:

[
  "0 0 1 1 2 3 4",
  "1 2 3 4 5 6 7",
  "2 3 4 5 6 7 8"
]

Each value represents contribution intensity.

⸻

🎯 Contribution Density Scale

Value	Intensity
0	Empty
1	Very Light
2	Light
3	Moderate
4	Active
5	Heavy
6	Very Heavy
7	Dark Green
8	Maximum Activity

⸻

⚙️ Running GitForge

Execute:

python3 script.py

You will be prompted to enter a year:

Enter year to draw pattern ➜ 2025

GitForge will:

1. Read pattern.json
2. Calculate commit dates
3. Generate commits
4. Apply historical commit timestamps
5. Push commits to GitHub

⸻

🔥 Example Use Cases

Contribution Art

Create:

* Initials
* Logos
* Symbols
* Pixel Designs
* Text-Based Patterns

Activity Simulation

Generate:

* Natural activity patterns
* Development sprints
* Seasonal activity distributions
* Experimental contribution graphs

Learning Git Internals

Understand:

* Git history rewriting
* Commit timestamps
* Contribution tracking
* GitHub graph mechanics

⸻

🖥 Platform Support

Platform	Supported
macOS	✅
Windows	✅
Linux	✅

⸻

📈 Best Practices

For more natural-looking contribution graphs:

* Use mixed density values
* Leave some empty days
* Avoid maximum intensity everywhere
* Create uneven activity distributions
* Use realistic commit messages

This produces cleaner and more believable visual patterns.

⸻

🤝 Contributing

Contributions are welcome.

You can help by:

* Reporting bugs
* Suggesting improvements
* Optimizing performance
* Improving pattern generation
* Enhancing documentation

Fork the repository and submit a pull request.

⸻

📄 License

Released under the MIT License.

You are free to use, modify, and distribute the project.

⸻

👨‍💻 Author

Mrinal Kanth Padhi

🌐 Portfolio: https://mrinal-devfolio.vercel.app

🐙 GitHub: https://github.com/MinalKanth

⸻

<div align="center">

⭐ If GitForge helped you, consider starring the repository.

Built with Python, Git, and curiosity.

</div>