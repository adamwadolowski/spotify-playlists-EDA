# Welcome!

Below, you can find instructions how to run the code stored in this repository.

1. Clone this repository to your prefered location.

2. Recreate the environment:
    + Download miniconda if you haven't done so already and install it on your computer.
    + In powershell or command prompt create a new environment and install necessary packages.
        '''bash
            conda init
            conda create --name spotifyproject
            conda activate spotifyproject
            conda install pip
            pip instal -r requirements.txt
        '''
2. Go to [this website](https://developer.spotify.com/documentation/web-api) and follow the instructions to obtain your Spotify API credentials. You might need to create an account if you are not a Spotify user.
3. Create a `.env` file in the folder where all the files from this repository are stored and save your client id and client secret in the following format where `<your client id>` and `<your client secret>` should be replaced. 
    '''json
    {
        "CLIENT_ID": "<your client id>",
        "CLIENT_SECRET":  "<your client secret>"
    }
    '''

4. You are ready to go, run the notebooks in the `notebooks` folder according to their numbering.

### Please note
The playlists, and thus, visualizations you obtain will differ depending on your country of residence as the API's responses are matched to the region you are in.