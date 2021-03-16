## Custom CSS Firefox Theme

A custom theme made with [MaterialFox](https://github.com/muckSponge/MaterialFox),
using transparency and added animated New Tab logo.
###
![alt text](img/gif.gif)


## Installation
*From [MaterialFox](https://github.com/muckSponge/MaterialFox)*
1. Copy the chrome folder and user.js file into your Firefox profile directory. To find your profile directory, go to about:support or about:profiles.
2. See [Recommended instructions](#recommended-instructions) if you'd prefer a more Chrome-like experience.
3. Restart Firefox.

### Recommended instructions
Add space above tab bar:
* Right click on toolbar -> Customize.
* Check Drag Space checkbox.

Replicate Chrome behaviour for clipped tabs:
* [about:config] Set ```browser.tabs.tabClipWidth``` to ```83``` (default is ```140```).

Replicate Chrome's "Not Secure" text on HTTP:
* [about:config] Set ```security.insecure_connection_text.enabled``` to ```true```.