Repo Info
=========
Builds a [Squid] proxy [Docker] image.

Usage
-----
Spin up container(s) for proxy caching:
```
docker run -d --name squid -p 3128:3128 mrlesmithjr/squid
```

Spin up as a [Docker] swarm service:
```
docker service create --name squid --mode global -p 3128:3128 mrlesmithjr/squid
```

License
-------

BSD

Author Information
------------------

Larry Smith Jr.
- [@mrlesmithjr]
- [everythingshouldbevirtual.com]
- [mrlesmithjr@gmail.com]


[Docker]: <https://www.docker.com>
[Squid]: <http://www.squid-cache.org/>
[@mrlesmithjr]: <https://twitter.com/mrlesmithjr>
[everythingshouldbevirtual.com]: <http://everythingshouldbevirtual.com>
[mrlesmithjr@gmail.com]: <mailto:mrlesmithjr@gmail.com>
