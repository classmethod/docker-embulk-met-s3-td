# Embulk with config file

Data import from Amazon S3 to Treasure Data

# Usage

```
$ docker run -ti \
  -e MAX_THREADS="16" \
  -e S3BUCKET="" \
  -e MET_SERVICE="" \ # a piece of S3 prefix
  -e YEAR="" \        # a piece of S3 prefix
  -e MONTH="" \       # a piece of S3 prefix
  -e DAY="" \         # a piece of S3 prefix
  -e TDAPIKEY="" \
  -e TDDATABASE="" \
  -e TDTABLE="" \
classmethod/embulk-met-s3-td 
```

