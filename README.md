# MG11 Statement Writer

A single-page tool for writing MG11 witness statements and laying them out as numbered A4 pages.

- Live A4 preview with automatic page count in the declaration and continuation sheets
- Print / Save as PDF
- Optional restricted contact details page
- Drafts are saved in your own browser (localStorage); nothing is sent to a server

Hosted with GitHub Pages: everything lives in `index.html`.

## Draft with Claude

Paste rough notes into **Draft with Claude** and it writes the statement in the first person, using the details already on the form. It fills in any empty witness fields, and lists anything you still need to ask the witness.

To use it, add your own Anthropic API key under **API settings** (get one at console.anthropic.com). The key is stored only in your browser and is sent directly to api.anthropic.com. Have the witness read and agree every line before signing.
