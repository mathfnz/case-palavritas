# Case Palavritas — Análise de Retenção de Usuários
**the news | Processo Seletivo — Analista de Dados Produto & Growth**

## Sobre o projeto
Análise de retenção do Palavritas, jogo de palavras diário do app da the news.
Pergunta central: o que está determinando se um usuário volta a jogar?

## Arquivos
- `palavritas_case_analise_final.ipynb` — análise completa com limpeza, EDA, retenção, análise avançada e significância estatística
- `dashboard_palavritas.html` — dashboard interativo com todos os achados

## Dashboard
👉 [Acessar dashboard](https://mathfnz.github.io/case-palavritas/dashboard_palavritas.html)

## Principais achados
- **Streak** é o maior preditor de retenção D1 — usuários com 7 dias seguidos retornam 53% mais
- **Período matutino** é o maior preditor de retenção D30 — 37,8% vs 29,0% do período noturno
- **D1 prediz D30** — quem volta no dia seguinte tem 3x mais retenção em 30 dias
- **Combinação streak + morning** — 40,1% de D30, diferença de 10,7 p.p. vs pior perfil (p < 0,0001)
- **Primeira sessão** — usuários que acertam na 1ª tentativa têm 33% mais retenção D30

## Propostas de ação
1. Sistema de streak visível + notificação push
2. Incentivar período matutino via push entre 7h e 9h
3. Onboarding adaptativo para novos usuários
4. Campanha para ativar o perfil de maior retenção

## Ferramentas
Python · pandas · matplotlib · seaborn · scipy · plotly
