# info-go

## PS config
```ps1
$env:GOPRIVATE="url/*"
```

## git config for go priv
```sh
git config --list --show-origin --show-scope
git config --global url."https://U:T@github.com/".insteadOf "https://github.com/"
```
