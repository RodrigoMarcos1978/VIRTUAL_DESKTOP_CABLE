# 🖥️ VIRTUAL DESKTOP CABLE

Conexão Virtual Desktop via cabo (ADB + Gnirehtet)
Feito por Rodrigo Marcos

## 🎯 Objetivo

Permitir usar o Virtual Desktop no Meta Quest/ Pico por **cabo USB**, reduzindo dependência do Wi-Fi e ajudando a manter uma conexão mais estável (principalmente em ambientes com rede congestionada).

---

## ⚙️ Como funciona

O programa utiliza:

- 📱 **ADB** para comunicação com o Quest
- 🔄 **Gnirehtet** (APK + JAR) para rotear a rede pelo cabo
- ☕ **Java (JDK)** para executar o Gnirehtet

Tudo é **automatizado**:

- ✅ Valida Java
- ✅ Valida ADB
- ✅ Instala o APK se necessário
- ✅ Inicia a conexão automaticamente
- ✅ Exibe status e logs

---

## 📝 Requisitos obrigatórios

- 🕶️ Meta Quest em **Modo Desenvolvedor**
- 🐞 **Depuração USB** habilitada
- 🔌 Cabo USB de qualidade + porta **USB 3.0**
- 📲 Ao conectar, aceite no Quest: “Permitir depuração USB” (autorize o computador)

---

## 🚀 Passo a passo

1. Ative o **Modo Desenvolvedor** no app da Meta (configurações do dispositivo)
2. No Quest, habilite **USB Debugging / Depuração USB**
3. Conecte o Quest ao PC via **USB 3.0**
4. Abra o **VIRTUAL DESKTOP CABLE**
5. Se o Java não estiver instalado, o programa solicitará permissão e abrirá o instalador
6. Se o APK não estiver instalado, o programa solicitará confirmação e instalará via ADB
7. Quando estiver tudo OK, ele conecta automaticamente

---

## 🕹️ Botões do programa

- **CONNECT / DISCONNECT QUEST**
  - Conecta ou desconecta a sessão do Gnirehtet
- **RESET ADB**
  - Encerra sessões travadas do ADB e reinicia o serviço (use se o Quest não aparece ou fica “unauthorized”)
- **REINSTALL APK QUEST**
  - Reinstala o Gnirehtet APK no Quest (disponível apenas quando ADB estiver ativo)

---

## 🛠️ Solução de problemas

- **ADB não conecta / aparece “unauthorized”**
  - Coloque o Quest no headset e aceite o popup de autorização de Depuração USB
- **Quest não aparece**
  - Troque a porta USB, use USB 3.0, teste outro cabo e use “RESET ADB” e teste novamente
- **Conexão cai / instável**
  - Desligue o Wi-Fi no Quest para manter a rota pelo cabo

---

> Feito com 💙 para a comunidade VR!
