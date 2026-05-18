# Trabalho: Internet, Protocolos e Navegadores 
## Objetivo 
Compreender a origem e evolução da Internet, seus conceitos fundamentais, os principais protocolos de comunicação e o papel dos navegadores no acesso à Web. 

## 1. História da Internet: A Internet surgiu a partir de projetos de pesquisa voltados para a comunicação entre computadores em rede.
- ARPANET (décadas de 60/70): foi a rede precursora da Internet, criada pelo Departamento de Defesa dos Estados Unidos para interligar universidades e centros de pesquisa.
- Expansão acadêmica e militar: nos anos 70 e 80, a rede passou a ser usada por instituições acadêmicas, científicas e militares para troca de informações.
- Comercialização nos anos 90: a Internet começou a se popularizar com o surgimento de provedores e do acesso para usuários comuns.
- Criação da WWW por Tim Berners-Lee: a World Wide Web tornou a navegação mais simples ao introduzir HTML, HTTP e URLs, facilitando o acesso a páginas por navegadores.
  
## 2. Conceitos Fundamentais
  ### Internet vs. Web
- Internet: é a infraestrutura de redes conectadas no mundo inteiro.
- Web: é um serviço que funciona sobre a Internet, permitindo acessar sites e páginas por navegadores.
  
  ### Arquitetura cliente-servidor
  A comunicação na Web funciona no modelo cliente-servidor:
- O cliente faz a solicitação, como um navegador.
- O servidor recebe o pedido, processa e envia a resposta.
Exemplo:
- O usuário digita um endereço no navegador.
- O navegador envia uma requisição ao servidor.
- O servidor responde com a página solicitada.
  
## Uso de endereços IP
O IP identifica dispositivos na rede.
Exemplos:
- IPv4: 192.168.0.1
- IPv6: 2001:db8::1
Na prática, quando um usuário acessa um site, o nome do domínio é convertido em um endereço IP para que a comunicação aconteça corretamente.
## 3. Protocolos
### TCP/IP 
  É a base da comunicação na Internet.
- TCP: garante que os dados cheguem corretamente e na ordem certa.
- IP: identifica os dispositivos e encaminha os pacotes pela rede.
    Exemplo prático: ao abrir um site, os dados trafegam em pacotes e chegam ao destino por meio do TCP/IP.
  
### HTTP/HTTPS
São protocolos usados para transferir conteúdo da Web.
- HTTP: realiza a comunicação entre navegador e servidor.
- HTTPS: faz o mesmo, mas com criptografia, aumentando a segurança.
    Exemplo prático: ao acessar um site bancário, o navegador usa HTTPS para proteger os dados.
  
### DNS
O DNS traduz nomes de domínio em endereços IP.
Exemplo prático: ao digitar www.google.com, o DNS descobre o IP correspondente.

### FTP
O FTP é usado para transferir arquivos entre computadores.
  Exemplo prático: envio de arquivos de um site do computador do desenvolvedor para o servidor de hospedagem.

## 4. Navegadores
Os navegadores permitem acessar e interpretar conteúdos da Web.

### Função dos navegadores
Eles interpretam:
- HTML: estrutura da página
- CSS: estilo visual
- JavaScript: interatividade
O navegador recebe os arquivos do servidor, processa esses elementos e exibe a página ao usuário.

### Principais motores de renderização
- Blink (Chrome/Edge): rápido e muito usado em navegadores modernos.
- Gecko (Firefox): motor do Firefox, com foco em padrões abertos.
- WebKit (Safari): usado no Safari, muito presente no ecossistema Apple.
  
## 5. Exercício Prático – Análise de Protocolos
