# Contains the following features: (maybe more will be added as I use)

Modular design for easy modification and installation according to individual needs, and enabled only on the corresponding page to reduce the performance footprint.

Please install function modules as required.

## 1. Automatic login

### Save password version

[Click here Install](https://github.com/wuyilingwei/MyUserScript/raw/main/userjs/UofT-idpz/Auto_login_Spwd.user.js)

This User js is for U of T's idpz student/faculty login system, automate it and don't have to do anything.

The Script will automatically save the password to the User Script Manager, and the User Script Manager will automatically fill in the password when you visit the login page and click login.

I not upload password to any server, and the password is stored in the browser's local storage(Use Base64 Encode).

Please note that this may lead to password leakage and sharing (but if your browser storage is no longer secure, then your entire device has most likely been compromised).

This script has been modified from the Schoology version to fit the idpz login system and the beautified overlay box.

~~Damn, can't they write an automatic login? I log into the school's websites at least ten times a day.~~