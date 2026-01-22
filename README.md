# Unlock all console commands for Left 4 Dead 2
Place the .smx file into the <code>addons\sourcemod\plugins</code> directory. This plugin allows you to directly execute, in the console, the commands that have the "launcher" (including duplicate "launcher" tags) and "cmd" flags from the list at https://developer.valvesoftware.com/wiki/List_of_Left_4_Dead_2_console_commands_and_variables. These commands will also appear in the command drop-down text. For example, take the "developer" command—it has the flags "launcher" (note: corrected from the original "luancher", "cl"）.

<img width="106" height="57" alt="image" src="https://github.com/user-attachments/assets/a9f9394b-d95b-43fe-8d3b-bcf8834b109b" />

Note: You must first use the map command to create and load a map, and enter the game—only then can this plugin be loaded and used.Note: You must first use the map command to create and load a map, and enter the game—only then can this plugin be loaded and used.Note: You must first use the map command to create and load a map, and enter the game—only then can this plugin be loaded and used.Note: You must first use the map command to create and load a map, and enter the game—only then can this plugin be loaded and used.

The function of the "developer" command is: Set developer message level. According to the syntax of this command, you can increase the value that follows it to view more developer debugging information in the console.The function of the "developer" command is: Set developer message level. According to the syntax of this command, you can increase the value that follows it to view more developer debugging information in the console.
For example: developer 2

<img width="161" height="58" alt="image" src="https://github.com/user-attachments/assets/c25866e1-1e9b-4e4f-8909-8dc8f92454c9" />

Press Enter to execute：

<img width="532" height="323" alt="image" src="https://github.com/user-attachments/assets/c120774b-bdf1-4187-80e3-a6fe5e7257fc" />

Some launcher commands may require enabling "sv_cheats 1". If you find this troublesome, add "-dev" to your launch options—this will enable sv_cheats 1 by default.
