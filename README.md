<h3 align="center">
	<img src="https://raw.githubusercontent.com/catppuccin/catppuccin/main/assets/logos/exports/1544x1544_circle.png" width="100" alt="Logo"/><br/>
	<img src="https://raw.githubusercontent.com/catppuccin/catppuccin/main/assets/misc/transparent.png" height="30" width="0px"/>
	Catppuccin for <a href="https://www.waveterm.dev/">WaveTerm</a>
	<img src="https://raw.githubusercontent.com/catppuccin/catppuccin/main/assets/misc/transparent.png" height="30" width="0px"/>
</h3>

<p align="center">
	<a href="https://github.com/catppuccin/waveterm/stargazers"><img src="https://img.shields.io/github/stars/catppuccin/waveterm?colorA=363a4f&colorB=b7bdf8&style=for-the-badge"></a>
	<a href="https://github.com/catppuccin/waveterm/issues"><img src="https://img.shields.io/github/issues/catppuccin/waveterm?colorA=363a4f&colorB=f5a97f&style=for-the-badge"></a>
	<a href="https://github.com/catppuccin/waveterm/contributors"><img src="https://img.shields.io/github/contributors/catppuccin/waveterm?colorA=363a4f&colorB=a6da95&style=for-the-badge"></a>
</p>

<p align="center">
	<img src="https://raw.githubusercontent.com/catppuccin/catppuccin/main/assets/previews/preview.webp"/>
</p>

## Previews

<details>
<summary>🌻 Latte</summary>
<img src="https://raw.githubusercontent.com/catppuccin/catppuccin/main/assets/previews/latte.webp"/>
</details>
<details>
<summary>🪴 Frappé</summary>
<img src="https://raw.githubusercontent.com/catppuccin/catppuccin/main/assets/previews/frappe.webp"/>
</details>
<details>
<summary>🌺 Macchiato</summary>
<img src="https://raw.githubusercontent.com/catppuccin/catppuccin/main/assets/previews/macchiato.webp"/>
</details>
<details>
<summary>🌿 Mocha</summary>
<img src="https://raw.githubusercontent.com/catppuccin/catppuccin/main/assets/previews/mocha.webp"/>
</details>

## Usage

### Tab Backgrounds

1. Download the background presets from the [`themes/backgrounds/`](themes/backgrounds/) directory, or use one of the methods below:

   **All Flavors**
   ```bash
   curl -LO --output-dir ~/.config/waveterm/presets/ https://github.com/catppuccin/waveterm/raw/main/themes/backgrounds/catppuccin-backgrounds.json
   ```

2. Merge the contents of `catppuccin-backgrounds.json` into your `~/.config/waveterm/presets/presets.json` file (create it if it doesn't exist).

3. Apply a background:
   - **Via UI**: Right-click on any tab → Select **Backgrounds** → Choose your desired Catppuccin flavor
   - **Via Config**: Edit your `settings.json` file and add:
     ```json
     {
       "tab:preset": "bg@catppuccin-mocha"
     }
     ```

### Terminal Color Schemes

1. Download the theme files from the [`themes/terminal/`](themes/terminal/) directory, or use one of the methods below:

   **🌻 Latte**
   ```bash
   curl -LO --output-dir ~/.config/waveterm/termthemes https://github.com/catppuccin/waveterm/raw/main/themes/terminal/catppuccin-latte.json
   ```

   **🪴 Frappé**
   ```bash
   curl -LO --output-dir ~/.config/waveterm/termthemes https://github.com/catppuccin/waveterm/raw/main/themes/terminal/catppuccin-frappe.json
   ```

   **🌺 Macchiato**
   ```bash
   curl -LO --output-dir ~/.config/waveterm/termthemes https://github.com/catppuccin/waveterm/raw/main/themes/terminal/catppuccin-macchiato.json
   ```

   **🌿 Mocha**
   ```bash
   curl -LO --output-dir ~/.config/waveterm/termthemes https://github.com/catppuccin/waveterm/raw/main/themes/terminal/catppuccin-mocha.json
   ```

2. The theme files should be placed in your WaveTerm config directory:
   - **Linux**: `~/.config/waveterm/termthemes/`
   - **macOS**: `~/.config/waveterm/termthemes/`
   - **Windows**: `%USERPROFILE%\.config\waveterm\termthemes\`

3. Apply the theme:
   - **Via UI**: Right-click in the header area of any terminal block → Select your desired Catppuccin flavor
   - **Via Config**: Edit your `settings.json` file and add:
     ```json
     {
       "term:theme": "catppuccin-mocha"
     }
     ```

### Setting a Default Theme

To set a Catppuccin theme as your default for all new tabs and terminals, add both settings to your `settings.json`:

```json
{
  "term:theme": "catppuccin-mocha",
  "tab:preset": "bg@catppuccin-mocha"
}
```

For more information on Wave Terminal customization, see the [official documentation](https://docs.waveterm.dev/customization).

## 💝 Thanks to

- [Jairo Morales - (icky17)](https://github.com/Icky17)

&nbsp;

<p align="center">
	<img src="https://raw.githubusercontent.com/catppuccin/catppuccin/main/assets/footers/gray0_ctp_on_line.svg?sanitize=true" />
</p>

<p align="center">
	Copyright &copy; 2021-present <a href="https://github.com/catppuccin" target="_blank">Catppuccin Org</a>
</p>

<p align="center">
	<a href="https://github.com/catppuccin/catppuccin/blob/main/LICENSE"><img src="https://img.shields.io/static/v1.svg?style=for-the-badge&label=License&message=MIT&logoColor=d9e0ee&colorA=363a4f&colorB=b7bdf8"/></a>
</p>
