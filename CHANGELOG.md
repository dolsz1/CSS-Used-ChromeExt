**ver 3.0.0 | 15/01/2023**

1. Migrated to Manifest V3.
1. Resources are read from local caches, making it much faster and solves the [cross-origin issue](https://github.com/painty/CSS-Used-ChromeExt/issues/52).
1. Optimized style parsing in a more efficient way.
1. Dropped support for some outdated CSS, mostly -o- and -ms- prefixed properties.
1. Implemented a new UI powered by Svelte, with some visual tweaks.

**ver 2.5.0 | 15/03/2021**

1. New. Option page.
2. New. Option to preserve relative URLs. [#31](https://github.com/painty/CSS-Used-ChromeExt/issues/31)

**ver 2.4.3 | 04/03/2021**

1. Fix. Send to CodePen may not work. [#38](https://github.com/painty/CSS-Used-ChromeExt/issues/38)

**ver 2.3.2 | 18/11/2018**

1. More friendly prompt text for first use or error display.
2. The add tabs permission is used to identify special urls. Such as chrome://newtab

**ver 2.2.12 | 11/11/2018**

1. No new feature or bugfix. Just split the content.js into some modules.

**ver 2.2.11 | 10/06/2018**

1. Fix. preview button doesn't work [#15](https://github.com/painty/CSS-Used-ChromeExt/issues/15) [#16](https://github.com/painty/CSS-Used-ChromeExt/pull/16)
2. specify protocol for img in Preview

**ver 2.2.10 | 07/11/2018**

1. Better regex for cleaning empty rules.
2. Add. scrollbar style

**ver 2.2.8 | 07/08/2018**

1. Fix. @import inside media query should be invalid.

**ver 2.2.7 | 06/27/2018**

1. Add. Media property of css link/tag preserved.
2. Update dependencies

    "postcss": "6.0.23",
    "postcss-safe-parser": "3.0.1"

**ver 2.2.6 | 08/30/2017**

1.Fix. css link with empty href

**ver 2.2.5 | 08/25/2017**

1.Change Send-to-codepen's url from "http://" to "https://"

**ver 2.2.4 | 08/23/2017**

1.Add. User-friendly way of requesting file access

**ver 2.2.3 | 04/30/2017**

1.fix bug that the first comment is lost
2.won't import the invalid @import css

**ver 2.2.2 | 04/29/2017**

1.Endless loop @import handling. eg: a.css import b.css and b.css import a.css

**ver 2.2.1 | 04/27/2017**

1.Better tips for first time use
2.changed CSS parsing from Chrome to postcss

**ver 2.1.1 | 04/25/2017**

1. Better external CSS Cache

**ver 2.1.0 | 04/24/2017**

1. Now works with iframes

**ver 2.0.0 | 04/24/2017**

1. A Break Though in speed improvement.

**ver 1.5.0 | 04/23/2017**

1. Rewrite. to async way. Now CSS-Used could have a quicker UI response. Still be CAUTIOUS when selecting too many elements which may freeze the current tab.
2. Add. Two buttons: `Copy to clipboard` & `Send to codepen`
3. Better handling for pseudo element/class

**ver 1.4.2 | 04/15/2017**

1. Add. calculating progress display.

**ver 1.4.1 | 04/09/2017**

1. multiple pseudo class/element detection

**ver 1.4.0 | 04/09/2017**

1. Add. media query support
2. Add. font-face support
3. Fix. unused stylesheet will not show in the result.

**ver 1.3**

1. Convert all background image url to absolute path.

**ver 1.2**

1. The link tag is preserved now.

**ver 1.1.5**

1. Keyframe animation extract is now supported.
