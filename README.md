# Contact Organiser

A local-only browser utility for opening, reading, editing, organising and saving vCard contact files.

## Scope

- Open `.vcf` files from the device
- Read contacts locally in the browser
- Search large contact lists
- Incrementally render contacts for better performance
- Edit common vCard fields
- Add and delete contacts
- Save an edited `.vcf`
- Warn before leaving with unsaved changes
- Preserve unsupported vCard properties where possible

## Privacy

Contact data is kept in browser memory for the current session. The app does not use localStorage, IndexedDB, Firebase, accounts, or cloud upload.

Closing or reloading the page discards unsaved changes.

## Current format

vCard / VCF is the initial supported contact-file format.
