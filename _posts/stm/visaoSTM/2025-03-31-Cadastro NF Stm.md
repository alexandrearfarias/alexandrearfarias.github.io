---
title: STMWEB - Criando um Nota Fiscal de Serviço.
date: 2025-03-31 09:36
categories: [STMWEB, Tutoriais]
tags: [tutoriais, stmweb, stm]
permalink: /STMWEB/cadastroNFstm
parent: visaoStm
---

# Nota Fiscal

Para lançar notas fiscais no sistema, acesse o menu **"Lançamentos"** e selecione a opção **"Nota Fiscal de Serviço"**.

![Aba de Notas Fiscais no menu](/assets/img/stm/cadastro-nf-stm/nf-stm1.png)

Em seguida, clique em **"Novo"**, no canto superior direito da listagem, para iniciar o cadastro de uma nova nota.

![Botão para adicionar Notas Fiscais](/assets/img/stm/cadastro-nf-stm/nf-stm2.png)

Você será direcionado ao **formulário de inserção**, composto por duas páginas:
- **Página 1**: Informações descritivas da nota;
- **Página 2**: Itens e impostos vinculados à nota.

![Formulário de Nota Fiscal](/assets/img/stm/cadastro-nf-stm/nf-stm3.png)

> Caso ainda não tenha realizado as configurações iniciais do sistema, recomendamos a leitura da seção **["Página inicial do STM"](/STMWEB/visaoStm#tabelas)**, que apresenta os elementos fundamentais para o funcionamento adequado do sistema antes da geração de documentos fiscais.
{: .prompt-warning }

## Cadastro da Nota

Durante o preenchimento do formulário, serão solicitadas as seguintes informações:

### Informações de Identificação da Nota Fiscal

- Número,
- Série,
- Código da Nota,
- Data de Lançamento.
- Informações do Prestador.
- Informações do Tomador.
- Informações de Serviço.

> Todas as informações para identificação da nota são definidas indiretamente pelo sistema, através dos parâmetros.
{: .prompt-info }

### Informações do Prestador

Nesta seção, selecione o contribuinte responsável pela nota, por meio de um campo de busca. Serão exibidos também o **CPF/CNPJ** e a indicação se o prestador **opta pelo Simples Nacional**.

![Prestador de Serviço](/assets/img/stm/cadastro-nf-stm/nf-stm4.png)

### Informações do Tomador

Aqui você deve indicar quem está recebendo o serviço. Assim como no prestador, utilize o campo de seleção para escolher um tomador previamente cadastrado no sistema.

Existem dois tipos de tomadores:
- Tomador Padrão
- Tomador Estrangeiro

![Bloco de Tomador de Serviço](/assets/img/stm/cadastro-nf-stm/nf-stm5.png)

Ambos os tipos devem ser previamente cadastrados na **"Tabela de Tomadores"**, localizada no menu **"Tabelas"**. O cadastro é simples e requer apenas as informações essenciais de cada tomador.

![Tomadores de Serviço no Menu](/assets/img/stm/cadastro-nf-stm/nf-stm6.png)

Tomadores de Serviço e Tomadores Estrangeiros são cadastros simples com informações pontuais a serem preenchidas.

#### Exemplos de Tomadores de Serviço

![Tomadores de Serviço](/assets/img/stm/cadastro-nf-stm/nf-stm7A.png)  
![Tomadores de Serviço](/assets/img/stm/cadastro-nf-stm/nf-stm7B.png)  
![Tomadores de Serviço](/assets/img/stm/cadastro-nf-stm/nf-stm7C.png)  

#### Exemplos de Tomadores Estrangeiros

![Tomadores Estrangeiros](/assets/img/stm/cadastro-nf-stm/nf-stm8A.png)  
![Tomadores Estrangeiros](/assets/img/stm/cadastro-nf-stm/nf-stm8B.png)  

### Informações de Serviço

No último bloco da aba de cadastro, informe os dados relacionados aos serviços prestados, como:
- Serviço utilizado para cálculo de **ISSQN** e **IR**;
- Campo descritivo para o histórico da nota.

![Bloco de Informações para Serviço](/assets/img/stm/cadastro-nf-stm/nf-stm9.png)

## Itens do Serviço

A segunda página do formulário está dividida em dois blocos:
- Itens da Nota Fiscal
- Cálculo e detalhamento de impostos

A inclusão de itens é simples e requer o preenchimento dos seguintes campos:
- Descrição clara do item;
- **Unidade de medida (UND)**;
- **Quantidade de itens** conforme a unidade;
- **Valor unitário** do item;
- **Desconto aplicado** (deixe em branco caso não haja desconto).

Após preencher os campos, adicione o item à nota. Os registros são armazenados temporariamente até a finalização do processo.

![Itens da Nota Fiscal](/assets/img/stm/cadastro-nf-stm/nf-stm10.png)

> Para visualizar o detalhamento do cálculo dos impostos, é necessário salvar a nota. O sistema atualizará os campos automaticamente com base nos itens cadastrados.
{: .prompt-info }

Não se preocupe com erros na adição dos itens — os cálculos são reprocessados sempre que a nota é salva.

![Detalhamento de cálculo](/assets/img/stm/cadastro-nf-stm/nf-stm11.png)

# Observações

- Após a inclusão da nota fiscal, **não será mais possível alterar os serviços vinculados ao ISS**.

![Campo de Serviço ISS bloqueado após a inclusão](/assets/img/stm/cadastro-nf-stm/nf-stm12.png)

- O botão **"Apagar Serviços"** exclui **todos os registros da tabela de itens**. Tenha cuidado ao atualizar a lista de itens ou ao tentar remover um registro.

- Qualquer alteração na lista de itens ou exclusão de registros deve ser feita com cautela.

![Cuidado ao remover itens da nota!](/assets/img/stm/cadastro-nf-stm/nf-stm13.png)

# Dúvidas

Se precisar de ajuda, entre em contato com o suporte clicando **<a src="https://api.whatsapp.com/send?phone=5586981417162&text=Ol%C3%A1%20%5BNome%20e%20Munic%C3%ADpio%5D,%20preciso%20de%20ajuda%20com%20%5Bdescri%C3%A7%C3%A3o%20breve%20do%20problema%5D.%20Voc%C3%AAs%20poderiam%20me%20orientar%20sobre%20como%20resolver%20ou%20indicar%20o%20setor%20respons%C3%A1vel?%20Agrade%C3%A7o%20desde%20j%C3%A1%20pela%20aten%C3%A7%C3%A3o!" target="_blank">aqui!</a>**

[**Voltar para a sessão principal.**](/STMWEB/visaoStm)
