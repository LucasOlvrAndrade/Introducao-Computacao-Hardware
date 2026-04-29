# 🎮 Startup: Sistema de Guia para Platina de Jogos

## 1. Problema
Jogadores têm dificuldade para organizar e acompanhar o progresso rumo à platina, principalmente por causa da quantidade de troféus, da complexidade dos requisitos e da falta de uma estrutura centralizada para planejar a jornada em cada jogo.

### Dados coletados
- Histórico de troféus desbloqueados  
- Progresso por jogo  
- Preferências de plataforma: PS5, Xbox, PC e Nintendo  
- Tempo gasto em cada jogo  
- Grau de dificuldade dos troféus  
- Taxa de conclusão por título  
- Troféus já perdidos ou *missables*  
- Estilo de jogo do usuário  

---

## 2. Processamento

### Funcionamento geral
**Coleta → Armazenamento → Processamento → Análise**

- **Coleta:** o sistema registra o progresso do jogador, conquistas obtidas e tempo dedicado a cada jogo  
- **Armazenamento:** os dados ficam salvos em um banco de dados organizado por jogo, plataforma e perfil do usuário  
- **Processamento:** algoritmos analisam o progresso, identificam pendências e cruzam informações sobre troféus  
- **Análise:** a IA gera recomendações personalizadas para facilitar a rota da platina  

### Tecnologias utilizadas
- Inteligência Artificial  
- Algoritmos de recomendação  
- Banco de dados  
- Dashboard de progresso  
- Integração com APIs das plataformas de jogos  
- Sistema de alertas e lembretes  

### Elementos do sistema
- **Sistema:** aplicativo de guia para platina  
- **Processos:** análise de progresso + sugestão de rota ideal  
- **Banco de dados:** histórico de jogos, troféus e desempenho do usuário  
- **Fluxo:** dados → análise → recomendação → conclusão da platina  

---

## 3. Informação

### Descobertas geradas
- Identificação de jogos com maior dificuldade para platinar  
- Padrões de progresso do jogador  
- Troféus mais demorados ou mais fáceis de obter  
- Estimativa de tempo restante para concluir cada platina  
- Alertas sobre conquistas que podem ser perdidas no caminho  

### Como o sistema ajuda
- Indica o que fazer primeiro em cada jogo  
- Sugere a melhor ordem para conquistar troféus  
- Mostra etapas obrigatórias e opcionais  
- Ajuda a evitar retrabalho e perda de progresso  
- Organiza a jornada de platina em um formato claro e prático  

---

## 4. Decisão

### Decisões apoiadas pelo sistema
- Qual jogo iniciar ou continuar  
- Quais troféus priorizar  
- Quando repetir fases ou missões  
- Qual rota seguir para platinar mais rápido  
- Quando revisar troféus perdidos ou pendentes  

### Valor gerado
- Maior organização da jogatina  
- Mais eficiência na conquista de platinas  
- Menos tempo perdido tentando descobrir caminhos  
- Experiência mais clara e guiada para o jogador  
- Comunidade mais engajada com metas, rankings e progresso compartilhado  

---

## 5. Mapa Conceitual
- [DADOS]
- (histórico, troféus, tempo de jogo, dificuldade)
- ↓
- [PROCESSAMENTO]
- (coleta, IA, análise de progresso)
- ↓
- [INFORMAÇÃO]
- (relatórios, alertas, sugestões)
- ↓
- [CONHECIMENTO]
- (padrões de conquista e rotas ideais)
- ↓
- [DECISÃO]
- (próximo troféu, melhor caminho, prioridade)
- ↓
- [VALOR]
- (platina mais rápida, organização e engajamento)

---

## 🔁 Ciclo do Sistema

**Entrada → Processamento → Saída → Feedback**

O feedback vem do próprio desempenho do jogador, permitindo que o sistema aprenda com o comportamento dele e refine as recomendações ao longo do tempo.
