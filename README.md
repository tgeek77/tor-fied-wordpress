# tor-fied-wordpress
## Intro: This is a docker-compose script for creating a simple wordpress hidden service onion.
### Special thanks to [cmehay](https://github.com/cmehay/docker-tor-hidden-service) and to the [Docker project](https://docs.docker.com/compose/wordpress/) for their projects which allowed me to built this one.

### About the script:
In truth, very little was done apart from copying and pasting from the two above mentioned projects into a new docker-compose file and tailoring it a little to make the two projects works together. Be mindful that the "wordpress" mysql and the mysql root passwords are terrible and need to be changed to something a little more reliable than password if you actually want a site that goes live.

## Usage:

```
$ docker-compose up -d
```

