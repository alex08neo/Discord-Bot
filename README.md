# Discord-Bot
A Discord AI bot which uses Python and integrates ChatGPT to generate responses for the prompts given by the user


## Getting the model ready

Open the command prompt in the folder where you have downloaded the files of this repository. Type `pip install requirements.txt` to download the required Python libraries required for this model to run. The Python libraries required for this model are listed in the '**requirements.txt**' file

## Running the model

+ Open the Discord app. Create a server of your own or use an existing server to make a bot of your own. To get help on how to create a Discord Bot on any server, please refer to [https://www.ionos.com/digitalguide/server/know-how/creating-discord-bot/](https://www.ionos.com/digitalguide/server/know-how/creating-discord-bot/)
+ Save the token you get while creating the bot. Login to [https://platform.openai.com/](https://platform.openai.com/) and create your API key from [https://platform.openai.com/account/api-keys](https://platform.openai.com/account/api-keys). Save this API key.
+ Go to the '**model.py**' file and replace the value of the `API_KEY` variable with a string containing your own OpenAI API key.
+ Go to the '**main.py**' file and replace the value of the `BOT_TOKEN` variable with a string containing your Discord Bot token.
+ Run the `main.py` file to initialize the bot. Go to your Discord server and see the bot in action.
