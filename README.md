depth-wall
==========

#### 1. Running Locally
```
npm install
foreman start
```

#### 2. Running Remote
Install the heroku toolbelt, login, and then run the following commands
```
heroku create
git push heroku master
heroku open
```

#### 3. Linking an iOS Device
Point Safari on your iOS device to `http://[my-heroku-app-name].herokuapp.com/sensor`

Realistically only iPhones are supported, because it's the only iOS device with a compass (so far).
