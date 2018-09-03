# line-flex-worldcup
Demonstrate how LINE Flex Message work, by implementing World Cup 2018 score update apps with Flex Message.

## How it work
Please visit my blog [Using Flex Message to create World Cup LINE Bot](https://medium.com/@kamnan43/using-flex-message-to-create-world-cup-line-bot-60e0591f9d02)

# Install
Clone and run
```
npm install
```
Create config file in JSON and named it as `config.json`
```json
{
  "channelAccessToken": "YOUR_CHANNEL_ACCESS_TOKEN",
  "channelSecret": "YOUR_CHANNEL_SECRET",
  "BASE_URL": "https://your.host.name",
  "PORT": 3000,
  "firebase": {
    "apiKey": "xxxxx",
    "authDomain": "xxxxx",
    "databaseURL": "https://xxxxx.firebaseio.com",
    "projectId": "xxxxx",
    "storageBucket": "",
    "messagingSenderId": "xxxxx",
    "serviceAccountFile": "path/to/firebase-admin-key.json"
  },
  "apiFootball" : {
    "apiKey": "API_FOOTBALL_KEY",
    "leagues": [1736, 1737, 1738, 1739, 1740, 1741, 1742, 1743, 1803] ,
    "startDate": "2018-06-13",
    "endDate": "2018-07-16",
    "url" : "http://apifootball.com/api/"
  }
}
```
Run
```
npm start
```
then you can access [http://localhost:3000](http://localhost:3000)

*** apiFootball  is paid service ***
## Author
Sitthi Thiammekha
