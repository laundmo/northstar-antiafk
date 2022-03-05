# Anti AFK

Mod that kicks AFK players. Highly Configurable

# Configuration

| ConVar          | Default                         | Description                                                                               |
| --------------- | ------------------------------- | ----------------------------------------------------------------------------------------- |
| antiafk_enabled | 1                               | Whether Anti AFK should run (1 is on, 0 is off).                                          |
| antiafk_immune  |                                 | List of Pipe `\|` seperated UIDs which are immune.                                        |
| antiafk_message | "YOU\nARE\nAFK!\nPLEASE\nMOVE!" | Message which will be displayed to players `antiafk_warn` seconds before they are kicked. |

| PlaylistVar       | Default | Description                                                              |
| ----------------- | ------- | ------------------------------------------------------------------------ |
| antiafk_grace     | 30.0    | Seconds since the last movement event for a alive player to be kicked.   |
| antiafk_gracedead | 360.0   | Seconds since the last movement event for a dead player to be kicked.    |
| antiafk_warn      | 10.0    | Seconds _before_ the player is kicked for the warning message to appear. |
| antiafk_interval  | 2.0     | Interval in Seconds for AFK checks                                       |
