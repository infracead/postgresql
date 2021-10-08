## Bastille postgresql13 13.0-RELEASE

#### Use

```bash
root@manunggul [ /usr/local/etc ] #: bastille template [container] infracead/postgresql.git
```

#### Change user, password and version

```bash
root@manunggul [ /usr/local/etc ] #: bastille template [container] infracead/postgresql --arg VERSION=11 --arg USER=-alsa --arg PASSWORD=akira
```

