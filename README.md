# 🤖 Klovzzada Bot

Bot de WhatsApp desenvolvido em Node.js, focado em automação, diversão e utilidades.

---

## 📦 Requisitos

Antes de iniciar, certifique-se de ter:

- Termux atualizado
- Node.js LTS
- Git
- FFmpeg

---

## 🚀 Comandos iniciais (Termux)

Execute os comandos abaixo:

```bash
pkg upgrade -y && pkg update -y && pkg install git -y && pkg install nodejs-lts -y && pkg install ffmpeg -y


```bash
termux-setup-storage



```bash
cd /storage/emulated/0/Download


```bash
git clone https://github.com/arthurrenzo104-bit/klovzzada-bot



```bash
cd klovzzada-bot




```bash
chmod -R 755 ./*



```bash
npm start




📱 Conectando o Bot ao WhatsApp:
Insira o número de telefone e pressione Enter
Informe o código que aparece no Termux no seu WhatsApp


📹 Vídeo explicativo:
(coloque aqui o link do vídeo)



Aguarde cerca de 10 segundos
Para parar o bot, pressione:

CTRL + C


Após parar o bot, configure o arquivo abaixo:


```bash
src/config.js



Conteúdo de exemplo:
// Prefixo padrão dos comandos.
export const PREFIX = ".";

// Emoji do bot.
export const BOT_EMOJI = " 🫣 ";

// Nome do bot.
export const BOT_NAME = "Klovzzada Bot";

// LID do bot.
// Use o comando <prefixo>lid respondendo a uma mensagem do bot.
export const BOT_LID = "12345678901234567890@lid";

// LID do dono do bot.
// Use o comando <prefixo>meu-lid.
export const OWNER_LID = "12345678901234567890@lid";



🔁 Iniciando o Bot Novamente.

Depois de configurar tudo, inicie o bot novamente:
```bash
npm start



☝🏻Observações Importantes
O comando de permissões deve ser executado apenas uma vez.

Sempre use CTRL + C para parar o bot corretamente.

Mantenha o Termux atualizado para evitar erros.

🧠 Créditos
Bot de WhatsApp Klovzzada, desenvolvido e mantido por Klovzzada.






