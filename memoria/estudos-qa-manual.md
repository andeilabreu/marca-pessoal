# Estudos de QA Manual

## Origem

Conteúdo relevante extraído em 15 de setembro de 2026 do arquivo
`exportacao_conversas_disponiveis.md`, gerado a partir de conversas realizadas
fora deste repositório.

Somente os estudos relacionados a qualidade de software foram incorporados.
Assuntos sobre Ubuntu, câmera e jogos não fazem parte deste registro.

## Objetivo corrigido

O objetivo não será descrito como “aprender QA do zero”, pois Andeil já possui
experiência prática anterior com testes e diagnóstico de sistemas.

Objetivo adotado:

> Atualizar, organizar e formalizar os conhecimentos de Andeil em qualidade de
> software, começando por QA Manual.

## Conceitos estudados

- Bug.
- Caso de teste.
- Plano de testes.
- Severidade e prioridade.
- Resultado esperado.
- Resultado obtido.
- Pré-condições.
- Passos de execução.
- Status do teste.
- Teste positivo.
- Teste negativo.
- Teste de valores-limite.

## Exercício de tela de cadastro

O exercício utilizou uma tela fictícia com:

- nome;
- e-mail;
- senha;
- botão “Cadastrar”.

Situações avaliadas:

- envio de campos vazios;
- uso de e-mails inválidos;
- campos com conteúdo muito longo;
- senha inválida.

## Caso de teste — e-mail inválido

### Pré-condição

O usuário está na tela de cadastro.

### Passos

1. Informar um nome válido.
2. Informar um e-mail inválido.
3. Informar uma senha válida.
4. Selecionar o botão “Cadastrar”.

### Resultado esperado

O cadastro não deve ser concluído e o sistema deve informar que o e-mail é
inválido.

## Exercício de valores-limite

Foi utilizado um requisito fictício segundo o qual a senha deveria conter
exatamente cinco dígitos:

- quatro dígitos: inválido;
- cinco dígitos: válido;
- seis dígitos: inválido.

Esse exemplo serviu para estudar valores imediatamente abaixo, no limite e
imediatamente acima do valor permitido.

### Aviso de segurança

A senha de cinco dígitos pertence somente ao exercício. Ela não representa uma
recomendação para sistemas reais, pois seria uma regra de segurança fraca.

## Teste positivo e teste negativo

- Teste positivo: verifica uma entrada ou comportamento que deve ser aceito.
- Teste negativo: verifica uma entrada ou comportamento que deve ser rejeitado
  ou tratado pelo sistema.

## Severidade e prioridade

Foi estudado que:

- severidade representa o impacto do problema;
- prioridade representa a urgência ou a ordem de correção.

Um problema pode ter severidade baixa e prioridade alta quando, por exemplo,
afeta uma apresentação ou uma necessidade urgente de um cliente.

## Significados da sigla CT

A sigla precisa ser interpretada conforme o contexto:

- nos estudos atuais, **CT** significa **Caso de Teste**;
- nos relatos profissionais anteriores de Andeil, **CT** foi informado como
  **Centro de Testes**.

Nos documentos futuros, o termo completo deverá aparecer na primeira menção
para evitar confusão.

## Estado do aprendizado

### Já estudado

- estrutura básica de um caso de teste;
- teste de e-mail inválido;
- valores-limite;
- testes positivos e negativos;
- diferença entre severidade e prioridade.

### Próximos passos sugeridos

- praticar casos de teste com resultado obtido e status;
- criar exemplos com campos vazios e tamanhos máximos;
- estudar particionamento de equivalência;
- criar um relatório de bug baseado nos exercícios;
- organizar os exercícios como evidência documental no GitHub;
- continuar o roteiro em `planejamento/roteiro-de-estudos.md`.
