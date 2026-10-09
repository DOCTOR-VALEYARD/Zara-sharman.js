::: {align="center"}
`<img src="https://capsule-render.vercel.app/api?type=waving&color=0:090018,20:4B0082,45:9D00FF,70:FF36B8,100:00D9FF&height=230&section=header&text=ZARA%20BOT%20V4&fontSize=62&fontColor=FFFFFF&fontAlignY=40&animation=fadeIn&desc=✦%20WHATSAPP%20AUTOMATION%20✦&descSize=18&descAlignY=64&descColor=F7E9FF" width="100%" alt="Banner animado ZARA BOT V4" />`{=html}

`<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=700&size=18&pause=900&color=E879F9&center=true&vCenter=true&width=680&lines=💜+Bem-vindo+ao+ZARA+BOT+V4;🤖+Automação+para+WhatsApp;📱+Instalação+no+Termux;⚡+Simples.+Prático.+ZARA." alt="Texto animado ZARA BOT V4" />`{=html}

`<br/>`{=html}

`<img src="https://img.shields.io/badge/💜%20ZARA%20BOT-V4-C026D3?style=for-the-badge" alt="ZARA BOT V4" />`{=html}
`<img src="https://img.shields.io/badge/📱%20ANDROID-TERMUX-18181B?style=for-the-badge&logo=android&logoColor=3DDC84" alt="Android Termux" />`{=html}
`<img src="https://img.shields.io/badge/⚙️%20NODE.JS-LTS-43853D?style=for-the-badge&logo=nodedotjs&logoColor=white" alt="Node.js LTS" />`{=html}

### ✧･ﾟ: *✧･ﾟ:* **AUTOMAÇÃO • TECNOLOGIA • IDENTIDADE** *:･ﾟ✧*:･ﾟ✧
:::

------------------------------------------------------------------------

::: {align="center"}
## 🌌「 SOBRE O PROJETO 」🌌

**ZARA BOT V4** é um bot para WhatsApp executado pelo Termux com
Node.js.

💜 Instalação guiada\
⚡ Comando único\
♻️ Inicialização rápida\
🛠️ Orientações para erros comuns
:::

------------------------------------------------------------------------

## 📑 ✦ NAVEGAÇÃO ✦

