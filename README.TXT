VIRTUAL DESKTOP CABLE
Conexão Virtual Desktop via cabo (ADB + Gnirehtet)

Objetivo

Permitir usar o Virtual Desktop no Meta Quest por cabo USB, reduzindo dependência do Wi-Fi e ajudando a manter uma conexão mais estável (principalmente em ambientes com rede congestionada).

Como funciona (resumo)

O programa usa:

ADB para comunicação com o Quest;

Gnirehtet (APK + JAR) para rotear a rede pelo cabo;

Java (JDK) para executar o Gnirehtet.

Tudo é automatizado:

valida Java,

valida ADB,

instala o APK se necessário,

inicia a conexão automaticamente,

exibe status e logs.

Requisitos obrigatórios

Meta Quest em Modo Desenvolvedor

Depuração USB habilitada

Cabo USB de qualidade + porta USB 3.0

Ao conectar, você precisa aceitar no Quest: “Permitir depuração USB” (autorize o computador)

Passo a passo

Ative o Modo Desenvolvedor no app da Meta (configurações do dispositivo).

No Quest, habilite USB Debugging / Depuração USB.

Conecte o Quest ao PC via USB 3.0.

Abra o VIRTUAL DESKTOP CABLE.

Se o Java não estiver instalado, o programa vai solicitar permissão e abrir o instalador.

Se o APK não estiver instalado, o programa solicita confirmação e instala via ADB.

Quando estiver tudo OK, ele conecta automaticamente.

Botões do programa

CONNECT / DISCONNECT QUEST
Conecta ou desconecta a sessão do Gnirehtet.

RESET ADB
Encerra sessões travadas do ADB e reinicia o serviço (use se o Quest não aparece ou fica “unauthorized”).

REINSTALL APK QUEST
Reinstala o Gnirehtet APK no Quest (disponível apenas quando ADB estiver ativo).

Solução de problemas

ADB não conecta / aparece “unauthorized”
Coloque o Quest no headset e aceite o popup de autorização de Depuração USB.

Quest não aparece
Troque a porta USB, use USB 3.0, teste outro cabo e use “RESET ADB”.

Conexão cai / instável
Desligue o Wi-Fi no Quest para manter a rota pelo cabo.
