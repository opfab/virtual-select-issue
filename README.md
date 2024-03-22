
# Issue with Virtual Select

This repository contains files to reproduce an issue with the virtual select feature when setting an empty list of options.

## Steps to Reproduce

1. Open `test.html`. Initially, the list of options is searchable in the multiselect.
2. Click on the `removeall` button. This will empty the list of options.
3. Try to use the search feature. It will not be usable due to the absence of any entries.
4. Click on the `fill` button. This will repopulate the list of options.
5. Try to use the search feature again. Despite the presence of entries, the search feature remains unusable.