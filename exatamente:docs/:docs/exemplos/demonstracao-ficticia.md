# 🧪 Demonstração Prática com Dados Fictícios

Esta simulação demonstra como o assistente configurado no **Gemini** aplica suas 4 habilidades sequencialmente para ajudar um usuário fictício a sair de um objetivo vago até um plano revisável.

---

## Cenário Fictício
* **Usuário:** Lucas Almeida (Analista Administrativo, 28 anos).
* **Contexto:** Quer aprender SQL e Power BI para conseguir uma promoção interna na área de operações, mas tem uma rotina corrida.

---

## Etapa 1: Ativando a Habilidade 1 (Esclarecer o Objetivo)

> **Usuário:** "Quero aprender análise de dados para crescer na empresa onde trabalho."

> **Assistente (Gemini):**
> Vamos estruturar isso com clareza antes de montar seu cronograma.
>
> * **Fatos Confirmados:** Você já trabalha na empresa e quer desenvolver habilidades em análise de dados visando crescimento profissional interno.
> * **Hipóteses:** Presumo que o foco seja análise aplicada a negócios/operações (BI e bancos de dados), e não programação científica avançada.
>
> Para transformar isso em um plano executável, responda a 3 perguntas:
> 1. **Qual entrega prática** provaria esse conhecimento na sua empresa (ex.: automatizar um relatório atual ou criar um dashboard para sua área)?
> 2. **Em quanto tempo** (em semanas ou meses) você quer ter esse projeto pronto?
> 3. **Quantas horas reais por semana** você consegue reservar sem comprometer seu descanso?

---

## Etapa 2: Ativando a Habilidade 2 (Montar o Plano de Ação)

> **Usuário:** "1. Quero recriar o relatório mensal de indicadores da minha área no Power BI puxando dados via SQL. 2. Tenho 4 semanas. 3. Consigo 5 horas por semana (1h segunda, quarta e sexta à noite + 2h no sábado de manhã)."

> **Assistente (Gemini):**
> Perfeito! Aqui está sua **Meta SMART** e o **Plano de Ação em 4 Fases**:
>
> * **Meta SMART:** Construir e apresentar um dashboard funcional no Power BI conectado a consultas SQL para substituir o relatório mensal manual da área de operações em 4 semanas (20h totais de dedicação).
>
> | Fase | Entrega Principal (Milestone) | Tarefas-Chave | Prazo |
> | :--- | :--- | :--- | :--- |
> | **Fase 1: Preparação** | Ambiente pronto e base mapeada | Instalar Power BI Desktop e cliente SQL; mapear colunas do relatório atual | Semana 1 |
> | **Fase 2: Construção** | Consultas SQL e modelo de dados | Escrever queries de extração/filtro; conectar base ao Power BI e criar relacionamentos | Semana 2 |
> | **Fase 3: Validação** | Dashboard visual e métricas (DAX) | Criar KPIs principais, gráficos comparativos e validar números contra o relatório antigo | Semana 3 |
> | **Fase 4: Entrega** | Apresentação e documentação | Ajustar layout final, documentar regras de negócio e apresentar ao gestor | Semana 4 |

---

## Etapa 3: Ativando a Habilidade 3 (Encaixar na Rotina & Obstáculos)

> **Assistente (Gemini):**
> ### Encaixe na sua Rotina (5h/semana)
> * **Hábito-Âncora:** Iniciar o bloco às 20h00 logo após o jantar (dias úteis) e às 09h00 após o café (sábado).
> * **Segunda (20h–21h):** Estudo dirigido da técnica da semana.
> * **Quarta (20h–21h):** Aplicação prática direta no seu projeto.
> * **Sexta (20h–21h):** Testes, correção de erros e anotações.
> * **Sábado (09h–11h):** Bloco de avanço profundo (*Deep Work*) e revisão semanal.
>
> ### Matriz de Obstáculos & Plano B
> | Obstáculo Previsto | Gatilho de Alerta | Plano de Contingência (Plano B) |
> | :--- | :--- | :--- |
> | **Cansaço após o expediente** | Sentir dificuldade de concentração às 20h | Aplicar o *Modo Mínimo Viável*: estudar apenas 20 minutos de teoria leve e deixar a prática pesada para sábado. |
> | **Erro de conexão ou sintaxe SQL** | Ficar travado por mais de 25 minutos | Colar a mensagem de erro no assistente pedindo diagnóstico e seguir para outra tarefa visual do dashboard. |

---

## Etapa 4: Ativando a Habilidade 4 (Revisar o Progresso)

> **Usuário (Fim da Semana 2):** "Consegui fazer 3,5h das 5h planejadas porque tive hora extra na quarta. Escrevi as queries SQL, mas ainda não conectei no Power BI."

> **Assistente (Gemini):**
> ### Check-in da Semana 2
> * **Taxa de Execução:** 70% das horas realizadas (3,5h / 5h) | **Status:** 🟡 Atenção leve (sem comprometimento do prazo final).
> * **O que funcionou:** Você concluiu a parte mais crítica da semana (as queries SQL).
> * **Ajuste para a Semana 3:** Na segunda-feira (1h), faça apenas a conexão do SQL com o Power BI (tarefa pendente da Semana 2) e use quarta, sexta e sábado (4h) para montar os visuais e métricas da Fase 3. O prazo de 4 semanas segue mantido.
