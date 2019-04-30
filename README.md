# EXPRESS GEOSUPPORT
An HTTP API for GeoSupport

## Development

All development must occur either within the Docker container or within a Linux environment. *This includes installing dependencies.*

Use `bin/run` to add node dependencies. For example:

`bin/run npm install busboy`

### Run the development server

```bash
docker run \
    -it \
    -v $PWD:/express-geosupport \
    -w /express-geosupport \
    -p 4000:4000 \
  chriswhong/geosupport ./bin/www
```

Visit [http://localhost:4000](http://localhost:4000)

### Run an interactive terminal

```bash
docker run \
    -it \
    -v $PWD:/express-geosupport \
    -w /express-geosupport \
    -p 4000:4000 \
  chriswhong/geosupport /bin/bash
```
