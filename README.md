# Homeserver

Trying to simplify my current setup.

### Goals:

- Make it easy to set this up, preferably one docker compose command to get this up and running.
- Make it easy to update images

... not to worried about data loss as of now, main os is running on a ssd disk, but raid 0 for storage

# Env variables before running

Create a folder where all of the config for the docker images will be stored, something like `~/homserverconfig`

```bash
export HOMESERVERBASEPATH="~/homserverconfig"
```
