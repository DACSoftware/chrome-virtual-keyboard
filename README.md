# Chrome virtual keyboard

#### To deploy new version:

- remember to increment version numbers in package.json & dist/manifest.json files
- run `node deploy/zip.js`
- go to https://chrome.google.com/webstore/devconsole
- choose *Virtual Keyboard*
- in left menu, choose *Package*
- click *Send updated package* button
- upload dist-zip/chrome-virtual-keyboard-v[VERSION NUMBER].zip file
- click *Publish product* button
- wait until Published version in *Package* tab is correct (up to an hour)
- send email to IT-support for update extension on qiosks