<p align="center">
  <img src="marca/gerado/banner-readme.jpg" alt="Nexo" width="100%">
</p>

<p align="center">
  <b>Os recomps, ports e emuladores da comunidade num lugar só.</b><br>
  Descubra, instale, atualize e jogue — direto do GitHub de cada desenvolvedor.
</p>

<p align="center">
  <a href="https://github.com/nexolauncher-glitch/nexo/releases/latest"><img alt="Versão" src="https://img.shields.io/github/v/release/nexolauncher-glitch/nexo?label=vers%C3%A3o&color=3b7bff"></a>
  <img alt="Windows e Linux" src="https://img.shields.io/badge/Windows%20%7C%20Linux-x64-555">
  <a href="LICENSE"><img alt="Grátis" src="https://img.shields.io/badge/uso-gr%C3%A1tis-2ea44f"></a>
</p>

<p align="center"><b>Português</b> · <a href="README.en.md">English</a></p>

---

![Início do Nexo](docs/capturas/inicio.jpg)

## O que é o Nexo

Nos últimos anos, a comunidade transformou jogos clássicos de console em programas que rodam
**nativos no PC**: as recompilações (*recomps*) e os *ports*. Zelda 64, Sonic Unleashed, Bloodborne,
Tears of the Kingdom e muitos outros. Cada um vive no seu repositório, com o seu jeito de instalar,
atualizar e preparar o jogo.

O **Nexo** junta tudo isso num launcher leve, para Windows e Linux:

- um **catálogo com mais de 1.700 projetos** e mais de 20 emuladores, com capa, banner e estrelas;
- **instala e atualiza com um clique**, baixando sempre da release oficial de quem fez o projeto;
- confere o **SHA-256** de cada arquivo e **nunca apaga os seus saves**;
- tem **modo TV** com controle, para jogar no sofá ou no Steam Deck.

### Adicione qualquer projeto, sem esperar ninguém

Saiu um recomp novo ou um emulador que ainda não está no catálogo? **Cole o link do repositório em
"Adicionar jogo" (ou "Adicionar emulador") e pronto**: o Nexo instala, atualiza e organiza como qualquer
outro, direto na sua máquina, sem esperar os administradores do Nexo incluírem. Funciona com GitHub,
Codeberg e outros Forgejo/Gitea, para recomps, ports e emuladores.

> O Nexo **não traz jogos, chaves, firmware nem BIOS**. Os projetos do catálogo pedem a sua própria
> cópia do jogo; o Nexo só baixa o que o desenvolvedor publicou e organiza para você.

## Funcionalidades

**Descobrir e organizar**
- Dois universos: **PC** (recomps e ports) e **Emuladores**, cada um com Início, Biblioteca,
  Favoritos e Descobrir próprios.
