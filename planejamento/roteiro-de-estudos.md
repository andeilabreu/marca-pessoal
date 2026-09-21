# Roteiro de estudos — primeiros 30 dias

## Objetivo

Preparar Andeil para iniciar candidaturas em qualidade de software enquanto
atualiza os conhecimentos e transforma sua experiência anterior em evidências
profissionais.

Este roteiro:

- utiliza apenas materiais gratuitos;
- possui 18 horas fixas por semana;
- reserva duas horas opcionais para revisão;
- prioriza testes manuais antes de automação;
- não exige programação no início;
- não adicionará código a este repositório.

## Formato de cada bloco de três horas

1. **45 minutos — aprender:** leitura ou aula.
2. **15 minutos — pausa.**
3. **60 minutos — praticar:** executar uma atividade.
4. **15 minutos — pausa.**
5. **45 minutos — registrar:** escrever o que aprendeu e as dúvidas.

O registro é obrigatório. Assistir ou ler sem praticar não conta como conclusão
da atividade.

## Materiais gratuitos principais

- [Syllabus CTFL 4.0 em português — BSTQB](https://bstqb.qa/files/syllabus_ctfl_4.0br.pdf):
  referência de fundamentos e vocabulário. Não é necessário estudar para a
  certificação neste primeiro mês.
- [Treinamento oficial gratuito de Jira — Atlassian](https://enable.atlassian.com/student/path/815443-jira-fundamentals):
  conceitos básicos, navegação e acompanhamento de trabalho.
- [GitHub Skills](https://skills.github.com/):
  atividades práticas oficiais de GitHub.
- [Início rápido do Postman](https://learning.postman.com/docs/getting-started/first-steps/overview):
  primeiro contato com requisições e testes de API.

Se algum material deixar de ser gratuito ou ficar indisponível, ele deverá ser
substituído antes do início da atividade.

## Progresso incorporado em 15 de setembro de 2026

Andeil deu continuidade aos estudos fora deste repositório e já teve contato
com:

- estrutura de casos de teste;
- testes positivos e negativos;
- teste de valores-limite;
- diferença entre severidade e prioridade;
- exercícios de validação de cadastro, e-mail e senha.

Esses assuntos não serão considerados dominados apenas por terem sido
estudados. Na primeira semana, eles deverão ser revisados rapidamente e usados
em exercícios práticos. O registro detalhado está em
`memoria/estudos-qa-manual.md`.

## Semana 1 — Fundamentos e experiência anterior

### Segunda-feira — O que é qualidade de software

**Aprender**

- Ler a introdução e os fundamentos iniciais do syllabus CTFL.
- Rever a diferença entre qualidade, teste, erro, defeito e falha.

**Praticar**

- Relacionar cada conceito a uma experiência real de Andeil.
- Usar os casos do Sistema Aula, Infolab, PaperCut e Chart Sistemas.

**Registrar**

- Criar um glossário com os termos aprendidos.
- Anotar palavras que ainda não ficaram claras.

**Entrega:** glossário inicial de qualidade de software.

### Terça-feira — Cenários e casos de teste

**Aprender**

- Entender cenário de teste, caso de teste, pré-condição, passos, resultado
  esperado e resultado obtido.

**Praticar**

- Escolher uma funcionalidade simples de uma aplicação pública de demonstração.
- Criar cinco casos de teste.
- Incluir situações de sucesso e de erro.

**Registrar**

- Revisar se outra pessoa conseguiria executar os testes usando somente o
  documento.

**Entrega:** cinco casos de teste manuais.

### Quarta-feira — Relatório de bug

**Aprender**

- Estudar os campos de um registro de defeito:
  - título;
  - ambiente;
  - pré-condição;
  - passos para reproduzir;
  - resultado esperado;
  - resultado obtido;
  - evidência;
  - severidade;
  - prioridade.

**Praticar**

- Escrever dois exemplos de bugs.
- Um exemplo pode ser baseado em experiência antiga, sem dados confidenciais.
- O outro deve vir da aplicação pública de demonstração.

**Registrar**

- Conferir se os passos são claros e reproduzíveis.

**Entrega:** dois relatórios de bugs.

### Quinta-feira — Reteste e regressão

**Aprender**

- Rever:
  - reteste: confirmar que o defeito foi corrigido;
  - regressão: verificar se a mudança não prejudicou outras funções.

**Praticar**

- Criar uma lista de reteste para um dos bugs.
- Criar uma lista pequena de funcionalidades relacionadas para regressão.

**Registrar**

- Explicar com suas palavras a diferença entre reteste e regressão.

**Entrega:** lista de reteste e regressão.

### Sexta-feira — Currículo e posicionamento

**Praticar**

- Revisar `curriculo/README.md`.
- Identificar informações incorretas, incompletas ou repetidas.
- Separar as experiências mais relevantes para qualidade de software.

**Registrar**

- Anotar todas as dúvidas antes de alterar informações.

**Entrega:** lista de correções necessárias no currículo.

### Sábado — Revisão e primeira busca por vagas

**Praticar**

- Revisar as entregas da semana.
- Pesquisar vagas de testes manuais e qualidade de software.
- Registrar, sem se candidatar automaticamente:
  - título da vaga;
  - empresa;
  - modalidade;
  - requisitos;
  - ferramentas solicitadas;
  - pontos que Andeil já atende;
  - pontos que precisa estudar.

**Entrega:** levantamento inicial de vagas e requisitos.

## Semana 2 — Jira, GitHub e portfólio

### Segunda-feira — Primeiros passos no Jira

**Aprender**

- Iniciar o treinamento oficial gratuito da Atlassian.
- Conhecer item de trabalho, responsável, status, prioridade e comentários.

**Praticar**

- Reescrever um dos relatórios de bug usando a estrutura apresentada no curso.

**Entrega:** um bug estruturado no padrão estudado.

### Terça-feira — Fluxo de um bug

**Aprender**

- Entender um fluxo simples:
  - aberto;
  - em análise;
  - em desenvolvimento;
  - pronto para teste;
  - aprovado ou reaberto;
  - concluído.

**Praticar**

- Desenhar em Markdown o fluxo de um bug.
- Simular a passagem de um defeito por cada etapa.

**Entrega:** fluxo documentado de defeitos.

### Quarta-feira — Git e GitHub

**Aprender**

- Realizar uma atividade introdutória no GitHub Skills.
- Rever repositório, arquivo, alteração, commit e histórico.

**Praticar**

- Atualizar um documento de estudo neste repositório.
- Registrar a alteração seguindo a orientação recebida, sem criar código.

**Entrega:** atualização documentada e compreendida.

### Quinta-feira — Portfólio de QA

**Praticar**

- Organizar no GitHub:
  - glossário;
  - casos de teste;
  - relatórios de bugs;
  - reteste;
  - regressão.

**Cuidados**

- Não usar nomes, dados ou telas confidenciais de clientes.
- Informar quando um caso for simulado.
- Não apresentar estudo como experiência profissional.

**Entrega:** primeira versão do portfólio documental.

### Sexta-feira — LinkedIn

**Praticar**

- Atualizar nome profissional e título.
- Preparar a seção “Sobre”.
- Revisar as experiências mais relevantes.
- Não publicar habilidades ainda não praticadas.

**Entrega:** rascunho do novo perfil.

### Sábado — Candidaturas iniciais

**Praticar**

- Selecionar vagas compatíveis com testes manuais.
- Comparar cada vaga com o currículo.
- Adaptar palavras-chave sem inventar experiências.
- Enviar candidaturas somente após revisar currículo e perfil.

**Entrega:** primeiras candidaturas registradas.

## Semana 3 — APIs e Postman

### Segunda-feira — O que é uma API

**Aprender**

- Entender API como uma forma de comunicação entre sistemas.
- Relacionar o conceito à experiência com Infolab e equipamentos laboratoriais.
- Conhecer requisição, resposta e código de status.

**Entrega:** explicação de API com palavras próprias.

### Terça-feira — Primeiro uso do Postman

**Aprender e praticar**

- Seguir o início rápido oficial do Postman.
- Enviar uma primeira requisição de exemplo.
- Observar endereço, método, resposta e código de status.

**Entrega:** relatório simples da primeira requisição.

### Quarta-feira — Cenários de API

**Praticar**

- Criar cenários com:
  - dados corretos;
  - campo ausente;
  - valor inválido;
  - recurso inexistente.

**Entrega:** quatro cenários manuais de API.

### Quinta-feira — Validação de respostas

**Aprender**

- Observar status, tempo de resposta e conteúdo retornado.
- Conhecer os códigos 200, 201, 400, 401, 403, 404 e 500.

**Praticar**

- Registrar resultado esperado e obtido para os cenários.

**Entrega:** relatório de execução dos cenários.

### Sexta-feira — Currículo e GitHub

**Praticar**

- Adicionar ao portfólio somente o que foi realmente realizado.
- Atualizar currículo apenas se já houver prática suficiente para mencionar
  “noções de Postman e testes de API”.

**Entrega:** portfólio revisado.

### Sábado — Vagas e revisão

- Continuar candidaturas.
- Comparar requisitos das vagas com o aprendizado.
- Registrar dúvidas e dificuldades.
- Revisar os assuntos da semana.

**Entrega:** lista atualizada de lacunas.

## Semana 4 — Consolidação e introdução à automação

### Segunda-feira — Técnicas de teste

- Revisar particionamento de equivalência e valores-limite em nível
  introdutório.
- Criar exemplos simples para campos numéricos e formulários.

**Entrega:** casos de teste usando as duas técnicas.

### Terça-feira — Testes não funcionais

- Conhecer, sem aprofundamento:
  - usabilidade;
  - acessibilidade;
  - segurança;
  - desempenho;
  - compatibilidade.
- Relacionar esses temas às experiências anteriores.

**Entrega:** mapa dos tipos de teste já vivenciados.

### Quarta-feira — Automação

- Entender quando automatizar e quando manter testes manuais.
- Conhecer a finalidade de Selenium e Cypress.
- Não iniciar dois cursos de automação ao mesmo tempo.

**Entrega:** comparação introdutória entre teste manual e automatizado.

### Quinta-feira — Projeto final do mês

- Escolher uma funcionalidade.
- Criar cenários e casos de teste.
- Executar os casos.
- Registrar bugs.
- Definir severidade e prioridade.
- Preparar reteste e regressão.

**Entrega:** estudo de caso completo.

### Sexta-feira — Currículo, LinkedIn e apresentação

- Revisar currículo e LinkedIn.
- Preparar uma apresentação profissional de até um minuto.
- Explicar a transição para qualidade de software sem apagar a experiência
  anterior.

**Entrega:** apresentação profissional escrita.

### Sábado — Avaliação dos 30 dias

- Registrar o que foi concluído.
- Registrar o que não foi concluído e por quê.
- Avaliar candidaturas e respostas.
- Identificar as ferramentas mais pedidas nas vagas.
- Definir o próximo ciclo de estudos.

**Entrega:** relatório mensal de progresso.

## Uso das duas horas opcionais

As duas horas opcionais podem ser usadas para:

- rever um assunto difícil;
- terminar uma entrega atrasada;
- melhorar currículo ou LinkedIn;
- pesquisar vagas;
- descansar quando a semana estiver pesada.

Não devem ser usadas para iniciar assuntos novos sem concluir os anteriores.

## Critérios para considerar o mês concluído

- [ ] Currículo revisado.
- [ ] LinkedIn reconstruído.
- [ ] Glossário básico criado.
- [ ] Pelo menos cinco casos de teste documentados.
- [ ] Pelo menos dois relatórios de bugs documentados.
- [ ] Um exemplo de reteste e regressão.
- [ ] Treinamento inicial de Jira realizado.
- [ ] Atividade introdutória de GitHub realizada.
- [ ] Primeiro contato prático com Postman.
- [ ] Portfólio documental organizado.
- [ ] Candidaturas iniciadas.
- [ ] Relatório de progresso preenchido.

## Observação

Este roteiro não promete contratação em 30 dias. Ele organiza ações que
aumentam a preparação e permitem iniciar candidaturas com evidências reais,
sem inventar domínio de ferramentas.
