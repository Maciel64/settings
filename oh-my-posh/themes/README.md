# Tema Suassuna para PowerShell

![Captura de tela para o tema Suassuna](/assets/powershell.png)

# Setup em Português

- Para utilizar o tema, é necessário instalar o oh my posh da forma que preferir. Com `winget` execute um PowerShell como administrador e rode:

```
Set-ExecutionPolicy RemoteSigned -Scope CurrentUser
winget install JanDeDobbeleer.OhMyPosh -s winget
```

- Então rode o comando `code $PROFILE`, se você utilizar o VS Code, se não, é possível usar o bloco de notas com `note $PROFILE`.

- O arquivo aberto é o de inicialização do PowerShell, então toda comando definido ali será rodado ao abrir uma instância do PowerShell.

- Coloque o seguinte comando no arquivo:

```
oh-my-posh init pwsh --config C:/Users/macie/AppData/Local/Programs/oh-my-posh/themes/suassuna.omp.json | Invoke-Expression
```

- Então, vá no caminho `C:\Users\{SeuUsuário}\AppData\Local\Programs\oh-my-posh\themes` e crie o arquivo suassuna.omp.json e SUCESSO! O tema está funcionado.

<br>

# English Setup

- For using the theme, it's necessary to install oh my posh the way you prefer. With `winget` execute a PowerShell as administrator and run:

```
Set-ExecutionPolicy RemoteSigned -Scope CurrentUser
winget install JanDeDobbeleer.OhMyPosh -s winget
```

-  So, run the command `code $PROFILE`, if you use VS Code, if not, it is possible to use the notepad with `note $PROFILE`.

-  The opened file is the PowerShell initialization one, so every command set there will run when a PowerShell instance is open.

- Put the following command on the file:

```
oh-my-posh init pwsh --config C:/Users/macie/AppData/Local/Programs/oh-my-posh/themes/suassuna.omp.json | Invoke-Expression
```

- Go to the path `C:\Users\{SeuUsuário}\AppData\Local\Programs\oh-my-posh\themes` and create the file suassuna.omp.json and SUCCESS! The theme is now working.