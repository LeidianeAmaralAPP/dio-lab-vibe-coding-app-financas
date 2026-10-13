# 💸 App My Money Pal ( organizador de Finanças) com Vibe Coding

PRD refinado no Copilot Web: 

# My  Money  Pal

Aplicativo de organização financeira pessoal desenvolvido utilizando Vibe Coding com Lovable.

O objetivo do projeto é permitir que usuários iniciantes organizem sua vida financeira através de uma experiência conversacional simples e intuitiva, eliminando a necessidade de planilhas complexas ou formulários extensos.

---

# Objetivo do Projeto

O My Money Pal foi criado para ajudar pessoas que desejam controlar seus gastos, acompanhar metas financeiras e compreender melhor sua situação financeira através de uma conversa natural com um assistente virtual.

A proposta é tornar a educação financeira mais acessível, simples e prática.

---

# Resumo da Aplicação

O sistema permite que o usuário registre receitas e despesas utilizando linguagem natural.

Exemplos:

```text
Gastei R$ 45 no almoço

Paguei R$ 120 de luz

Recebi R$ 3.000 de salário
```

A aplicação identifica automaticamente:

- Valor
- Tipo da transação
- Categoria
- Impacto no orçamento

Além disso, oferece:

- Dashboard Financeiro
- Controle de receitas e despesas
- Metas financeiras
- Resumo semanal, quinzenal e mensal
- Educação financeira
- Simulador de reserva de emergência
- Agente Financeiro Conversacional

---

# Funcionalidades Implementadas

## Chat Financeiro

Permite registrar gastos e receitas através de linguagem natural.

## Dashboard Financeiro

Permite acompanhar:

- Saldo disponível
- Receitas
- Despesas
- Gastos por categoria
- Indicadores financeiros

## Metas Financeiras

Possibilita criar e acompanhar metas como:

- Reserva de emergência
- Notebook
- Viagem
- Veículo

## Educação Financeira

Apresenta conteúdos educativos relacionados a:

- Reserva de emergência
- CDI
- Poupança
- Planejamento financeiro

## Simulador de Reserva de Emergência

Compara o rendimento entre:

- Poupança
- Aplicações atreladas ao CDI
- Bancos digitais

---

# Processo de Desenvolvimento

O projeto foi desenvolvido utilizando a abordagem de Vibe Coding.

Durante o desenvolvimento foram utilizados prompts iterativos para refinar continuamente a aplicação.

---

# Principais Interações com o Lovable

## Estrutura Inicial

```text
Crie um app de finanças pessoais com base no seguinte PRD (Product Requirements Document).
```

## Melhorias de Interface

```text
Coloque uma tela mais bonita e onde eu possa colocar minha renda de salário para quando for para a página de gastos eu saiba quanto gastei e quanto ainda tenho ou se já passei do meu limite.
```

## Dashboard Financeiro

```text
Entre Resumo e Metas coloque um Dashboard Financeiro onde a pessoa consiga ter um controle semanal e mensal dos gastos e também baixar relatórios em PDF.
```

## Sistema de Login

```text
Crie uma tela inicial de login onde a pessoa informe nome e e-mail.

Nas próximas entradas utilize apenas o e-mail cadastrado.

Envie link de acesso apenas no primeiro cadastro.
```

## Controle de Sessão

```text
Adicione um botão de sair para que o usuário possa retornar para a tela de login.
```

## Melhorias Visuais

```text
Utilize ícones para representar as categorias.

Moradia → Casa

Alimentação → Cesta de compras

Transporte → Carro
```

## Educação Financeira

```text
Crie uma tabela de conscientização para reserva de emergência comparando poupança e CDI.
```

---

# PRD Utilizado

O aplicativo foi desenvolvido a partir de um Product Requirements Document (PRD) refinado com auxílio do Microsoft Copilot.

O documento define:

- Problema
- Público-alvo
- Objetivos do produto
- Funcionalidades
- Critérios de sucesso
- Princípios de UX
- Acessibilidade
- Design Universal

O conteúdo completo do PRD encontra-se abaixo.

---

# Evidências do Processo

## Capturas de Tela

### Chat Financeiro

Inserir imagem.

### Dashboard Financeiro

Inserir imagem.

### Metas Financeiras

Inserir imagem.

### Educação Financeira

Inserir imagem.

---

# Reflexão Sobre o Processo

## O que funcionou bem?

- O uso do PRD ajudou a fornecer contexto para a IA.
- As funcionalidades principais foram geradas rapidamente.
- O fluxo conversacional ficou próximo do esperado.
- A navegação da aplicação evoluiu a cada iteração.

## O que não funcionou como esperado?

- Algumas funcionalidades precisaram ser refinadas com vários prompts.
- O primeiro layout gerado era simples e pouco intuitivo.
- Foi necessário ajustar componentes visuais manualmente.

## O que aprendi sobre conversar com IAs?

