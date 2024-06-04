

<h1 align="center">SecureSurf</h1>
<p align="center">
  <img src="https://github.com/MrGovindDubey/SecureSurf/assets/118271775/b47775d8-2a35-45e2-b624-78fef1b0418f" alt="Alt Text" width="500"\>
</p>



 SecureSurf fortifies your online security by meticulously scanning URLs for potential threats. Receive instant alerts upon detecting malicious websites, ensuring your browsing experience is consistently secure and protected.




## Features

- **Real-time URL Scanning**: Automatically scans the current URL for potential threats .
- **API Key Management**: Supports multiple API keys with automatic rotation to avoid hitting API rate limits.
- **Threat Detection Alerts**: Displays warning messages and modals when a threat is detected, with detailed information about the detection.
- **Customizable Threshold**: Allows users to set a threshold for the number of detections that trigger alerts.

## Installation

1. **Install a UserScript Manager**:
   - [Tampermonkey](https://www.tampermonkey.net/)
   - [Greasemonkey](https://www.greasespot.net/)
   - [Violentmonkey](https://violentmonkey.github.io/)

2. **Install SecureSurf**:
   - Open your UserScript manager and create a new script.
   - Copy and paste the contents of the `SecureSurf.user.js` file into the script editor (Fork) .
   - Save the script.

## Usage

Once installed, SecureSurf will automatically run on all websites you visit. It will scan the current URL and provide real-time alerts if any threats are detected.

## Setup:
### Obtaining API Key

1. Go to the [VirusTotal](https://www.virustotal.com/) website.
2. Sign up for a free account if you don't already have one.
3. After logging in, navigate to your profile settings.
4. Locate the API Key section. Here you will find your personal API key.
5. Copy the API key.

## Setup

1. Open the `SecureSurf.js` file in a text editor.
2. Locate the following section in the script:
   ```javascript
   const apiKeys = [
       'API_KEY_1',       
       // 'API_KEY_2'
       // 'API_KEY_3'
       // 'API_KEY_4'
   ];
   ```
3. Replace 'API_KEY_1' with the API key you copied from VirusTotal.
4. Save the changes to the SecureSurf.js file.


### Configuration (Optional)
Threshold: The default threshold for displaying the warning modal is set to 5. You can change this value by modifying the threshold variable in the script.


## Contributing
Contributions are welcome! Please open an issue or submit a pull request on GitHub.

## License
This project is licensed under the MIT License. See the LICENSE file for details.


## Author

SecureSurf is developed by [Mr Govind Dubey](https://www.linkedin.com/in/mr-govind-dubey/). Don't forget to star 🌟 the repository if you find it useful!


### Enhance your online security with SecureSurf. Stay safe!
<p align="center">
  <img src="https://github.com/MrGovindDubey/SecureSurf/assets/118271775/b3fa470f-1577-4840-b878-e2376a3c10a4" alt="Alt Text" width="300"\>
</p>



