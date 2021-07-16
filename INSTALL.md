### [Funkwhale](https://funkwhale.audio/)

#### Install manually

1. Go to Administration > Settings.
2. Find "Custom CSS code" under "User Interface".
3. Paste in the following css.
4. Hit "Save".

```css
:root {
  --dracula-bg: #282a36;
  --dracula-fg: #f8f8f2;
  --dracula-current-line: #44475a;
  --dracula-comment: #6272a4;
  --dracula-abyss: rgb(29, 30, 38);
  --dracula-cyan: #8be9fd;
  --dracula-green: #50fa7b;
  --dracula-orange: #ffb86c;
  --dracula-pink: #ff79c6;
  --dracula-purple: #bd93f9;
  --dracula-red: #ff5555;
  --dracula-yellow: #f1fa8c;
}
.theme-dark,
.theme-light {
  --main-background: var(--dracula-bg);
  --text-color: var(--dracula-fg);
  --link-color: var(--dracula-purple);
  --link-hover-color: var(--dracula-purple);
  --input-background: var(--dracula-abyss);
  --segment-background: var(--dracula-abyss);
  --card-background: var(--dracula-abyss);
  --success-color: var(--dracula-green);
  --success-hover-color: var(--dracula-current-line);
  --discrete-text-color: var(--dracula-fg);
  --really-discrete-text-color: var(--dracula-comment);
  --button-basic-hover-color: var(--dracula-fg);
  --button-basic-color: var(--dracula-comment);
  --card-box-shadow: 0 1px 3px 0 black, 0 0 0 1px black;
  --sidebar-background: var(--dracula-abyss);
  --vibrant-color: var(--dracula-green);
  --vibrant-hover-color: var(--dracula-green);
  --player-color: var(--dracula-fg);
  --player-background: var(--dracula-abyss);
  --site-background: var(--dracula-bg);
  --danger-color: var(--dracula-red);
  --danger-hover-color: var(--dracula-red);
  --primary-color: var(--dracula-cyan);
  --primary-hover-color: var(--dracula-cyan);
  --secondary-menu-active-item-color: var(--dracula-comment);
}
button,
.ui.success.button,
.ui.success.buttons .button,
.ui.vibrant.button,
.ui.vibrant.button:hover,
.ui.vibrant.buttons .button,
.ui.vibrant.buttons .button:hover,
.ui.primary.button,
.ui.primary.buttons .button {
  color: var(--dracula-bg);
}
button:hover,
.ui.success.button:hover,
.ui.success.buttons .button:hover {
  color: var(--dracula-fg);
}
.sidebar .logo path {
  fill: var(--dracula-bg);
}
.ui.table td.active, .ui.table tr.active {
  color: var(--dracula-fg);
  background: var(--dracula-abyss);
}
.ui.info.message {
  color: var(--dracula-fg);
  background: var(--dracula-current-line);
}
.ui.selectable.table > tbody > tr:hover,
.ui.table tbody tr td.selectable:hover,
.ui.selectable.table tr.active:hover,
.ui.selectable.table tr:hover td.active,
.ui.table tr td.selectable.active:hover,
button:hover, .ui.success.button:hover,
.ui.success.buttons .button:hover {
  color: var(--dracula-fg);
  background: var(--dracula-current-line);
}
i.pink.icon {
  color: var(--dracula-pink);
}
.ui.info.message .header {
  color: var(--dracula-fg);
}
i.inverted.bordered.vibrant.icon,
i.inverted.circular.vibrant.icon {
  background: var(--dracula-purple);
}
```
