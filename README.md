# About

Requires Python 3.11 or greater

Collection of scripts for use in a *nix environment, meant to speed up some of my workflows. Most scripts are probably kubectl related because I don't like typing. These scripts were developed / tested on WSL, but should work with any linux like enviroment.

# Commands

## kgpl

```
usage: kgpl [-h] [-n NAMESPACE] [-F] [-i INDEX] podname

Kubectl Get Pod Logs (KGPL)

positional arguments:
  podname

options:
  -h, --help            show this help message and exit
  -n NAMESPACE, --namespace NAMESPACE
                        Namespace where the pod is located
  -F, --file            Stores pod logs in a file in the current directory with the name (Pod-Name.log)
  -i INDEX, --index INDEX
                        Index of the pod (Default=0)
```
