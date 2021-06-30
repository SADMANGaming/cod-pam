# Setup Guide
First, start by uploading the codam_pam.gsc to main/codam.

Then proceed, to codam/modlist.gsc and insert the plugin to initialize on the start of the server.

[[ register ]]( "AntiPam", codam\anti_pam::main, "antipam" );
And then, open the dedicated.cfg or server.cfg. The main server configuration and insert this variable at the bottom of the config and also make sure the game type is set to SD before starting.

serverstate ready_up
If you're stuck in playing mode, you can restore the ready_up mode by entering this via console or rcon:

/rcon <pass> serverstate ready_up
serverstate ready_up