- Busca, filtros por console, plataforma e gênero, e ordenação por populares, recentes ou A a Z.
- Capas e banners automáticos, do [SteamGridDB](https://www.steamgriddb.com), sem configurar nada; ou os seus.
- Adicione qualquer projeto pelo link do GitHub, Codeberg ou outro Forgejo/Gitea.

**Instalar e atualizar com segurança**
- Escolhe sozinho o arquivo certo para o seu sistema; dá para escolher outro.
- Download com retomada e conferência do SHA-256 publicado.
- Cada versão fica na sua pasta. A anterior continua lá até você decidir apagar, e dá para voltar
  ou **fixar** uma versão.
- Saves e arquivos seus são levados para a versão nova; o que um update trocaria vai antes para um
  backup.
- **Receitas automáticas** para projetos que precisam de preparo: o Nexo roda o setup, compila
  shaders e até **monta o jogo a partir dos seus NSP/NSZ do Switch**, sem ferramentas externas.

**Jogar**
- Jogar direto ou pelo launcher do projeto, com o tempo jogado contado.
- **Backup automático dos saves** (antes de cada update e ao desinstalar), com restauração.
- **Adicionar à Steam** com a capa do jogo: o atalho abre pelo Nexo, com versão, Proton e tempo de jogo.
- No Linux, jogos de Windows rodam pelo **Proton, umu-run ou Wine**.

**Aparência e conforto**
- Visual escuro ou claro, em português ou inglês.
- **Modo TV**: tela cheia, tudo maior e navegação completa pelo controle. Liga sozinho no modo jogo
  do Steam Deck, ou com um clique no botão da TV.
- O próprio Nexo se atualiza a partir das releases deste repositório, sempre com a sua permissão, e
  só aceita versões com a assinatura do Nexo.

## Capturas

| Descobrir | Página do jogo |
|---|---|
| ![Descobrir](docs/capturas/descobrir.jpg) | ![Página do jogo](docs/capturas/jogo.jpg) |
| **Emuladores** | **Downloads** |
| ![Emuladores](docs/capturas/inicio-emuladores.jpg) | ![Downloads](docs/capturas/downloads.jpg) |

**Modo TV**

![Modo TV](docs/capturas/modo-tv.jpg)

## Como instalar

Baixe a versão mais nova em **[Releases](https://github.com/nexolauncher-glitch/nexo/releases/latest)**.

### Windows 10/11 (64 bits)
1. Baixe `Nexo-…-Instalador-Windows.zip` e **extraia** (botão direito → **Extrair tudo**).
2. Abra o **`Instalar Nexo ….exe`** e siga os passos.
3. Na primeira vez, o Windows pode mostrar **"O Windows protegeu o computador"**, porque o Nexo ainda
   não tem certificado de assinatura pago. Clique em **Mais informações → Executar assim mesmo**.

### Linux (qualquer distribuição x64)
1. Baixe `Nexo-…-Instalador-Linux.tar.gz` e **extraia** (botão direito → **Extrair aqui**).
2. Abra o **`Instalar-Nexo-…`** e siga os passos. Pelo terminal:
   ```bash
   tar -xzf Nexo-*-Instalador-Linux.tar.gz && ./Instalar-Nexo-*
   ```
3. Para jogos que só têm versão de Windows, instale o **Proton** (pela Steam) ou o **umu-launcher**.

O mesmo pacote roda em Ubuntu, Fedora, Arch, Mint, SteamOS, Bazzite, CachyOS e outras, sem instalar nada
antes.

O instalador pergunta onde ficam o programa, os jogos de PC, os emuladores, os seus jogos de emulador e os
backups dos saves (o recomendado é tudo numa pasta só) e cria os atalhos:

![Instalador do Nexo](docs/capturas/instalador.jpg)

No Steam Deck e em outros sistemas com o modo jogo da Steam, use **Configurações → Pôr o Nexo na Steam** para abri-lo em modo TV direto do modo jogo.

### Updates
O Nexo procura versões novas ao abrir e de tempos em tempos. Quando sai uma, ele mostra as novidades e
pergunta antes de atualizar. O download vem das releases deste repositório; o Nexo confere a assinatura da versão e o SHA-256 do
pacote antes de trocar qualquer arquivo.

## Perguntas frequentes

**O Nexo é pirataria?** Não. Ele não hospeda nem baixa jogos comerciais. Os projetos do catálogo são
programas livres publicados pelos autores no GitHub, e cada um pede os arquivos do jogo que você já
tem.

**Onde ficam os jogos?** Nas pastas que você escolher no instalador ou em **Configurações → Pastas**:
uma para os jogos de PC e outra para os emuladores (por padrão, `Nexo/Jogos/PC` e `Nexo/Jogos/Emuladores`
no seu usuário). Cada jogo tem uma pasta por versão.

**Como desinstalar o Nexo?** No Windows, em **Configurações → Aplicativos → Nexo**; no Linux, clique com
o botão direito no Nexo no menu de aplicativos → **Desinstalar o Nexo**. Sai só o programa e os atalhos:
jogos, emuladores e saves ficam onde estão.

**Desinstalar um jogo apaga os meus saves?** Não. O Nexo só apaga os arquivos que ele mesmo instalou, e
mostra antes o que vai sair.

**Achei um projeto que não está no catálogo.** Use **Adicionar jogo** (ou **Adicionar emulador**) com o
link do repositório: ele já funciona na hora, no seu Nexo. Se quiser que entre no catálogo de todo mundo,
abra uma *issue* aqui.

## Linha de comando

Junto vem o `nexo-cli`, para scripts e servidores: `nexo-cli ajuda` lista tudo. Os principais são `lista`,
`instalar <id>`, `verificar`, `atualizar`, `jogar <id>` e `remover <id>`.

## Créditos e licença

- Catálogo montado a partir da curadoria do Nexo, do [recomplauncher.com](https://recomplauncher.com) e do
  [recomphub.com](https://recomphub.com); arte do [SteamGridDB](https://www.steamgriddb.com).
- Interface feita com [Slint](https://slint.dev).
- Fontes [Inter](https://rsms.me/inter/), [Sora](https://github.com/sora-xor/sora-font) e
  [Lora](https://github.com/cyrealtype/Lora-Cyrillic) (SIL OFL).
- Ícones [Lucide](https://lucide.dev) (ISC) e [Simple Icons](https://simpleicons.org) (CC0).
- Cada projeto do catálogo pertence a seus autores, e os jogos, às suas empresas.
- As bibliotecas usadas e as licenças delas vão no `TERCEIROS.txt`, dentro de cada pacote.

O Nexo é **grátis e de código fechado**: pode usar e compartilhar o pacote oficial à vontade, sem
modificar e sem vender (veja a [licença](LICENSE)). Novidades de cada versão estão no
**[CHANGELOG](CHANGELOG.md)**.

<p align="center"><a href="https://slint.dev"><img alt="Made with Slint" src="https://raw.githubusercontent.com/slint-ui/slint/master/logo/MadeWithSlint-logo-whitebg.png" height="40"></a></p>
