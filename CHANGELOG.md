# Novidades do Nexo

Cada versão traz **Novidades**, **Melhorias** e **Correções**. A ordem é a versão:
1.0.**1** = correções, 1.**1**.0 = novidades, **2**.0.0 = mudança grande.
O Nexo instalado avisa quando sai uma versão nova e só atualiza com o seu OK.

*English summary at the end of each version.*

## [1.5.0] — 16/11/2026

### Novidades
- **Armazenamento**: nova guia (o botão de disco na barra de cima) que mostra quanto o Nexo ocupa em
  cada disco, jogo por jogo e versão por versão.
  - **Por disco**: uma barra para cada disco com o que é jogo de PC, emulador, versão antiga, saves e
    backups, downloads e dumps, o que é de outros programas e o espaço livre.
  - **Jogo por jogo**: os projetos do mesmo jogo ficam juntos. Abrindo um jogo, aparece cada versão
    (a em uso e as antigas), o preparo e o jogo montado, os backups dos saves e o resto da pasta, com
    o caminho, o tamanho e quantos arquivos tem. Filtro por jogos de PC ou emuladores.
  - **Detalhes de uma pasta**, como num analisador de disco: o que tem dentro, do maior para o
    menor, entrando nas subpastas até o arquivo, e o botão para abrir a pasta.
  - **Sugestões de limpeza**: versões antigas que saem sem perder nada seu, downloads guardados,
    downloads que pararam no meio e sobras de instalações interrompidas. Nada sai sem uma janela
    mostrando antes a lista do que vai ser apagado, e os saves nunca entram.
  - Também mostra as pastas que não são de nenhum jogo instalado (sobras de jogos desinstalados) e
    um jogo que ficou com pastas em dois lugares depois de a biblioteca mudar de disco. Essas o Nexo
    só mostra: você abre e decide.
  - A medição roda em segundo plano e fica guardada: a guia abre na hora e mede de novo quando a
    biblioteca muda ou no botão **Medir de novo**.
- `nexo-cli espaco`: o mesmo relatório na linha de comando.

### Melhorias
- **Aviso de pouco espaço**: antes de baixar, o Nexo confere se cabem o download e o jogo
  extraído. Se não couber, avisa na hora, em vez de o download falhar no meio.

### English
New **Storage** tab (the drive button on the top bar): how much Nexo takes up on each drive, game by
game and version by version. A bar per drive splits PC games, emulators, old versions, saves and
backups, downloads and dumps, other programs and free space. **Game by game** groups each game's
projects and lists every version (in use and old), preparation data, save backups and the rest of
the folder, with path, size and file count, filtered by PC games or emulators. **Folder details**
work like a disk analyzer: contents from largest to smallest, down to the file. **Cleanup
suggestions** cover old versions that can go without losing anything of yours, kept and unfinished
downloads and leftovers from interrupted installs; nothing is deleted without a window listing what
will go, and saves are never included. Folders that belong to no installed game, and games left in
two places after the library moved, are shown but never deleted. Measuring runs in the background and
is saved, so the tab opens instantly. Also `nexo-cli espaco`, and a **low space warning** before a
download that wouldn't fit.

## [1.4.0] — 15/11/2026

### Novidades
- **Um card por jogo**: os recomps e ports do mesmo jogo agora ficam juntos no Descobrir e nas
  fileiras do Início. O Zelda: Ocarina of Time, por exemplo, virou um card só com os seus 16
  projetos, em vez de vários cards soltos.
  - O selo no canto da capa diz quantos projetos o jogo tem.
  - Na página do jogo, a lista **"N projetos de…"** vai do mais recomendado ao menos: primeiro os
    que têm versão para baixar e mais estrelas no GitHub. Cada linha mostra o console de origem e os
    sistemas.
  - Num atalho da Steam de um jogo com vários projetos, o nome vira "Jogo - Projeto".
- **68 projetos novos no catálogo**, lançados nos últimos 60 dias:
  - **Switch 2:** Mario Kart World (3 projetos), Pokémon Pokopia, Star Fox, Fire Emblem: Fortune's
    Weave, Donkey Kong Bananza e mais 5 do Ocarina of Time (NX2navi, Longshot, Project ReLink...).
  - **Switch:** Super Mario Odyssey, Xenoblade Chronicles 2 e 3, Smash Ultimate, Pokémon Scarlet e
    Violet, Metroid Prime 4.
  - **Xbox 360:** GTA V, Ninja Gaiden II, Battlefield 1943, Skate 2, PGR4, Chaves Kart e outros.
  - **Xbox:** Panzer Dragoon Orta, Red Dead Revolver, Soulcalibur II, The Warriors, Halo 2 (em
    desenvolvimento).
  - **PS3:** Demon's Souls, inFAMOUS 2, God of War: Ascension, Resistance 1 e 3.
  - **PS4:** Gravity Rush 2, Diablo III, Dead Nation, Resogun.
  - **PS2:** GTA San Andreas, TimeSplitters 2, Haunting Ground, Shadow of Rome, Ratchet & Clank,
    Crash: The Wrath of Cortex e outros.
  - E ainda jogos de PS Vita, Pandora's Tower (Wii), Mario Kart Arcade GP, Monster Hunter 3
    Ultimate (Wii U) e Castlevania: Grimoire of Souls.
  - Mario Kart World, Pokopia, Super Mario Odyssey e GTA V entram no destaque do Início.

### Melhorias
- Nomes diferentes do mesmo jogo no catálogo foram unificados (o Ocarina of Time do N64, do 3DS e do
  Switch 2 ficam juntos, por exemplo).
