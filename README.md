# Discord bot Python env

This is just a small container files that I created to set up Python with the goal to code a Discord bot
The requirements.txt file includes the Discord.py library but you can remove that and it's bassicaly a Python dev container

## Setup
1. Clone the repo.
2. Create a '.env' file and add 'DISCORD_TOKEN=your_token'. Replace your_token for your actual bot TOKEN key
3. Run 'docker compose up -d' to build the container
4. The container will run in the background and to run your .py file just use 'docker compose exec python-dev python <name of file>.py'
