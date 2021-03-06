[![Marketplace Version](https://vsmarketplacebadge.apphb.com/version/ericadamski.carbon-now-sh.svg)](https://marketplace.visualstudio.com/items?itemName=ericadamski.carbon-now-sh)
[![Installs](https://vsmarketplacebadge.apphb.com/installs/ericadamski.carbon-now-sh.svg)](https://marketplace.visualstudio.com/items?itemName=ericadamski.carbon-now-sh)

# carbon-now-sh

A VS Code extension to open the current editor content in [carbon.now.sh](https://carbon.now.sh).

Simply highlight the code you want to capture, and run the Carbon extension. You'll be redirected to [carbon.now.sh](https://carbon.now.sh) with your selected code populating the textarea. 

![vscode-carbon now sh](https://user-images.githubusercontent.com/6516758/46617867-df765680-caeb-11e8-8899-95778cdcceb7.gif)

## Running the Extension
There are three ways to run the carbon-now-sh extension. 

* `Alt+Cmd+A` or (`Alt+Windows+A` on Windows) - a shortcut key that will instantly launches the extension
* Open the Command Pallete (`Cmd+Shift+P` or `Ctrl+Shift+P` on Windows), and type Carbon. 
* From the context menu within the editor.

## Overriding Carbon Options
In your VSCode settings, you can override the carbon defaults using these settings:

```json
{
    "carbon.backgroundColor": "rgba(0,0,0,0)",
    "carbon.theme": "seti",
    "carbon.dropShadow": true,
    "carbon.windowControls": true,
    "carbon.autoAdjustWidth": true,
    "carbon.paddingVertical": 24,
    "carbon.paddingHorizontal": 16,
    "carbon.lineNumbers": false,
    "carbon.fontFamily": "Hack",
    "carbon.fontSize": 13
}
```
