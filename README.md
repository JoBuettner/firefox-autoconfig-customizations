## Changing Private Window Keyboard Shortcut
- Create [AutoConfig files](https://support.mozilla.org/en-US/kb/customizing-firefox-using-autoconfig)
- Add additional line to autoconfig.js (see [autoconfig.js](autoconfig.js) for complete content):

    `pref("general.config.sandbox_enabled", false);` 
- Paste contents of [firefox.cfg](firefox.cfg) into your own `firefox.cfg`. Contents are based on:
	- https://arunvelsriram.medium.com/customising-firefox-using-autoconfig-1e92b78048c4
	- https://github.com/arunvelsriram/dotfiles/blob/main/firefox/autoconfig.cfg
