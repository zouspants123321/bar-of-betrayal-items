# Bar of Betrayal: Steam item icons

The pictures Steam shows for Bar of Betrayal's premium characters and the pack of every character, in players'
inventories and the item store. Steam downloads each one from here (its `icon_url` and `icon_url_large` in the game's
item definitions), so **don't move, rename or delete these files**.

- `items/<character>.png`: 200x200 · `items/<character>_large.png`: 2048x2048
- `items/pack_all.png` / `items/pack_all_large.png`: the pack

Made by the game's art pipeline (`art/build/export_characters.lua`); a new character's icons are added here when it is.
