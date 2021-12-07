# Spotify-Data-301
# Contributors: Jack Engstrom, Matt Cuento, Rahul Nair, Ujwal Jain

Data Science project for Cal Poly Class DATA 301 

How to Run:
- If you want to use our spotify data:
    - Ignore files (mc_group_project.ipynb and preprocessing.ipynb), they are meant to create the _history_with_features files in the data folders.
    - Run any of the other notebook files as they are, the data they need is contained in the previously mentioned data folders.
- If you have your own spotify data:
    - You also need to get spotify API keys
    - Then set up a .env file containing variables
        - USERNAME your spotify username, will be the same as the prefic of the data folder and the prefix of your files
        - CLIENT_ID your spotify key
        - CLIENT_SECRET your spotify secret key
    - Run files mc_group_project.ipynb and preprocessing.ipynb in that order, that will get the data required by the other scripts and store it
        - mc_group_project.ipynb will take approximately 30-60 minutes to run depending on the size of your data, there is simply a lot of API calls that need to be made
    - Run any of the other notebook files as they are

