# SecureSurf
 SecureSurf fortifies your online security by meticulously scanning URLs for potential threats. Receive instant alerts upon detecting malicious websites, ensuring your browsing experience is consistently secure and protected.



## Features

- **Real-time URL Scanning**: Automatically scans the current URL for potential threats using VirusTotal API.
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
   - Copy and paste the contents of the `SecureSurf.user.js` file into the script editor.
   - Save the script.

## Usage

Once installed, SecureSurf will automatically run on all websites you visit. It will scan the current URL and provide real-time alerts if any threats are detected.

## Configuration

### Setting the Threshold

You can set the threshold for the number of detections that trigger alerts. The default threshold is 5.

To change the threshold:
1. Open the UserScript manager.
2. Find the SecureSurf script.
3. Modify the line `const threshold = GM_getValue('threshold', 5);` to your desired value.

### Adding API Keys

To add more API keys:
1. Open the UserScript manager.
2. Find the SecureSurf script.
3. Add your API keys to the `apiKeys` array:

```javascript
const apiKeys = [
    'YOUR_API_KEY_1',
    'YOUR_API_KEY_2',
    'YOUR_API_KEY_3',
    // Add more API keys as needed
];

```

## Contributing
Contributions are welcome! Please open an issue or submit a pull request on GitHub.

## License
This project is licensed under the MIT License. See the LICENSE file for details.

## Author
SecureSurf is developed by Mr Govind Dubey.
