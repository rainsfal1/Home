![image](assets/img/header.png)

<br />

## 🚀 Usage

### 🏡 As Home Page

1. Fork this repo
2. Enable the Github Pages service `Settings → GitHub Pages → Source [master branch] → Save`
3. Set it as Home Page:
   - Click the menu button. and select Options. Preferences.
   - Click the Home panel.
   - Click the menu next to Homepage and new windows and choose to show custom URLs and add your `Github Pages link`

## 🎨 Customization

All customization can be managed in the `config.js` file:

### 👋 General: Name, Image Background and Greetings

To change the default name, the greetings and if you want to have an image background or open your links in new tabs, edit the first configs in the `config.js`.

```js
 // General
  name: 'John',
  imageBackground: false,
  openInNewTab: true,

  // Greetings
  greetingMorning: 'Good morning!',
  greetingAfternoon: 'Good afternoon,',
  greetingEvening: 'Good evening,',
  greetingNight: 'Go to Sleep!',

```



### 🌑 Auto change theme

The theme can be automatically changed by the OS' current theme or personalized hours
that you can change in the `config.js` file:

```js
  // Autochange
  autoChangeTheme: true,

  // Autochange by OS
  changeThemeByOS: false, 

  // Autochange by hour options (24hrs format, string must be in: hh:mm)
  changeThemeByHour: true, // If it's true, it will use the values below:
  hourDarkThemeActive: '18:30', // Turn on the dark theme after this hour
  hourDarkThemeInactive: '07:00', // Turn off the dark theme after this hour and before the above hour
```

![](assets/img/darkMode.png)
