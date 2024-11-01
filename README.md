# Ilios Dark Mode

[![Install directly with Stylus](https://img.shields.io/badge/Install%20directly%20with-Stylus-00adad.svg)](https://raw.githubusercontent.com/HyperKids/ilios-dark-mode/refs/heads/main/index.user.css) [![Install directly with Arc Boosts](https://img.shields.io/badge/Install%20directly%20with-Arc%20Boosts-F85068)](https://arc.net/boost/8157134F-66F1-4827-A5A5-9930AE1A76BB) [![License: MIT](https://img.shields.io/badge/License-MIT-lightgrey.svg?longCache=true)](LICENSE.md)

This is a custom dark mode theme for the [Ilios Curriculum Management System](https://github.com/ilios/ilios) platform, intended for use at UCSF.

## Installation

To use this file, inject it into `curriculum.ucsf.edu` with a browser extension, such as:

- **User Javascript and CSS (recommended):** [Chrome Web Store](https://chromewebstore.google.com/detail/user-javascript-and-css/nbhcbdghjpllgmfilhnhkllmkecfmpld)
- **Stylus:** [Chrome Web Store](https://chrome.google.com/webstore/detail/stylus/clngdbkpkpeebahjckkjfobafhncgmne) | [Firefox Add-ons](https://addons.mozilla.org/en-US/firefox/addon/styl-us/)
- **Arc Boosts:** [Arc Browser](https://arc.net/)

### Automatic Install Instructions

Automatic install is available for Stylus and Arc Boosts.

- **Stylus:** [You can use the userstyle for a faster install and automatic updates](https://raw.githubusercontent.com/HyperKids/ilios-dark-mode/refs/heads/main/index.user.css). After opening the file, set "Custom included sites" to `*://curriculum.ucsf.edu/*`, and then click "Install style".
- **Arc Boosts:** If you use the Arc browser, [you can use the pre-made boost for a one-click install](https://arc.net/boost/8157134F-66F1-4827-A5A5-9930AE1A76BB).

### Manual Install Instructions

Once you have your extension installed, follow the instructions below.

- [Select all the code in the `index.css` file](https://raw.githubusercontent.com/HyperKids/ilios-dark-mode/refs/heads/main/index.css) (NOT ~~`index.user.css`~~) file and copy it to your clipboard.

- Navigate to `curriculum.ucsf.edu`

- Create a new style in your extension:

  - **User Javascript and CSS:** On the top right of your browser, click the Extensions button (a puzzle icon in Chrome), then click on User Javascript and CSS. Click on the yellow "New rule" button. A window will pop up - paste the code into the right half of the window, then click "Save" on the top right. _Ignore the "Developer Mode" popups - it is not needed for this._
  - **Stylus:** On the top right of your browser, click the Extensions button (a puzzle icon in Chrome), then click on Stylus. Under "Write a new style for...", select the word `curriculum` in the URL (so that you are writing a style for `curriculum.ucsf.edu`). A window will pop up - paste your code there, and click the "Save" button on the left side.
  - **Arc Boosts:** Go to `curriculum.ucsf.edu`, click the Boosts icon, and select "Create Boost". Choose "Code", then "CSS", and paste the code.

- Save the style in your extension. It will now automatically apply to `curriculum.ucsf.edu`.

## Features

- **Dark mode:** A complete dark theme for Ilios, improving readability and reducing eye strain in low-light environments.
- **Customizable:** Change the color scheme and font size by modifying the variables in the `:root` section of the CSS.
- **Improved font:** Uses the Inter font for better readability (you can remove this if you prefer the default font.)
- **Hidden UI elements:** Hides some unused UI elements. You can re-enable these by removing the relevant CSS rules.

## Important Notes

This file hides the user guide link, language selector, and the ICS feed link by default. You can re-enable these elements by commenting out or deleting the corresponding CSS rules at the beginning of the file.

## Contributing

This project is open to contributions. All contributions must be compatible with UCSF's version of Ilios. If you are customizing the code for another institution's custom installation of Ilios, please create a fork instead.

## License

This code is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.

## Disclaimer

This project is not affiliated with or endorsed by the University of California, San Francisco (UCSF) or the Ilios Curriculum Management System (Ilios).
