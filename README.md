[![Issues](https://img.shields.io/github/issues/Minematic/SkLogSnag)](https://github.com/Baezor1/Shop/issues) ![Forks](https://img.shields.io/github/forks/Minematic/SkLogSnag) ![Stars](https://img.shields.io/github/stars/Minematic/SkLogSnag)

# SkLogSnag
SkriptLang integration with [LogSnag](https://logsnag.com/). Track player activity, payments, reports, and more with [LogSnag](https://logsnag.com/).

# Documentation
### Log Function
#### Usage
`?` = Optional Argument
```
logsnag(event, description, channel, ?notify, ?icon, ?project)
```
#### Examples
```hs
logsnag("Server Online", "The server epic-server-01 is not online!" "status")
logsnag("Intense Lag", "The server epic-server-01 is at 3 tps!" "status", "true" "🔥")
```
