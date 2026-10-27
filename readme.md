# Subject to Change
<br>
# The Goal:
- a fullstack web application that can stream lossless music
- have a database that has the songs themselft and is hosted 
- backend pull the flac files and then reads and streams them outward to the front end

## How does the tech stack of this work?
- *Front End* - VueJS and tailwind css
- *Backend* - Go based backend API that handles music playback and fetching
- *DataBase* - postgress database stores info, flac lives on hard drives
- *Hosting* -  containarized into a docker containers via docker compose along with cicd pipeline for easy deployment and testing hosted on a local computer acting as a vps along with nginx

## Early feature set idea:
- can play pause forward and backwards music
- can shuffle 
- can also make your own playlist 
- can search the database of songs to pick which to play from artist
- can also add and upload lossless music
- can also download lossless music 

