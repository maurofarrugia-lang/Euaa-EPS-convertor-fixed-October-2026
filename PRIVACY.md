# Privacy design

The static application does not contain server-side upload code. File parsing and conversion occur in the browser. The current Excel parser is loaded from jsDelivr; CSV processing uses no third-party parser. For a fully offline deployment, vendor an approved copy of SheetJS and replace the script reference in `index.html`.
