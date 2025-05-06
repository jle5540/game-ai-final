AI Final Project  

Names: Hayden Fisher, Joe Elgin, Aaron Earhart Repository:[ https://github.com/jle5540/game-ai-final ](https://github.com/jle5540/game-ai-final) 

Functions Added: 

- Character Creator Template 
  - This template acts as a character creator that will have the users give a name, choose what class they want, the sub-class, skills, and what the character’s background is. The save\_character tool is also attached to this template so that when the user is done creating their character, they can then save them and reuse them whenever they connect in the future. 
- Dungeon Master init Template Switching 
  - This is so that whenever the user connects to the server it won’t have then create a character if they have one saved. The saved character is in the character.json file. 
- Process Function Call 
  - This is included to help process the tool call when the user is ready to save their character. 
- Save Character 
  - This function is the one that the tool call uses to save the characters to the file character.json and then changes to the dm\_chat template. 
- Added Tool call in Chat Generator Function 
  - This is an if statement that will determine when to run the tool call. This is to force the AI to run the tool call function so that it doesn’t prematurely run it while the user is still creating their character. 

scenarios:
NONE