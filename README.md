# jit
jit[ter] journal script: quickly write a timestamped,  tagged log entry.

## Installation

### Requirements

* bash
* vim

No installation required, except that you may want to add the jit command to your `$PATH` variable.
How this works depends on your platform. On linux, you should place this snippet in your `~/.bashrc` file:

```
export PATH=$PATH:~/path/to/jit/
```

### Configuration

When you first launch jit, a config file will be created and opened in vim. Make sure that the config file (config.cfg) is filled in correctly. The config file is essentially a small bash script, so make sure to use bash syntax (key=value without spaces in between!).

In the config file you need to set following variables:

|Var | Description |
|---|---|
|`AUTHOR` | The name that will be used as the author for each note |
|`LOG_DIR` | The path to the log dicrectory. All new entries will be stored here |
|`TEMP_DIR` | A local directory to temporary store entries in case the `LOG_DIR` is not available. For example if `LOG_DIR` is on unreachable network storage. |

