# Roll20-Macros
Just some Roll20.net macros that I've found/created/use for Roll20 D&amp;D.

### NPC Initiative

Simple macro that let's you run Initiative without opening the NPC character sheet.

`%{selected|npc_init}`

### PC Target Prompt

If using D&D5e put this in the Attack description on the character sheet. It prompts you for the target you are attacking. Very cool. See https://wiki.roll20.net/Running_D%26D5e_on_Roll20 for reference.

`Target @{target|token_name}`

### PC Initiative

`@{selected|token_name} Initiative [[1d20 + @{selected|initiative_bonus} &{tracker}]]`

### Perception

`@{selected|token_name} Perception [[1d20 + @{selected|perception_bonus}]]`

