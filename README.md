# Web-Environment-Integrity-Blocker

The Web-Environment-Integrity-Blocker is a simple UserScript designed to protect your privacy online. This script blocks any website that uses Web Environment Integrity (WEI), a technology that could potentially breach your privacy.

For more information about why WEI is considered harmful, [click here](https://www.fsf.org/blogs/community/web-environment-integrity-is-an-all-out-attack-on-the-free-internet).

The Web-Environment-Integrity-Blocker script checks all properties on the window object of a page for the `getEnvironmentIntegrity` method. If this method is found, it indicates that the website is using WEI. My FE knowledge is limited, please [submit a PR](https://github.com/groundcat/Web-Environment-Integrity-Blocker/pulls) if you have any better approaches!

## Features

* Blocks websites using WEI
* Displays a warning message if WEI is detected
* Halts further execution of scripts on the page

## Installation

1. To use this UserScript, you need to have a UserScript manager installed in your browser (like [Tampermonkey](https://www.tampermonkey.net/) or [Violentmonkey](https://violentmonkey.github.io/)).
2. [Install](https://greasyfork.org/en/scripts/472234-web-environment-integrity-blocker) the script.
3. After installing, the script will automatically run on all websites.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details
