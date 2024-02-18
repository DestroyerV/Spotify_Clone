# Spotify Clone

A Simple and beginner level web based music player with spotify like UI.

## Features:

- **Spotify-like UI**.
- **Customizable**.
- **Custom Playlist**.
- **Custom API for songs**.
- **Local songs**.
- **Offline mode**.
- **Responsive**.
- **Many more**.

## How to use:

- ### *Use like local music player*

  1. Clone this repository using
   ``git clone https://github.com/DestroyerV/Spotify_Clone.git``.

   2. Create playlists and add songs in `songs` folder.
   
   3. Add a image you want to display for your playlist in the playlist folder with the name of `cover.jpg`.

   4. Add `info.json` in each playlist folder for tile and description of the playlist like the formate below:
        > 
        > ```json
        > {
        >     "title": "Playlist Name",
        >     "description": "Playlist Description"
        > }
        > ```
   
    5. Change the URL path of line 23, 76, 89 in the `script.js` file like.
    > ```js
    > 23. https://127.0.0.1:3000/${currFolder}/`
    > 76. https://127.0.0.1:3000/songs/
    > 89. https://127.0.0.1:3000/songs/${folder}/info.json`
    >```
   
   6. Run the `index.html` and injoy your music.

- ### *Use like online music player*

  1. Follow all the steps mentioned above.

  2. Just replace all  the URL of the `5` step with your google drive or custom API.

  3. Deploy the project and enjoy.

---

> ### Things to be noted :
> 1. Do not add any song direct in the `songs` folder. Add the songs in their corresponding `${playlist}` folder.
> 2. Your `${playlist}` folder contains `cover.jpg` and `info.json` files.
> 3. Your API server must have  `*Access-Control-Allow-Origin header*` otherwise it will give CORS error.
> 4. Add API only in the above format.

---
> # Project is open for condructions.

> # Made with ❤️ by [DestroyerV](https://github.com/DestroyerV)