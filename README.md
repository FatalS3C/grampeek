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