# Planner TDAH Adultos — Pacote de Materiais

Este pacote reúne versões impressas e digitais do planner para adultos com TDAH, cobrindo rotina, estudos, empreendedorismo e gerenciamento pessoal. Foi criado para complementar o app existente e facilitar a entrega imediatamente após a compra.

- **Versão imprimível (PDF/Print-ready)**: páginas em HTML + CSS otimizadas para exportar em A4 (pode gerar PDF direto no navegador).
- **Versão editável (Google Sheets / Excel / LibreOffice)**: planilhas estruturadas para controle diário, semanal, financeiro e de hábitos.
- **Versão Notion / substituto digital**: template em Markdown com blocos indicados para importação rápida.
- **Guias rápidos**: instruções de uso e sugestões de rotina para diferentes perfis (estudantes, empreendedores, profissionais CLT).

## Identidade visual

As referências cromáticas seguem a logo fornecida.

| Uso | HEX | Descrição |
| --- | --- | --- |
| **Primária** | `#9DBAF8` | Fundo suave (mesmo tom azul da marca) |
| **Secundária** | `#5273C7` | Acentos e títulos principais |
| **Apoio** | `#F4F7FF` | Fundos neutros e boxes |
| **Texto principal** | `#1F2D52` | Texto de alto contraste |
| **Texto secundário** | `#3E4A6E` | Informações auxiliares |
| **Ação** | `#F7B733` | Destaques para tarefas críticas |

Tipografia recomendada:

- **Títulos:** Poppins Bold/Medium
- **Corpo e labels:** DM Sans Regular/Medium
- Disponíveis via Google Fonts (pré-carregados nas versões HTML).

## Estrutura dos arquivos

```
planner_package/
├── README.md                # Este guia geral
├── printable/               # HTML + CSS para impressão ou exportação em PDF
├── sheets/                  # Modelos .csv para importar em Google Sheets/Excel
├── notion/                  # Template em Markdown para importação
└── guides/                  # Instruções adaptadas por perfil
```

> Após gerar PDFs ou duplicar as planilhas, personalize os textos com o nome do comprador antes de distribuir.

## Como usar

1. Leia o passo a passo em `guides/getting-started.md` para montar a rotina ideal conforme o perfil do cliente.
2. Utilize `printable/index.html` para gerar PDFs (configure a impressão conforme descrito no checklist).
3. Importe os `.csv` em Google Sheets ou Excel para criar as versões editáveis. Ajuste validações e formatações conforme necessário.
4. Importe `notion/template.md` no Notion para disponibilizar o hub digital.
5. Antes de liberar o pacote, valide os itens em `guides/delivery-checklist.md`.
