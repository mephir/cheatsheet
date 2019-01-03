# Curl

### Return response status code only

```bash
$ curl --silent --write-out "%{http_code}"-o /dev/null url
```
