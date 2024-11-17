
<a name=top></a>
## NATHACKS
# # Focus Boost


See our devpost [FocusBoost](https://devpost.com/software/neuro-stress-monitor)

## 📑 Summary

**FocusBoost** 

**FocusBoost** is a real-time focus detection tool that uses the BioAmp EXG Pill and Arduino to capture brain signals and notify the user when they are focused in an Electron-based application, and chromium (for practical example like watching a youtube short).



## ✨ About
- **Brain wave monitoring** Detects brain waves using BioAmp EXG Pill
- **Filtering for stress** Filters EXG signals into brain wave frequency region (0-50 Hz)
- **Notifications** when filtered signals exit beta frequency range (14-40 Hz).
- **Sound alerts** for real-time focus warnings.




## 📷 Screenshots



## Development Timeline
### November 14
- **Daksh, and Hasan**
  - Started laying the groundwork for the project
### November 15
- **Hasan**
  - Implemented barebones feature of the youtube selenium script to autoskip videos (Next step is to implement exg pill data for the skipping
- **Daksh**
  - Set up the elctron app by creating the renderer files: index(html/js), preload.js, styles.css. Also updated the package.json file and cleaned up other files
  - Dealt with troubleshooting and refinements, fixed GPU crashes through disabling GPU rendering. Debugged other issues so that the window would open properly. Resolved through developing a gitignore file. 
  - Tested window using mock data, used to test real-time visualization of the app. Refined the chart code for better visuals. 
  - Improved other aspects of the project like helping with the arduino data processing, communicating aspects with teamates, cleaned and set up README.md with better setup instructions, and developed how to prompt notifications.

## November 16
- **Hasan**
  - Implemented reading exg pill data to display notifications on chromium, decided by being focused or unfocused, and closing the page if the person remains unfocused


## 🔨 Tools

### Software

This project is built using the following tools and frameworks:

* [GitHub](https://www.github.com) - Version control and project management.
* [Node.js](https://nodejs.org/) - Runs JavaScript in real-time on web app
* [Chart.js](https://www.chartjs.org/) - For real-time charting and data visualization.
* [Electron.js](https://www.electronjs.org/) - For cross-platform desktop app development.
* [Arduino IDE](https://www.arduino.cc/) - For coding and uploading firmware to the Arduino.
* [Chromedriver](https://developer.chrome.com/docs/chromedriver/) - For chromium for youtube/tiktok functionalities

### Python Libraries

The project uses the following Python libraries. Install them using `pip install` or include them in your `requirements.txt` file:

* `selenium>=4.0.0` - For automated testing and interaction simulation.
* `serial



### Hardware

* Bioamp EXG pill
* Arduino

# FILE STRUCTURE
```
Neuro-focus-Monitor/
├──.gitignore
├── .env                # Environment variables (API keys, secrets, etc.)
├── stress_monitor.py   # Main Python script for monitoring focus
├── README.md           # Documentation for the project
├── requirements.txt    # Python dependencies for the backend
├── database.py         # Database management logic
├── backend/            # Backend Python module
│   ├── __init__.py     # Initializes the backend module
|   ├── backend.py      # Core backend logic
├── main.js               # Entry point for the Electron app
├── renderer/             # Renderer process for the Electron app
│   ├── index.html        # Frontend for the Electron app
    ├── styles.css
    ├── preload.js        # Preload script for secure communication
│   └── index.js         # Script to handle real-time visualization
├── package.json          # Node.js configuration and dependencies
├── package-lock.json     # Locked Node.js dependencies
└── node_modules/         # Installed Node.js packages (generated by npm)

```
## Code execution guide
```
pip install -r requirements.txt
python stress_monitor.py
npm start
python3 youtube-nav.py (for now it this is the command)
npm install dotenv

```
Make sure you’ve downloaded ChromeDriver:
*  Go [to ChromeDriver](https://developer.chrome.com/docs/chromedriver/downloads) Downloads.
*  Download the version that matches your Chrome browser version (check chrome://settings/help in Chrome for the version).
*  Extract the ChromeDriver executable.

## 👨‍👧‍👧 Team

<!--- put your links here --->

* [Avery Bettesworth](https://github.com/Betts6430) - Computer engineer
* [Daksh Sethi](https://github.com/daksh3333) - Software engineer
* [Hasan Khan](https://osu.github.io/portfolio/) - Computer Scientist and Psychologist 
* [Hassan Farooq Mohammed ](https://github.com/osu) - Computer Scientist
* [Tatjana Golovin] - Neuro Scientist
* [Varinder Singh] - Psychologist


## 📰 Notes

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)

* Use your own branch and pull request to main

[🔝 Back to Top](#top)
