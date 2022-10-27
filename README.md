# Giveaway-watcher

Simple Twitch chatbot to watch for StreamElements giveaway announcements, watch for winner response, and call some commands 
the streamer might find useful

Requires Instafluff's ChatBlocks 
 - Hosted version: https://www.instafluff.tv/ChatBlocks/
 - github repository: https://github.com/instafluff/ChatBlocks

Sends the following commands to the chat for the streamer's use:
 - !gstart 
 - !gstop  
 - !waiting <username> 
 - !winner 
 - !womp   

When a name is drawn, it will send an announcement to chat, start a 60 second timer, and ONLY IF it is run from a different 
user account than the streamer, whisper the streamer with the winner's name.
