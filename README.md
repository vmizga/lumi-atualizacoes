<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="imagens/logo-lumi-legendas.png">
    <img src="imagens/logo-lumi-legendas-claro.png" alt="Lumi legendas" width="420">
  </picture>
</p>

<p align="center">
  Atualizações oficiais do <b>Lumi</b>, plugin para DaVinci Resolve Studio que corta silêncios e tomadas erradas
  e gera legendas animadas palavra por palavra.
</p>

<p align="center">
  <img src="imagens/mascote-lumi.png" alt="O Lumi, gato mascote" width="420">
</p>

## Como funciona
Depois de instalado, o Lumi confere sozinho se existe versão nova aqui e se atualiza, sem pedir nada ao usuário.
Ele lê o `latest.json` daqui quando o painel abre e depois a cada 30 minutos. Cada versão fica neste repositório:

- `latest.json`: o aviso da versão mais nova, assinado digitalmente (o Lumi recusa qualquer pacote sem a assinatura certa);
- `v<versão>/app-<versão>.zip`: o pacote da atualização, usado na próxima vez que o painel abrir.

Este repositório guarda só os pacotes públicos. O código-fonte do Lumi é privado.
