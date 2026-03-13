Otherscape Fantasy Grounds Sheet v0.1

Contents
- base.xml
- campaign/charsheet.xml
- campaign/charsheet_themes.xml
- campaign/charsheet_loadout.xml
- strings/strings_otherscape.xml

What this package does
- Creates a CoreRPG-derived character sheet with two tabs:
  - Themes
  - Loadout
- Themes tab includes 4 fixed Otherscape theme cards.
- Each theme card includes:
  - Theme name
  - Family dropdown (Mythos / Self / Noise)
  - 6 tag rows with Active and Weakness checkboxes
  - Identity field
  - Theme Special name
  - Theme Special text
  - 3 upgrade checkboxes
- Loadout tab includes 8 fixed rows with:
  - On checkbox
  - Item name
  - Note

How to use
1. Unzip this folder into a new FG ruleset folder, or merge these files into your existing ruleset.
2. If merging into an existing ruleset:
   - add the includefile lines from base.xml
   - make sure your existing charsheet windowclass is replaced or merged with campaign/charsheet.xml
   - include the strings file
3. Launch Fantasy Grounds and create/open a character.

Notes
- This is intentionally v0.1 and focuses only on Themes and Loadout.
- No tag power automation is included yet.
- No tag combos, rules reference, portrait styling, or family summary counters yet.
