#
Live as @Equinox_astroBot on Telegram.
start with /help to know all commands.

# ATMOS Weather Bot

Telegram bot that fetches the latest accurate weather statistics that the user can subscribe to for daily/one-time updates, generate random aesthetic images from Unsplash, etc. Also has an admin panel supporting editing, deleting or blocking users, as well as changing bot settings (API Key).

## Frontend

This app is bootstrapped by Vite, and uses ReactJS for the frontend, and Firebase/FirebaseUI for auth purposes for the admin panel. Uses axios for networking ops and TailwindCSS for styling the UI.

## Backend

This app is bootstrapped with NestJS, along with NodeJS for the backend and uses ExpressJS as middleware. Uses axios for networking ops, nestjs-telegraf & telegraf for communicating with Telegram's BOT API and MongoDB for database storage. Utilizes OpenWeatherMap's Geocoding/Weather APIs for weather stats and Unsplash API for random images.

## Installation

Fork and clone the repo to your machine, and make sure you have npm/node installed prior to executing these commands.

### Backend

> `cd .\server`
> `npm install && npm i -g @nestjs/cli`
> `npm run start:dev`

Server should be ruuning on localhost:3000

### Frontend

> `cd .\client`
> `npm install`
> `npm run dev`
