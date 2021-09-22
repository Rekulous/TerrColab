[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/AndreVuillemot160/TerrColab/blob/main/TerrColab.ipynb)

## :hear_no_evil:  First of all, what is google Colab?
As the official FAQ says, colaboratory, or “Colab” for short, is a product from Google Research. Colab allows anybody to write and execute arbitrary python code through the browser, and is especially well suited to machine learning, data analysis and education. More technically, Colab is a hosted Jupyter notebook service that requires no setup to use, while providing free access to computing resources including GPUs.
In short, it is a vm provided for learning, running python code, machine learning or for general purpose.
## :moneybag:  Is it really free to use?
Yes, Colab is free to use. But there are some points which, according to me one should keep in mind:
1. Though colab is a free service, it shouldn't be exploited indiscriminately or without any care. One should value that its a resource offered for no cost and can get depleted/restricted if the demand increases out of control.
2. If it isn't obvious, one shouldn't run mission-critical services (like large and important servers/databases/python programs) on it. Its resources are not guaranteed and not unlimited, and the usage limits sometimes fluctuate. Also, the notebook has a maximum runtime of 12 hours, after which, it should be manually restarted.
3. One should not try to spread it as wildfire (in my opinion), that there's a free service available to every living being out there. If such a sudden boom in user base happens, Google would be forced to close down the free tier of google colab, devoiding many hobbists of the free service. Keep it like a secret, telling it to only those who are worthy and know how to use it.

Also, a note, by default the server uses Ubuntu VM and server writes everything in this VM, so please use the server config provided in this repo.
## :zap:  So, how does it actually work?
As Google Colab is a VM running Ubuntu 18.04 server as base OS, it can be easily used as a server. Here are the steps which the notebook performs to setup the server:
1. Update the system's apt cache.
2. Get Terraria server files and config file from repo.
3. Mount Google Drive to access the minecraft folder (Drive is used here to provide persistent storage).
4. Setup Ngrok (by asking for key by user and opening a tunnel at port 7777).
5. Change directory to the terratia folder on google drive (I have here used "terratia" as the server folder in the root directory of my Google's Team Drive, but you can also use this name as well for your team drive if you are lazy to edit files)
6. List/Print the file list on the screen to indicate succesful directory change.
7. Startup the Terraria server
8. ??????
9. PROFIT!

## Install
You must get **ALL** files including the serverconfig.txt, put them in your gdrive where you going to execute and follow the program steps.

## License
The project is licnsed under GNU GPL v3.

## Thanks
I would like to say thanks to the [MineColab](https://github.com/thecoder-001/MineColab) because most of the code is used here, is used here
