# Fluxo BPMN — Saldo+

Processo de gestão e operação dos projetos do **Programa Saldo+**, desde a inscrição de um novo parceiro até o envio semanal dos relatórios na plataforma Ludos Pro.

**Acesse o fluxo:** https://mariaclara2424.github.io/bpmnsaldo/

---

## Sobre

O Saldo+ é um programa de educação financeira gamificada para estudantes do ensino médio, desenvolvido pela Associação Hub Brasil (Impact Hub Brasil) na plataforma Ludos Pro.

Esta página documenta o processo operacional usado para colocar um parceiro na plataforma, acompanhar a execução e reportar os resultados. O conteúdo está organizado em três partes:

1. **Fluxo BPMN:** diagrama com raias por responsável, etapas, decisões e ciclos de repetição.
2. **Detalhamento das etapas:** o que fazer em cada etapa e quem executa.
3. **Matriz de Responsabilidades (RACI):** papel de cada agente em cada atividade.

## Etapas do processo

| Etapa | Atividade |
|---|---|
| 1 | Inscrição e formalização do parceiro |
| 2 | Criação ou duplicação do curso (novo ID para novo parceiro) |
| 3 | Criação das turmas e acessos de gestão |
| 4 | Configuração da experiência do parceiro (ranking, Roda de Apoio, boas-vindas e identidade visual) |
| 5 | Cadastro dos participantes via API e associação às turmas |
| 6 | Aprovação e liberação do curso |
| 7 | Envio dos acessos, live de kick-off e suporte durante a trilha |
| 8 | Monitoramento |
| 9 | Geração e preparação dos relatórios (HTML e lista de e-mails) |
| 10 | Envio e acompanhamento semanal |

**Fluxo resumido:** Inscrição → Formalização → Listagem → Duplicação ou criação do curso → Novo ID do curso → Turmas → Acessos dos gestores → Ranking / Roda de Apoio / Boas-vindas → Identidade visual → Cadastro dos participantes via API → Associação às turmas → Aprovação → Liberação → Envio dos logins → Live de kick-off → Suporte → Monitoramento → Relatório HTML → Envio semanal → Monitoramento contínuo

## Agentes envolvidos

| Agente | Papel |
|---|---|
| Gestão de Projetos | Formaliza o parceiro, aprova a configuração, conduz o kick-off e analisa os indicadores |
| Operações / TI | Configura a plataforma, cadastra participantes, presta suporte, monitora dados e gera relatórios |
| Parceiro / Gestor Escolar | Envia inscrição e listagem, valida informações da instituição |
| Professor | Aplica a trilha em sala e acompanha a turma |
| Participante | Acessa a plataforma e realiza a trilha |
| Ludos Pro | Suporte técnico da plataforma e da API |

## Estrutura do repositório

| Arquivo | Descrição |
|---|---|
| `index.html` | Página publicada no GitHub Pages com o fluxo, o detalhamento e a RACI |
| `README.md` | Este arquivo |

## Como atualizar

1. Edite ou substitua o arquivo `index.html` (o nome precisa ser exatamente esse).
2. Faça o commit na branch `main`.
3. Aguarde de 1 a 2 minutos e recarregue a página com Ctrl+F5.

O GitHub Pages está configurado em **Configurações → Páginas → Implantar a partir de um branch → `main` / `(root)`**.

---

Associação Hub Brasil — Programa Saldo+