- Quanto mais detalhado o prompt, melhor o resultado.
- Um PRD estruturado reduz retrabalho.
- Dividir solicitações complexas em pequenas etapas gera respostas melhores.
- A IA produz melhores resultados quando recebe contexto sobre usuário, objetivo e experiência desejada.

---

# Aprendizados

Este projeto demonstrou na prática como a abordagem de Vibe Coding permite transformar uma ideia em um software funcional utilizando IA como parceira de desenvolvimento.

A principal lição foi compreender que escrever requisitos claros é tão importante quanto escrever código.

---

# Tecnologias Utilizadas

- Lovable
- Microsoft Copilot
- Vibe Coding
- Design Universal
- UX Conversacional

---
``
Interações com o Lovable:
> crie um app de finanças pessoais com base no seginte PRD ( Product Requiriments Documents)
> Corrigir erro
> coloque uma tela mais bonita e onde eu possa colocar minha renda de salario para quando for para a pagina de gastos eu saiba quanto gastei e quanto ainda tenho ou se ja passei do meu limite
> entre resumo e metas coloque um Dashboard Financeiro ( onde a pessoa consegue ter um controle tanto semanal, quanto mensal, onde a pessoa consegue ter uma visao clara dos seus gasto e ate baixar em pdf)
> crie uma tela inicial de login, onde a pessoa coloque o email e o nome para asseco e na segunda vez que ele entra ja entre somente com o emal cadastrado
> quando a pessoa ja tiver o cadastro nao precisa enviar um link de acesso, envie o link de acesso somente quando a pessoa for fazer o primeiro cadastro
> coloque um botao de sair para a pessoa poder voltar a tela de login
> nesta opçao coloque uma imagem, exemplo: em moradia coloque uma casinha, em alimentaçao coloque uma cesta de compra, em trasporte um carro
> chat nessa parte coloque a concientizaçoa de ter uma reserva de emergencia, chat estoou fazendo um site onde é um organizador financeiro crie para mim uma tabela de concientizaçao onde a pessoa saiba que se ela colocar uma reserva de emergencia no CDI ele rende melhor, exemplo: se a pessoa coloca 1000 reais no CDI da ital rende tantos por cento, em seis meses a pessoa terar tanto, no nubenk rende tanto no cdi e no mercado pago tanto e concientizado que rende mais que na polpança

Resultado final no Lavoble: https://app-my-money-pal.lovable.app/auth

<img width="1667" height="857" alt="image" src="https://github.com/user-attachments/assets/ece303a4-8488-4a14-a3d7-7a6442e05682" />
<img width="1622" height="861" alt="image" src="https://github.com/user-attachments/assets/b0751f41-64bb-4e48-a424-306e958f2ccc" />
<img width="1567" height="857" alt="image" src="https://github.com/user-attachments/assets/623e5373-a9bc-4ca3-899d-96494cd9210c" />
<img width="1402" height="847" alt="image" src="https://github.com/user-attachments/assets/9e44bb00-ef73-43f2-b6e1-3942d1342a9e" />
<img width="1276" height="855" alt="image" src="https://github.com/user-attachments/assets/a83aa9ec-ab8f-4ea0-b5a5-e2c5d4df45b6" />

# Organizador Financeiro Conversacional

Uma aplicação de organização financeira pessoal baseada em conversação, desenvolvida para simplificar o controle financeiro de usuários iniciantes.

O usuário pode registrar receitas e despesas utilizando linguagem natural, enquanto um Agente Financeiro inteligente interpreta as informações, classifica transações automaticamente e gera insights financeiros.

---

# Visão Geral

O objetivo da plataforma é transformar o gerenciamento financeiro em uma experiência simples e intuitiva.

Ao invés de preencher formulários complexos ou utilizar planilhas, o usuário conversa com o sistema da mesma forma que enviaria uma mensagem para um amigo.

Exemplos:

```text
Gastei R$ 45 no almoço

Paguei R$ 120 de luz

Recebi R$ 3.000 de salário
```

O sistema identifica automaticamente:

- Valor
- Tipo de movimentação
- Categoria
- Data da transação

---

# Principais Funcionalidades

## Registro Financeiro por Conversa

Permite registrar receitas e despesas utilizando linguagem natural.

### Exemplos

```text
Gastei R$ 50 no mercado

Paguei R$ 120 de internet

Recebi R$ 3.000 de salário
```

### Benefícios

- Sem formulários complexos
- Registro rápido
- Experiência mais natural
- Menor atrito para o usuário

---

## Classificação Automática

O sistema categoriza automaticamente as movimentações financeiras.

### Categorias

- Alimentação
- Mercado
- Transporte
- Moradia
- Saúde
- Educação
- Lazer
- Compras
- Outros

### Exemplo

```text
Usuário:
Paguei R$ 120 de luz

Sistema:
Despesa de R$ 120 registrada em Moradia
```

---

## Controle Financeiro em Tempo Real

A aplicação atualiza automaticamente os indicadores financeiros.

### Indicadores

#### Renda do Mês

Valor total recebido no período.

#### Já Gastei

Total das despesas registradas.

#### Ainda Tenho

Saldo disponível após os gastos.

