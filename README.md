## Installation

1. Clone repo
2. run `npm install`
3. Set up your MongoDB database:
Create a database and collections (users, chartedSongs).
Update database configuration in your code if necessary.
run `node server.js`
5. Open the app in your browser:
## Usage
Random Radio Station
The home page (/home) displays a random station daily.
Users can listen to the station using the embedded audio player.
A "Vote for this station" button allows users to vote on the current station.

Charted Songs
Users can add new songs to the chart using the form on the home page.
Songs are listed with details such as artist name, song title, and votes.
Users can:
Upvote or downvote songs using the thumbs-up and thumbs-down icons.
Delete songs using the trash icon.

## API Integration
Radio Browser API
The Radio Browser API is used to fetch random radio stations and register votes for stations.

Endpoints:
/random-station: Fetches a random radio station to display on the home page.
/vote-station: Registers a vote for the selected station.

## License
This project is licensed under the MIT License. See the LICENSE file for details.

<img width="940" alt="Index" src="https://github.com/user-attachments/assets/2ac56f6b-8bd4-44b1-ae24-cb812a28a279">

<img width="940" alt="login" src="https://github.com/user-attachments/assets/648b1d1c-fafd-4177-a678-dc28557576d7">

<img width="940" alt="home" src="https://github.com/user-attachments/assets/0e0f891e-1ec3-4188-a5b5-ba6453517901">




