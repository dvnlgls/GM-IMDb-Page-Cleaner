# IMDb Page Cleaner

> This is a Greasemonkey script to clean IMDb movie & tv pages and to modify layout. I wrote this to satisfy my needs but it can easily be modified to suit yours as well.

### Version: 1.0.0

### What this script does:
- Removes a lot of extraneous information from the page. Examples: popularity rating in the header, news, contribution, the whole right pane with useless stuff, etc.
- Moves user review section just below the header. Also expands the section so you can see the full review. (see function `modifyLayout` to change this behavior)
- Moves photos & videos just below the cast.

### What else can this script do?
- The code is simple & easy to edit. You can add/remove any sections you want. Make sure you choose the right selector.
  - Protip: A HTML node collection may look like an array but it's technically not an array. So convert to array if you intend to do array operations.
- It's also easy to modify the sections as you please. Look for the `data-testid` attribute on the page, as they tend to be unique & don't have obfuscated names.