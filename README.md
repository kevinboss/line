![line](https://socialify.git.ci/kevinboss/line/image?font=Jost&language=1&logo=https%3A%2F%2Fi.imgur.com%2Fb4Onimm.png&name=1&pattern=Diagonal%20Stripes&theme=Dark)

# line

[![CI](https://raw.githubusercontent.com/kevinboss/heartbeat/main/badges/kevinboss_line.svg)](https://github.com/kevinboss/heartbeat)

A minimalist, simple, mouse centered userChrome — heavily inspired by [Cascade](https://github.com/andreasgrafen/cascade).

Preview:
![screenshot](https://github.com/kevinboss/userChrome/blob/master/screenshot.png)


## How to use a userChrome.css theme

1. Type `about:config` into your URL bar. Click on the **I accept the risk** button if you're shown a warning.
2. Seach for **`toolkit.legacyUserProfileCustomizations.stylesheets`**, **`layers.acceleration.force-enabled`**, **`gfx.webrender.all`** and **`svg.context-properties.content.enabled`** and set them to **`true`**.
3. Go to your profile folder:
    - Linux: `$HOME/.mozilla/firefox/######.default-release/`
    - MacOS: `Users/[USERNAME]/Library/Application Support/Firefox/Profiles/######.default-release`
    - Windows: `C:\Users\[USERNAME]\AppData\Roaming\Mozilla\Firefox\Profiles\######.default-release`
4. If it doesn't exist already create a folder called `chrome`.
5. Clone this repositoy into the `chrome` folder.
