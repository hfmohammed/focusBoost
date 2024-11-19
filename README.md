
<a name=top></a>
## NATHACKS
## FocusBoost

![Focus Boost](https://raw.githubusercontent.com/your-username/your-repo/main/path-to-gif.gif)
![focusBoost (1)](https://github.com/user-attachments/assets/12a56211-5150-4627-b854-dec5d208a1f4)

See our devpost [FocusBoost](https://devpost.com/software/neuro-stress-monitor)
Check out the demo on youtube [FocusBoost](https://youtu.be/1BXJl57HUnk?si=Ltc4ndslZQM0E7aO)

## 📑 Summary

**FocusBoost** 

**FocusBoost** is a real-time focus detection tool that uses the BioAmp EXG Pill and Arduino to capture brain signals and notify the user when they are focused in an Electron-based application that monitors your focus levels in real-time using data from an Arduino. The application provides notifications and motivational alerts to help you maintain focus and productivity and over a chromium software (for practical example like watching a youtube short). 




## ✨ About
- **Brain wave monitoring** Detects brain waves using BioAmp EXG Pill
- **Filtering for stress** Filters EXG signals into brain wave frequency region (0-50 Hz)
- **Notifications** when filtered signals exit beta frequency range (14-40 Hz).
- **Sound alerts** for real-time focus warnings.




## 📷 Screenshots
![alt text](src/eeg-image.png)
![alt text](src/focusboost.png)


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

* Bioamp EXG pill for biosignal capture
* Arduino board

# FILE STRUCTURE
```
Neuro-focus-Monitor/
├── __pycache__
│   ├── __pycache__/stress_monitor.cpython-312.pyc
├── .vscode
│   ├── settings.json
├── ARDUINO
│   ├── ARDUINO.ino
├── my-electron-app/               # Main Electron app directory
│   ├── public/                    # Static files for React (used in Electron frontend)
│   │   ├── favicon.ico
│   │   ├── index.html             # Entry point for the Electron-rendered React app
│   │   ├── logo192.png
│   │   ├── logo512.png
│   │   ├── manifest.json          # Metadata for web app (optional for PWA)
│   │   └── robots.txt
│   ├── src/                       # Source files for React app
│   │   ├── App.css
│   │   ├── App.js                 # React app main component
│   │   ├── App.test.js
│   │   ├── index.css
│   │   ├── index.js               # React app entry point
│   │   ├── logo.svg
│   │   ├── reportWebVitals.js     # Optional for performance tracking
│   │   └── setupTests.js          # Optional for React tests
│   ├── main.js                    # Electron main process script
│   ├── package.json               # Dependencies and scripts for Electron app
│   ├── README.md                  # Electron app-specific documentation
│   └── node_modules/              # Dependencies (git ignored)
├── renderer/                  # Electron renderer process
│   ├── alert.mp3              # Sound file for alerts
│   ├── file.txt               # File tracking focus state
│   ├── index.html             # Electron-rendered HTML
│   ├── preload.js             # Preload script for IPC communication
│   ├── renederer.js           # Main script for Electron renderer logic
│   └── styles.css   
├── src/                           # General assets used across the project
│   ├── eeg-image.png              # EEG visualization
│   ├── focusBoost.mp4             # Background video for the app
│   ├── tk-image.png               # Icon for TikTok functionality
│   └── yt-image.png               # Icon for YouTube functionality
├── venv/                          # Python virtual environment (should be git ignored)
├── .gitignore                     # Ignore unnecessary files (e.g., __pycache__, node_modules)
├── README.md                      # General project documentation
├── chromedriver                   # ChromeDriver executable (permission adjusted)
├── chromedriver.exe               # Windows ChromeDriver executable
├── main.js                        # Main Electron process for legacy setup (if needed)
├── package.json                   # Legacy Electron dependencies and scripts (if needed)
├── requirements.txt               # Python dependencies
├── stress_monitor.py              # Python script for monitoring stress
├── tiktok-nav.py                  # TikTok navigation automation script
└── youtube-nav.py                 # YouTube navigation automation script

```
## Code execution guide
```
pip install -r requirements.txt
python stress_monitor.py
npm start

```
Make sure you’ve downloaded ChromeDriver:
*  Go [to ChromeDriver](https://developer.chrome.com/docs/chromedriver/downloads) Downloads.
*  Download the version that matches your Chrome browser version (check chrome://settings/help in Chrome for the version).
*  Extract the ChromeDriver executable.


## 📰 Notes

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)

* Use your own branch and pull request to main

## References

* BioAmp EXG Pill Documentation (https://github.com/upsidedownlabs/BioAmp-EXG-Pill)
* Serial communication between Python and Arduino (https://projecthub.arduino.cc/ansh2919/serial-communication-between-python-and-arduino-663756)


[🔝 Back to Top](#top)
