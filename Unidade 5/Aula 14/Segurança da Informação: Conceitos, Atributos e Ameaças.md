# Aula 14 – Segurança da Informação: Conceitos, Atributos e Ameaças

## Objetivo
Compreender os conceitos fundamentais da segurança da informação, identificar seus principais atributos e reconhecer ameaças comuns, aplicando os conhecimentos em estudo de caso prático.

## Práticas de laboratório de informática


### 1. Conceitos Fundamentais
- Definição de **Segurança da Informação** (ISO/IEC 27000:2018):
    - Segurança da Informação é a proteção das informações contra diversos tipos de ameaças, garantindo principalmente:
      
- Explicação dos atributos principais:
  
    - **Confidencialidade:**
  Acesso restrito apenas a indivíduos, entidades ou processos explicitamente autorizados.
    
    - **Integridade:**
  Garantia de precisão e completude. Os dados não podem ser alterados ou corrompidos indevidamente (protegidos via backup e criptografia).
    
    - **Disponibilidade:**
  Acesso contínuo e garantido à informação e aos sistemas sempre que o usuário necessitar.
    
    - **Privacidade:**
  Proteção rigorosa de dados pessoais e sensíveis, em total conformidade com a LGPD

### 2. Ameaças e Vulnerabilidades
- Exemplos de ameaças digitais (phishing, malware, engenharia social).
- Vulnerabilidades técnicas e humanas.
- Impactos potenciais em sistemas e organizações.

### 3. Estudo de Cenário
  - Contexto do ataque:
    O WannaCry foi um ransomware que infectou mais de 230 mil computadores em 150 países. O ataque bloqueava arquivos e exigia pagamento em Bitcoin. Hospitais, empresas e órgãos públicos foram afetados, incluindo o sistema de saúde do Reino Unido.
    
  - Vulnerabilidade explorada:
    O malware explorou a falha “EternalBlue” no Windows, ligada ao protocolo SMB. Muitos computadores estavam desatualizados e sem correções de segurança.
    
  - Impactos causados:
    - Paralisação de serviços e empresas.
    - Bloqueio de dados e sistemas.
    - Cancelamento de atendimentos hospitalares.
    - Prejuízo estimado em US$ 4 bilhões.
      
  - Medidas de mitigação aplicadas ou recomendadas:
    - Atualização dos sistemas Windows.
    - Desativação do SMBv1.
    - Uso de antivírus e backups.
    - Monitoramento e correção rápida de vulnerabilidades.
    - Treinamento de usuários em segurança digital.
   
## Referências: 

- CloudFlare. http://cloudflare.com/pt-br/learning/security/ransomware/wannacry-ransomware/
  
- Karspersky. https://www.kaspersky.com.br/resource-center/threats/ransomware-wannacry

- Fortnet. https://www.fortinet.com/br/resources/cyberglossary/wannacry-ransomware-attack
