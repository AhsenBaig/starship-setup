# Setup starship

## Work in progress

### OS

> [Windows]
> ```ps
> winget install --id Starship.Starship
>```

> [PowerShell]
> ```ps
> Invoke-Expression (&starship init powershell)
>```

Temp works
powershell -ExecutionPolicy Bypass -File $PROFILE

Real fix:
Set-ExecutionPolicy -ExecutionPolicy RemoteSigned -Scope CurrentUser


