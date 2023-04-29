Comandos no terminal:
`Install-Module posh-git -Scope CurrentUser`<>
`Install-Module oh-my-posh -Scope CurrentUser`
`notepad $PROFILE`
`Get-PoshThemes`

Se o comando (`Get-PoshThemes`) não funcionar use o
link com todos os temas (link:https://ohmyposh.dev/docs/themes)

insira no arquivo $PROFILE(Microsoft.PowerShell_profile.ps1)

```Microsoft.PowerShell_profile.ps1
Import-Module posh-git
Import-Module oh-my-posh
Set-PoshPrompt -Theme <nome_do_tema>// Define um tema do terminal
$ThemeSettings.Font = 'Cascadia Code Nerd Font, 12'
```

"""

Essa Font pode ser instalada em (link:https://www.nerdfonts.com/font-downloads)

"""

"""

Outra forma de alterar o tema é criando um

arquivo theme.omp.json(ou o nome que preferir)
em sua maquina e inserir dentro do arquivo o codigo
de um dos temas presentes aqui:https://ohmyposh.dev/docs/themes
após isso inserir o codigo:
(oh-my-posh init pwsh --config
 '`<caminho-para-o-arquivo->`theme.omp.json'
 | Invoke-Expression)// em linha unica
em seu arquivo
"""
