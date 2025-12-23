# 🖥️ VIRTUAL DESKTOP CABLE

Conexão Virtual Desktop via cabo (ADB + Gnirehtet)
Feito por Rodrigo Marcos

## 🎯 Objetivo

Permitir usar o Virtual Desktop no Meta Quest/Pico por **cabo USB**, reduzindo dependência do Wi-Fi e ajudando a manter uma conexão mais estável (principalmente em ambientes com rede congestionada).

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
- ✅ Desabilita o Wifi no Headset quando a conexão é estabelecida e reabilita quando o programa é fechado.

---

## 📝 Requisitos obrigatórios

- 🕶️ Meta Quest em **Modo Desenvolvedor**
- 🐞 **Depuração USB** habilitada
- 🔌 Cabo USB de qualidade + porta **USB 3.0**
- 📲 Ao conectar, aceite no Quest: “Permitir depuração USB” (autorize o computador)


## 🚀 Como ativar o Modo Desenvolvedor

1- Acesse o painel de desenvolvedor: https://developer.oculus.com/manage
2. Faça login com a conta usada no Quest e crie uma Organização.
3- Aceite os termos de desenvolvedor.
4- No celular (com Bluetooth ligado), abra o app Meta Quest.
5- Vá em: ☰ → Dispositivos → Configurações do Headset → Modo Desenvolvedor.  Ative e reinicie o Quest.

6. Se o Java não estiver instalado, o programa solicitará permissão e abrirá o instalador
7. Se o APK não estiver instalado, o programa solicitará confirmação e instalará via ADB

---

## 🚀 Passo a passo

1- Garanta que o Modo Desenvolvedor esteja ativado na sua conta/dispositivo Meta  e habilite **USB Debugging / Depuração USB**. 

2- Conecte o cabo USB 3.0 no Meta Quest  e numa porta 3.0 traseira do seu computador. No Quest, clique em Permitir sempre que aparecer. Dica: marque “Sempre permitir neste dispositivo” para não precisar autorizar toda vez.

3. Deixe o Virtual desktop Streamer aberto e abra o **VIRTUAL DESKTOP CABLE**

3- Se o Java ou APK ainda não estiver instalado no Computador/headset, ele será instalado automaticamente. Confirme a instalação e aguarde. Na primeira execução, pode aparecer um pedido para autorizar o app a criar uma VPN. Autorize e reinicie o headset.

4- Se o Quest não conectar de jeito nenhum, use o botão RESETAR ADB. Se ainda não conectar, é possível que alguém tenha negado anteriormente a permissão de ADB no Quest. Nesse caso, faça o seguinte:  No Quest, vá em: Configurações → Avançado → Redefinir recursos experimentais → Redefinir para o padrão. Depois, reinicie o Meta Quest.

8. Quando estiver tudo OK,basta abrir o Virtual desktop no Headset e  aguardar de 5 a 15 segundos. Ele conectará automaticamente


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
  - Confirme que esta usando Cabo USB 3.0
  - Troque a porta USB, use a porta USB 3.0 traseira, teste outro cabo, use “RESET ADB” e teste novamente

---

> Feito com 💙 para a comunidade VR!
