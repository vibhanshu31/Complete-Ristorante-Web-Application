# Ristorante ConFusion 1.0

A web application built for a restaurant where customers can make their
restaurant bookings and gather more information about the restaurant.

<br>

# Quick Start :rocket:

### Add a config.js file in the root folder with the following

```
module.exports = {
	"secretKey": "secret",
	"mongoURI": "<your_mongoDB_Atlas_uri_with_credentials>"
}
```

### Install server dependencies

```
npm install
```

### Install client dependencies

```
cd client
npm install
```

### Run both Express & React from root

```
npm run dev
```

### Build for production

```
cd client
npm run build
```
