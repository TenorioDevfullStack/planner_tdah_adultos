# Planner TDAH — Hub

Use este arquivo para importar no Notion (Import > Markdown). Cada seção contém blocos e propriedades sugeridas.

---

## 📆 Painel Diário (Database)

- Tipo: tabela
- Propriedades sugeridas:
  - `Data` (Date) — obrigatório
  - `Foco do dia` (Text)
  - `Humor` (Select: 1, 2, 3, 4, 5)
  - `Top 3` (Multi-select)
  - `Status geral` (Select: Planejado, Em andamento, Concluído)
  - `Vitórias` (Text)

### Template de página diária

```
🌟 Top 3 prioridades
- [ ] 
- [ ] 
- [ ] 

⚡ Tarefas rápidas (<10 min)
- [ ] 
- [ ] 

⌛ Blocos de foco (25/50 min)
- 06:00 →
- 08:00 →
- 10:00 →
- 14:00 →
- 16:00 →

💙 Autocuidado & pausas
- 

✅ Vitórias do dia
- 
```

---

## 🗓 Planejamento Semanal

- Crie um board ou lista de semanas.
- Propriedades:
  - `Semana` (Date range)
  - `Objetivo-chave` (Text)
  - `Recompensa` (Text)
  - `Prioridades` (Relation com Painel Diário opcional)
  - `Revisão` (Rich text)

### Checklist semanal

```
- [ ] Revisar metas mensais
- [ ] Definir top 3 da semana
- [ ] Planejar rotina da manhã
- [ ] Planejar rotina da noite
- [ ] Delegar tarefas críticas
- [ ] Revisar compromissos fixos
```

---

## 🧠 Metas & Projetos

- Banco de dados tipo tabela com:
  - `Meta` (Title)
  - `Categoria` (Select: Profissional, Estudos, Pessoal, Saúde, Financeiro)
  - `Prazo` (Date)
  - `Status` (Select: Ideia, Planejando, Em progresso, Concluído)
  - `Motivação` (Text)
  - `Sprint atual` (Relation com Painel Semanal)

### Template de projeto

```
🎯 Resultado desejado:

🚀 Por quê isso importa:

🛠 Recursos necessários:
- 

🗓 Macrocronograma
| Entrega | Prazo | Responsável |
| --- | --- | --- |
| | | |
| | | |

✅ Próximos passos (até 7 dias)
- [ ] 
- [ ] 
- [ ] 
```

---

## 💰 Controle Financeiro

- Database tipo tabela
  - `Tipo` (Select: Receita, Despesa fixa, Despesa variável, Investimento, Reserva)
  - `Descrição` (Text)
  - `Data` (Date)
  - `Valor` (Number, formato moeda, BRL)
  - `Status` (Select: Previsto, Pago)
  - `Categoria` (Multi-select: Moradia, Saúde, Estudos, Ferramentas, Marketing, etc.)

### Visualizações
- **Mensal**: filtro por mês
- **Por categoria**: group by `Categoria`
- **Receitas x Despesas**: board com status

---

## 🔁 Rastreador de Hábitos

- Crie uma database `Hábitos`
  - `Hábito` (Title)
  - `Categoria` (Select: Saúde, Foco, Organização, Social)
  - `Meta semanal` (Number)
  - `Motivação` (Text)
  - `Link útil` (URL)
- Crie uma database `Check-ins`
  - `Data` (Date)
  - `Hábito` (Relation → Hábitos)
  - `Status` (Select: Feito, Parcial, Pulado)
  - `Comentário` (Text)
  - `Energia` (Select: Baixa, Média, Alta)

### Template de revisão semanal

```
✅ Melhor hábito da semana:

⚠️ Desafio encontrado:

🧩 Ajuste para próxima semana:

❤️ Como me recompenso?
```

---

## 📚 Trilhas por perfil

### Estudantes
- Bloco de foco: Pomodoro adaptado (45min + 15min pausa)
- Lembretes: trabalhos, provas, leituras
- Meta: 1 mini revisão por dia

### Empreendedores
- Revisão financeira rápida diária
- Sprint semanal de 3 objetivos
- Espaço para leads / follow-up

### Profissionais CLT
- Planejamento semanal alinhado às entregas fixas
- Diário com check-ins de reuniões
- Rastreador de energia pós-expediente

### Autônomos criativos
- Banco de ideias rápidas
- Agenda de produção x entrega
- Rotina de autocuidado para evitar burnout

---

## 📥 Caixa de Entrada

Bloco simples de `Toggle list` com `Adicionar tarefa`, `Referência` e `Delegar`. Revisar diariamente durante o planejamento.
