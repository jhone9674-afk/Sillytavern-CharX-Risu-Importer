# ST-CharX Risu Importer

Full RisuAI Character V3 / `.charx` support for SillyTavern.

This project adds RisuAI-focused import and compatibility features to SillyTavern, so RisuAI characters can work much closer to how they work inside RisuAI itself.

It is made for users who want to import RisuAI characters into SillyTavern while keeping support for things like images, regex, background embedding HTML, trigger scripts, multiple portraits, and other RisuAI card behavior.

## What It Supports

- RisuAI Character V3 `.charx` import 
- Import button inside SillyTavern
- RisuAI regex import as **Scoped Scripts**
- RisuAI image calls in chat
- RisuAI Background Embedding HTML
- RisuAI Trigger Script support
- Character expressions / portrait assets
- Multiple portrait images, with arrow buttons to switch portraits
- Lorebook and character information import
- Better compatibility for advanced RisuAI cards

## Import Button

After installation, the importer appears in SillyTavern as the **pink arrow button pointing up** near the top UI.

<img width="79" height="57" alt="image" src="https://github.com/user-attachments/assets/51e05d88-57ed-4065-aed3-f4290fa65ae8" />

Use that button to import supported RisuAI cards.

## Installation

This package is made to be installed by **extracting it directly into your SillyTavern folder**.

### Steps

1. Close SillyTavern.
2. Back up your SillyTavern src folder first.
3. Download `ST-CharX Risu Importer.zip`.
4. Extract the zip into your main `SillyTavern` folder.
5. If Windows asks to replace files, choose **Replace**.
6. Start SillyTavern again.

That’s it.

The zip is already organized so the files fall into the correct places automatically:
- `plugins/`
- `public/scripts/extensions/`
- `src/`

## How To Use

1. Open SillyTavern.
2. Click the **pink import arrow**. <img width="79" height="57" alt="image" src="https://github.com/user-attachments/assets/84730391-d189-41f8-8f5f-c2ad9dcc755c" />

3. Select a supported RisuAI card:
   - `.charx`
4. Import the character.
5. Open the imported the CharX character and use it normally.

## RisuAI Features Inside SillyTavern

This project adds support for several RisuAI-specific systems that are normally missing or incomplete in SillyTavern.

### Background Embedding HTML
RisuAI background embedding HTML can be imported and used inside SillyTavern.

### Trigger Script
A **Trigger Script (RisuAI)** box is available for compatible characters, so imported trigger data can be viewed and edited.

<img width="1624" height="397" alt="image" src="https://github.com/user-attachments/assets/8a081231-9e85-4927-9d2e-7449154ea938" />

### Scoped Scripts / Regex
RisuAI regex rules are imported as **Scoped Scripts** when possible, so card logic can continue working in chat.

<img width="822" height="286" alt="image" src="https://github.com/user-attachments/assets/4fdbaf32-3092-4b96-9faf-b37e46aa7957" />


### Multiple Portraits
If the card has multiple portrait images, you can switch between them using the portrait arrows.

<img width="83" height="100" alt="image" src="https://github.com/user-attachments/assets/0ecb7532-28a5-4760-9d43-e4bdcd439bf0" />

### Images In Chat
RisuAI image calls used by the character can be rendered in chat, including character-specific image behavior used by many advanced cards.
<img width="1619" height="871" alt="image" src="https://github.com/user-attachments/assets/fae9d33b-bef3-44cd-8cc4-885467e9c1f3" />

## Important Notes

- This is **not** a normal one-click SillyTavern extension install.
- This package includes changes outside the extension folder too.
- Because of that, installation is done by extracting into the main SillyTavern folder.
- Always back up your SillyTavern folder before updating or replacing files.

## Compatibility

This project is focused on **RisuAI Character V3 / CharX** compatibility.

Support includes:
- character import
- regex/scoped scripts
- lorebook data
- chat images
- background embedding HTML
- trigger behavior
- portrait assets

Some very unusual or extremely custom RisuAI cards may still behave differently depending on how their scripts were built.

## Credits

- [RisuAI](https://github.com/kwaroran/RisuAI)
- [SillyTavern](https://github.com/SillyTavern/SillyTavern)

## Disclaimer

This project is a compatibility extension/patch for SillyTavern to improve support for RisuAI cards.  
It is not an official release from the RisuAI team or the SillyTavern team.
This Project is not out of possible bugs.
This projected it was vibecoded by multiple AI.
