# firefox-configs
Custom user.js and policies for securing Firefox automatically.

# Installation—Profiles
Go to your default Firefox Profile (`about:profiles`) and open your primary folder. Add `user.js` to it and restart Firefox.

# Installation—Policies
In the main Firefox Dictionary, e.g., `C:\Program Files\Firefox Developer Edition`, create a new folder named `distribution` and add `policies.json` to it (May require special privilege, in that case, open the folder in VSCode with admin privilege and add it).

# CSS Edit
Add to `userChrome.css` in e.g., `C:\Users\main\AppData\Roaming\Mozilla\Firefox\Profiles\kplz2q22.dev-edition-default\chrome` to enable smooth transition for a theme plugin.
```css
#navigator-toolbox,
#TabsToolbar,
#nav-bar,
#PersonalToolbar,
#sidebar-box,
.tab-background,
.urlbar-background,
findbar {
    transition:
        background-color 0.5s cubic-bezier(0, 0, 0, 1), border-color 0.5s cubic-bezier(0, 0, 0, 1) !important;
}
```
