# This is an wrapper of dracula theme

### To use this Locally
Open cmd/powershell and copy past the follwing commands.

```
git clone https://github.com/mahidsec/omp-theme.git
```
For PowerShell User
```
cp omp-theme/mahidsec.json $env:POSH_THEMES_PATH/
```
For CMD User
```
copy omp-theme/mahidsec.json %USERPROFILE%/AppData/Local/Programs/oh-my-posh/themes/
```

## Then set the theme

For OMP (PowerShell)
```
oh-my-posh init pwsh --config "$env:POSH_THEMES_PATH/mahidsec.json" | Invoke-Expression
```


For Clink (cmd)
```
load(io.popen('oh-my-posh init cmd --config "%USERPROFILE%/AppData/Local/Programs/oh-my-posh/themes/mahidsec.json"'):read("*a"))()
```