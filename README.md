# Spin Bike server

Server communicates with the [Spin Bike UI](https://github.com/lamosty/spin-bike-ui) through WebSocket. When a trip is started and while it is running, data are sent to this server, which saves it into a RethinkDB database. User is then able to browse through his/her past biking records and compare the performance.
