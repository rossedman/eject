# Eject!

This is a simple setup for managing Apple device configuration using `homebrew` and `mackup`. This will install application, utilities and language runtimes as well as restore the configuration for those applications from iCloud.

## Install

This will install and restore a backup from iCloud for `mackup`. This should configure and setup most of the applications needed to bootstrap a computer.

```
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/rossedman/eject/master/scripts/install)"
```

To run a backup with the latest upstream configuration run 

```
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/rossedman/eject/master/scripts/backup)"
```

## References

- https://gist.github.com/ChristopherA/a579274536aab36ea9966f301ff14f3f