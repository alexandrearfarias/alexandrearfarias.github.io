---
title: Importar empenhos do SFP
date: 2025-03-24
categories: [SCP, Balancete]
tags: [balancete, tutoriais, scp]
permalink: /SCP/Balancetes/importar-empenhos
parent: Balancetes
grand_parent: SCP
---

## Integração entre SFP (Folha de Pagamento) e SCP (Contabilidade Pública)

### Introdução

Caso utilize o sistema de **Folha de Pagamento SFP 18H** da **Simples Informática**, é possível importar os dados da folha para a **confecção automática dos empenhos e liquidação da folha** no sistema de **Contabilidade Pública SCP 21H**, também da Simples Informática.

---

## Passo a Passo

### 1. [SCP] Configurar Parâmetros

No sistema **SCP (Contabilidade Pública)**, acesse:

**Menu:** Parâmetros  
Preencha o campo **Código On-line** com o código da sua empresa (fornecido pelo suporte da Simples Informática).

![Configuração de Parâmetros - SCP](/assets/img/scp/balancetes/scp-sfp1.png)

---

### 2. [SCP] Exportar Orçamento

No SCP, vá em:  
**Menu Orçamento → Importação de Orçamento/Saldos → 8. Exportar Orçamento para Integração com a Folha de Pagamento (Prefeitura)**

![Exportar Orçamento - SCP](/assets/img/scp/balancetes/scp-sfp2.png)

---

### 3. [SFP] Configurar Parâmetros

No **SFP (Folha de Pagamento)**, acesse os parâmetros do sistema e informe o **Código da Empresa**, **igual ao informado no SCP**.

![Configuração de Parâmetros - SFP](/assets/img/scp/balancetes/scp-sfp3.png)

---

### 4. [SFP] Importar Dados do Orçamento

**Menu:**  
Tabelas → Tabelas do SCP (Orçamento LOA) → **LOA - Unidades Orçamentárias**

![Importar LOA - SFP](/assets/img/scp/balancetes/scp-sfp4.png)

Escolha a opção: **5. Importar Unidades Orçamentárias do SCP**

![Importar Unidades Orçamentárias](/assets/img/scp/balancetes/scp-sfp5.png)

---

### 5. [SFP] Ajuste de Lotações

**Menu:** Tabelas → Lotações → 2. Alterar/Manutenção

![Ajuste de Lotações - SFP](/assets/img/scp/balancetes/scp-sfp6.png)

Preencha os campos:
- **Ficha**
- **Fonte**
- **Credor**

Essas informações devem estar de acordo com o orçamento do SCP.

---

### 6. [SFP] Ajustar Credores nas Verbas

**Menu:** Tabelas → Verbas/Eventos → 2. Alterar/Manutenção

![Ajustar Credores - Verbas SFP](/assets/img/scp/balancetes/scp-sfp7.png)

Informe os **códigos dos credores**, conforme importado do SCP.

---

### 7. [SFP] Conferência e Exportação da Folha

**Menu:** Relatórios → Folha de Pagamento Sintética para a Contabilidade

![Relatório Folha para Contabilidade](/assets/img/scp/balancetes/scp-sfp8.png)

Na primeira execução, escolha **"NÃO"** para a opção **"Exportar"**, apenas para conferência.

![Opção Exportar - NÃO](/assets/img/scp/balancetes/scp-sfp9.png)

Confira o PDF gerado com os dados da folha:

![PDF da Conferência](/assets/img/scp/balancetes/scp-sfp10.png)

Se os dados estiverem corretos, gere novamente o relatório escolhendo **"SIM"** para **"Exportar"**, para enviar os dados ao servidor online.

![PDF Conferência Final](/assets/img/scp/balancetes/scp-sfp11.png)

---

### 8. [SCP] Importar Empenhos da Folha

Retorne ao sistema SCP e acesse:

**Menu:** Balancetes → Empenhos da Despesa → **A. Importar Empenhos On-line (Folha de Pagamento)**

![Importar Empenhos SCP](/assets/img/scp/balancetes/scp-sfp12.png)

✅ Esse processo **finaliza a integração**, permitindo gerar os empenhos da folha no sistema contábil.

> **Importante:** Execute esse passo **somente após a finalização da Folha de Pagamento no SFP**.

[Voltar para a sessão principal.](/SCP)

[Voltar para a sessão de Balancetes.](/SCP/Balancetes)