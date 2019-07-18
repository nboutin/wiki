# Python

## Execute module

`py -m <module>`

example:
`py -m pip install <package>`
 
 
## pip install

`python3 -m pip install <package> --user`

## Pip with proxy

`py -m pip --proxy http://<user>:<pwd>@<ip>:<port> install --user -U <package>`

## Virtual Env

```
python3 -m pip install --user virtualenv

virtualenv path/to/ENV

source path/to/ENV/bin/activate
```