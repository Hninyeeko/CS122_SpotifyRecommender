**Project: Spotify Dashboard & Song Recommender**

Team Chrapple: Apple Ko and Christopher Oh

This project is implemented in two parts: Spotify Dashboard and the Song Recommendation System. SpotifyDashboard.ipynb contains the code to build the Spotify music dashboard and Listenbrainz Recommendation.ipynb contains the code for the song recommendation system.

**How to Run the Spotify Music Dashboard Program**

**Step 1:** Open the SpotifyDashboard.ipynb file and run the first two cells to install spotipy and import the necessary libraries.

**Step 2:** Then run the third cell to set up and authenticate the Spotify app. After running the cell, click on the url link that is generated in the output. This link will redirect you to a new tab on your browser and ask you to log in to your Spotify account. (See Appendix A in report)

**Step 3:** After successful login, you will be redirected to a new tab on your browser. Copy the full url of this new tab. (See Appendix B in report)

**Step 4:** Run the fourth cell and wait for an input box to appear in the output. Paste the full url of the redirected page that you copied in the previous step and press enter. This will parse the url to extract the access token and authenticate the user. (See Appendix C in report)

**Step 5:** Run the fifth cell to define the functions that make the API calls to access your Spotify data.

**Step 6:** Run the sixth cell to define the function that will build the layout of your music profile dashboard.

**Step 7:** Run the seventh cell to display the dashboard that you’ve created and Voila!!


**How to Run the ListenBrainz Recommender**

**Step 1:** Open the ListenBrainz_Recommendation.ipynb. Run the first cell to install musicbrainz api, playwright library, and spotify api

**Step 2:** Run the next following cells. These are the functions that fetch data from MusicBrainz, ListenBrainz, and Spotify

**Step 3:** Go to the last cell commented with RUN ME

**Step 4:** Find the ListenBrainz url for the album(s) you like. The code will recommend the songs based on the album(s). For example, the url for The Beatles' Sgt Pepper's Lonely Hearts Club is https://listenbrainz.org/album/bff544a7-56e0-3ed6-9e0f-3b676cca9111/

**Step 5:** Copy and paste the urls into the list marked as "album_urls" as string literals. Note: While the code can process a list of albums, in practice it's better to do this one album at a time, as each album takes roughly 8-10 minutes to gather the recommendations for.

**Step 6:** Run the cell and receive the song recommendations!

