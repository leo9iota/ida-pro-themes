# IDA Pro One Dark Theme

A clean, modern **One Dark** theme for IDA Pro (7.3+ and 9.x), inspired by Atom's One Dark aesthetic.

## Features

- **Compatibility**: Verified for IDA Pro 7.x, 8.x, and 9.x (Qt6).

- **One Dark Color Palette**: Consistent use of `#282c34` background and `#abb2bf` foreground.
- **Modern UI**: Non-distracting flat design for comfortable reverse engineering.
- **Custom Syntax Highlighting**: Assembly optimized colors matching the One Dark scheme.
- **Windows Title Bar Integration**: Optional registry tweak to unify the window frame color.

## Installation

1.  **Clone or Download** this repository.
2.  Copy the `themes` directory into your IDA Pro installation directory (or your user-specific IDA directory).
    - Ensure your final structure looks like: `.../themes/onedark/` containing `icons/` and `theme.css`.
    - (Note: The theme relies on the standard `themes/_base` found in your IDA installation).
3.  **Activate in IDA**:
    - Open IDA Pro.
    - Go to **Options** -> **Colors**.
    - Select **onedark** from the "Current theme" dropdown.
    - Click **OK**.

> **Note**: A restart of IDA is recommended to ensure all UI elements strictly adhere to the new style.

## Title Bar Customization (Windows Only)

To make your IDA window title bar match the theme's dark background:

1.  Navigate to `themes/onedark/`.
2.  Double-click `accent_onedark.reg`.
3.  Confirm the registry change.

_This sets the Windows DWM accent color for active windows to `#282c34`._

## Credits

- Based on the "52dark" and "dp701" themes.
