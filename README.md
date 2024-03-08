# This is a wrapper of the Dracula theme

## To use this Locally Or to use online see (this)[#online]
Open cmd/PowerShell and copy and paste the following commands.

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

## Then set the theme Offline

For OMP (PowerShell)
```
oh-my-posh init pwsh --config "$env:POSH_THEMES_PATH/mahidsec.json" | Invoke-Expression
```

For Clink (cmd)
```
load(io.popen('oh-my-posh init cmd --config "%USERPROFILE%/AppData/Local/Programs/oh-my-posh/themes/mahidsec.json"'):read("*a"))()
```

## Online
```
oh-my-posh init pwsh --config 'https://raw.githubusercontent.com/mahidsec/omp-theme/main/mahidsec.json' | Invoke-Expression
```