- Um projeto que você adicionou à mão e que também está no catálogo herda o jogo, o console e as
  estrelas de lá, e passa a aparecer junto dos outros projetos do mesmo jogo.

### English
**One card per game**: recomps and ports of the same game now share a single card in Discover and on
the Home rows (Zelda: Ocarina of Time is one card with its 16 projects), with a badge showing how
many projects there are. The game page lists them from most to least recommended (downloadable and
most-starred first), with each one's source console and systems; Steam shortcuts for games with
several projects are named "Game - Project". **68 new projects** released in the last 60 days,
including Mario Kart World, Pokémon Pokopia, Super Mario Odyssey, Xenoblade 2 and 3, GTA V, Ninja
Gaiden II, Demon's Souls, God of War: Ascension, Gravity Rush 2, TimeSplitters 2 and more; Mario
Kart World, Pokopia, Super Mario Odyssey and GTA V join the Home carousel. Different spellings of the
same game were merged, and a project you added by hand that's also in the catalog inherits its game,
console and stars.

## [1.3.0] — 13/11/2026

### Novidades
- **Notícias**: nova aba com os destaques de 20 sites brasileiros de games, consoles, emulação e
  PC (IGN Brasil, Adrenaline, GameBlast, Nintendo Blast, Critical Hits, MeuPlayStation, Arkade...).
  - Uma matéria em destaque e as outras em grade, com imagem, site e há quanto tempo saiu.
  - **Escolher sites**: ligue e desligue os que você quer acompanhar. Os de tecnologia em geral
    começam desligados.
  - O clique abre a matéria no site, no navegador. A aba se atualiza sozinha a cada 30 minutos ou
    no botão **Atualizar**.
- **Coleções por franquia**: Zelda, Mario, Sonic, Resident Evil, Doom, Pokémon e mais de 130
  séries, cada uma com os seus jogos e, em cada jogo, os recomps e ports que existem para ele.
  - Fileira **Coleções** no Início, página com todas (com busca) e a página de cada coleção.
  - Na página de um jogo, o selo **Coleção** leva direto para a série.
- **Jogos novos no catálogo**:
  - **Hookshot**, o Zelda: Ocarina of Time do Switch 2;
  - **DKB Recomp**, o Donkey Kong Bananza, com instalador;
  - o fork **local-prs** do DKB Recomp.
  - Os dois jogos abrem o destaque do Início.

### Melhorias
- A barra de cima cabe inteira mesmo com a janela no tamanho mínimo.
- A capa e o banner de um jogo podem ser fixados no catálogo, quando a busca automática acharia
  outro jogo com o mesmo nome (um remake, por exemplo).

### English
New **News** tab: highlights from 20 Brazilian gaming, console, emulation and PC sites, with a
featured story and a grid with image, site and time; **Choose sites** turns each site on or off
(general tech sites start off); a click opens the story in your browser; it refreshes every 30
minutes or with **Refresh**. New **Collections by franchise**: Zelda, Mario, Sonic, Resident Evil,
Doom, Pokémon and 130+ series, each with its games and, for each game, the recomps and ports that
exist; a Collections row on Home, a page with all of them (with search), a page per collection and a
**Collection** badge on game pages. New in the catalog: **Hookshot** (Zelda: Ocarina of Time,
Switch 2), **DKB Recomp** (Donkey Kong Bananza, with installer) and its **local-prs** fork; both
games lead the Home carousel. The top bar now fits at the minimum window size, and the catalog can pin
a game's cover and banner when the automatic search would find another game with the same name.

## [1.2.0] — 12/11/2026

### Novidades
- **Comunidade**: dê nota de 1 a 5 e comente como cada projeto rodou no seu PC. Todo mundo que usa o
  Nexo vê as notas e os comentários.
  - Entre com o **Discord** (uma vez só; o Nexo guarda a sessão). Só o seu nome e a sua inicial
    aparecem; nada é publicado no seu Discord.
  - Nova aba **Comunidade**, com os mais bem avaliados e as avaliações recentes.
  - Na página de cada jogo: a nota média, os comentários e a sua avaliação, que você edita ou apaga
    quando quiser.
  - Comentários não aceitam links. Avaliações com 3 denúncias ficam escondidas até a moderação
    revisar.
  - **Apagar minha conta** apaga na hora a conta e todas as suas avaliações.
    [Política de privacidade](https://github.com/nexolauncher-glitch/nexo/blob/main/docs/privacidade.md).

### Correções
- No Windows, links com endereço comprido podiam abrir a pasta Documentos em vez do navegador.

### English
New **Community**: rate projects from 1 to 5 and comment on how they ran on your PC, visible to every
Nexo user. Sign in once with Discord (only your name and initial are shown; nothing is posted to your
Discord). New Community tab with top-rated projects and recent ratings; each game page shows the
average, comments and your own rating, which you can edit or delete. No links in comments; ratings with
3 reports are hidden until reviewed; **Delete my account** removes your account and all your ratings
right away ([privacy policy](https://github.com/nexolauncher-glitch/nexo/blob/main/docs/privacidade.md)). Fixed: on Windows, long links could open the
Documents folder instead of the browser.

## [1.1.1] — 12/11/2026

### Melhorias
- Créditos do catálogo atualizados: o catálogo é montado pela curadoria do Nexo a partir de bases
  públicas da internet. A arte continua vindo do SteamGridDB.

### English
Catalog credits updated: the catalog is built by Nexo's own curation from public sources on the
internet. Art still comes from SteamGridDB.

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
