

# Using Firefox With Multiple Profiles in MacOS *(Sierra)*

## Summary
Many web services require a unique caching and login structure to properly function.  Services which provide cross-system data storing are usually focused on this type of methodology.

| Cross-system data sharing | Name | Data shared |
| ------------------------- | ------- | -------------: |
|                           | Google | bookmarks, cookies, search content |
| Account control and Caching | Amazon | local cookies, cache, account creds, variables, *(contains lots of javascript)*  |


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
