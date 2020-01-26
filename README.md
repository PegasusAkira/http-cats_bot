# Cats Http Bot

Esse é um bot que posta uma fotos de gatos relacionadas a erros de http a cada uma hora no [@CatsHttp_Bot](https://twitter.com/CatsHttp_Bot)  
![404](https://http.cat/404)

## Instalando e executando
Primeiro é necessário instalar o python 3 e o pip3 se já não instalados.
```
apt install python3
apt install python3-pip
```
Clonar o repositório para a sua máquina local e acessar o repositório.
```
git clone https://github.com/PegasusAkira/http-cats_bot.git
cd http-cats_bot
```
E então usar o pip para instalar os requisitos do bot.
```
pip3 install -r requirements.txt
```
Modificar o arquivo core.py, adicionando suas credenciais da API do Twitter nas variáveis consumer_key, consumer_secret, access_token e access_token_secret.

E por último é só acessar a pasta do arquivo core.py e executar o bot.
```
cd src
python3 core.py
```

## Futuras atualizações:
- [X] Conseguir um seviço de hospedagem gratuito para o bot.
- [X] O bot mostrar no terminal uma mensagem com a hora assim que uma mensagem for postada.
- [ ] Criar um intervalo para o bot não repetir uma imagem no mesmo dia.
- [ ] Mensagem para o bot responder alguém quando for marcado.
- [ ] Atualização de Status relativa a imagem a cada atualização.  

Fotos retiradas do site [HTTP Cats](https://http.cat/)
