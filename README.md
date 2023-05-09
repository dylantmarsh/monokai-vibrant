<p align="center">
    <img src="https://raw.githubusercontent.com/dylantmarsh/monokai-vibrant/master/images/icon.png" width="80" />
    <h2 align="center" style="letter-spacing:2px;font-weight:700">MONOKAI VIBRANT</h2>
</p>

<p align="center">A very dark and vibrant Monokai based theme.</p>

<p align="center">
    <img alt="Visual Studio Marketplace Rating" src="https://img.shields.io/visual-studio-marketplace/r/s3gf4ult.monokai-vibrant?color=%231dd1e5&style=for-the-badge">
    <img alt="Visual Studio Marketplace Installs" src="https://img.shields.io/visual-studio-marketplace/i/s3gf4ult.monokai-vibrant?color=%23ff3f4e&style=for-the-badge">
    <img alt="Visual Studio Marketplace Version" src="https://img.shields.io/visual-studio-marketplace/v/s3gf4ult.monokai-vibrant?color=%23ff9700&style=for-the-badge">
</p>

![Monokai Vibrant JavaScript Example](https://f000.backblazeb2.com/file/app-media/monokai-vibrant.jpg)

* 🌙 Super dark editor color scheme
* 🍭 Vibrant colors for better readability
* 💻 Italicized keywords compliments "Operator Mono" or similar fonts (optional)

## Install

1. Open the **Extensions** sidebar in VS Code.
2. Search for `Monokai Vibrant`. Choose the one by **s3gf4ult**
3. Click the **Install** button
4. Go to Preferences ‣ Color Theme ‣ **Monokai Vibrant**

## Disable Italics

If you are not using a font that does not support italics, you can add this to your `settings.json` to disable them.

```json
"editor.tokenColorCustomizations": {
  "textMateRules": [
    {
      "name": "Monokai Vibrant - No Italics",
      "scope": [
        "comment",
        "string.comment",
        "variable.language",
        "keyword",
        "storage",
        "variable.parameter"
      ],
      "settings": {
        "fontStyle": ""
      }
    }
  ]
}
```

## Extras

A long-term goal of this project is to provide color schemes for other popular applications in the `/extras` folder. A vim/nvim theme would be greatly appreciated if anyone is interested in contributing.

---

Don't forget to leave a review on the marketplace! **Enjoy!**
