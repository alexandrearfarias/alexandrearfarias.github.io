---
title: STMWEB - Criando uma Nota Fiscal Eletrônica.
date: 2025-03-19 14:30
categories: [STMWEB, Tutoriais]
tags: [tutoriais, stmweb, siat]
permalink: /STMWEB/cadastroNFsiat
parent: visaoSiat
---

> ⚠️ Este manual apresenta a visão de um prestador dentro do sistema. Se você está cadastrado como prefeitura (administrador), [acesse aqui](/STMWEB/visaoStm) o manual de cadastro correto.
{: .prompt-warning }

# Criando Nota Fiscal

Para iniciar um novo registro, acesse a lista de notas fiscais e clique em **Novo**.

![Caminho para lançar notas fiscais](/assets/img/stm/cadastro-nf-siat/nf-siat1.png)

O formulário é composto por três abas que devem ser preenchidas da esquerda para a direita:
1. Cadastro da Nota;
2. Itens de Serviço;
3. Informações Adicionais.

![Tela inicial do formulário de cadastro](/assets/img/stm/cadastro-nf-siat/nf-siat2.png)

## Cadastro da Nota

O cadastro da nota fiscal é dividido em cinco blocos de informações:
- **Identificação**;
- **Prestador**;
- **Tomador**;
- **Serviço**;
- **Retenção de ISSQN**.

### Bloco de Identificação

Este bloco apresenta informações automáticas de identificação da nota, como número de série, número da nota, código automático e datas. Não há campos para preenchimento manual.

![Bloco de Identificação](/assets/img/stm/cadastro-nf-siat/nf-siat3.png)

### Bloco do Prestador

Contém os dados do prestador (usuário logado) e um seletor para a conta bancária vinculada. O campo de seleção do prestador é desabilitado, pois não é permitido emitir notas para terceiros.

![Bloco do Prestador](/assets/img/stm/cadastro-nf-siat/nf-siat4.png)

### Bloco do Tomador

Permite selecionar o tomador de serviço, carregando automaticamente suas informações no formulário.

![Bloco do Tomador](/assets/img/stm/cadastro-nf-siat/nf-siat5.png)

### Bloco de Serviço

Este bloco contém:
- Seletor do serviço referente à nota;
- Campo para inserção da alíquota.

O campo de alíquota personalizada só está disponível para prestadores optantes pelo Simples Nacional.

![Bloco de Serviço](/assets/img/stm/cadastro-nf-siat/nf-siat6.png)

### Bloco de Retenção de ISSQN

Permite indicar se o valor do ISS foi retido em outro município. Inclui:
- Checkbox para confirmação da retenção em outro município. **(Importante marcar!)**
- Seletor para escolher o município de retenção;
- Campo para informar a alíquota aplicada.

![Bloco de Retenção de ISSQN](/assets/img/stm/cadastro-nf-siat/nf-siat7.png)

### Cadastro de Campos Auxiliares

Se não houver uma **conta bancária** cadastrada, acesse **Tabelas > Conta Bancária** e registre suas informações.

![Cadastro de Conta Bancária](/assets/img/stm/cadastro-nf-siat/nf-siat8.png) ![Detalhes da Conta Bancária](/assets/img/stm/cadastro-nf-siat/nf-siat9.png)

---

Se não houver um **tomador** cadastrado, acesse **Tabelas > Tomadores de Serviço** para registrar um novo tomador.

![Navegação para Tomadores](/assets/img/stm/cadastro-nf-siat/nf-siat10.png)

![Cadastro de Tomador - Parte 1](/assets/img/stm/cadastro-nf-siat/nf-siat11.png) ![Cadastro de Tomador - Parte 2](/assets/img/stm/cadastro-nf-siat/nf-siat12.png)

### ⚠️ ATENÇÃO ⚠️

Após preencher o **Cadastro da Nota**, clique em **Incluir** para avançar e visualizar corretamente as demais seções do formulário. Esse processo de incluir e continuar será frequente durante a utilização do sistema.

![Prosseguir para as demais seções](/assets/img/stm/cadastro-nf-siat/nf-siat13.png)

## Itens de Serviço

A aba de Itens de Serviço contém cinco blocos:
- **Listagem de itens/serviços**;
- **Tributos Federais**;
- **Construção Civil**;
- **Outras Informações**;
- **Detalhes de Cálculo**.

### Tributos Federais

Permite declarar retenções como PIS, COFINS, INSS e IR, que não são recolhidas diretamente pela prefeitura.

![Bloco de Tributos Federais](/assets/img/stm/cadastro-nf-siat/nf-siat14.png)

### Construção Civil

Bloco específico para notas fiscais relacionadas à construção civil, permitindo informar o artigo e o código da obra.

![Bloco de Construção Civil](/assets/img/stm/cadastro-nf-siat/nf-siat15.png)

### Outras Informações

Campo livre para inserir detalhes adicionais relevantes sobre os itens da nota.

![Bloco de Outras Informações](/assets/img/stm/cadastro-nf-siat/nf-siat16.png)

### Detalhes de Cálculo

Exibe os totais dos itens, impostos e deduções. Para atualizar os valores, clique em **Recarregar** no topo da página.

![Detalhes de Cálculo](/assets/img/stm/cadastro-nf-siat/nf-siat17.png)

### Listagem de Itens  

A listagem exibe todas as informações sobre o item e, ao final, o valor total resultante do somatório dos mesmos. O usuário tem liberdade para adicionar, remover e editar registros enquanto a nota ainda não tiver sido emitida.  

- Para adicionar um novo item, clique no botão **Novo** à direita do formulário;  
- Para editar um item, clique no ícone de lápis ao lado do registro;  
- Para remover um item, clique no ícone de **X** ao lado do registro.  

![Listagem de Itens](/assets/img/stm/cadastro-nf-siat/nf-siat18.png)

Dentro do formulário de itens da nota fiscal, existem seis campos descritivos que devem ser preenchidos pelo usuário.  

- **Descrição do item**;
- **Valor unitário do item**;
- **Quantidade referente ao item**;
- **Unidade de medida do item** (UND, metro, gramas...);
- **Descontos no valor final do item** (quantidade × valor unitário);
- **Outras reduções no valor final do item**.

Os demais campos são apenas informativos.

![Formulário de Item](/assets/img/stm/cadastro-nf-siat/nf-siat19.png)

## Informações Adicionais

A última página tem como objetivo complementar as informações. Nela, estão disponíveis campos referentes a dados de cartório, observações sobre a nota, informações de intermediação (caso existam), detalhes sobre o cálculo das receitas e o histórico da nota, indicando sua origem ou relação com outro documento ou processo anterior.

![Informações Adicionais](/assets/img/stm/cadastro-nf-siat/nf-siat20.png)

> O campo **Houve Intermediação** controla a exibição dos campos para preenchimento dos dados do intermediário da Nota Fiscal. Por padrão, esse campo vem desmarcado.
{: .prompt-info }

[Voltar para a sessão anterior](/STMWEB/visaoSiat)
