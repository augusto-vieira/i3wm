# i3wm
Gerenciador de Janelas.

---
### Programas essenciais para funcionamento do i3wn:
Pacotes do Debian.

- Gerenciar telas com protocolo x11:
  - xorg

- Gerenciador de telas: 
    - i3-wm

- Barras de baixo (informações).
    - i3status

- Senha da tela do not:
    - i3blocks
    - i3lock
    - i3lock-fancy

- Terminal:
    - xfce4-terminal

- dmenu: gerar um menu para acessar o programa.
    - suckless-tools

- Versão mais automatica do dmenu.
    - j4-dmenu-desktop

- Também faz menu, scripts:
    - rofi

- Faz o que o j4-dmenu-desktop e suckless-tools pelo terminal.
    - fzf

- Ferramenta gráfica para ajustar monitor:
    - arandr

- Ferramentas para obter informações das janelas e mandar instruções (combinação de tecla, emular mouse, movimento).
  - xdotool
  - wmctrl

- Gerenciador de arquivos gráficos:
    - pcmanfm (está sendo abandonado)

- Gerenciador/navegador de arquivos não-gráficos.
    - ranger

- Trocar os temas dos ambientes gráficos do programa, mas só funciona com gtk.
  - lxappearance (está sendo abandonado)

- Para controlar papel de parede:
    - nitrogen

- Fontes de textos:
  -  *fonts-open-sans*   = fontes que não são espaçadas.
  -  *fonts-inconsolata* = terminal.

- Temas:
  - arc-theme 
  - papirus-icon-theme
  - breeze-cursor-theme

- Editor de textos:
  - mousepad

- Navegador:
  - A DEFINIR

---

### Instalação:
```console
sudo apt install $(< lista.txt)
# Segundo método
cat lista.txt | sudo apt install
```
` $(< lista.txt)`: expansão do shell, equivalente a um `cat` puramente pelo Shell.


Simular uma instalação no Shell:
```console
sudo apt install --dry-run $(< lista.txt)
```
`--dry-run`: simula uma instalação, listando todos os pacotes e dependências.

---