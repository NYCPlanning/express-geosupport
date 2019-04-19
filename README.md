# EXPRESS GEOSUPPORT
An HTTP API for GeoSupport

## Docker Development

Run the server

```bash
docker run \
    -it \
    -v $PWD:/express-geosupport \
    -w /express-geosupport \
    -p 4000:4000 \
  chriswhong/geosupport ./bin/www
```

Visit [http://localhost:4000](http://localhost:4000)


Interactive terminal:

```bash
docker run \
    -it \
    -v $PWD:/express-geosupport \
    -w /express-geosupport \
    -p 4000:4000 \
  chriswhong/geosupport /bin/bash
```
