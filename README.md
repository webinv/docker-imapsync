#  Supported tags and respective Dockerfile links

- `1.836`, `latest` [(1.836/Dockerfile)](https://github.com/webinv/docker-imapsync/blob/master/1.836/Dockerfile)

# Run

```docker run -ti --rm webinventions/imapsync \
       --host1 example.com --port1 993 --user1 test1 --password1 secret1 --ssl1 \
       --host2 example2.com --port2 993--user2 test2 --password2 secret2 --ssl2 \
       --addheader
```
    
[Usage details](https://github.com/imapsync/imapsync/blob/master/README)