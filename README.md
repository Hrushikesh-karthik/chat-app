This project demonstrates real world chat application which establishes a connection through socket.io.
I have used nodeJs and ExpressJs to make it done.
We might face cors error during execution and it can be handled by adding const io = require('socket.io')(8000, {cors: {origin: "*"}}); to index.js file.
