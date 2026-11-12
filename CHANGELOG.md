# Novidades do Nexo

Cada versão traz **Novidades**, **Melhorias** e **Correções**. A ordem é a versão:
1.0.**1** = correções, 1.**1**.0 = novidades, **2**.0.0 = mudança grande.
O Nexo instalado avisa quando sai uma versão nova e só atualiza com o seu OK.

*English summary at the end of each version.*

## [1.1.0] — 12/11/2026

### Novidades
- **Instalador com passo a passo** no Windows e no Linux, com a arte do Nexo: escolha onde ficam o
  programa, os jogos de PC, os emuladores, os seus jogos de emulador e os backups dos saves (o
  recomendado é tudo numa pasta só), com atalhos na área de trabalho e no menu.
- **Desinstalador**: no Windows, em Configurações > Aplicativos; no Linux, no menu de aplicativos.
  Sai o programa, os atalhos e o registro; jogos, emuladores e saves nunca são apagados.
- **Pastas separadas** para os jogos de PC e para os emuladores, em Configurações > Pastas.

### Melhorias
- **Linux universal**: o mesmo pacote roda em qualquer distribuição x64 de 2018 para cá (Ubuntu,
  Fedora, Arch, Mint, SteamOS, Bazzite, CachyOS...), sem instalar nada antes.
- O update do Nexo também atualiza a licença e a lista de bibliotecas de terceiros.

### English
New step-by-step installer for Windows and Linux with Nexo's artwork: choose where the program, PC
games, emulators, your emulator games and save backups go (everything in one folder is recommended),
plus desktop and menu shortcuts. New uninstaller (Windows Settings > Apps, or the Linux applications
menu) that never deletes games, emulators or saves. Separate folders for PC games and emulators. The
Linux package now runs on any x64 distro from 2018 on (SteamOS included), and self-updates also refresh
the license and third-party notices.

## [1.0.0] — 12/11/2026

Primeira versão pública e estável.

### Novidades
- **Visual novo**: barra de cima com as abas, destaque do Início em tela larga com título em serifa,
  cartões com cantos arredondados que sobem e brilham sob o mouse ou o controle, com os ícones de
  Windows/Mac/Linux e a plataforma de origem.
- **Dois universos**: PC (recomps e ports) e Emuladores, cada um com Início, Biblioteca, Favoritos e
  Descobrir próprios.
- **Catálogo** com mais de 1.700 projetos e mais de 20 emuladores, com busca, filtros por console,
  plataforma e gênero, e capas automáticas do SteamGridDB, sem precisar configurar nada.
- **Instalar e atualizar** direto das releases de cada desenvolvedor, com conferência do SHA-256,
  download com retomada, uma pasta por versão, versão fixável e saves sempre preservados.
- **Receitas automáticas**: projetos que precisam de preparo (setup, shaders, montar o jogo) ficam
  prontos sozinhos, com o selo "Atualiza sozinho" ou "Atualiza e prepara sozinho" na página do jogo.
- **Jogos de Switch a partir dos seus NSP/NSZ**: o Nexo junta base, update e DLCs e monta o jogo, sem
  ferramentas externas (usado pelo Savage Wind).
- **Downloads** em três partes: Baixando, Atualizações disponíveis ("vX já saiu. Você tem a vY.") e
  Concluídos recentemente, com capa e o tipo de cada projeto.
- **Favoritos**, com o botão dourado quando marcado e uma fileira no Início.
- **Saves**: backup automático antes de updates e ao desinstalar, e restauração.
- **Steam**: pôr um jogo na biblioteca da Steam com a capa do Nexo, ou pôr o próprio Nexo para abrir
  em modo TV no modo jogo.
- **Modo TV** com navegação completa pelo controle, e um botão na barra de cima para entrar e sair na
  hora.
- **Linux**: jogos de Windows pelo Proton, umu-run ou Wine.
- **Português e inglês**, tema escuro e claro.

### Correções
- Builds `x86_64` não aparecem mais como "32 bits", e não são oferecidas em PCs ARM.
- **Update do próprio Nexo** pelas releases do GitHub, com as novidades na tela e confirmação antes.
  Só aceita versões com a assinatura do Nexo.

### English
First public, stable release: a new look (top bar, wide hero, glowing rounded cards), PC and Emulators
universes, a catalog of 1,700+ projects and 20+ emulators, one-click install and updates from each
developer's releases with SHA-256 checks, automatic setup recipes, Switch games assembled from your own
NSP/NSZ files, a reorganized Downloads page, favorites, save backups, Steam shortcuts, TV mode with full
controller support, Proton/umu/Wine on Linux, Portuguese and English, and signed self-updates from GitHub
releases. Fix: `x86_64` builds no longer show as "32-bit" and aren't offered on ARM PCs.
