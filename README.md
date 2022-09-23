# postgresql

Is a script for installing, setting up and managing PostgreSQL via the source code

# Features

- Install/Reinstall PostgreSQL
- Set up/set up new the ``data`` directory
- Start PostgreSQL
- Restart PostgreSQL
- Stop PostgreSQL
- Get the status of PostgreSQL

# Installation

```bash
wget https://raw.githubusercontent.com/Justman10000/postgresql/main/postgresql
mv postgresql /usr/bin
chmod +x /usr/bin/postgresql
adduser postgres --no-create-home --disabled-login
```

After that you can simply call the script via ``postgresql`` in your terminal

# Usage

Use the Script like:

``postgresql {option}``

<br>

``{option}`` is replaced by the option, the choices are:
```
setup   (Setup PostgreSQL)
status  (Get PostgreSQL status)
start   (Start PostgreSQL)
restart (Restart PostgreSQL)
stop    (Shut down PostgreSQL)
```

Note: One of the above arguments **must** be specified!