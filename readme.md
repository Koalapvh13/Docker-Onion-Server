# Tor Hidden Services withining Docker

Implementação de um servidor ````.onion`` usando Docker e NGINX.

## Como rodar

1. Rode o compose:
```bash
$ docker compose up -d
```
2. Recupere a URL do site usando o comando:
```bash
$ docker exec tor cat /var/lib/tor/hidden_service/hostname
```

3. Acesse o site usando o Tor Browser.

## Editar páginas
Todas as páginas do servidor estão no diretório ```./src```, para adicionar mais páginas ao projeto utilize-o.

## Disclaimer
Projeto feito com propósito de aprender mais sobre a rede tor e gerenciamento de servidores.

Tutorial adaptado do canal NetworkChuck: 

[![Watch the video](https://img.youtube.com/vi/bllS9tkCkaM/default.jpg)](https://youtu.be/bllS9tkCkaM)