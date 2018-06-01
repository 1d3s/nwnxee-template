# NWNXEE Source control template repository

Reference project for running [nwnxee](https://github.com/nwnxee/unified) with docker-compose.

## Run

Run: `docker-compose up -d`
Kill: `docker-compose down`

## Configuration

The bundled module DockerDemo is loaded by default. To load a different module, say `mymodule`, place the module file in `server/modules/mymodule.mod` and change the compose environment to say `NWN_MODULE=mymodule`.

For further help configuring nwserver, see the [nwserver documentation](https://hub.docker.com/r/beamdog/nwserver/).

## Hint

If you're interested in version controlling your module in a textual format, check out [nwn-devbase](https://github.com/jakkn/nwn-devbase "The best tool") to learn how to process your files outside of the toolset.
