# Spotify_Music_Discovery_LS_DS_BW
## TrackFinder 2021
This is a Lambda school build week project - an app to recommend song suggestions based on data from the Spotify library. Our app will take the name of a song from a user and returns ten suggestions based on a K-Nearest Neighbors model.

[Check out the results here.](https://trackfinder2021.herokuapp.com/)

## Data Source
The spotify data set was already pretty clean, thankfully! Specifically, we used the ['data.csv' file from Kaggle](https://www.kaggle.com/yamaerenay/spotify-dataset-19212020-160k-tracks?select=data.csv).

## Running locally in the terminal
Once you cd to the main directory, install the dependencies, and activate the virtual environment, run the following code:
```
export FLASK_APP=app
flask run
```

## Built with
- Python3
- Flask

## Authors
1. [Israel Aikulola](https://github.com/israelaikulola)
2. [Filipe Collares](https://github.com/fcollares)
3. [Hillary Khan](https://github.com/hillarykhan)
4. [Stephen Lupsha](https://github.com/StephenSpicer)
5. [Nick Major](https://github.com/SophistryDude)

## Moving forward
We hope to add access to the Spotify API and several other features, including filters for return suggestions, links to tracks in the Spotify app, and more visuals.

# License
This project is licensed under the MIT License - see the LICENSE.md file for details

MIT © hillarykhan
