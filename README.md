# 💰 Meu Orçamento

App pessoal de gestão financeira, feito como PWA (Progressive Web App) — roda direto no navegador, funciona offline e pode ser instalado no celular e no computador como se fosse um app nativo.

🔗 **Acesse:** https://alecmandev.github.io/meu-orcamento

## Funcionalidades

**Orçamento**
- Lançamentos de Receita, Despesa fixa e Despesa variável, organizados por mês
- Navegação entre meses ou filtro por período personalizado (30 dias, 90 dias, 12 meses, intervalo customizado)
- Categorias por botão, com cor própria — criar, renomear ou excluir categorias a qualquer momento
- Gráfico de pizza por categoria em cada aba, e gráficos de evolução (receita x despesa, 12 meses)
- Despesas parceladas (ex.: 3x no cartão) e despesas/receitas fixas recorrentes todo mês
- Edição e exclusão de qualquer lançamento, com confirmação

**Investimentos**
- Cadastro de ativos (nome, valor investido, valor atual, taxa/indexador)
- Metas de objetivo com foto, valor alvo, taxa e local onde está guardado, com barra de progresso
- Meta de investimento mensal baseada em % da receita
- Gráfico de aportes e saldo investido nos últimos 12 meses
- Calculadoras de juros compostos e de tempo/aporte necessário para bater uma meta

**Cartões de crédito**
- Cadastro de cartões com limite, dia de fechamento e dias até o vencimento
- Lançamentos no cartão contam automaticamente na fatura certa (considerando o fechamento)
- Gráficos de gasto por cartão (mês, ano e evolução de 12 meses)
- Registro de valores emprestados a terceiros no seu cartão, com data prevista de recebimento e aviso no topo do app quando o pagamento estiver próximo

**Financiamentos e dívidas**
- Financiamentos, consórcios e empréstimos, com progresso de parcelas pagas

**Outros**
- Patrimônio total e saldo acumulado, consistentes entre si (investir ou guardar numa meta desconta do saldo e não "cria" dinheiro)
- Opção de cobrir um saldo negativo do mês descontando de um investimento
- Exportação e importação de backup em `.json`
- Funciona offline (service worker) e pode ser instalado como app (PWA)

## Como instalar

- **Celular (Android/Chrome):** abra o link acima → menu ⋮ → "Instalar app"
- **iPhone (Safari):** abra o link → Compartilhar → "Adicionar à Tela de Início"
- **Computador (Chrome/Edge):** abra o link → ícone de instalação na barra de endereço → "Instalar"

## Tecnologia

HTML, CSS e JavaScript puro (sem frameworks ou build step), com os dados salvos localmente no navegador (`localStorage`). Nenhuma informação financeira é enviada a servidores externos.

## Backup dos dados

Como os dados ficam só no navegador, use o botão **💾 Exportar backup** (na aba Visão geral) regularmente, e **📥 Importar backup** para restaurar em outro dispositivo ou navegador.

---
Feito por Alessandro Alves da Silva.
