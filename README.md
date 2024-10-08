## Website
[CA Lab Website](https://chunyen-chen.github.io/Calab-new-web.github.io/)


## Reference
1. [Original reference](https://github.com/learning-zone/website-templates)
1. [Font Awesome](https://fontawesome.com/v6/download)


## Maintenance
1. Rules of the home page
   * less than 5 news (news in home should be happened in previous year or this year)
   * less than 12 members
   * less than 5 publications
   * less than 6 courses

1. Add a new publication
   * Use the `script/bib2html.py`

1. Picture
   * File format: `.webp` would be best.
   * Sponser picture size: 200x50
   * Project picture size: 400x289 / 600x450
   * Member  picture size: 225x225 (best), or a square img (size can be random)

1. Video
   * File format: `.webm` would be the best.

1. Add a new member
   * Image size
   * links
   * set the id and class

1. Minify the CSS
   * use the `script/minifyCSS.py` (not tested yet)

1. Common html part
   * the common html is placed under `script/common/`
   * use the `script/replace_content.py` to replace the content

## Known bugs
1. `background-attachment: fixed;` does not work on any ios devices. See [here](https://caniuse.com/?search=background-attachment%3A).
Current [solution](https://stackoverflow.com/questions/26372127/background-fixed-no-repeat-not-working-on-mobile).

## Tips
1. Add a special character in HTML.
   * [Greek](https://www.thoughtco.com/html-codes-greek-characters-4062212)
   * [German](https://websitebuilders.com/tools/html-codes/german/)
   * [Math](https://www.toptal.com/designers/htmlarrows/math/)
   * [Bar over character](https://stackoverflow.com/questions/12402831/print-a-with-bar-over-it-in-html)
   * [Power of character](https://www.w3schools.com/tags/tag_sup.asp)

1. Check if the CSS parameter is available across all devices
   * [Can I Use](https://caniuse.com/)

## TODO
### Warning
* clean the warning from the map

### Before to go
* clean all the empty links
* link all the members to their section in member page
* Add the readme or instruction about the maintenance of website
* fill the words which need to be filled
* check the mobile version (include the css setting and different OS)
* re-layout the footer
* use the minimized .css and .js

### Optimizations
* let the content change width to be a variable in css (complex!!!)
* Try to let the background of contact to be fixed
* check the figure of project and member => use github workflow?
* the publication filters initialized as hide but still show at start
* sort button of publucation?
* a fold navbar e.g. (member => prof, RA, PHD...)
* fill term of use and privacy policy at footer [This](https://www.termsofusegenerator.net) and [This](https://termify.io/privacy-policy-generator?gad_source=1&gclid=CjwKCAiAopuvBhBCEiwAm8jaMSbkpk0Mk7J4fZngmu3RuioKEHaxlYKaBKgx_55PW-REAaizBIze5BoC0NIQAvD_BwE)
* optimize the load speed (https://pagespeed.web.dev/ or use the Edge insight)
* share the footer and the header
