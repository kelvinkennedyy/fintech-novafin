# NovaFin — Projeto Fintech (FIAP | Fase 4 - View)

Interface web responsiva desenvolvida para a atividade **Muito estilo sem sofrimento e Rede Social dos Desenvolvedores** do curso de **Análise e Desenvolvimento de Sistemas (FIAP)**.

## Sobre o Projeto

O **NovaFin** é uma tela completa de dashboard financeiro pessoal que centraliza:
- **Ações rápidas**: Área Pix, Transferir, Pagar Boleto e Investir.
- **Indicadores financeiros (KPIs)**: Saldo disponível, receitas mensais, despesas do mês e patrimônio investido.
- **Fluxo financeiro dos últimos 6 meses**: Gráfico comparativo de receitas e despesas construído com HTML semântico, Tailwind CSS e CSS puro (sem dependência de JavaScript).
- **Cartão virtual NovaFin**: Visual de cartão com acompanhamento de fatura atual e barra de limite disponível.
- **Últimas transações**: Tabela responsiva com categorização visual e status de lançamentos.
- **Metas financeiras e impacto ESG**: Progresso de objetivos (Reserva de Emergência, Setup & Estudos Dev e Fundo Verde Sustentável) e indicador de saúde financeira.

## Tecnologias Utilizadas

- **HTML5** semântico e acessível (`header`, `aside`, `nav`, `main`, `section`, `article`, `table`, `footer`)
- **CSS3** separado em arquivo dedicado (`css/styles.css`) com variáveis de identidade visual e estilos complementares
- **Tailwind CSS** para estruturação de layout, grid, espaçamentos e responsividade mobile-first
- **SVG local** (`assets/`) para logo, avatar e chip do cartão, garantindo carregamento imediato sem dependências externas quebradas

## Estrutura de Arquivos

```text
fintech-novafin/
├── index.html
├── css/
│   └── styles.css
├── assets/
│   ├── avatar.svg
│   ├── card-chip.svg
│   └── logo.svg
└── README.md
```

## Como Executar

Basta abrir o arquivo `index.html` diretamente em qualquer navegador moderno (Google Chrome, Edge, Firefox ou Safari). Não é necessário instalar dependências nem executar servidores locais.
