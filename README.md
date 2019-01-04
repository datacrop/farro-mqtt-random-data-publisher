This is a random number generator that publishes the values it generates to an MQTT topic.

### REQUIREMENTS

* [Node.js](https://nodejs.org/) >= *10.1.0*
* [npm](https://www.npmjs.com/) >= *5.6.0*
* Any message broker that implements the MQTT protocol version 3.1.x or later.

### CLONE

    git clone git@github.com:far-edge/mqtt-random-data-publisher.git

### CONFIGURE

Create `.env` based on `.env.example`.

    cp .env.example .env

Edit `.env`.

### CREATE THE VIRTUAL ENVIRONMENT

    cd mqtt-random-data-publisher
    nodeenv -n 10.1.0 --prebuilt env

### ACTIVATE THE VIRTUAL ENVIRONMENT

    . env/bin/activate

### INSTALL THE DEPENDENCIES

    npm install

### RUN

    npm start

### DEACTIVATE THE VIRTUAL ENVIRONMENT

    deactivate_node

### LINT

    npm run lint
