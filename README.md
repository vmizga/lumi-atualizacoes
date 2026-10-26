# lumi-atualizacoes

Pacotes públicos da atualização automática do **Lumi** (plugin de legendas para o DaVinci Resolve).
O código-fonte fica no repositório privado; aqui ficam só os pacotes (embaralhados e assinados).

- `latest.json`: a versão mais nova, com o sha256 do pacote e a assinatura ed25519.
- `v<versão>/app-<versão>.zip`: o app de cada versão.

O Lumi lê `latest.json` daqui ao abrir e a cada 30 minutos, baixa o pacote, confere o sha256 e a
assinatura, e usa a versão nova na próxima vez que o painel abrir. Pacote sem assinatura válida é ignorado.
