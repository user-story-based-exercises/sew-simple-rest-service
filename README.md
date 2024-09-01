SEW | CORE | Simple REST Service

## Overview
The main focus of this year will be the development of a web application for uploading and consuming music. Let's call this project YouSong.

## User Story 1
*As a song provider I want my songs to be available through an api, so that everyone can use the data and/or create their own interface.*

### Acceptance Criteria
- A REST api, which provides all songs, is available.
- A song is repesented as a model on the server.
- The properties title, artist, genre, length are available for each song.
- Each song is stored in a database.
- The endpoint /api/songs provides the caller with all songs available in the database.

### Hint
- If you run into the CORS issue, try to use the annotation @CrossOrigin on your repository.

## User Story 2
*As a consumer I want to see a list of all available songs, so that I can pick the one that suits me the most.*

### Acceptance Criteria
- A VueJs app, which displays the songs from the REST api, is available.
- Each song is displayed using a song-component.
- The properties for each song are displayed.
