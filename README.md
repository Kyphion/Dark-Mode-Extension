<p align="center">
  <a href="https://addons.mozilla.org/en-US/firefox/addon/sil-dark-mode/">
    <img 
      alt="Dark Mode Icon"
      src="Source/Icons/icon96.png"
    />
  </a>
</p>

<p align="center">
  <strong>
    Dark Mode for Firefox – A Smart, Intelligent, and Lightweight Add-on
  </strong>
</p>

<p align="center">
  <a href="https://addons.mozilla.org/en-US/firefox/addon/sil-dark-mode/">
    <img 
      alt="Firefox Badge" 
      src="https://img.shields.io/badge/Firefox-%231c1c1c?style=for-the-badge&logo=firefoxbrowser&logoColor=%23ffffff&logoSize=auto"
    />
  </a>
</p>


---

### Overview

**Dark Mode** is a lightweight, intelligent dark theme engine that dynamically adjusts text and background colors based on visual luminance. It ensures high contrast and strong accessibility without relying on hardcoded color overrides.

---

### Features

- **Real-Time Adaptation** 
  Automatically detects and transforms overly bright or low-contrast elements, including dynamic content as it loads.

- **Non-Invasive Styling** 
  Applies adjustments only when necessary. Original styles are preserved unless contrast requires an override.

- **Performance-Optimized** 
  Uses `MutationObserver` with throttled updates for fast, efficient behavior.

- **Fully Configurable** 
  Luminance thresholds and replacement colors can be modified through a simple config object.

- **Cross-Browser Compatible** 
  Works on Chrome, Brave, Edge, Firefox, and other Chromium-based browsers.

- **Zero Dependencies** 
  Pure vanilla JavaScript with no frameworks, libraries, or external stylesheets.

---

### Installation (Chrome, Brave, Edge)

1. Download and extract the ZIP file.
2. Open your browser and go to: `chrome://extensions/`
3. Enable **Developer mode** (toggle in the top right).
4. Drag and drop the `Source` folder.
5. The extension should now be installed and active.

---

### Why It’s Different

Unlike most dark mode extensions that overwrite entire stylesheets:

- **Design-Aware** ⏤ Adapts to the original layout and visual intent. 
- **Selective Styling** ⏤ Only adjusts what’s needed for contrast. 
- **Accessibility First** ⏤ Prioritizes legibility and color balance. 
- **Preserves Native Behavior** ⏤ Doesn’t interfere with the page’s logic. 
- **Lightweight & Efficient** ⏤ Minimal logic, fast load.
- **Plug-and-Play** ⏤ Works immediately without configuration.
- **Smart Engine** ⏤ Uses real luminance calculations, not preset color lists.

---

### Privacy & Footprint

- No data collection
- No remote requests
- No tracking
- No external libraries
- No inline `<style>` tags
- No `<script>` injections
- No extra permissions
- Fully local and DOM-only
- Compact ~11KB source code

---

### Credits

If you use this project or parts of it in your work, please consider:

- **Giving credit** by linking back to this repository.
- **Starring:** If you find this project useful, starring the repo helps a lot and is appreciated.
