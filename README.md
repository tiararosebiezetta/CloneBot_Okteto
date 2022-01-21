# CloneBot_Okteto
CloneBot for Okteto Cloud

## Running
For quick use, use this repo directly and deploy it to Okteto Cloud. Customize `docker-compose.yml` as you want if needed.

## Variables
`telegram_token`, `user_ids`, `group_ids`, `PORT`

## Notice
Add `PORT` as an environmental variable, and add any port you want. If you don't know, just fill `8080`. It's to make it possible to ping the app link to avoid sleeping (I hope) or else, the deployment won't work.
