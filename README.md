# EngiFlow / SST Flow - Hub e Documentação Técnica

## 1. Objetivo e Finalidade
Hub corporativo, central de documentação técnica e propostas comerciais interativas para engenharia e automação.

## 2. Tecnologias Utilizadas
- Node.js, SST (Serverless Stack), Cloudflare Workers, HTML5, CSS3, JavaScript

## 3. Arquitetura e Estrutura de Diretórios
Estrutura moderna serverless com SST (`sst/`) e Cloudflare Workers, servindo documentos técnicos interativos e propostas comerciais estilizadas em `public/`.

## 4. Principais Arquivos e Responsabilidades
- `sst/package.json`: Configurações de infraestrutura como código SST.
- `sst/public/index.html`: Hub central de navegação.
- `sst/public/tecnica/`: Documentação técnica aprofundada de engenharia.
- `sst/public/vendas/`: Modelo de proposta comercial e apresentação de serviços.

## 5. Funcionalidades Identificadas
- Apresentação técnica interativa de fluxos de engenharia
- Propostas comerciais dinâmicas com cálculo de investimento
- Infraestrutura serverless de baixo custo e alta disponibilidade

## 6. Como Compilar ou Executar
```bash
cd sst
npm install
npx sst dev
```

## 7. Estado Atual do Projeto
**Completo**

## 8. Pendências e Limitações Identificadas
Geração automatizada de proposta em PDF para download direto pelo cliente.
