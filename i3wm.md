**Arquivo com as configurações pessoais do i3:**
```console
vim .config/i3/config
```
**Arquivos do i3:**
```console
ls .config/i3/
```
- **Saída:**
    >dconf/ gtk-2.0/ gtk-3.0 htop/ Mousepad/ nitrogen/ xfce4/

**Sair do i3:**
> SUPER + shift + e 

`e` : exit

**iniciar o i3:**
```console
startx
```

**Abrir um terminal:**
> SUPER + Enter

*Configurar a tela do monitor:*
```console
arandr
```

**Configurando scrips para iniciar no i3:**
```console
vim .config/i3/config
```
> \# auto-início ... 
> 
>  exec --no-startup-id ~/.screenlayout/default_telas.sh
> 
>  exec --no-startup-id nitrogen --restore

*Fechar o programar (confg. default):*
>SUPER + Shfit + Q

*Procurar um programa pelo dmenu:*
>SUPER + d

*Configurando as fontes das letras no i3:*
```console
vim .config/i3/config
```
> \# Fontes 
> 
>  font pango:Open Sans 9
> 
>  bar {
>       
>        font pango:Open Sans 10
>        status_command i3status
> }

*Recarregar as configurações no i3:*
> SUPER + Shfit + r

*Fechar o programar (confg. default):*
>SUPER + Shfit + q


*Modificando a tecla da tela flutuante do i3:*
```console
vim .config/i3/config
```
> \# Mod4 = tecla SUPER
> 
> \# Mod1 = tecla alt
> 
> floating_modifier $mod1
> 

*Configurando tecla para encerrar um programa no i3:*
```console
vim .config/i3/config
```
> \# kill focused window
> 
>  bindsym $mod+Shift+q kill
> 
> \# Modificado para
>
> bindsym $mod+q kill

**Listar as teclas de atalho no i3:**
```console
grep ^bindsym .config/i3/config
```
