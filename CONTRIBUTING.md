# Project preference: Use filename as Image Labels

This project adds a UI preference that allows users to toggle whether filenames are used as image labels on generated bingo cards. Implementation details:

- UI: Add a checkbox `#useFilenameLabels` after the upload images area. Default: checked.
- JS: Expose DOM element `useFilenameLabels` and read `useFilenameLabels.checked` when generating cards.
- Card generation: `createBingoCardHTML` gains `includeImageLabels` parameter. If false, per-cell filename labels are omitted.

No changes to .editorconfig or CONTRIBUTING.md are required.