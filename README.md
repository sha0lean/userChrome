## QUICK GUIDE

- Go to `about:profiles` (in the URL)
- Find your profile folder by clicking on `open folder` in the `root repertory` section
- Create a `chrome` folder and add the `userChrome.css` file inside
  - Exemple: `C:\Users\shao\AppData\Roaming\Mozilla\Firefox\Profiles\exemple.default-release\chrome\userChrome.css`
- Go to : `about:config`
- Set `toolkit.legacyUserProfileCustomizations.stylesheets` to `true`
- Refresh browser from `about:profiles`

Enjoy.

source video : https://www.userchrome.org/how-create-userchrome-css.html


---


If you want to edit directly in your browser you need to use Firefox Developer Edition

Check the settings :
- “`Enable browser chrome and add-on debugging toolboxes`”
- “`Enable remote debugging`”

And then use `ctrl`+`shift`+`alt`+`I`

https://firefox-source-docs.mozilla.org/devtools-user/browser_toolbox/index.html
