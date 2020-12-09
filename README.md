The github repository is made as a part of the final exam project for the course 02805, Social graphs and interactions, at DTU during the fall of 2020.

The project is presented on the [webpage](https://artists-collaborations-network.netlify.app).
While all analysis are showed and explained in depth in the `main_TheExplainerNotebook.ipynb`.


The structure of the repository is explained below:

```
├── main_TheExplainerNotebook.ipynb		<- main explainer notebook where all analysis is showed and explained.
├── data 
│   ├── graphs					<- networkx graphs
│   │   ├── G_ARTGen.graphml
│   │   ├── G_final.graphml
│   │	 ├── G_final_sentiment.graphml
│   │	 └── G_uNW.graphml
│   ├── other_files				<- data files used for the notebooks
│   │   ├── artist_song_id.json
│   │   ├── df_artist_info.pkl
│   │   ├── df_song_info.pkl
│   │   ├── genre_text.json
│   │   ├── genre_text.json
│   │	├── song_sentiment.json
│   │	└── song_year.json
│   ├── sentiment			
│   │   └── Data_set_S1.txt         <- file used to calculated sentiment of words
│   └── network.json
├── src		
│   ├── analysis				
│   │   ├── data_preparation.ipynb		<- notebook to prepare data for the analysis
│   │   ├── network_artists.ipynb		  <- notebook to prepare and filter the network before analysis
│   │	└── useful_functions.ipynb     <- notebook with functions used through out the notebooks
│   └── data
│   │   ├── scraper-genius.ipynb		  <- notebook used for extracting song lyrics from Genius
│   │   ├── scraper-spotify.ipynb		  <- notebook used for extracting information from Spotify
│   │	└── scraper-wikipedia.ipynb		<- notebook used to retrieve list of artists
├── webpage	                          <- scripts used to construct plots for the webpage
├── README.md
└── requirements.txt
```

Due to datalimitations smaller datafiles can be found under the 'data/' folder.
The bulk of the data can only be downloaded from [sharpoint](https://dtudk.sharepoint.com/:f:/s/SocialGraphs/EuBRcNF_in5DstLNO9TLj-cB15cRZaLtjwzbqWebhIfczw?e=M93Op4) due to data limitations on github. 



Authors:
- Andreas Kaae, s154395
- Silvia De Sojo, s192374
- Pietro Rampazzo, s203257
