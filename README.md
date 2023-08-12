# Proverbios Portugueses
To be used with [`fortune`](https://linux.die.net/man/6/fortune).


# How to use
```
git clone $THIS_REPO
```


Then add to `~/.bashrc`, `~/.config/fish/config.fish` or equivalent to your shell

```
fortune proverbios-portugueses-fortune
```

# How it was generated
Got from https://pt.wikiquote.org/wiki/Prov%C3%A9rbios_portugueses

```js
copy(Array.from(document.querySelectorAll('h2 + ul li')).map((a) => a.textContent.split('"')[1]).filter((a) => a && a.length).join('\n%\n'))
```

Fortune requires the items to be delimited with a `%` in its own line.
