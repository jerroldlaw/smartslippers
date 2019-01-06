# Smart Slippers
### A project done for the Health Transformation Hackathon 2018.
The goal of the smart slippers is to use IoT technology to create fall detection devices for the elderly at risk when they are at home or outside.

## Implementation
The backend server consists of a websocket server which will transmit data from the slippers to the frontend SPA.
Data included:
##### Exact location of person in the home.
This is identified by bluetooth signals triangulation to detect the exact location of the user. 
##### Orienctation of slippers.
The orientation of the slippers was identified using a gyroscope attached to the smart slippers.
##### Fall detection.
Fall detection was identified by unsual acceleration from the accelerometer attached to the smart slippers.

## Tech Stack
Frontend:
```
React
```
Backend
```
Node.js
Express
Arduino C/C++
Python
```

![screenshot](https://i.imgur.com/sUfkXCp.png)

## Credits
* [jerroldlaw](https://github.com/jerroldlaw)
* [alvinwang19](https://github.com/alvinwang19)
* [dennis-ng](https://github.com/dennis-ng)
* [joncwr](https://github.com/joncwr)
