# Dark qBittorrent WebUI [![Version][version]][1] [![Install directly with Stylus][stylus]][2] [![userstyles.org installations][userstyles]][3] [![GitHub stars][stars]][4] [![GitHub issues][issues]][5] [![GitHub license][license]][6]
**_A darker theme for qBittorrent WebUI_ (ispired by [Cozzy's theme])**

[![preview][preview]][1]
# Installation (one of two ways)
1. Download one of these add-ons for your browser
   * Stylus (recommended): [Firefox][7], [Chrome][8],  or [Opera][9].
   * Stylish: [Firefox][10], [Chrome][11],  or [Opera][12].
   * Click [here][2] to install directly with Stylus, or go to [userstyles.org][3] and click on "Install Style" button to install with Stylish.
   * Done! From now on it will automatically update.
2. Use Alternative WebUI in  qBittorrent
   * Follow the instructions to use [Alternate WebUI usage][13].
   * Copy dark-qbittorrent-webui.user.css to `<new folder>/public/css`.
   * Edit `<new folder>/public/index.html`.  
     Add `<link rel="stylesheet" type="text/css" href="css/dark-qbittorrent-webui.css?v=${VERSION}" \>` after the other CSS links in header.
   * Copy dark-qbittorrent-webui.css to `<new folder>/private/css`.
   * Edit `<new folder>/private/index.html`.       
     Add `<link rel="stylesheet" type="text/css" href="css/dark-qbittorrent-webui.css?v=${VERSION}" \>` after the other CSS links in header.  
 
[version]: https://img.shields.io/badge/version-1.0.0-ED1C24.svg?longCache=true&style=flat-square
[1]: #
[stylus]: https://img.shields.io/badge/install%20directly%20with-Stylus-00adad.svg?longCache=true&style=flat-square "Click here!"
[2]: https://raw.githubusercontent.com/iFelix18/Dark-qBittorrent-WebUI/master/dark-qbittorrent-webui.user.css
[userstyles]: https://img.shields.io/badge/dynamic/json.svg?label=userstyles.org%20installations&url=https%3A%2F%2Fwidget.userstyles.org%2Fstyles%2F160858%2Fdark-qbittorrent-webui.json&query=total_installs&colorB=e51ced&longCache=true&style=flat-square
[3]: https://userstyles.org/styles/160858/dark-qbittorrent-webui
[stars]: https://img.shields.io/github/stars/iFelix18/Dark-qBittorrent-WebUI.svg?longCache=true&style=flat-square
[4]: https://github.com/iFelix18/Dark-qBittorrent-WebUI/stargazers
[issues]: https://img.shields.io/github/issues/iFelix18/Dark-qBittorrent-WebUI.svg?longCache=true&style=flat-square
[5]: https://github.com/iFelix18/Dark-qBittorrent-WebUI/issues
[license]: https://img.shields.io/github/license/iFelix18/Dark-qBittorrent-WebUI.svg?longCache=true&style=flat-square
[6]: https://creativecommons.org/licenses/by-sa/4.0/
[Cozzy's theme]: https://userstyles.org/styles/152766/
[preview]: https://i.imgur.com/M3TAp0l.png
[7]: https://addons.mozilla.org/firefox/addon/styl-us/
[8]: https://chrome.google.com/webstore/detail/clngdbkpkpeebahjckkjfobafhncgmne
[9]: https://addons.opera.com/extensions/details/stylus/
[10]: https://addons.mozilla.org/firefox/addon/stylish/
[11]: https://chrome.google.com/webstore/detail/stylish-custom-themes-for/fjnbnpbmkenffdnngjfgmeleoegfcffe
[12]: https://addons.opera.com/extensions/details/stylish/
[13]: https://github.com/qbittorrent/qBittorrent/wiki/Alternate-WebUI-usage
