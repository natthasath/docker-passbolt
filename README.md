# 🎉 Docker Passbolt

Passbolt is an open-source password manager designed for teams. It offers secure storage and sharing of passwords, ensuring easy collaboration while maintaining high security standards. Built with privacy in mind, Passbolt supports strong encryption and user authentication.

![version](https://img.shields.io/badge/version-1.0-blue)
![rating](https://img.shields.io/badge/rating-★★★★★-yellow)
![uptime](https://img.shields.io/badge/uptime-100%25-brightgreen)

### 🏆 Run

- [https://localhost/](https://localhost/) username : `admin` password : `admin`

```shell
docker-compose up -d
```

### 👉🏻 Try it out

```shell
docker-compose exec passbolt su -m -c "/usr/share/php/passbolt/bin/cake passbolt register_user -u admin@example.com -f Admin -l Example -r admin" -s /bin/sh www-data
```