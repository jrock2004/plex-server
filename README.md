# Plex Server

My local plex server for watching my DVD movies

# Setup

Before starting the server make sure the following directories exist

- `/media/jcostanzo/extradrive1/config`
- `/media/jcostanzo/extradrive1/TV Shows`
- `/media/jcostanzo/extradrive1/Movies`

**Note:** If you have files in a different location, you will need to update the compose file with new path

# Run Server

To run this, you will run the following command:

``` sh
> docker-compose up -d
```

If you are running in Linux you might have to put `sudo` in front of it
