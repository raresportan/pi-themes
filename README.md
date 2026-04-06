# 🎨 pi-themes

A curated collection of high-quality themes for the [pi coding agent](https://github.com/badlogic/pi-mono).

## 🌟 Included Themes

- **Night Owl** 🦉: Based on Sarah Drasner's famous Night Owl theme. Perfect for those who code late into the night with a deep navy background and high-contrast syntax.
- **Dracula** 🧛‍♂️: Based on the legendary Dracula theme. A consistent, vibrant, and high-contrast palette loved by developers worldwide.
- **Monokai Night** 🌙: A dark, refined take on the classic Monokai palette.
- **Monokai Vibrant** 🍭: A high-contrast, energetic version of Monokai designed for maximum readability.
- **Nightcall** 🌌: A mellow, moody theme featuring deep blues and vibrant neon purples and pinks.
- **SynthWave '84** 🌅: A retro-futuristic neon aesthetic inspired by the 80s.

## 🚀 Installation

Install the package using the pi CLI:

```bash
pi install git:github.com/raresportan/pi-themes
```

## 🛠️ Usage

Once installed, the themes are automatically discovered by the pi agent. To activate one:

1. Open your pi coding agent.
2. Type `/settings` and press Enter.
3. Select your preferred theme from the list.

Alternatively, you can set it directly in your `settings.json`:

```json
{
  "theme": "nightcall"
}
```

## 📜 Credits

This package is a port of existing color schemes. Some colors are changed. All credits go to the original creators:
- **Night Owl** by [Sarah Drasner](https://css-tricks.com/creating-a-vs-code-theme/)
- **Dracula** by [Zeno Rocha](https://draculatheme.com/)
- **Monokai Vibrant** by [dylantmarsh](https://github.com/dylantmarsh/monokai-vibrant)
- **Nightcall** by [Bobby Patterson](https://github.com/bpat86/nightcall-vscode-theme)
- **SynthWave '84** inspired by the SynthWave '84 aesthetic.

Implemented using [pi](https://github.com/badlogic/pi-mono/tree/main/packages/coding-agent), and Gemma 4 / Qwen 3.5 local models. 

License: MIT