### Exemplo

```text
Renda do mês:
R$ 3.000,00

Já gastei:
R$ 187,50

Ainda tenho:
R$ 2.812,50
```

---

## Indicador de Saúde Financeira

Avalia o comportamento financeiro do usuário.

### Exemplo

```text
Seus gastos estão dentro da renda

6% da renda utilizada
```

### Objetivo

Ajudar o usuário a compreender rapidamente sua situação financeira.

---

## Sugestões Inteligentes

O sistema oferece exemplos rápidos para acelerar o registro de movimentações.

### Exemplos

```text
Gastei 45 no almoço

Paguei 120 de luz

Recebi 3000 de salário

Uber 22,50
```

---

## Dashboard Financeiro

Área destinada à visualização consolidada das informações financeiras.

### Recursos

- Receitas
- Despesas
- Saldo disponível
- Gastos por categoria
- Evolução financeira
- Indicadores de desempenho

### Filtros Disponíveis

- Semanal
- Quinzenal
- Mensal

---

## Resumos Financeiros

Geração automática de análises financeiras.

### Resumo Semanal

```text
Você gastou R$ 350 nesta semana.
```

### Resumo Quinzenal

```text
Mercado representou 42% das suas despesas.
```

### Resumo Mensal

```text
Você economizou R$ 850 neste mês.
```

---

## Metas Financeiras

Permite criar e acompanhar objetivos financeiros.

### Exemplos de Metas

- Reserva de emergência
- Viagem
- Notebook
- Veículo
- Entrada de imóvel

### Informações Exibidas

- Valor alvo
- Valor acumulado
- Percentual concluído
- Previsão de conclusão

---

## Educação Financeira

Módulo educativo para auxiliar usuários iniciantes.

### Conteúdos

- O que é CDI
- O que é Reserva de Emergência
- Poupança vs CDI
- Juros Compostos
- Planejamento Financeiro
- Organização de Gastos

---

## Simulador de Reserva de Emergência

Ferramenta de conscientização financeira.

### Objetivo

Demonstrar o impacto de diferentes tipos de investimento para uma reserva de emergência.

### Comparações

- Poupança
- 100% do CDI
- 110% do CDI
- 115% do CDI

### Exemplo

```text
R$ 1.000 investidos

Poupança:
Valor estimado após período

100% do CDI:
Valor estimado após período

115% do CDI:
Valor estimado após período
```

---

## Agente Financeiro Inteligente

Assistente virtual responsável por orientar o usuário durante toda a jornada financeira.

### Responsabilidades

- Registrar movimentações
- Classificar transações
- Esclarecer dúvidas
- Explicar conceitos financeiros
- Identificar padrões de consumo
- Sugerir economia

### Exemplo

```text
Você gastou 20% mais com alimentação este mês em comparação ao mês anterior.
```

---

# Fluxo Principal

```text
Usuário acessa o aplicativo
        ↓
Informa sua renda
        ↓
Registra despesas pelo chat
        ↓
Sistema categoriza automaticamente
        ↓
Dashboard é atualizado
        ↓
Usuário acompanha metas
        ↓
Agente Financeiro gera insights
        ↓
Usuário aprende e melhora seus hábitos financeiros
```

---

# Diferenciais do Produto

- Conversa em linguagem natural
- Foco em iniciantes
- Baixa curva de aprendizado
- Educação financeira integrada
- Organização automática
- Dashboard simplificado
- Metas financeiras
- Simulador de reserva de emergência
- Experiência Mobile First
- Design Universal e acessibilidade

---

# Objetivo do Projeto

Tornar a educação financeira e o controle de gastos acessíveis para qualquer pessoa, através de uma experiência simples, conversacional e intuitiva.
```


 **reflexão sobre o processo**:
  # # # O que funcionou bem?
  O refinamento do PRD feito no copilot, ajudou muito pois os creditos do Lovable acabara com 03 interações.

  # # # O que não funcionou como o esperado?
  Esperava ter um resultado com menos creditos.

  # # # O que aprendeu sobre conversar com IAs?
  Percebi que criar com IA se parece muito mais com orientar um parceiro de trabalho do que apenas executar comandos.


## 💬 Conclusão
Desenvolver o My Money Pal foi uma experiência interessante para entender como a Inteligência Artificial pode atuar como parceira no processo de criação de software.
Ao longo do projeto, percebi que a qualidade dos resultados está diretamente ligada à qualidade das instruções fornecidas. Cada refinamento no PRD e nos prompts tornou a aplicação mais próxima da visão que eu tinha para o produto.
Mais do que construir um organizador financeiro, este projeto me mostrou que Vibe Coding não é apenas sobre gerar código com IA, mas sobre comunicar ideias de forma clara, estruturar requisitos e evoluir soluções através de conversas iterativas.
O resultado foi uma aplicação simples, acessível e focada em ajudar pessoas a desenvolverem uma relação mais consciente com suas finanças, transformando tarefas que normalmente seriam complexas em uma experiência mais natural e intuitiva.
