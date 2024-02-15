Project directory as seen by the Windows Subsystem for Linux shell.

```lua
remoteprojectdir ("path")
```

### Parameters ###

`path` specifies the directory on the remote machine that WSL sees the project in

### Applies To ###

The `config` scope.

### Availability ###

Premake 5.0.0 beta 3 or later, only applies to Visual Studio Linux projects.

### Examples ###

```lua
remoteprojectdir "$(RemoteRootDir)/$(ProjectName)"
```
