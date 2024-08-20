# Tokyo Night Fox Theme

![240820_13h25m18s_screenshot](https://github.com/user-attachments/assets/f9274d7b-a1f0-41db-8c40-83444a947ad4)

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Customization](#customization)
- [Contributing](#contributing)
- [License](#license)

## Introduction

This project is a custom Firefox theme inspired by the "Tokyo Night" color scheme. It provides a clean, minimalistic, and visually appealing browsing experience by modifying various UI elements within Firefox. The theme applies specific styles to the browser's tabs, toolbar, and other elements to enhance the look and feel of your browsing experience.

## Features

- **Reorganized Toolbar:** Moves essential buttons like the main menu and URL bar to make them more accessible while hiding less frequently used items.
- **Customized Tab Appearance:** Rounded corners, adjusted tab height, and smooth transitions for a modern look.
- **Minimalist Design:** Hides unnecessary elements like the Firefox logo, search bar, and more to focus on the content.
- **Tokyo Night Colors:** Incorporates a dark theme with blue and purple accents, inspired by Tokyo's nightlife.
- **Animated Hover Effects:** Adds subtle animations to tab close buttons and top sites for a more interactive experience.
- **Custom New Tab Page:** Applies a dark, Tokyo-themed background with a welcoming message and custom layout for top sites.

## Prerequisites

- **Firefox**: Ensure that you have the latest version of Firefox installed.

## Installation

1. **Clone the Repository**:

   ```bash
   git clone https://github.com/Stan-breaks/Tokyo-night-Fox.git
   ```

2. **Locate Your Firefox Profile**:

   - Open Firefox.
   - Type `about:support` in the address bar and press Enter.
   - Under the "Application Basics" section, find the "Profile Folder" entry, and click "Open Folder." or navigate to the directory.

3. **Create `chrome` Folder**:

   - Inside your profile folder, create a directory named `chrome` if it doesn’t exist.

4. **Copy Files**:

   - Copy `userChrome.css` and `userContent.css` from the cloned repository to the `chrome` folder in your Firefox profile.

5. **Enable Custom Styles**:

   - Type `about:config` in the address bar and press Enter.
   - Search for `toolkit.legacyUserProfileCustomizations.stylesheets`.
   - Set the value to `true` by double-clicking on it.

6. **Restart Firefox**:
   - Close and reopen Firefox to apply the theme.

## Customization

- **Adjusting Colors and Fonts**:
  - You can modify the color scheme or font used by editing the `userContent.css` file.
- **Changing Layout**:
  - Tweak the layout by editing `userChrome.css` to better suit your preferences.

## Contributing

Contributions are welcome! If you have suggestions, feel free to fork the repository and submit a pull request. Whether it's new features, bug fixes, or optimizations, your input is valuable.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
