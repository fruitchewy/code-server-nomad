# nomad - Docker mod for code-server

This mod adds nomad to code-server, to be installed/updated during container start.

In code-server docker arguments, set an environment variable `DOCKER_MODS=linuxserver/mods:code-server-nomad`

If adding multiple mods, enter them in an array separated by `|`, such as `DOCKER_MODS=linuxserver/mods:code-server-nomad|linuxserver/mods:code-server-mod2`
