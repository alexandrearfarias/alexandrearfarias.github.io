---
title: STMWEB - Criando um Documento Avulso.
date: 2025-03-31 08:59
categories: [STMWEB, Tutoriais]
tags: [tutoriais, stmweb, stm]
permalink: /STMWEB/cadastroDocumentoAvulso
parent: visaoStm
---

# Documento Avulso  
O **Documento Avulso** é um recurso auxiliar utilizado para realizar a cobrança de taxas e impostos que não foram incluídos durante a emissão de documentos principais ou que precisam ser cobrados em um momento posterior à sua criação.  

> Caso você ainda não tenha realizado as configurações iniciais do sistema, recomendamos a leitura da seção ["Página inicial do STM"](/STMWEB//STM/#tabelas), onde são apresentados os elementos essenciais para o funcionamento do sistema antes da geração de novos documentos.
{: .prompt-warning }

Para visualizar os documentos avulsos, acesse o menu **"Lançamentos"** e clique na aba **"Documento Avulso"**.  
Na listagem de documentos, estão disponíveis três tipos de ações para cada registro:  
1. **Editar** o documento avulso;  
2. **Gerar DAM** (Documento de Arrecadação Municipal);  
3. **Cancelar** o documento.  

![Listagem de Documentos Avulsos](/assets/img/stm/cadastro-avulso/avulso1.png)

## Adição de Documentos  
Para adicionar um novo documento, clique no botão "Novo", localizado no canto superior direito da listagem. Você será direcionado a um formulário para preenchimento dos dados necessários.  

![Formulário de Documento Avulso](/assets/img/stm/cadastro-avulso/avulso2.png)  

Como o Documento Avulso é uma estrutura auxiliar para geração de DAMs sem vínculo com outros documentos do sistema, o número de informações exigidas é reduzido. Os campos obrigatórios são:  
- Um campo para **seleção de contribuintes**.  
- Um campo para **seleção da Base Legal**.  
- Um campo para definir a **Base de Cálculo** para os impostos/taxas.  
- Um bloco para adição das receitas do documento.  

## Edição de Documentos  
A edição de um documento é limitada **apenas para documentos com o status "lançado"**. É possível abrir o formulário de edição em documentos emitidos e cancelados para título de informação, mas suas ações não serão salvas.  

![Botão de salvar travado para documentos com status diferentes de "lançado".](/assets/img/stm/cadastro-avulso/avulso3.png)  

Os campos **"Contribuinte"** e **"Base Cálculo"** são travados por padrão assim que o documento é inserido no sistema.  

## Geração de DAM  
A geração da DAM referente ao documento é feita apenas uma única vez, entretanto, você pode emitir essa DAM quantas vezes quiser que ela não será gerada repetidamente. O processo de montagem da DAM é automático e ao clicar no ícone de dólar na coluna de ações, uma nova aba será aberta com as 3 vias da DAM.  

![Botão Gerar DAM](/assets/img/stm/cadastro-avulso/avulso4.png)  
![Via do Contribuinte](/assets/img/stm/cadastro-avulso/avulso5.png)  

## Cancelar Documento  
Para cancelar um documento, basta clicar no botão de ação **"cancelar documento"**. Um pop-up será exibido com um campo para preencher o motivo do cancelamento.  

![Botão Cancelar Documento](/assets/img/stm/cadastro-avulso/avulso6.png)  
![Modal para cancelar documento avulso](/assets/img/stm/cadastro-avulso/avulso7.png)  

> O cancelamento de um documento também cancela as DAMs vinculadas a ele.
{: .prompt-info }

# Dúvidas  
Se precisar de ajuda, entre em contato com o suporte clicando **[aqui!](https://api.whatsapp.com/send?phone=5586981417162&text=Ol%C3%A1%20%5BNome%20e%20Munic%C3%ADpio%5D,%20preciso%20de%20ajuda%20com%20%5Bdescri%C3%A7%C3%A3o%20breve%20do%20problema%5D.%20Voc%C3%AAs%20poderiam%20me%20orientar%20sobre%20como%20resolver%20ou%20indicar%20o%20setor%20respons%C3%A1vel?)**  

[Voltar para a sessão principal.](/STMWEB/visaoStm) 