-   [🚀 Instalação](#-01--instalação-completa)
-   [📲 Conectar ao WhatsApp](#-02--conectar-ao-whatsapp)
-   [♻️ Iniciar novamente](#-03--iniciar-o-bot-novamente)
-   [🧰 Solução de problemas](#-04--solução-de-problemas)
-   [🔐 Segurança](#-05--segurança)
-   [👑 Créditos](#-créditos-oficiais)

------------------------------------------------------------------------

## 🚀 01 --- INSTALAÇÃO COMPLETA

::: {align="center"}
**╭━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━╮**\
**┃ 💜 COMANDO DE INSTALAÇÃO 💜 ┃**\
**╰━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━╯**

📥 Baixa · 📦 Extrai · ⚙️ Instala · 🤖 Inicia
:::

Copie o comando inteiro abaixo e cole no Termux:

``` bash
pkg update -y && pkg install -y nodejs-lts wget unzip ffmpeg && mkdir -p "$HOME/DOCTOR VALEYARD C'rizz Lunático" && cd "$HOME/DOCTOR VALEYARD C'rizz Lunático" && wget -O ZaraBot-V4.zip "https://github.com/DOCTOR-VALEYARD/Zara-sharman.js/raw/refs/heads/main/ZaraBot-V4.zip" && unzip -o ZaraBot-V4.zip && cd ZaraBot && npm install && node zarabot.js
```

```{=html}
<details>
```
```{=html}
<summary>
```
✨ `<b>`{=html}O que acontece durante a instalação?`</b>`{=html}
```{=html}
</summary>
```
   Etapa  Ação
  ------- ----------------------------------------------
     ①    🔄 Atualiza os pacotes do Termux
     ②    📦 Instala Node.js LTS, wget, unzip e FFmpeg
     ③    📁 Cria a pasta do projeto
     ④    🌐 Baixa o ZIP do repositório
     ⑤    🗜️ Extrai os arquivos do bot
     ⑥    🧩 Instala as dependências do projeto
     ⑦    🤖 Inicia o ZARA BOT V4

```{=html}
</details>
```
> \[!IMPORTANT\] ⚠️ Este comando espera encontrar a pasta `ZaraBot`
> dentro do ZIP e o arquivo de entrada `zarabot.js` dentro dessa pasta.

------------------------------------------------------------------------

## 📲 02 --- CONECTAR AO WHATSAPP

**🔗 Siga os passos indicados pelo próprio bot:**

1.  ⏳ Aguarde a inicialização no Termux.
2.  📷 Se aparecer um QR Code, abra o WhatsApp.
3.  ⚙️ Entre em **Configurações → Aparelhos conectados**.
4.  📱 Toque em **Conectar um aparelho**.
5.  ✅ Leia o QR Code e aguarde a confirmação.

> 💡 Se o bot apresentar outro método de conexão, siga as instruções
> mostradas no terminal.

------------------------------------------------------------------------

## ♻️ 03 --- INICIAR O BOT NOVAMENTE

::: {align="center"}
### 😴 Fechou o Termux?

### 💜 Não precisa baixar tudo outra vez!
:::

Abra o Termux e execute somente este comando:

``` bash
cd "$HOME/DOCTOR VALEYARD C'rizz Lunático/ZaraBot" && node zarabot.js
```

**✅ Pronto!** O comando entra na pasta já instalada e inicia o bot.

### 🧩 Reinstalar as dependências, se necessário

``` bash
cd "$HOME/DOCTOR VALEYARD C'rizz Lunático/ZaraBot" && npm install
```

Depois:

``` bash
cd "$HOME/DOCTOR VALEYARD C'rizz Lunático/ZaraBot" && node zarabot.js
```

------------------------------------------------------------------------

## 🧰 04 --- SOLUÇÃO DE PROBLEMAS

  -----------------------------------------------------------------------
  ❌ Problema                         🔧 Solução
  ----------------------------------- -----------------------------------
  `node: command not found`           `pkg install -y nodejs-lts`

  `Cannot find module`                Entre na pasta `ZaraBot` e execute
                                      `npm install`.

  `No such file or directory`         Confira o nome da pasta e do
                                      arquivo principal.

  Falha no download                   Verifique a internet e se o ZIP
                                      ainda está disponível no GitHub.

  O bot encerra sozinho               Leia a mensagem de erro completa
                                      antes de reinstalar.
  -----------------------------------------------------------------------

Para conferir se o arquivo principal está no local esperado:

``` bash
ls -l "$HOME/DOCTOR VALEYARD C'rizz Lunático/ZaraBot/zarabot.js"
```

------------------------------------------------------------------------

## 🔐 05 --- SEGURANÇA

-   🔒 Nunca publique QR Codes, credenciais ou arquivos de sessão.
-   🛡️ Mantenha informações privadas fora de repositórios públicos.
-   🤝 Use o bot de forma responsável e respeite a privacidade dos
    usuários.
-   📜 Confira a licença do projeto antes de redistribuir ou
    comercializar o código.

------------------------------------------------------------------------

::: {align="center"}
## 👑 CRÉDITOS OFICIAIS 👑

### 💜 DOCTOR VALEYARD C'RIZZ LUNÁTICO 💜

**╭━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━╮**\
**┃　　　 ✦ ZARA BOT V4 ✦　　　 ┃**\
**┃　 WHATSAPP AUTOMATION BOT　 ┃**\
**╰━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━╯**

🔗 **Repositório oficial**

[github.com/DOCTOR-VALEYARD/Zara-sharman.js](https://github.com/DOCTOR-VALEYARD/Zara-sharman.js)

`<img src="https://capsule-render.vercel.app/api?type=waving&color=0:00D9FF,25:FF36B8,55:9D00FF,80:4B0082,100:090018&height=190&section=footer&animation=fadeIn" width="100%" alt="Rodapé ondulado animado ZARA BOT V4" />`{=html}

**💜 Feito para quem curte tecnologia, automação e estilo. 💜**
:::
