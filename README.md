<p align="center">
  <img src="https://i.ibb.co/RT4sy41f/imagem.png" width="400">
</p>

# ⚫️ GramPeek [0.1]
Ferramenta **research-grade** para inspeção de tráfego de rede durante ligações do Telegram, construída com Scapy.

<a href='https://www.python.org/downloads/' target="_blank"><img alt='python' src='https://img.shields.io/badge/Python_3-100000?style=for-the-badge&logo=python&logoColor=white&labelColor=black&color=black'/></a>


O foco do projeto é simples e direto: no momento em que a chamada é atendida, o IP remoto é identificado e exposto a partir da análise do tráfego de rede.

## Visão geral
- Sniffa pacotes relacionados a chamadas do Telegram
- Observa o handshake/conexão no momento do atendimento
- Extrai e revela o IP do outro lado da ligação
- Não depende de APIs externas
- Não toca em criptografia ou conteúdo da chamada

## Requisitos
- Python 3
- Permissão de administrador (sudo)

# 📦 Instalação
```bash
git clone https://github.com/FatalS3C/grampeek
cd grampeek
sudo python3 grampeek.py --sniff
```
⚠️ Importante: o Scapy já vem incluído na pasta do projeto.
Não é necessário instalar dependências via pip nem alterar o sistema do usuário.
> [!IMPORTANT]
> É necessário usar SUDO para capturar os pacotes.

# Uso
```bash
sudo python3 grampeek.py --sniff
```
Ligue ou aguarde uma ligação
<p align="center">
  <img src="https://i.ibb.co/Zz08SN1Y/peguinhapau.png" width="700">
</p>

# Parâmetros disponíveis
| Paramêtro  | Descrição |
| ------------- | ------------- |
| ```--nowhois``` | Não gera um WHOIS a cada IP  |
| ```--json``` | Gera o Whois em formato de JSON  |
| ```--sniff``` | Sniffa a ligação com Telegram  |
| ```--update``` | Checa por novas versões  |
#
### Obrigado pela atenção!

<a href='https://t.me/fatalsec' target="_blank"><img alt='telegram' src='https://img.shields.io/badge/fatalsec-100000?style=plastic&logo=telegram&logoColor=white&labelColor=black&color=black'/></a> <a href='https://x.com/F4t4lsec' target="_blank"><img alt='x' src='https://img.shields.io/badge/fatalsec-100000?style=plastic&logo=x&logoColor=white&labelColor=black&color=black'/></a> <a href='https://www.youtube.com/channel/UCVroJZsK3Qrvtvnk7NCKn-A' target="_blank"><img alt='youtube' src='https://img.shields.io/badge/Canal_no youtube-100000?style=plastic&logo=youtube&logoColor=white&labelColor=black&color=black'/></a> <a href='https://www.instagram.com/fatalsec' target="_blank"><img alt='instagram' src='https://img.shields.io/badge/Instagram-100000?style=plastic&logo=instagram&logoColor=white&labelColor=black&color=black'/></a>

### Caso queira me apoiar ^^
<a href='https://github.com/FatalS3C/FatalS3C/blob/main/my_btc.png?raw=true' target="_blank"><img alt='bitcoin' src='https://img.shields.io/badge/Meu_BTC-100000?style=plastic&logo=bitcoin&logoColor=white&labelColor=black&color=black'/></a> <a href='https://livepix.gg/fatallartes' target="_blank"><img alt='pix' src='https://img.shields.io/badge/LivePix-100000?style=plastic&logo=pix&logoColor=white&labelColor=black&color=black'/></a>
