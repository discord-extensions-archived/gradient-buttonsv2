<img src="./assets/banner.png">

# Downloads
### **[Powercord](https://powercord.dev/) & [Vizality](https://vizality.com/)**
Head over to your **Themes folder -> open your terminal of choice -> copy-paste the following, then press enter**:
```
git clone https://github.com/discord-extensions/gradient-buttons
```

### **[BetterDiscord](https://betterdiscord.app/)**
- [Direct Download](https://github.com/discord-extensions/gradient-buttons/releases/download/bd-download/gradient-buttons.theme.css)
- [Source](https://discord-extensions.github.io/gradient-buttons/src/source.css)

### **Stylus**
1. Install the browser extension for your respective browser.
    - [Chrome Webstore](https://chrome.google.com/webstore/detail/stylus/clngdbkpkpeebahjckkjfobafhncgmne)
    - [Firefox Addons](https://addons.mozilla.org/en-US/firefox/addon/styl-us/)
2. Once you have the browser extension, head over to [this link](https://github.com/discord-extensions/gradient-buttons/raw/main/clients/bd/gradient-buttons.user.css). It will open a new window to the page to install the style.
3. Press the "Install Style" button.

# Disabling Transitions
If you dislike the transitions on hover, you can simply just disable them using the variables. Head over to the root and paste the following under `/* Transitions */`.
```css
:root {
  /* Transitions */
  --button-transition: none;
  --font-default: 500;
  --font-hover: var(--font-default);
  --fontsize-hover: 14px;
  --transform-normal: scale(1);
  --transform-hover: var(--transform-normal);
  --button-transform-hover: var(--transform-normal);
}
```

# Contributors
|<a href="https://github.com/HooferDevelops"><img src="https://avatars.githubusercontent.com/u/60201971?v=4" width="90px" height="90px"></a>|<a href="https://github.com/bototo2"><img src="https://avatars.githubusercontent.com/u/70232113?v=4" width="90px" height="90px"></a>|
|:-:|:-:|
|[Hoofer](https://github.com/HooferDevelops)|[botato](https://github.com/bototo2)|

# Support Server
If you are having any issues with the theme, feel free to join the [support server](https://discord.gg/vYdXbEzqDs), or make an issue on this repository.