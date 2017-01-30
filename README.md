

# Using Firefox With Multiple Profiles in MacOS Sierra

## Profile editor mozilla
Profile editor must be launched with the -no-remote option to properly function and allow other profiles to lauch simultaneously.

## Shell Script to launch profile editor
fileaname: firefox.app
```bash
#!/bin/bash

/Applications/Firefox.app/Contents/MacOS/firefox-bin -P -no-remote
```

### Profiles Application
```
/Users/username/Library/Application Support/Firefox/Profiles
```
### Launch Firefox with Profile collection
```
/Applications/Firefox.app/Contents/MacOS/firefox-bin -P -no-remote
```

#### Addons
- Multi Tab Handler - piro.sakura.ne.jp (XUL Apps)

- Show Profile (happy face)

- Profile Switcher
[Profile Switcher](https://addons.mozilla.org/en-US/firefox/user/Paolo_Kaosmos/?src=api)
https://addons.mozilla.org/en-US/firefox/user/Paolo_Kaosmos/?src=api

- User Agent Switcher (pederick)
