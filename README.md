# Night Shadow (Firefox theme)

Night Shadow: a theme with a dark color scheme that fully modifies the appearance of Firefox browser far beyond the built-in customization features.

### Firefox advanced customization with CSS

Firefox’s user interface is built of web-like elements (HTML and XUL elements) and styled using CSS. Thus, there are additional options for changing the appearance (user interface) of Firefox browser by applying style rules with an optional files named [userChrome.css](https://www.userchrome.org/) and userContent.css. With these files, the Night Shadow theme's color scheme is applied to all elements of the Firefox interface, including: internal pages (all about: pages), dialog windows, error pages, infobars, developer tools etc.

**Attention**: since the changes are mainly made in userChrome.css and userContent.css files, which are not updated automatically with the theme, you should check the theme's GitHub repository from time to time for updated versions of these files.

## Screenshots

<img src="assets/screenshots/0215506.png" alt="Night Shadow: a theme with a dark color scheme that fully modifies the appearance of Firefox browser far beyond the built-in customization features" style="display: inline-block; margin: 15px 0 15px 0; max-width: 850px">

<details>
<summary>More screenshots</summary>
<img src="assets/screenshots/0215547.png" alt="Night Shadow: a theme with a dark color scheme that fully modifies the appearance of Firefox browser far beyond the built-in customization features" style="display: inline-block; margin: 15px 0 15px 0; max-width: 850px">

<img src="assets/screenshots/0215937.png" alt="Night Shadow: a theme with a dark color scheme that fully modifies the appearance of Firefox browser far beyond the built-in customization features" style="display: inline-block; margin: 15px 0 15px 0; max-width: 850px">

<img src="assets/screenshots/0210040.png" alt="Night Shadow: a theme with a dark color scheme that fully modifies the appearance of Firefox browser far beyond the built-in customization features" style="display: inline-block; margin: 15px 0 15px 0; max-width: 850px">

<img src="assets/screenshots/0345332.png" alt="Night Shadow: a theme with a dark color scheme that fully modifies the appearance of Firefox browser far beyond the built-in customization features" style="display: inline-block; margin: 15px 0 15px 0; max-width: 850px">

<img src="assets/screenshots/0215547.png" alt="Night Shadow: a theme with a dark color scheme that fully modifies the appearance of Firefox browser far beyond the built-in customization features" style="display: inline-block; margin: 15px 0 15px 0; max-width: 850px">

<img src="assets/screenshots/0210144.png" alt="Night Shadow: a theme with a dark color scheme that fully modifies the appearance of Firefox browser far beyond the built-in customization features" style="display: inline-block; margin: 15px 0 15px 0; max-width: 850px">

<img src="assets/screenshots/0210223.png" alt="Night Shadow: a theme with a dark color scheme that fully modifies the appearance of Firefox browser far beyond the built-in customization features" style="display: inline-block; margin: 15px 0 15px 0; max-width: 850px">

<img src="assets/screenshots/0210335.png" alt="Night Shadow: a theme with a dark color scheme that fully modifies the appearance of Firefox browser far beyond the built-in customization features" style="display: inline-block; margin: 15px 0 15px 0; max-width: 850px">

<img src="assets/screenshots/0210413.png" alt="Night Shadow: a theme with a dark color scheme that fully modifies the appearance of Firefox browser far beyond the built-in customization features" style="display: inline-block; margin: 15px 0 15px 0; max-width: 850px">

<img src="assets/screenshots/0210446.png" alt="Night Shadow: a theme with a dark color scheme that fully modifies the appearance of Firefox browser far beyond the built-in customization features" style="display: inline-block; margin: 15px 0 15px 0; max-width: 850px">

<img src="assets/screenshots/0210508.png" alt="Night Shadow: a theme with a dark color scheme that fully modifies the appearance of Firefox browser far beyond the built-in customization features" style="display: inline-block; margin: 15px 0 15px 0; max-width: 850px">

<img src="assets/screenshots/0210947.png" alt="Night Shadow: a theme with a dark color scheme that fully modifies the appearance of Firefox browser far beyond the built-in customization features" style="display: inline-block; margin: 15px 0 15px 0; max-width: 850px">

<img src="assets/screenshots/0211011.png" alt="Night Shadow: a theme with a dark color scheme that fully modifies the appearance of Firefox browser far beyond the built-in customization features" style="display: inline-block; margin: 15px 0 15px 0; max-width: 850px">

<img src="assets/screenshots/0211027.png" alt="Night Shadow: a theme with a dark color scheme that fully modifies the appearance of Firefox browser far beyond the built-in customization features" style="display: inline-block; margin: 15px 0 15px 0; max-width: 850px">
</details>

## Download and installation instructions

1. Install the core theme files on the "Add-ons for Firefox" web portal (addons.mozilla.org) by clicking the "Install Theme" button: [https://addons.mozilla.org/en-GB/firefox/addon/night-shadow/](https://addons.mozilla.org/en-GB/firefox/addon/night-shadow/)

2. Find your Firefox profile directory:
    - Type `about:support` in the address bar and press "Enter"
    - Go to "Profile Directory (Linux)" / "Profile Folder (Windows)" entry and click on "Open Directory (Linux)" / "Open Folder (Windows)" button

3. Download additional theme files, unzip the downloaded archive and copy the "chrome" directory to the previously opened Firefox profile directory: [chrome.zip, v20240125.01 (2024-01-25)](https://github.com/serhiyguryev/night-shadow-theme/releases/download/v20240125.01/chrome.zip)

4. Enable Loading of userChrome.css and userContent.css in Firefox:
    - Type `about:config` in the address bar and press "Enter", click "Accept the Risk and Continue" to go to the about:config page
    - Search for the `toolkit.legacyUserProfileCustomizations.stylesheets` preference and switch its value from `false` to `true`
    - Restart Firefox

## How to revert Firefox back to its default state?

If Firefox user interface suddenly looks broken after an update, you can temporarily disable the use of userChrome.css and userContent.css files and revert Firefox back to its default state:

1. Type `about:config` in the address bar and press "Enter", click "Accept the Risk and Continue" to go to the about:config page

2. Search for the `toolkit.legacyUserProfileCustomizations.stylesheets` preference and set it back to `false` by clicking on "Reset" button

3. Remove `chrome` directory from the Firefox profile directory

4. Restart Firefox

## Support my work

If you enjoy my work, please consider supporting what I do. Thank you.

<a href="https://ko-fi.com/serhiyguryev" title="Support me on Ko-fi"><img src="assets/kofi_bg_tag_white.svg" alt="Support me on Ko-fi" width="200px" style="display: inline-block; margin: 5px 0;"></a>

## License

Licensed under the [GNU General Public License v3.0](https://github.com/serhiyguryev/night-shadow-theme/blob/main/LICENSE)
