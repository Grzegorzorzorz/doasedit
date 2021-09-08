# doasedit
`doasedit` is the doas equivalent to [sudoedit](https://www.youtube.com/watch?v=Njsth_VeSxY).\
sudoedit is pretty nice but [sudo is insecure](https://www.youtube.com/watch?v=eamEZCj-CuQ) and [has had many vulnerabilities over the years](https://duckduckgo.com/?q=sudo+vulnerability). Which is why, if you are on GNU/Linux, you switch to [doas](https://github.com/nholstein/OpenDoas). Most BSD users probably already use doas.

There are two other `doasedit` implementations on GitHub but somehow they are both much longer than they need to be. This implementation is very small so I recommend you use this one.

## Installation

```sh
doas curl -sL "https://raw.githubusercontent.com/koalagang/doasedit/main/doasedit" -o /usr/bin/doasedit && doas chmod +x /usr/bin/doasedit
```
>To uninstall, just run `doas rm /usr/bin/doasedit`
