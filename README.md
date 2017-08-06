Package the Asana as a dekstop application with some design customizations
Tested on Mac OS X only


## Css
theme source: https://userstyles.org/styles/138350/asana-com-a-better-theme


## Package + install:
Install [nativefier](https://github.com/jiahaog/nativefier) first: `npm install nativefier -g`

Package the app and install it on Mac OS x:
`nativefier -n asana https://app.asana.com/ --inject ./custom.css --inject ./asana-usertheme.css ~/Applications`
