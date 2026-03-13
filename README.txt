Otherscape FG Sheet v0.2 (tightened package)

What changed from the first pass:
- Reduced the project to a clean CoreRPG child ruleset package
- Uses a simple two-tab character sheet: Themes and Loadout
- Uses fixed controls and predictable DB paths only
- Removes unnecessary placeholders and keeps the XML easy to extend
- Theme family selector uses a proper CoreRPG button_stringcycler

Key windowclasses:
- charsheet
- charsheet_themes
- charsheet_loadout

Key DB paths:
- themes.theme1..theme4
- loadout.item1..item8

Notes:
- This package is intentionally manual-entry focused.
- No automation has been added for power counting, theme balancing, or tag combos yet.
- If your existing ruleset already has custom strings, fonts, or graphics, this package should still load because it inherits from CoreRPG.


Version note: Theme cards now use 8 bordered rows each (6 power tag rows, 2 weakness tag rows), with one checkbox per row.
