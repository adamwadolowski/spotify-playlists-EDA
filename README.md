# Welcome!
This repository stores files used to collect, transform and analyze playlists data from [Spotify API](https://developer.spotify.com/documentation/web-api). If you are only interested in the main results, please visit [this page](https://adamwadolowski.github.io/spotify-playlists-EDA/)).


### Replicating the results
Below, you can find instructions how to run the code stored in this repository.

1. Clone this repository to your prefered location.

2. Recreate the environment:
    + Download miniconda if you haven't done so already and install it on your computer.
    + In a terminal of your preference create a new environment and install necessary packages.
```bash
conda init
conda create --name spotifyproject
conda activate spotifyproject
conda install pip
pip install -r requirements.txt
```
2. Go to [this website](https://developer.spotify.com/documentation/web-api) and follow the instructions to obtain your Spotify API credentials. You might need to create an account if you are not a Spotify user.
3. Create a `.env` file in the folder where all the files from this repository are stored and save your client id and client secret in the following format where `<your client id>` and `<your client secret>` should be replaced with your account details. 
```json
{
    "CLIENT_ID": "<your client id>",
    "CLIENT_SECRET":  "<your client secret>"
}
```

4. You are ready to go! Run the jupyter notebooks in the [notebooks](/notebooks) folder according to their numbering.

### Please note
The playlists, and thus, visualizations you obtain will differ depending on your country of residence and the date as the API's responses are matched to the region you are in and the database is updated every day. My data was collected for the region of UK on July $27^{th}$ 2024.


### GenAI acknowledgement
Throughout the project I made use of chatGPT-4o. To distinguish between my own work and the cooperation with the LLM, I made comments similar to 'chatGPT helped in the line below' and 'chatGPT helped in this cell'. In general, its use was mostly consering debugging my code and one visualization where I wanted to replace points with images.
