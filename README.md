::: {align="center"}
# 💜 ZARA BOT V4 💜

### ▭❦❲ Automação para WhatsApp · Termux · Node.js ❳❦▭

**🤖 Bot para WhatsApp · 📱 Android / Termux · ⚙️ Instalação prática ·
♻️ Inicialização rápida**

![Versão](https://img.shields.io/badge/VERS%C3%83O-V4-9B59B6?style=for-the-badge)
![Node.js](https://img.shields.io/badge/Node.js-LTS-339933?style=for-the-badge&logo=node.js&logoColor=white)
![Termux](https://img.shields.io/badge/ANDROID-TERMUX-111111?style=for-the-badge&logo=android&logoColor=3DDC84)
![WhatsApp](https://img.shields.io/badge/WHATSAPP-BOT-25D366?style=for-the-badge&logo=whatsapp&logoColor=white)

`<img src="https://capsule-render.vercel.app/api?type=waving&color=0:7F00FF,50:E100FF,100:00D4FF&height=170&section=header&text=ZARA%20BOT&fontSize=52&fontColor=ffffff&animation=fadeIn&fontAlignY=40&desc=V4%20%E2%80%A2%20WhatsApp%20Automation&descAlignY=65&descSize=17" width="100%" alt="Banner decorativo ZARA BOT V4" />`{=html}

👑 **Criado por Doctor Valeyard C'rizz Lunático**
:::

------------------------------------------------------------------------

## 📑 Navegação

[✨ Sobre](#-sobre-o-zara-bot-v4) · [🚀 Instalação](#-instalação) · [📲
Conexão](#-conectar-ao-whatsapp) · [♻️ Iniciar
novamente](#-como-iniciar-novamente) · [🛠️
Problemas](#️-solução-de-problemas) · [🔐 Segurança](#-segurança) · [📜
Licença](#-licença-e-créditos)

------------------------------------------------------------------------

## ✨ Sobre o ZARA BOT V4

O **ZARA BOT V4** é um projeto de automação para WhatsApp preparado para
execução no **Termux**, utilizando **Node.js**. Este README reúne o
comando de instalação, as orientações iniciais e o procedimento para
iniciar o bot novamente sem baixar tudo outra vez.

::: {align="center"}
   📱 Plataforma   ⚙️ Ambiente   📦 Instalação   🔄 Inicialização
  --------------- ------------- --------------- ------------------
      Android        Termux      Comando único    Comando rápido
:::

> 💜 **ZARA BOT V4 --- tecnologia, identidade e praticidade em um só
> projeto.**

## 🚀 Instalação

### ⚡ Comando único --- baixar, extrair, instalar e iniciar

Copie o comando abaixo e cole no Termux. Ele instala os pacotes
necessários, cria a pasta do projeto, baixa o ZIP, extrai os arquivos,
instala as dependências e inicia o bot.

``` bash
pkg update -y && pkg install -y nodejs-lts wget unzip ffmpeg && mkdir -p "$HOME/DOCTOR VALEYARD C'rizz Lunático" && cd "$HOME/DOCTOR VALEYARD C'rizz Lunático" && wget -O ZaraBot-V4.zip "https://github.com/DOCTOR-VALEYARD/Zara-sharman.js/raw/refs/heads/main/ZaraBot-V4.zip" && unzip -o ZaraBot-V4.zip && cd ZaraBot && npm install && node zarabot.js
```

### 📌 O que o comando faz?

1.  🔄 Atualiza a lista de pacotes.
2.  📦 Instala Node.js LTS, wget, unzip e FFmpeg.
3.  📁 Cria a pasta do projeto na área inicial do Termux.
4.  🌐 Baixa `ZaraBot-V4.zip` do repositório indicado.
5.  🗜️ Extrai os arquivos e entra na pasta `ZaraBot`.
6.  🧩 Instala as dependências com `npm install`.
7.  🤖 Executa `node zarabot.js`.

> \[!IMPORTANT\] O comando pressupõe que o ZIP contenha a pasta
> `ZaraBot` e que o arquivo principal seja `zarabot.js`. Se a estrutura
> interna do ZIP mudar, o caminho de extração ou o nome do arquivo de
> inicialização também poderá precisar mudar.

------------------------------------------------------------------------

## 📲 Conectar ao WhatsApp

1.  Aguarde o bot terminar a inicialização no Termux.
2.  Confira as instruções que aparecerem no terminal.
3.  Se aparecer um QR Code, abra o WhatsApp no celular.
4.  Acesse **Configurações → Aparelhos conectados → Conectar um
    aparelho**.
5.  Leia o QR Code exibido no Termux e aguarde a confirmação.

> ℹ️ Os nomes das opções podem variar conforme a versão do WhatsApp. Se
> o bot apresentar outro método de conexão, siga as instruções exibidas
> por ele.

------------------------------------------------------------------------

## ♻️ Como iniciar novamente

**Fechou o Termux ou reiniciou o celular?** Se os arquivos já estiverem
instalados, não precisa baixar o ZIP nem instalar tudo de novo.

Abra o Termux e execute este comando:

``` bash
cd "$HOME/DOCTOR VALEYARD C'rizz Lunático/ZaraBot" && node zarabot.js
```

Pronto: esse comando entra na pasta do bot e inicia o programa
novamente.

### 🧩 Se aparecer erro de dependências

Execute:

``` bash
cd "$HOME/DOCTOR VALEYARD C'rizz Lunático/ZaraBot" && npm install
```

Depois, inicie:

``` bash
cd "$HOME/DOCTOR VALEYARD C'rizz Lunático/ZaraBot" && node zarabot.js
```

### ⏹️ Para parar o bot

No terminal em que o bot está rodando, pressione **CTRL + C**. No Termux
para Android, normalmente você pode usar a tecla CTRL da barra extra do
teclado.

------------------------------------------------------------------------

## 🛠️ Solução de problemas

  -----------------------------------------------------------------------
  ⚠️ Mensagem / problema              ✅ O que verificar
  ----------------------------------- -----------------------------------
  `node: command not found`           Execute
                                      `pkg install -y nodejs-lts`.

  `npm install` apresenta erro        Confira a conexão com a internet e
                                      leia a mensagem completa do npm.

  `Cannot find module`                Entre na pasta correta e execute
                                      `npm install`.

  `No such file or directory`         Confira se a pasta `ZaraBot` existe
                                      e se o arquivo se chama
                                      `zarabot.js`.

  O QR Code não aparece               Aguarde a inicialização e verifique
                                      as instruções e os registros
                                      exibidos pelo bot.

  O bot fecha inesperadamente         Copie a mensagem completa do erro
                                      para investigar antes de apagar
                                      arquivos.
  -----------------------------------------------------------------------

Para conferir os arquivos e pastas do local atual, use:

``` bash
ls -la
```

Para verificar se o arquivo principal está na pasta esperada:

``` bash
ls -l "$HOME/DOCTOR VALEYARD C'rizz Lunático/ZaraBot/zarabot.js"
```

------------------------------------------------------------------------

## 🔐 Segurança e uso responsável

-   🔒 Não compartilhe QR Codes de autenticação, arquivos de sessão ou
    credenciais.
-   🛡️ Mantenha os arquivos de autenticação privados e fora de
    repositórios públicos.
-   🤝 Use o bot de forma responsável e respeite os termos do WhatsApp,
    a privacidade dos usuários e as leis aplicáveis.
-   🧰 Antes de apagar pastas ou reinstalar o projeto, guarde somente os
    dados de configuração que você precisa manter e que pode armazenar
    com segurança.

## 📜 Licença e créditos

A licença específica do código do bot não foi confirmada aqui. Antes de
redistribuir, modificar ou comercializar o projeto, confira se o
repositório contém um arquivo `LICENSE` e siga as condições
estabelecidas pelo autor. Este README, por si só, não concede direitos
adicionais sobre o código, as marcas ou os materiais de terceiros.

::: {align="center"}
### 👑 CRÉDITOS DO PROJETO

**DOCTOR VALEYARD C'RIZZ LUNÁTICO**

**Projeto:** ZARA BOT V4\
**Repositório:**
[DOCTOR-VALEYARD/Zara-sharman.js](https://github.com/DOCTOR-VALEYARD/Zara-sharman.js)\
**Execução:** Termux + Node.js

▭❦❲ ZARA BOT V4 · WhatsApp Automation ❳❦▭

`<img src="https://capsule-render.vercel.app/api?type=waving&color=0:00D4FF,50:E100FF,100:7F00FF&height=110&section=footer" width="100%" alt="Rodapé decorativo ZARA BOT V4" />`{=html}
:::
