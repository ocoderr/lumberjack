
### Lumberjack is a Go package for writing logs to rolling files.

see https://github.com/natefinch/lumberjack  for more infos

this repository add some features:

1. config backup path



## type Logger
``` go
type Logger struct {
.........
	// BackupPath is the path for Backup log .  
	// if startwith "/" is a Absolute path
	// otherwise is Relative path of Filename's basedir
	// "history" is default backup path if empty
	BackupPath string `json:"backuppath" yaml:"backuppath"`
...........
}
```

