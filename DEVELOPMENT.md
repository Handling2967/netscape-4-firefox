# Configuration Documentation

## Record all steps required for theme
- enable legacy stylesheets: about:config 'toolkit.legacyUserProfileCustomizations.stylesheets' true
- enable firefox "Light" theme: extensions and themes > Light

### Optional for best look
- change density to compacy: about:config 'browser.compactmode.show' true, right click toolbar > density > compact
- turn on menubar


## Manual Instructions (User must do)
- [ ] Enable legacy stylesheets
- [ ] Move userChrome.css
- [ ] Move user.js

## Automated via `user.js`
- [ ] `toolkit.legacyUserProfileCustomizations.stylesheets`: Required for CSS loading.
