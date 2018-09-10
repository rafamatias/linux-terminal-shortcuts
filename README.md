# Bash
Useful bash shortcuts by my own experience. All examples will use the command bellow to clarify its usage:

```
$ cp -r stargate newportal
```

I also used block unicode characters to indicate cursor position '█, ▒'.

## Moving
![](images/bash-moving.png)

|Shortcut|Result|Description|
|--|--|--|
|ctrl + a|  to the beginning of the line|`$▕█p -r stargate newme`|
|ctrl + e|Go to the end of the line|`$ cp -r stargate newm█`|
|alt + b|Back one word|`$ cp -r stargate▕█ewme`|
|alt + f|Forward one word|`$ cp -r stargat█ newme`|
|ctrl + b|Back one character|`$ cp -r stargat█ newme`|
|ctrl + f|Forward one character|`$ cp -r stargate n█wme`|
|ctrl + xx|Toggle between the start of line and current cursor positon|`$ █p -r newme st▒rgate`|

## License
This repository is under MIT License.