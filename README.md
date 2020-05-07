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


