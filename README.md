# base-de-conhecimento



## ATUALIZAR TODOS OS APLICATIVOS DO WINDOWS
No prompt ou power shelll como ADM:

winget upgrade  | winget upgrade --all --include-unknown --accept-package-agreements --accept-source-agreements --silent
***    ***    ***    ***


## Ativar Windows + Office:
Menu iniciar Powershell em modo administrador:

irm https://get.activated.win | iex
ou
iex (curl.exe -s --doh-url https://1.1.1.1/dns-query https://get.activated.win | Out-String)
***    ***    ***    ***

## Como remover senha do Windows 11 sem programa: 
https://m.youtube.com/watch?v=cA8HbNlO1Tw
***    ***    ***    ***

## Não reconhece o HD na hora de formatar
Ao aparecer a lista de discos vazia, pressionar SHIFT + F10 para abrir o prompt de comando e digitar:

diskpart e ENTER. Digite: list disk e ENTER. Digite: select disk e o número do disco. Digite: clean, ENTER.
Digite: create partition primary e ENTER. EXIT e EXIT novamente.
***    ***    ***    ***

## Pular conta Microsoft Windows 11
SHIFT+F10>>OOBE\BYPASSNRO;
***    ***    ***    ***

## Computador não segura as configurações de CMOS e a bateria está com carga
Provavelmente há um mau funcionamento dos diodos utilizados para chavear entre
alimentação pela bateria ou pela fonte do sistema. Faz-se necessário
a troca da placa-mãe.
***    ***    ***    ***

## Todos os ícones iguais no Windows
Acesse no regedit:

HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\Explorer\FileExts

Renomeie a chave FileExts para FileExts.old. Reinicie o Windows e verifique se o problema foi resolvido.
***    ***    ***    ***
