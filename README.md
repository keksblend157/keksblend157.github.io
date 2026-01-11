# САп, я KeksBlend и Я оч ЛЮблЮ мУЗыКУ
[YouTube](https://www.youtube.com/@keksblend157)
[Telegram](https://t.me/kerksmic888)
[VK](https://vk.com/kerksmic888)
[Soundcloud](https://soundcloud.com/keksblend)
[Spotify](https://open.spotify.com/user/31a375cgtmhyzzbnnqbvj4zml6i4)
[отправить трек](https://vk.com/aftershock1corpse)

const darkModeToggle = document.querySelector('dark-mode-toggle');

// Set the mode to dark
darkModeToggle.mode = 'dark';
// Set the mode to light
darkModeToggle.mode = 'light';

// Set the legend to "Dark Mode"
darkModeToggle.legend = 'Dark Mode';
// Set the light label to "off"
darkModeToggle.light = 'off';
// Set the dark label to "on"
darkModeToggle.dark = 'on';

// Set the appearance to resemble a switch (theme: light/dark)
darkModeToggle.appearance = 'switch';
// Set the appearance to resemble a toggle (dark mode: on/off)
darkModeToggle.appearance = 'toggle';

// Set a "remember the last selected mode" label
darkModeToggle.remember = 'Remember this';

// Remember the user's last color scheme choice
darkModeToggle.setAttribute('permanent', '');
// Forget the user's last color scheme choice
darkModeToggle.removeAttribute('permanent');
