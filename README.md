<img src="./assets/banner.png">

# Downloads
### **[Powercord](https://powercord.dev/) & [Vizality](https://vizality.com/)**
Head over to your **Themes folder -> open your terminal of choice -> copy-paste the following, then press enter**:
```
https://github.com/discord-extensions/gradient-buttons
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

# Credits
- [Hoofer](https://github.com/HooferDevelops) for the original code, aka Gradient Buttons v1. He didn't publish the code, so I asked if I could with extra stuff.
- [botato](https://github.com/bototo2) for letting me know that I can use `#id` instead of `[id=""]`.