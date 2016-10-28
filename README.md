This is a wedding einvite card that lets you flip through the pages in the invite.

To use:
- clone repo
- add directory called evite
- add jpgs to the evite directory
- correctly reference those jpgs in `gs-ecard.html` (you'll see the list of images somewhere there)
- update the number of pages in the javascript `totalPages: 16` to how many pages you need


Note:
- if you have an even number of pages, you'll want to remove the: `<div class="hard"></div>` line.
That was added just so that I could "close" the einvite on a single page.

