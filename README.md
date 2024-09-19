# Music Recommendation and Event Finder SpotifyXTicketmaster

## Description
This project is designed to provide users with personalized music recommendations and local event suggestions based on their music preferences. By analyzing top tracks and genres from the Spotify Web API, and cross-referencing event data from Ticketmaster API, the feature helps users discover concerts and events that match their taste in music. The project extracts a user's top tracks and genres through Spotify, then uses this data to recommend nearby events related to their music interests.
This would be helpful to get a sense of what kind of music the user likes and recommend nearby events that match that taste. It is a very useful tool for people living in big cities like New York CIty because there are so many events and it is difficult to find the one event that matches people's taste the most. We tried to solve that problem here. 


## APIs Used
1. **Spotify Web API**  
   - **Purpose**: Extract top tracks, genres, and artists that reflect the user’s music taste.
   - **Reason**: Spotify's API provides detailed music preference data, which is crucial for generating personalized recommendations.

2. **Ticketmaster API**  
   - **Purpose**: Find music events and concerts near the user that align with their music preferences.
   - **Reason**: Ticketmaster’s database offers a wide array of event listings, making it the ideal choice for suggesting relevant local concerts and music festivals.

## How to Use the Feature
### Step 1: Clone the Repository
git clone https://github.com/your-username/your-repo.git

cd your-repo

### Step 2: Install Required Libraries
Ensure you have the following Python libraries installed:

pip install spotipy requests

### Step 3: Set Up API Keys
You will need API keys for both the Spotify Web API and the Ticketmaster API.

## Spotify Web API:
Create a developer account at Spotify Developer and register your app to get the following credentials:

Client ID

Client Secret

Redirect URI

## Ticketmaster API:
Sign up at Ticketmaster Developer and generate an API key.

### Step 4: Set Up Environment Variables
Create a .env file in the root directory and add your API keys as follows:

SPOTIFY_CLIENT_ID=your_spotify_client_id

SPOTIFY_CLIENT_SECRET=your_spotify_client_secret

SPOTIFY_REDIRECT_URI=your_spotify_redirect_uri

TICKETMASTER_API_KEY=your_ticketmaster_api_key


### Step 5: Run the Script

## Prerequisites

Python

Spotify Web API credentials (Client ID, Client Secret, Redirect URI)

Ticketmaster API key


### Future Improvements

-Enhance recommendation logic using machine learning to refine event suggestions.
-Implement additional event filtering based on date and location preferences.

### Contributors

Komal Neupane, 
Aabaran Paudel, 
Ashok Timsina