# ffckoverlays
Right-click any overlay to remove it. Inspired by the Chrome extension "F*ck Overlays" (https://chrome.google.com/webstore/detail/fck-overlays/ppedokobpbdajgiejhnjfbdjlgobcpkp).

## Local Development

### Firefox
1. Open Firefox and navigate to `about:debugging`
2. Click "This Firefox" in the left sidebar
3. Click "Load Temporary Add-on..."
4. Navigate to the extension directory and select the `manifest.json` file
5. The extension will be loaded temporarily and will remain until you restart Firefox

### Orion Browser
1. Enable developer mode in Orion:
   - Go to Orion Settings
   - Navigate to the Extensions section
   - Enable "Developer Mode" or "Allow Unsigned Extensions" if available
2. Load the extension:
   - In Orion, go to the Extensions page
   - Click "Load Unpacked Extension" or similar option
   - Select the extension directory containing `manifest.json`
3. The extension should now be active in Orion

Note: For Orion, as it's based on WebKit, ensure the extension is compatible with Manifest V2 standards.
