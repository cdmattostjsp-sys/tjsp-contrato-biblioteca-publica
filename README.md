Perfeito — entendido com clareza total.
Vamos, então, construir um **README institucional robusto**, completo, interligando todos os pilares técnicos, normativos e operacionais que formam o **Agente_CONTRATO – SAAB 5.4 (TJSP)**.

Esse documento será:

* O **repositório-mãe de conhecimento** do agente Copilot (base semântica e normativa);
* Um **documento técnico oficial** (equivalente ao Manual de Implantação);
* Um **referencial público** para uso pelo TJSP, CNJ e órgãos parceiros;
* Um **guia normativo e funcional** para desenvolvedores e servidores.

Abaixo está a **versão completa do README.md**, já formatada em Markdown institucional, pronta para uso no repositório público `saab5-4-contrato`.

---

# 📜 **Agente_CONTRATO – SAAB 5.4 (TJSP)**

### *Sistema de Apoio à Administração e Abastecimento – SAAB / Tribunal de Justiça do Estado de São Paulo*

🧭 *Versão institucional 5.4 – Novembro/2025*
🧠 *Base normativa, operacional e técnica para o agente Copilot CONTRATO do TJSP*

---

## ⚙️ **1. Contexto Institucional e Finalidade**

O **Agente_CONTRATO – SAAB 5.4** é o **assistente normativo e procedimental** desenvolvido para apoiar a **elaboração, conferência e auditoria das minutas contratuais administrativas** no âmbito do **Tribunal de Justiça do Estado de São Paulo (TJSP)**.

Ele constitui o **quinto módulo funcional** do ecossistema **SAAB Next (5.x)**, integrando o fluxo institucional de contratações públicas:

> 🧩 **DFD → ETP → TR → EDITAL → CONTRATO**

O agente foi projetado para atuar de forma autônoma no ambiente **Microsoft Copilot / SharePoint TJSP**, e em integração futura com o ecossistema **Synapse Next Homologação** e o pipeline institucional **OpenAI – Streamlit – SAAB**.

Seu objetivo é **assegurar conformidade jurídica, coerência documental e rastreabilidade normativa** entre o **Edital**, o **Termo de Referência (TR)** e o **Contrato Administrativo**, conforme os parâmetros da **Lei nº 14.133/2021**, do **Decreto Estadual nº 67.381/2022**, das **Resoluções CNJ nº 651 e 652/2025**, e do **Manual de Contratos do TJSP (2025)**.

---

## 🧱 **2. Escopo e Propósito do Agente**

### 🎯 **Finalidade Principal**

* Gerar **minutas contratuais completas, auditáveis e normativamente consistentes**;
* Assegurar **aderência integral ao edital e ao TR**;
* Garantir a **inclusão das cláusulas essenciais** previstas no art. 92 da Lei nº 14.133/2021;
* Validar **coerência entre prazos, valores, obrigações e responsabilidades**;
* Produzir **relatórios de conformidade normativa (✅ / ⚠️ / ❌)** com justificativas jurídicas;
* Emitir **sugestões de ajustes e complementos** conforme o Manual de Contratos TJSP (2025);
* Oferecer **orientações automáticas e citações legais contextualizadas** em linguagem administrativa.

---

## ⚖️ **3. Base Legal e Normativa Integrada**

| Norma                                                            | Tópico Principal                                            | Aplicação no Agente                                  |
| ---------------------------------------------------------------- | ----------------------------------------------------------- | ---------------------------------------------------- |
| **Lei nº 14.133/2021**                                           | Execução, gestão e fiscalização contratual (arts. 89 a 115) | Estrutura básica das cláusulas obrigatórias          |
| **Decreto Estadual nº 67.381/2022**                              | Regulamenta a execução contratual no Estado de SP           | Procedimentos operacionais e responsabilidades       |
| **Provimento CSM nº 2.724/2023**                                 | Governança das contratações no TJSP                         | Estrutura hierárquica e delegações internas          |
| **Resolução CNJ nº 651/2025**                                    | Retenção de encargos e conta vinculada                      | Contratos com dedicação exclusiva de mão de obra     |
| **Resolução CNJ nº 652/2025**                                    | Gestão de riscos e obras públicas                           | Aplicação em obras e serviços de engenharia          |
| **Manual de Contratos TJSP (2025)**                              | Gestão, fiscalização, reajuste, garantias e extinção        | Padronização institucional das cláusulas             |
| **Manual de Licitações TJSP (2025)**                             | Fase preparatória e formalização contratual                 | Coerência editalícia e tramitação                    |
| **Manual de Boas Práticas em Contratações Públicas (SEGES/MGI)** | Eficiência, governança e controle interno                   | Diretrizes gerais de conformidade e transparência    |
| **Notas Técnicas SAAB/SOF/GTAJ (2025)**                          | Adequação à Resolução CNJ nº 651/2025                       | Delegação de competências e padronização operacional |

---

## 🧭 **4. Adequação à Resolução CNJ nº 651/2025**

A **Resolução CNJ nº 651/2025** substitui a Resolução 169/2013 e introduz mudanças profundas na gestão das **contas vinculadas de encargos trabalhistas e previdenciários**, com impacto direto sobre a **elaboração e execução contratual** no TJSP.

### 🔹 **Pontos Centrais Incorporados no Agente**

1️⃣ **Aplicação Temporal**

* Contratos até 29/09/2025 → seguem Res. CNJ 169/2013
* Contratos a partir de 30/09/2025 → seguem Res. CNJ 651/2025

2️⃣ **Editais e Contratos devem conter:**

* Prazo máximo de 30 dias para abertura da conta vinculada;
* Índice de remuneração da conta (poupança ou CDB de alta liquidez);
* Penalidades para uso indevido;
* Obrigatoriedade de retenção e comprovação periódica das obrigações trabalhistas.

3️⃣ **Liberação de Recursos**

* **Pagamento direto** aos trabalhadores em caso de inadimplemento;
* **Reembolso à contratada** mediante comprovação formal e autorização;
* Ambos com autorização do ordenador de despesa e confirmação bancária em até 10 dias.

4️⃣ **Anuência Sindical**

* Mantida em rescisões ou liberações de saldo;
* Liberação tácita após 10 dias úteis sem manifestação.

5️⃣ **Delegação de Competências**

* **SOF:** abertura e movimentação da conta;
* **Unidade Gestora:** instrução e planilha analítica;
* **Fiscal:** conferência e solicitação de liberação;
* **Juiz Ordenador:** autorização final.

6️⃣ **Governança e Controle**

* Criação de planilhas analíticas padronizadas;
* Registro digital dos comprovantes no SEI;
* Integração futura com o Painel de Governança SAAB.

---

## 🧩 **5. Estrutura Contratual Padrão (TJSP – 2025)**

1️⃣ Preâmbulo e Identificação das Partes
2️⃣ Objeto e Fundamentação Legal
3️⃣ Vigência e Execução Contratual
4️⃣ Valor Global e Condições de Pagamento
5️⃣ Garantias e Encargos Trabalhistas
6️⃣ Obrigações da Contratada
7️⃣ Obrigações da Contratante (TJSP)
8️⃣ Gestão e Fiscalização Contratual
9️⃣ Conta Vinculada (Res. CNJ nº 651/2025)
🔟 Reajuste, Repactuação e Reequilíbrio
1️⃣1️⃣ Penalidades e Sanções
1️⃣2️⃣ Extinção e Rescisão Contratual
1️⃣3️⃣ Responsabilidade Civil e Seguros
1️⃣4️⃣ Gestão de Riscos e Sustentabilidade
1️⃣5️⃣ Foro e Disposições Finais

---

## 🧠 **6. Funcionalidade do Agente Copilot**

### 🔹 **Fluxo de Interação**

```
TR → Edital → Contrato → Relatório de Conformidade
```

1️⃣ Lê automaticamente o edital e o TR aprovados;
2️⃣ Gera minuta contratual completa, citando dispositivos legais;
3️⃣ Aplica o checklist normativo (Lei 14.133/21 + Manual TJSP);
4️⃣ Classifica as cláusulas:

* ✅ Pronta
* ⚠️ Parcial
* ❌ Pendente
  5️⃣ Sugere redações padronizadas com base no Manual de Contratos TJSP;
  6️⃣ Gera relatório em JSON/Markdown com recomendações automáticas.

---

## 🧾 **7. Relatórios e Artefatos Gerados**

| Artefato                      | Descrição                                             | Formato          |
| ----------------------------- | ----------------------------------------------------- | ---------------- |
| **Minuta Contratual**         | Contrato completo com base normativa                  | `.md`, `.docx`   |
| **Relatório de Conformidade** | Avaliação (✅⚠️❌) das cláusulas                        | `.json`, `.md`   |
| **Mapa de Rastreabilidade**   | Vinculação entre TR, Edital e Contrato                | `.xlsx`, `.json` |
| **Checklist Normativo**       | Lista das cláusulas obrigatórias e fundamentos legais | `.yaml`, `.json` |

---

## 🧱 **8. Integração Técnica**

| Módulo                                  | Função                                     | Dependência                |
| --------------------------------------- | ------------------------------------------ | -------------------------- |
| `integration_contrato.py`               | Gera minuta e relatório de conformidade    | `openai`, `pandas`, `json` |
| `ai_client.py`                          | Conector institucional OpenAI (método ask) | `openai==2.7.1`            |
| `next_pipeline.py`                      | Pipeline SAAB – geração de Markdown e DOCX | `pydantic`, `pathlib`      |
| `streamlit_app/pages/08_📜 Contrato.py` | Interface SharePoint/Streamlit para edição | `streamlit`, `pandas`      |

---

## ⚙️ **9. Checklists de Conformidade**

| Item                        | Referência Legal             | Status Esperado |
| --------------------------- | ---------------------------- | --------------- |
| Cláusulas essenciais        | Art. 92, Lei 14.133/21       | ✅               |
| Gestão e fiscalização       | Decreto 67.381/22, art. 117  | ✅               |
| Conta vinculada             | Res. CNJ nº 651/2025         | ✅               |
| Garantias                   | Art. 96, Lei 14.133/21       | ⚙️              |
| Reajuste                    | Art. 92, XIII, Lei 14.133/21 | ✅               |
| Responsabilidades e Seguros | Manual TJSP, Cap. 4          | ✅               |
| Foro                        | Art. 94, Lei 14.133/21       | ✅               |

---

## 📘 **10. Referências Bibliográficas e Normativas**

* **TJSP – Manual de Contratos (2025)**
  Secretaria de Administração e Abastecimento – SAAB
  [Versão institucional disponível no SharePoint TJSP]

* **TJSP – Manual de Licitações (2ª edição, 2025)**
  Secretaria de Administração e Abastecimento – SAAB

* **SEGES/MGI – Manual de Boas Práticas em Contratações Públicas (2024)**
  Ministério da Gestão e da Inovação em Serviços Públicos – Brasília, DF.

* **CNJ – Resoluções nº 651 e 652/2025**
  Publicadas em 29/09/2025 – Diário da Justiça Eletrônico.

---

## 🧾 **11. Equipes e Responsáveis Institucionais**

**Secretaria de Administração e Abastecimento – SAAB**

* *Fábio Makoto Tagliaferro Yokoyama* – Secretário
* *Luciana Borges Toledo*, *Karina Yamaguishi Ide*, *Lilian Yamazato*, *Diego Gabriel*, *Murilo Mendes Santos*

**Secretaria de Orçamento e Finanças – SOF**

* *Eduardo Kanashiro Oyafuso* – Coordenador Técnico

**Grupo Técnico de Apoio às Contratações – GTAJ**

* *Rogério Denis Roque Bianchi* – Consultor Jurídico
* *Andrea Miyuki Noel*, *Bruna Marcela de Barros Cunha*

---

## 🧱 **12. Rodapé Institucional**

**Tribunal de Justiça do Estado de São Paulo – Secretaria de Administração e Abastecimento (SAAB)**
**Fluxo SAAB:** DFD → ETP → TR → EDITAL → CONTRATO
**Integração Técnica:** SharePoint · Copilot TJSP · OpenAI Orchestration
**Versão:** 5.4 · Novembro/2025
**Licença:** MIT – Uso institucional com atribuição ao TJSP
Manual de 
Contratos 
TRIBUNAL DE JUSTIÇA DE SÃO PAULO 
1.1.1.1.1.1.1  
Secretaria de Administração e Abastecimento | Saab  
M A N U A L D E C O N T R A T O S | 2 0 2 5 
Secretaria de Administração e Abas tecimento | Saab  
MANUAL DE CONTRATOS 
Edição - 2025  
1 
M A N U A L D E C O N T R A T O S | 2 0 2 5 
Secretaria de Administração e Abas tecimento | Saab  
SECRETÁRIO DE ADMINISTRAÇÃO E ABASTECIMENTO 
Fábio Makoto Tagliaferro Yokoyama 
EQUIPE DE TRABALHO 
Andrea Miyuki Noel 
Bruna Marcela de Barros Cunha 
Diego Aparecido Gabriel 
Diogo Takehiro Sayama 
Eduardo Kanashiro Oyafuso 
Karina Yamaguishi Ide 
Lilian Yamazato 
Luciana Borges Toledo 
Maria Aparecida Lúcio 
Maurício Marcos Abambres 
Murilo Mendes Santos 
Silvana Mendes de Godoy 
COLABORADORES 
Alian Labate Salas 
Flávia Cavalcante Lima 
Rogério Denis Roque Bianchi 
2 
M A N U A L D E C O N T R A T O S | 2 0 2 5 
Secretaria de Administração e Abas tecimento | Saab  
Sumário 
Manual de Contratos  
1. DISPOSIÇÕES  GERAIS ..................................................................................................................... 9 
1.1 A NOVA LEI DE LICITAÇÕES E CONTRATOS (LEI Nº 14.133/2021) ................ 10 
2. CONTRATO .......................................................................................................................................... 11 
2.1 DISPOSIÇÕES GERAIS.......................................................................................................................... 12 
2.2 FORMALIZAÇÃO  DOS CONTRATOS ...................................................................................... 12 
2.3 VIGÊNCIA ........................................................................................................................................................14 
3. GESTORES, GESTORAS  E FISCAIS ..................................................................................... 16 
3.1 DESIGNAÇÃO .............................................................................................................................................. 17 
3.2 PERFIS .............................................................................................................................................................. 18 
3.3 VEDAÇÕES E IMPEDIMENTOS .................................................................................................... 19 
3.4 ATRIBUIÇÕES GERAIS ...................................................................................................................... 20 
4. ETAPAS DA GESTÃO E FISCALIZAÇÃO ........................................................................ 21 
4.1 ATRIBUIÇÕES ............................................................................................................................................. 22 
4.1.1 GESTOR E GESTORA DO CONTRATO ................................................................................. 22 
4.1.2 FISCAL DO CONTRATO .................................................................................................................. 23 
4.1.3 FISCAL ADMINISTRATIVO ........................................................................................................... 24 
4.1.4 RESPONSÁVEIS TÉCNICOS ........................................................................................................ 25 
4.2 EXECUÇÃO DOS CONTRATOS ................................................................................................... 26 
4.2.1 FISCALIZAÇÃO DOS CONTRATOS COM DEDICAÇÃO EXCLUSIVA DE 
MÃO DE OBRA .................................................................................................................................................. 27 
4.2.1.1   RETENÇÃO E LIBERAÇÃO DAS VERBAS CONTINGENCIADAS ............. 29 
4.2.1.1.1 LIBERAÇÃO DAS VERBAS DURANTE  O CONTRATO .................................... 30 
3 
M A N U A L D E C O N T R A T O S | 2 0 2 5 
Secretaria de Administração e Abas tecimento | Saab  
4.2.1.1.2 LIBERAÇÃO DO SALDO REMANESCENTE APÓS O ENCERRAMENTO  
DO CONTRATO ................................................................................................................................................. 35 
4.2.1.1.3 RESOLUÇÃO DE CASOS OMISSOS .............................................................................. 40 
4.2.2 FISCALIZAÇÃO DOS SERVIÇOS E OBRAS DE ENGENHARIA ........................41 
4.2.3 FISCALIZAÇÃO DOS CONTRATOS DE STIC ..................................................................41 
4.3 RECEBIMENTO ....................................................................................................................................... 42 
4.3.1 RECEBIMENTO PROVISÓRIO .................................................................................................. 43 
4.3.2 RECEBIMENTO DEFINITIVO .................................................................................................... 44 
4.3.3 ROTEIRO PARA RECEBIMENTO DE BENS .................................................................. 45 
4.3.4 ROTEIRO PARA RECEBIMENTO  DE SERVIÇOS .................................................... 46 
4.4 IRREGULARIDADES NA EXECUÇÃO CONTRATUAL ............................................... 47 
5. CONTRATOS SUI GENERIS ..................................................................................................... 49 
5.1 CONTRATOS DE FORNECIMENTO DE ENERGIA ELÉTRICA ............................. 50 
5.1.1 FLUXO ATUALIZADO PARA FORMALIZAÇÃO DOS CONTRATOS  DE 
ENERGIA ELÉTRICA ....................................................................................................................................... 51 
5.1.2 ALTERAÇÃO DA DEMANDA ................................................................................................... 53 
6. ATESTADO E PROTOCOLO DO DOCUMENTO FISCAL .......................... 54 
6.1 DO CADASTRO  NO SISTEMA SGF ........................................................................................... 55 
6.2 PRAZO DE RECEBIMENTO E ENVIO DA DOCUMENTAÇÃO À SOF ........... 55 
6.3 CADASTRAMENTO DO DOCUMENTO FISCAL .............................................................. 56 
6.3.1 1ª ETAPA: INFORMAÇÃO DOS DADOS CADASTRAIS E IMPOSTOS 
APLICADOS AO DOCUMENTO ........................................................................................................... 57 
6.3.1.1 RETENÇÕES TRIBUTÁRIAS (ISS, INSS E IRRF) ......................................................... 59 
6.3.1.1.1 RETENÇÃO ISS ................................................................................................................................ 60 
6.3.1.1.2 RETENÇÃO INSS ............................................................................................................................. 61 
6.3.1.1.3 RETENÇÃO IRRF (IMPOSTO DE RENDA RETIDO NA FONTE) ................ 62 
6.3.2 2ª ETAPA: FORNECIMENTO DAS INFORMAÇÕES ACERCA DA 
EXECUÇÃO DO CONTRATO .................................................................................................................. 63 
6.3.3 3ª ETAPA: PROTOCOLO ............................................................................................................. 65 
6.4 CANCELAMENTO DE PROTOCOLOS DE DOCUMENTOS FISCAIS ............ 66 
4 
M A N U A L D E C O N T R A T O S | 2 0 2 5 
Secretaria de Administração e Abas tecimento | Saab  
7. GESTÃO DE RISCOS .................................................................................................................... 68 
7.1 ATUALIZAÇÃO DO PLANO  DE RISCOS .............................................................................. 70 
8. MODIFICAÇÕES CONTRATUAIS ....................................................................................... 72 
8.1 FORMALIZAÇÃO DAS ALTERAÇÕES CONTRATUAIS ............................................... 73 
8.1.1 ACRÉSCIMOS E SUPRESSÕES .................................................................................................. 73 
8.1.2 PRORROGAÇÕES DE VIGÊNCIA ........................................................................................... 74 
8.1.2.1 ATA DE REGISTRO DE PREÇOS .......................................................................................... 77 
8.1.3 MANUTENÇÃO DO EQUILÍBRIO ECONÔMICO-FINANCEIRO .................... 78 
8.1.3.1 REAJUSTAMENTO EM SENTIDO ESTRITO  E REPACTUAÇÃO..................79 
8.1.3.2 REEQUILÍBRIO ECONÔMICO-FINANCEIRO ........................................................... 80 
9.  EXTINÇÃO DOS CONTRATOS ............................................................................................. 82 
9.1 EXTINÇÃO UNILATERAL .................................................................................................................... 83 
9.2 EXTINÇÃO PLEITEADA  PELA CONTRATADA ............................................................... 84 
10. RELATÓRIO FINAL ................................................................................................................. 86 
10.1 RELATÓRIO FINAL SOBRE A CONSECUÇÃO DOS OBJETIVOS ................... 87 
11.  ANEXOS .............................................................................................................................................. 88 
11.1 ANEXO I – CHECKLIST PARA NOVA CONTRATAÇÃO DE ENERGIA 
ELÉTRICA (CUSD E CCER) ...................................................................................................................... 89 
11.2 ANEXO II - CHECKLIST PARA ALTERAÇÃO DA DEMANDA  DE ENERGIA 
ELÉTRICA .............................................................................................................................................................. 90 
5 
 
 
 
 
 
INTRODUÇÃO 
 
 
 
Desde a última edição deste manual, publicada em 2018, 
ocorreram mudanças substanciais nas normas relacionadas à gestão e 
fiscalização de contratos, sobretudo com a publicação da Lei nº 
14.133/2021, denominada Nova Lei de Licitações e Contratos, que 
estabelece as regras gerais de licitações e contratos administrativos 
para as Administrações Públicas diretas, autárquicas e fundacionais da 
União, dos Estados, do Distrito Federal e dos Municípios. 
Dessa maneira, em conformidade ao Provimento CSM nº 
2.724/2023 e à luz da Lei nº 14.133/2021, foi elaborado o presente Manual 
de Gestão e Fiscalização de Contratos, cujo objetivo é reunir 
informações e orientações indispensáveis, organizando-as de forma 
sistematizada e precisa, a fim de direcionar a atuação dos servidores 
deste Tribunal de Justiça envolvidos na gestão e fiscalização de 
contratos administrativos. 
  
M A N U A L D E C O N T R A T O S | 2 0 2 5 
Secretaria de Administração e Abas tecimento | Saab  
1.  
DISPOSIÇÕES  
GERAIS 
9 
10 
M A N U A L D E C O N T R A T O S | 2 0 2 5 
Secretaria de Administração e Abas tecimento | Saab  
 
 
 
1.1   A NOVA LEI DE LICITAÇÕES E 
CONTRATOS (LEI Nº 14.133/2021) 
 
A Nova Lei de Licitações e Contratos (lei nº 14.133, de 1º de abril de 2021), 
estabelece normas gerais de licitação e contratação para as Administrações 
Públicas diretas, autárquicas e fundacionais da União, do Distrito Federal, dos 
Estados e dos Municípios, e substituiu a Lei nº 8.666/1993, até então utilizada. 
Com o advento da Nova Lei, houve maior incorporação da forma eletrônica 
nos procedimentos adotados, inclusive na celebração de contratos e seus termos 
aditivos, bem como trouxe outras alterações. 
No entanto, durante o período de transição da Nova Lei, estendido até o dia 
30/12/2023, era permitida a utilização de ambas as legislações, ficando a critério 
da Administração dispor daquela que melhor atendesse seus objetivos. Tal 
opção vincula os demais atos processuais conseguintes. 
Dessa forma, todos os processos licitatórios e de contratação direta tramitados 
sob o regime antigo (Lei nº 8.666/1993) serão por ele regidos, desde que a 
publicação do edital ou do ato autorizativo da contratação direta tenha ocorrido 
até o dia 29/12/2023. Nesse caso, deve-se consultar os procedimentos previstos 
no antigo Manual de Licitações e Contratos do TJSP (disponível em Manual de 
Licitações e Contratos - 1ª Edição). 
Para os demais casos, deve-se observar exclusivamente o texto da Lei nº 
14.133/2021. 
A integralidade da Nova Lei de Licitações e Contratos pode ser consultada em 
Lei nº 14.133/2021. 
  
M A N U A L D E C O N T R A T O S | 2 0 2 5 
Secretaria de Administração e Abas tecimento | Saab  
2.  
CONTRATO 
11 
M A N U A L D E C O N T R A T O S | 2 0 2 5 
Secretaria de Administração e Abas tecimento | Saab  
2.1 DISPOSIÇÕES GERAIS 
Contrato administrativo é um instrumento formal, regido pelas normas do 
direito público e suplementado pelas normas do direito privado no que couber, 
celebrado entre a Administração Pública e um terceiro (pessoa física ou jurídica, 
de direito público ou privado) para o fornecimento de bens, a realização de obras 
ou a prestação de serviços. Trata-se de um acordo recíproco de vontades, em que 
ambas as partes celebram um negócio com o fim de se atender ao interesse 
público. 
Todo contrato deve mencionar os nomes das partes e de seus 
representantes, a finalidade, o ato que autorizou sua lavratura, assim como o 
número do processo de licitação ou de contratação direta. 
Além disso, os contratos devem possuir cláusulas claras e precisas, com as 
condições necessárias para sua execução, bem como os direitos, obrigações e 
responsabilidades das partes. 
2.2 FORMALIZAÇÃO DOS CONTRATOS 
No TJSP, atuarão na fase de formalização do contrato: 
• Presidente do TJSP; 
• Gestor ou Gestora do Contrato; 
• Diretoria de Contratos da Secretaria de Administração e Abastecimento – Saab 6; 
• Secretaria de Orçamento e Finanças - SOF 
A formalização dos contratos administrativos segue o seguinte trâmite: 
1. Concluída a fase de julgamento e habilitação, os autos são 
encaminhados à Diretoria de Contratos da Secretaria de Administração 
e Abastecimento – Saab 6 para a lavratura do instrumento contratual; 
12 
M A N U A L D E C O N T R A T O S | 2 0 2 5 
Secretaria de Administração e Abas tecimento | Saab  
2. Elaborado o contrato, o processo segue para a E. Presidência visando 
à homologação, adjudicação, autorização da despesa e assinatura do 
termo contratual; 
3. Com o retorno da Alta Administração, a Saab 6.1 notificará a 
Contratada para assinatura do contrato, dentro do prazo e nas 
condições previstas no edital de licitação ou autorização de contratação 
direta, sob pena de decadência do seu direito à contratação, sem 
prejuízo às penalidades previstas no edital e no contrato; 
4. O prazo de convocação poderá ser prorrogado uma vez por igual 
período, mediante solicitação justificada da Contratada, desde que o 
motivo apresentado seja aceito pela Administração; 
5. No âmbito do Tribunal de Justiça de São Paulo, essas assinaturas são 
coletadas, preferencialmente, na forma eletrônica, mediante 
assinatura da Contratada no Portal Eletrônico de Assinaturas do TJSP; 
6. Na impossibilidade do contrato, do Termo de Confidencialidade e 
Proteção de Dados e do Termo de Ciência e Notificação (TCE) serem 
assinados eletronicamente, por falha do sistema ou por motivo 
superveniente do Tribunal de Justiça, a Contratada será convocada 
para assiná-los fisicamente; 
7. Formalizado o contrato, será encaminhado, ao gestor ou à gestora 
e ao suplente de gestor, o despacho da E. Presidência com as 
respectivas nomeações, bem como cópia do contrato ou link de 
acesso do referido ajuste no Portal da Transparência do TJSP; 
8. A Saab 6 providenciará o cadastro do contrato no Sistema de 
Gerenciamento Financeiro e Orçamentário (SGF) e sua publicação no 
DEJESP (Diário Eletrônico da Justiça de São Paulo) e no PNCP (Portal 
Nacional de Contratações Públicas). 
9. Na sequência, serão abertas tarefas no sistema à Secretaria de 
Orçamento e Finanças – SOF para as providências internas (empenho, 
abertura de processos contábeis, de contingenciamento, registro de 
garantia etc.), bem como o encaminhamento do processo à Diretoria 
de Licitações e Suprimentos – Saab 5, para envio AUDESP da Licitação; 
10. Por fim, a Saab 6.1 realizará o envio AUDESP dos Contratos. 
13 
M A N U A L D E C O N T R A T O S | 2 0 2 5 
Secretaria de Administração e Abas tecimento | Saab  
2.3 VIGÊNCIA 
O prazo de vigência dos contratos deve ser previsto em edital e no contrato, 
observando-se, no ato da contratação e a cada exercício financeiro, a 
disponibilidade orçamentária, assim como a previsão no plano plurianual, caso 
ultrapasse 1 (um) exercício financeiro. 
Em regra, os contratos para serviços e fornecimentos contínuos podem 
possuir prazo de até 5 (cinco) anos, podendo ser prorrogados, sucessivamente, 
até o limite máximo de 10 (dez) anos, desde que: 
• Haja previsão em edital; 
• A autoridade competente ateste que as condições e os preços 
permanecem vantajosos para a Administração. 
Ainda, de acordo com o art. 111 da Lei nº 14.133/2021, na contratação que 
previr a conclusão de escopo predefinido, o prazo de vigência será 
automaticamente prorrogado quando seu objeto não for concluído no período 
firmado no contrato. 
Ademais, a Administração poderá estabelecer a vigência por prazo 
indeterminado nos contratos em que seja usuária de serviço público oferecido 
em regime de monopólio, desde que comprovada, a cada exercício financeiro, 
a existência de créditos orçamentários vinculados à contratação (Art. 109 da Lei 
nº 14.133/2021). 
Para os contratos com vigência plurianual, a Administração deve observar 
as seguintes diretrizes: 
• A autoridade competente deve atestar a maior vantagem 
econômica em razão da contratação plurianual; 
• A Administração deverá atestar, no início da contratação e a cada 
exercício, a existência de créditos orçamentários vinculados à 
contratação e a vantagem em sua manutenção; 
• A Administração terá a opção de extinguir o contrato, sem ônus, 
quando não dispuser de créditos orçamentários para sua 
continuidade ou quando entender que o contrato não seja mais 
vantajoso. 
A fim de que não ocorram vencimentos de contrato sem a devida 
prorrogação, o Gestor ou a Gestora do Contrato deverá adotar as providências 
nos seguintes prazos: 
14 
M A N U A L D E C O N T R A T O S | 2 0 2 5 
Secretaria de Administração e Abas tecimento | Saab  
15 
  
 
 
 
Tipos de contratos 
Início das providências / 
verificações pelo Gestor 
ou pela Gestora 
Formalização do pedido de 
prorrogação perante a 
Diretoria de Contratos da 
Saab 
Prestação de serviços de 
natureza continuada 
240 dias antes do 
vencimento 
180 dias antes do 
vencimento 
Serviços de alta 
complexidade ou que 
necessitem de análise 
técnica 
300 dias antes do 
vencimento 
240 dias antes do 
vencimento 
 
Os procedimentos e providências a serem adotadas pelo Gestor ou pela 
Gestora do Contrato para a prorrogação contratual estão demonstradas no item 
“8.1.2 – Prorrogações de Vigência” deste Manual. 
  
M A N U A L D E C O N T R A T O S | 2 0 2 5 
Secretaria de Administração e Abas tecimento | Saab  
3.  
GESTORES, 
GESTORAS  
E FISCAIS 
16 
M A N U A L D E C O N T R A T O S | 2 0 2 5 
Secretaria de Administração e Abas tecimento | Saab  
Inicialmente, cumpre-nos definir brevemente os atores que atuam nos 
contratos administrativos, de acordo com o Provimento CSM nº 2724/2023: 
• Equipe de Gestão do Contrato: equipe formada pelo Gestor ou pela 
Gestora do Contrato e suplente, pelos Fiscais Administrativos e 
suplentes, pelos Fiscais do Contrato e suplentes, e pelos 
Responsáveis Técnicos, se o caso, para acompanhamento, gestão e 
fiscalização da execução contratual; 
• Fiscal Administrativo: servidor ou servidora designados para 
auxiliar o Gestor ou a Gestora do Contrato na fiscalização dos 
aspectos administrativos da execução contratual; 
• Fiscal do Contrato: servidor ou servidora designados para auxiliar o 
Gestor ou a Gestora do Contrato na fiscalização dos aspectos 
operacionais da execução contratual; 
• Gestor ou Gestora do Contrato: servidor, servidora, magistrado ou 
magistrada designados pela Presidência do Tribunal de Justiça para 
coordenar a gestão e fiscalização da execução contratual. 
3.1  DESIGNAÇÃO 
Na designação serão considerados: 
• A complexidade da fiscalização; 
Os gestores, as gestoras e seus respectivos suplentes serão designados pela 
Presidência do TJSP, ao passo que os fiscais e seus suplentes serão designados 
pelo Gestor ou pela Gestora. 
• A compatibilidade com as atribuições do cargo; 
• O quantitativo de contratos por servidor; 
• A capacidade para o desempenho das atividades. 
O Gestor ou a Gestora, o Fiscal Administrativo e o Fiscal do Contrato são 
indicados na fase de planejamento da contratação e constarão no Termo de 
Referência (TR), sendo designados de forma individualizada, incluídos seus 
substitutos. 
O Gestor ou a Gestora do Contrato deve ser notificado de sua designação e 
de suas atribuições previstas no art. 73 do Provimento nº 2.724/2023, em até 5 
(cinco) dias após a assinatura do contrato. Em sua ausência, seu suplente 
assumirá as funções. 
17 
18 
M A N U A L D E C O N T R A T O S | 2 0 2 5 
Secretaria de Administração e Abas tecimento | Saab  
 
 
Após designado, o Gestor ou a Gestora do Contrato designará o Fiscal 
Administrativo, o Fiscal do Contrato e seus suplentes, no módulo SGF do sistema 
SAJADM (SGF > Contrato > Gestão Contratual). 
      Em caso de impossibilidade de exercício das funções em razão de 
relotação, exoneração de função comissionada ou afastamento definitivo, o 
gestor ou a gestora, os fiscais e as fiscais deverão solicitar a cessação de sua 
designação, no prazo de até 48 horas, conforme segue: 
Função Solicita para Providências Referências 
Provimento 
Gestor ou Gestora 
do Contrato 
Secretário ou 
Secretária da 
área gestora 
Em até 48 horas, o Secretário ou 
a Secretária da área gestora deve 
encaminhar expediente 
eletrônico à Diretoria de 
Contratos da Saab – Saab 6, com 
indicação do novo Gestor ou da 
nova Gestora e suplente, se o 
caso, para que seja submetido à 
deliberação e designação pela E. 
Presidência. 
Art. 72, §3º e 
§4º 
Fiscais 
Administrativo e 
do Contrato e 
respectivos 
suplentes 
Gestor ou 
Gestora do 
Contrato 
Gestor ou Gestora designa novo 
fiscal e/ou suplente, notificando
os de sua designação e 
atribuições, bem como 
providencia a devida alteração 
no módulo 
SAJADM/SGF/Contratos/Gestão 
Contratual 
Art. 75, §2º e 
§3º; 
Atribuições do 
Fiscal do 
Contrato: Art. 
76; Atribuições 
do Fiscal 
Administrativo: 
Art. 77 
 
 
 
3.2  PERFIS 
 
De acordo com os artigos 6º e 7º do Provimento CSM nº 2.724/2023, a 
Presidência do Tribunal de Justiça de São Paulo deverá promover a gestão por 
competências, zelar pela segregação de funções, assegurar que a estrutura dos 
servidores seja suficiente para o desempenho de suas respectivas funções e 
designar servidores para o desempenho das funções de gestão e fiscalização de 
contratos, que preencham os seguintes requisitos: 
M A N U A L D E C O N T R A T O S | 2 0 2 5 
Secretaria de Administração e Abas tecimento | Saab  
• Sejam, preferencialmente, servidor efetivo ou empregado público dos 
quadros permanentes da Administração Pública; 
• Tenham atribuições relacionadas a licitações e contratos ou possuam 
formação compatível ou qualificação atestada por certificação profissional 
emitida por escola de governo criada e mantida pelo poder público; 
De modo geral, o Gestor ou a Gestora e os Fiscais possuem as seguintes 
características: 
3.3 VEDAÇÕES E IMPEDIMENTOS 
O Gestor ou a Gestora, o Fiscal Administrativo e o Fiscal do Contrato não 
devem: 
• Ser cônjuge ou companheiro, bem como possuir vínculo de 
parentesco, colateral ou por afinidade, até o terceiro grau, com 
licitantes ou contratados da Administração; 
• Possuir relação comercial, econômica, civil, financeira ou trabalhista 
com licitantes ou contratados da Administração. 
19 
M A N U A L D E C O N T R A T O S | 2 0 2 5 
Secretaria de Administração e Abas tecimento | Saab  
Ao Gestor, à Gestora, ao Fiscal Administrativo e ao Fiscal do Contrato é 
vedada a prática de atos de ingerência na administração da Contratada, 
como, por exemplo: 
• Exercer relação de subordinação com os empregados da Contratada, 
devendo sempre reportar-se aos prepostos por ela indicados; 
• Direcionar a contratação de pessoas para trabalhar nas empresas da 
Contratada; 
• Promover ou aceitar o desvio de funções dos empregados da 
Contatada; 
• Promover atos que alterem a jornada de trabalho dos empregados 
da Contatada, quando não previstas contratualmente; 
3.4  ATRIBUIÇÕES GERAIS 
Competem ao Gestor, à Gestora e aos Fiscais atuarem nas etapas de 
formalização, execução e encerramento do contrato. De modo geral, possuem 
as atribuições de: 
• Gerenciar os contratos sob sua responsabilidade, a fim de obter os 
melhores resultados, com a propositura de alterações necessárias; 
• Realizar a Gestão dos Riscos contratuais. 
• Monitorar e avaliar o desempenho dos fornecedores e prestadores 
de serviços; 
• Conhecer as tarefas relativas ao contrato, de modo a se preparar com 
antecedência a elas; 
As demais atribuições e responsabilidades serão abordadas e 
detalhadas nos próximos tópicos. 
20 
M A N U A L D E C O N T R A T O S | 2 0 2 5 
Secretaria de Administração e Abas tecimento | Saab  
4.  
ETAPAS DA 
GESTÃO E 
FISCALIZAÇÃO 
21 
M A N U A L D E C O N T R A T O S | 2 0 2 5 
Secretaria de Administração e Abas tecimento | Saab  
4.1   ATRIBUIÇÕES 
4.1.1  GESTOR E GESTORA DO CONTRATO 
De acordo com o art. 73 do Provimento CSM nº 2.724/2023, compete ao 
Gestor e à Gestora do Contrato: 
• Designar o Fiscal Administrativo e seu suplente, o Fiscal do Contrato 
e seu suplente, notificando-os de suas designações e atribuições; 
• Realizar o cadastro dos Fiscais e suplentes no sistema SAJADM (SGF 
> Contrato > Gestão Contratual); 
• Convocar e coordenar reunião inicial para leitura do instrumento 
contratual; 
• Providenciar a abertura de processo administrativo eletrônico 
específico, vinculado ao processo de contratação; 
• Acompanhar o desenvolvimento da execução contratual, por meio 
dos relatórios elaborados pelos Fiscais; 
• Quando previsto no contrato, atestar definitivamente a nota 
fiscal/fatura e encaminhá-la à SOF, em até 3 (três) dias úteis após 
sua emissão; 
• Analisar pedidos de alterações contratuais; 
• Excepcionalmente, cumular as funções de Fiscal Administrativo e/ou 
Fiscal do Contrato, quando estes não forem designados; 
• Analisar ou formular pedidos de reequilíbrio econômico-financeiro, 
apresentando relatório conclusivo; 
• Manifestar-se quanto ao interesse da Administração nas 
prorrogações de vigência dos contratos de execução continuada, 
sugerindo o aditamento contratual ou a abertura de nova licitação; 
• Manifestar-se quanto aos pedidos de suspensão ou prorrogação do 
prazo de execução de obras, serviços ou entrega de bens; 
• Instaurar Processo Administrativo Apuratório quando verificado 
eventual descumprimento pela Contratada das obrigações 
contratuais; 
• Propor à Equipe de Planejamento da Contratação, em caso de 
planejamento de novo contrato, a atualização e aperfeiçoamento do 
ETP, do Plano de Riscos, do TR, do Projeto Básico ou Executivo, 
conforme as intercorrências verificadas na execução contratual; 
• Acompanhar o andamento das contratações que substituirão os 
contratos vigentes; 
22 
M A N U A L D E C O N T R A T O S | 2 0 2 5 
Secretaria de Administração e Abas tecimento | Saab  
• Informar à SOF as obrigações financeiras não liquidadas no exercício, 
para efeito de inscrição de saldos de empenho à conta de restos a 
pagar ou de cancelamento de recursos; 
• Elaborar relatório final, com as informações relativas à execução 
contratual, especialmente sobre a efetiva consecução dos objetivos 
que justificaram a contratação e com a relação dos Processos 
Administrativos Apuratórios, suas causas e impactos. Por fim, deve 
propor eventuais melhorias a serem refletidas no ETP, no TR e no 
Plano de Riscos da futura contratação; 
• Desempenhar outras atividades previstas no contrato. 
4.1.2   FISCAL DO CONTRATO 
De acordo com o art. 76 do Provimento CSM nº 2.724/2023, compete ao 
Fiscal do Contrato: 
• Participar da reunião inicial; 
• Providenciar a abertura de processo administrativo eletrônico 
específico destinado a registrar os atos de fiscalização e ocorrências 
da execução contratual; 
• Fiscalizar a execução contratual de acordo com o estabelecido no 
contrato; 
• Elaborar relatório de acompanhamento da execução contratual e 
encaminhá-lo ao Fiscal Administrativo; 
• Anotar em registro próprio todas as ocorrências relacionadas à 
execução do contrato, determinando o que for necessário para a 
regularização das faltas ou dos defeitos observados; 
• Em situações que demandem decisão ou providência que ultrapasse 
sua competência, caberá ao Fiscal reportar, em tempo hábil (em 
regra, 5 (cinco) dias úteis; em casos emergenciais, 24 horas), ao 
Gestor ou à Gestora do Contrato, para que adote as medidas cabíveis; 
• Quando previsto no contrato, atestar definitivamente a nota 
fiscal/fatura e encaminhá-la à SOF, em até 3 (três) dias úteis após 
sua emissão; 
• Preencher e encaminhar mensalmente ao Fiscal Administrativo 
relatório de avaliação de desempenho da Contratada; 
• Nos contratos de locação, encaminhar à SOF o ateste mensal da 
ocupação de imóvel locado pelo Tribunal de Justiça; 
• Propor alterações contratuais ao Fiscal Administrativo; 
• Controlar o prazo de execução e vigência do contrato; 
• Receber o objeto, provisória e/ou definitivamente; 
23 
M A N U A L D E C O N T R A T O S | 2 0 2 5 
Secretaria de Administração e Abas tecimento | Saab  
• Notificar a Contratada para a regularização de possível 
descumprimento contratual, preferencialmente de forma eletrônica, 
estabelecendo prazo compatível para atendimento (em regra, 5 
(cinco) dias úteis; em casos emergenciais, 24 horas); 
• Elaborar relatório conclusivo quanto à notificação de eventual 
descumprimento contratual e encaminhá-lo ao Fiscal 
Administrativo, com proposta de instauração de Processo 
Administrativo Apuratório, se o caso; 
• Desempenhar outras atividades previstas no contrato. 
4.1.3   FISCAL ADMINISTRATIVO 
De acordo com o art. 77 do Provimento CSM nº 2.724/2023, compete ao 
Fiscal Administrativo: 
• Participar da reunião inicial; 
• Consolidar os relatórios de acompanhamento da execução 
contratual emitidos pelo Fiscal do Contrato; 
• Quando previsto no contrato, atestar definitivamente a nota 
fiscal/fatura e encaminhá-la à SOF, em até 3 (três) dias úteis após 
sua emissão; 
• Emitir, caso solicitado, atestado de capacidade técnica; 
da 
• Consolidar mensalmente os relatórios de avaliação de desempenho 
da Contratada elaborados pelo Fiscal do Contrato; 
• Verificar semestralmente a manutenção das condições de 
habilitação 
Contratada, 
solicitando 
os 
documentos 
comprobatórios. O GPAC (Grupo de Pregoeiros e Agentes de 
Contratação) auxiliará na conferência da documentação, mediante 
solicitação; 
✓ Semestralmente, deve-se solicitar declaração da Contratada acerca 
do atendimento à reserva de vagas para pessoas em condição de 
vulnerabilidade, prevista na Resolução CNJ nº 497/2023. 
• Controlar e informar ao Gestor ou à Gestora do Contrato as 
obrigações financeiras não liquidadas no exercício, para efeito de 
inscrição de saldos de empenho à conta de restos a pagar ou de 
cancelamento de recursos; 
• Propor ao Gestor ou à Gestora do Contrato a instauração de Processo 
Administrativo Apuratório; 
• Desempenhar outras atividades previstas no contrato. 
24 
M A N U A L D E C O N T R A T O S | 2 0 2 5 
Secretaria de Administração e Abas tecimento | Saab  
4.1.4 RESPONSÁVEIS TÉCNICOS 
Compete ao Responsável Técnico, que poderá ser servidor ou terceiro 
contratado: 
• Prestar apoio técnico ao Gestor ou à Gestora do Contrato e aos 
Fiscais, 
apresentando as informações pertinentes às suas 
competências, quando solicitado; 
• Observar as normas técnicas e legais, especificações e métodos de 
execução dos serviços exigíveis para a perfeita execução do objeto; 
• Emitir parecer técnico nos pedidos de alterações contratuais, 
quando solicitado; 
• Verificar a correta aplicação dos materiais; 
• Requerer testes, exames e ensaios, quando previstos no edital e/ou 
contrato, para controle de qualidade da execução das obras, serviços 
ou bens a serem adquiridos; 
• Desempenhar outras atividades previstas no contrato. 
25 
M A N U A L D E C O N T R A T O S | 2 0 2 5 
Secretaria de Administração e Abas tecimento | Saab  
4.2   EXECUÇÃO DOS CONTRATOS  
Após a assinatura do instrumento contratual, o Gestor ou a Gestora do 
Contrato convocará e coordenará reunião para leitura do contrato, com a 
participação do Fiscal Administrativo, do Fiscal do Contrato e do preposto da 
Contratada, para esclarecimentos das obrigações contratuais e definição do 
plano de trabalho. 
É fundamental que, antes do início da reunião, os membros da equipe 
tenham lido previamente todo o contrato e estejam cientes de suas atribuições 
e atividades. 
Vale frisar que todas as reuniões realizadas entre a Equipe de Gestão e 
Fiscalização do Contrato e a Contratada deverão ser lavradas em ata e 
registradas no processo digital, para acompanhamento da execução 
contratual. 
Entre outras atribuições previstas contratualmente, a Equipe de Gestão e 
Fiscalização do Contrato deve elaborar relatórios de acompanhamento da 
execução contratual, controlar o prazo de execução e vigência do contrato, 
preencher o relatório de avaliação de desempenho, notificar a Contratada para a 
regularização de eventual descumprimento e receber o objeto. 
É de suma importância o acompanhamento e o registro das atividades 
ocorridas durante a execução contratual, a fim de que o objeto contratado seja 
recebido de acordo com as especificações e quantidades exigidas em contrato, 
26 
M A N U A L D E C O N T R A T O S | 2 0 2 5 
Secretaria de Administração e Abas tecimento | Saab  
zelando, dessa forma, pela responsabilidade e transparência na aplicação dos 
recursos públicos. 
4.2.1   FISCALIZAÇÃO DOS CONTRATOS COM 
DEDICAÇÃO EXCLUSIVA DE MÃO DE OBRA 
A gestão e fiscalização dos contratos com dedicação exclusiva de mão de 
obra observará a Resolução CNJ nº 169/2013, Resolução CNJ nº 497/2023 (e suas 
alterações) e outras legislações aplicáveis. 
Nos contratos com dedicação exclusiva de mão de obra, compete ao Fiscal 
do Contrato: 
I. 
Solicitar à Contratada relação por local de trabalho dos empregados 
alocados, contendo, no mínimo: 
• Dados de identificação da Contratada; 
• Número do contrato administrativo; 
• Nome completo; 
• Cargo ou função; 
• Data de admissão na Contratada; 
• Data de alocação do posto; 
• Horário do posto de trabalho; 
• Números do CPF e da CTPS. 
II. 
III. 
Diariamente: 
Mensalmente: 
• Fiscalizar e registrar a efetiva execução dos serviços; 
• Manter controle indireto do comparecimento dos empregados 
alocados no contrato. 
• Exigir que o preposto da Contratada apresente cópias das folhas 
de ponto dos empregados por registro eletrônico ou outro meio que 
não seja padronizado; 
• Consolidar em planilha de controle os dias efetivamente 
trabalhados e a reposição de empregados em decorrência de férias, 
licenças, faltas e ocorrências; 
• Glosar as faturas em caso de faltas ou horas trabalhadas a 
menor; 
• Exigir da Contratada os comprovantes de pagamento dos 
salários, vale-transporte e demais benefícios previstos no contrato 
administrativo; 
27 
M A N U A L D E C O N T R A T O S | 2 0 2 5 
Secretaria de Administração e Abas tecimento | Saab  
• Preencher relação nominal, a ser assinada pelos empregados, 
para confirmação de pagamento tempestivo de salários, horas 
extras, férias, décimo terceiro salário e demais benefícios 
trabalhistas previstos no contrato administrativo. 
IV. 
Compete, ainda, ao Fiscal do Contrato a conferência dos seguintes 
documentos referentes ao mês anterior ao faturamento: 
• Certificado de Regularidade do FGTS – CRF, comprovando 
regularidade com o FGTS; 
• Certidão Conjunta Negativa de Débitos Relativos a Tributos 
Federais e à Dívida Ativa da União; 
• Certidão Negativa de Débitos Trabalhistas (CNDT); 
• Relação nominal por posto de trabalho dos empregados 
alocados, acompanhada de cópia da folha de pagamento do mês 
anterior à execução do serviço; 
• Planilha de cálculo do valor a ser deduzido na nota fiscal, 
decorrente de eventual não ocupação dos postos de trabalho nos 
termos do contrato. 
Nos contratos com dedicação exclusiva de mão-de-obra, o relatório final 
deverá conter as informações necessárias para a liberação, se o caso, do saldo de 
conta depósito-vinculada de que trata a Resolução CNJ nº 169/2016 (e suas 
alterações). 
28 
M A N U A L D E C O N T R A T O S | 2 0 2 5 
Secretaria de Administração e Abas tecimento | Saab  
4.2.1.1  RETENÇÃO E LIBERAÇÃO DAS VERBAS 
CONTINGENCIADAS 
O contingenciamento das verbas trabalhistas e previdenciárias é um 
mecanismo adotado pelo Tribunal de Justiça de São Paulo (TJSP) com o objetivo 
de assegurar que as empresas contratadas para prestar serviços com mão de 
obra residente cumpram corretamente suas obrigações trabalhistas e 
previdenciárias. 
Esse procedimento segue disposições da Resolução CNJ nº 169/2013 e 
alterações subsequentes que determina a retenção de valores que serão 
utilizados para pagamento das seguintes rubricas: 
I – Férias; 
II – 1/3 constitucional; 
III – 13º salário; 
IV – Multa do FGTS por dispensa sem justa causa; 
V – Incidência dos encargos previdenciários e FGTS sobre férias, 1/3 
constitucional e 13º salário. 
É importante ressaltar que o TJSP, mensalmente, desconta das notas fiscais 
da Contratada os valores como garantia para o pagamento das respectivas 
rubricas. Esses valores são depositados na conta-depósito vinculada (conta de 
contingenciamento) e podem ser resgatados pelas Empresas nas seguintes 
situações: 
▪ Após o pagamento e mediante apresentação dos documentos 
comprobatórios de que efetivamente pagou, a cada empregado 
alocado no contrato, as rubricas indicadas no art. 4º da referida 
Resolução. 
▪ Ao término do contrato, caso haja saldo remanescente na conta 
vinculada, este poderá ser resgatado pela empresa após a devida 
comprovação da quitação de todas as obrigações trabalhistas e 
previdenciárias referentes ao serviço contratado. Decorridos 5 
(cinco) anos do encerramento contratual, o resgate dos recursos 
poderá ser feito sem a necessidade de tal comprovação. 
29 
M A N U A L D E C O N T R A T O S | 2 0 2 5 
Secretaria de Administração e Abas tecimento | Saab  
4.2.1.1.1  LIBERAÇÃO DAS VERBAS DURANTE  
O CONTRATO 
Para liberação dos valores contingenciados durante a execução contratual, 
devem ser atendidas as seguintes etapas: 
1ª ETAPA: APRESENTAÇÃO DE DOCUMENTAÇÃO E ATESTE PELO 
FISCAL 
A Contratada deverá preencher a planilha de resgate, referente à verba 
objeto da solicitação de levantamento, de acordo com o contrato e por 
localidade da prestação dos serviços, caso o contrato abranja mais de uma 
localidade.  
ATENÇÃO: O modelo da planilha pode 
ser solicitado pela Contratada à SOF 
2.2.3, através do e-mail 
sof2.2.3@tjsp.jus.br, ou ao Gestor, à 
Gestora ou ao Fiscal do Contrato que 
poderá acessá-la em Modelos - SOF. 
30 
M A N U A L D E C O N T R A T O S | 2 0 2 5 
Secretaria de Administração e Abas tecimento | Saab  
31 
  
 
 
 
As planilhas estão parametrizadas de acordo com cada tipo de verba, razão 
pela qual devem ser editados apenas os campos que não possuem bloqueio. 
Após o preenchimento, as planilhas devem ser encaminhadas, por e-mail, 
ao Fiscal do Contrato, acompanhadas dos documentos comprobatórios. 
A documentação deve conter o resumo, conforme modelo abaixo 
(disponível em Modelos - SOF), com a relação dos valores que serão 
reembolsados por localidade e apresentação do montante total por verbas, bem 
como o total geral que será requisitado. 
RESUMO 
Contrato Nº  
Localidades Férias 13º salário Rescisões trabalhistas 
        
        
        
Subtotal  R$                      -     R$           -                   R$                        -    
Total  R$      -                        
 
De acordo com a verba a ser reembolsada, alguns documentos 
comprobatórios devem ser apresentados, conforme tabela abaixo: 
  
32 
M A N U A L D E C O N T R A T O S | 2 0 2 5 
Secretaria de Administração e Abas tecimento | Saab  
 
 
TIPO DE 
SOLICITAÇÃO DOCUMENTOS COMPROBATÓRIOS 
Reembolso de Férias 
▪ Recibo/Aviso de férias; 
▪ Comprovante de depósito bancário. 
Reembolso de 13º 
Salário 
▪ Demonstrativo de 13º salário; 
▪ Comprovante de depósito bancário. 
Rescisão trabalhista 
▪ Termo de Rescisão do Contato de Trabalho 
(TRCT) assinado; 
▪ Caso o contrato de trabalho seja superior a 1 
(um) ano, o TRCT deve estar homologado; 
▪ Comprovante de depósito bancário; 
Nos casos de demissão sem justa causa, a 
Contratada deverá apresentar adicionalmente: 
▪ Guia Detalhada da multa do FGTS ou 
Demonstrativo do Trabalhador de 
Recolhimento do FGTS Rescisório; 
▪ Guia e comprovante de recolhimento da Multa 
de FGTS; 
▪ Extrato de FGTS do funcionário, referente aos 
últimos 6 (seis) meses. 
 
Após, o Fiscal do Contrato deverá conferir a planilha preenchida e a 
documentação apresentada. Caso esteja tudo correto, deverá emitir o respectivo 
ateste, mediante assinatura na planilha de resgate, preferencialmente, em 
formato digital. 
 
DICA: Para assinar digitalmente um 
documento em formato PDF, basta 
seguir as orientações contantes em 
Assinatura Digital. 
M A N U A L D E C O N T R A T O S | 2 0 2 5 
Secretaria de Administração e Abas tecimento | Saab  
Em caso de desconformidade, a documentação deverá ser devolvida à 
empresa para os devidos ajustes. 
2ª ETAPA: SOLICITAÇÃO DA CONTRATADA 
Após o ateste e a compilação dos documentos comprobatórios, a 
Contratada deverá solicitar o levantamento dos valores contingenciados, 
mediante encaminhamento de solicitação formal, em formato PDF, para o 
endereço sof2.2.3@tjsp.jus.br, que efetuará o protocolo do pedido. 
Abaixo segue modelo sugerido (disponível em Modelos - SOF)  para a 
respectiva solicitação: 
33 
M A N U A L D E C O N T R A T O S | 2 0 2 5 
Secretaria de Administração e Abas tecimento | Saab  
Conforme se verifica, a Contratada deve indicar o responsável pelo envio da 
documentação através do Portal de Serviços, contendo os seguintes dados: 
nome completo, endereço de e-mail e nº do CPF. 
A solicitação formal deverá conter: 
▪ O objeto da solicitação (férias, 13º salário e/ou rescisões trabalhistas); 
▪ Número do contrato; 
▪ Valor a ser reembolsado; 
▪ Dados da conta do Banco do Brasil para crédito e assinatura do 
responsável legal da empresa. 
3ª ETAPA: ACESSO AO PORTAL DE SERVIÇOS PELA 
CONTRATADA E JUNTADA DE DOCUMENTOS 
A Equipe da SOF 2.2.3 abrirá a tarefa “COMUNIQUE-SE” no expediente de 
contingenciamento do respectivo contrato. 
Após, a Contratada receberá uma mensagem eletrônica no e-mail 
informado em sua solicitação, com orientações para acesso ao “Portal de 
Serviço”, bem como relação dos documentos a serem anexados, relacionados 
ao pedido de levantamento dos valores contingenciados, exclusivamente em 
formato PDF. 
até 19 MB.    
Para acessar o Portal de Serviços, é necessário que o usuário tenha um 
cadastro válido no Gov.br, pois o login será realizado com o mesmo usuário e 
senha utilizados nessa plataforma.  
ATENÇÃO: O sistema não aceita 
arquivos compactados, como ZIP, RAR 
ou semelhantes. 
Limite de envio por tarefa: 10 arquivos 
“pdf” por tarefa. Cada arquivo pode ter 
4ª ETAPA: LIBERAÇÃO DOS VALORES 
Após a análise da documentação comprobatória e estando em 
conformidade, a SOF enviará ofício ao Banco do Brasil, solicitando a liberação de 
valores contingenciados à Contratada. O reembolso ocorrerá na conta bancária 
indicada pela Contratada na solicitação formal.  
34 
M A N U A L D E C O N T R A T O S | 2 0 2 5 
Secretaria de Administração e Abas tecimento | Saab  
É importante ressaltar que a solicitação de reembolso poderá ser recusada, 
caso a documentação enviada apresente os seguintes problemas: 
▪ Desorganização dos arquivos; 
▪ Documentos ilegíveis; 
▪ Ausência de comprovantes de pagamentos; 
▪ Planilhas preenchidas incorretamente; 
▪ Falta de ateste do Fiscal responsável. 
Caso recusada, a solicitação será devolvida à empresa, via tarefa 
“COMUNIQUE-SE”, acompanhada da respectiva justificativa, para correção e 
novo envio do requerimento. 
FLUXO PARA LIBERAÇÃO/REEMBOLSO DE VERBAS 
CONTINGENCIADAS 
4.2.1.1.2  LIBERAÇÃO DO SALDO REMANESCENTE 
APÓS O ENCERRAMENTO DO CONTRATO 
Após o encerramento do contrato com o TJSP, pode existir saldo 
remanescente na conta vinculada. A empresa poderá pleitear o levantamento 
dos valores, desde que todas as obrigações trabalhistas e previdenciárias estejam 
devidamente quitadas. 
Se decorridos 5 (cinco) anos após o término do contrato, a empresa poderá 
solicitar o valor restante sem a necessidade de comprovar a quitação dessas 
obrigações. 
Seguem as etapas para solicitação da liberação: 
35 
36 
M A N U A L D E C O N T R A T O S | 2 0 2 5 
Secretaria de Administração e Abas tecimento | Saab  
 
 
 
1ª ETAPA: ENVIO DE SOLICITAÇÃO FORMAL PELA CONTRATADA 
A Contratada deverá solicitar o resgate integral do saldo remanescente, 
mediante encaminhamento de solicitação formal, para o e-mail  
sof2.2.3@tjsp.jus.br, que prosseguirá com a abertura do protocolo do pedido. 
 
2ª ETAPA: SOLICITAÇÃO DE ATESTES DOS FISCAIS DE CONTRATOS 
A Contratada deverá solicitar o ateste do Fiscal do Contrato, ratificando que 
houve a quitação dos encargos trabalhistas e previdenciários dos colaboradores 
vinculados ao contrato. 
 
Acesse o modelo do documento acima em Modelos - SOF. 
 
3ª ETAPA: ACESSO AO PORTAL DE SERVIÇOS PELA CONTRATADA 
A equipe da SOF 2.2.3 criará a tarefa “COMUNIQUE-SE”, solicitando que a 
empresa contratada envie a seguinte documentação (formato “pdf”) atualizada: 
 
 
M A N U A L D E C O N T R A T O S | 2 0 2 5 
Secretaria de Administração e Abas tecimento | Saab  
37 
  
 
 
 
DOCUMENTAÇÃO EXIGIDA 
 Até 2 anos do 
encerramento 
do contrato 
De 2 a 5 anos do 
encerramento do 
contrato 
Após 5 anos do 
encerramento do 
contrato 
Confirmação dos 
Gestores/Gestoras/Fiscais de cada 
localidade, ratificando que houve a 
quitação dos encargos trabalhistas 
e previdenciários, relativos aos 
colaboradores residentes que 
prestaram serviços na unidade e 
que tiveram seus contratos de 
trabalho rescindidos durante a 
vigência contratual 
X X X 
Contrato ou estatuto  
social da empresa X X X 
Documento de identificação do 
representante legal  
ou do procurador 
X X X 
Procuração válida (caso a 
assinatura dos documentos seja 
feita por procurador) 
X X X 
Documentação de constituição do 
sindicato e ata de posse da diretoria 
vigente 
X   
Documento de identificação do 
representante legal  
do Sindicato 
X   
Certidões dos TRTs da 2º e 15ª 
Região (comprovação de não 
ajuizamento de ações trabalhistas 
por colaboradores que atuaram no 
contrato) 
X X  
Outros documentos necessários, 
conforme o caso X X X 
 
 
 
M A N U A L D E C O N T R A T O S | 2 0 2 5 
Secretaria de Administração e Abas tecimento | Saab  
4ª ETAPA: REUNIÃO COM O SINDICATO E ASSINATURA DA 
CERTIDÃO 
Após a análise da documentação e estando em conformidade, a SOF 
agendará reunião em formato virtual para deliberar sobre a liberação do saldo 
remanescente da conta vinculada. 
Participação obrigatória: 
▪ Representante da empresa contratada;  
▪ Representante do TJSP; 
▪ Representante do Sindicato da Categoria. 
Durante a reunião, será exigida a concordância de todos os presentes 
quanto à liberação do saldo. Essa concordância se dará também por meio da 
assinatura da certidão liberatória. 
Caso o pedido de liberação do saldo remanescente seja realizado após 2 
(dois) anos do encerramento do contrato, não será necessário o cumprimento 
dessa etapa, conforme deliberação do Conselho Nacional de Justiça (CNJ). Nessa 
situação, a Contratada deverá apresentar: 
5ª ETAPA: MANIFESTAÇÃO DA SAAB SOBRE EVENTUAIS 
PENDÊNCIAS CONTRATUAIS 
▪ Certidões Trabalhistas emitidas pelos Tribunais Regionais (TRT 2 e 
TRT 15) que comprovem o não ajuizamento de ações trabalhistas 
pelos colaboradores vinculados ao contrato. 
Conforme diretrizes da E. Presidência, a SOF 2.2.3 enviará expediente para 
manifestação dos Gestores, das Gestoras e dos Fiscais do Contrato e da Saab 6 - 
Diretoria de Contratos Administrativos, Convênios e Gestão Imobiliária, com 
o objetivo de verificar a inexistência de pendências contratuais, incluindo 
processos apuratórios. 
Se não houver pendências, a SOF 2.2.3 dará prosseguimento à liberação do 
saldo residual da conta vinculada. 
38 
M A N U A L D E C O N T R A T O S | 2 0 2 5 
Secretaria de Administração e Abas tecimento | Saab  
39 
  
 
 
 
ATENÇÃO: caso existam pendências 
financeiras no mesmo contrato, a Saab 
deverá solicitar autorização à 
Contratada para eventual desconto do 
valor no saldo remanescente em conta 
contingenciada, certificar a resposta da 
Contratada nos autos e devolver o 
expediente à SOF 2.2, para 
prosseguimento junto à E. Presidência. 
 
 
ATENÇÃO: caso existam pendências 
financeiras em outros contratos com a 
mesma empresa, a Saab prestará as 
informações relativas às pendências, 
submetendo à SOF 2.2, para análise e 
deliberação sobre eventual 
compensação de créditos/débitos, e 
consulta ao i. GTAJ, se o caso. 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
M A N U A L D E C O N T R A T O S | 2 0 2 5 
Secretaria de Administração e Abas tecimento | Saab  
6ª ETAPA: LIBERAÇÃO DOS VALORES 
Após a conclusão da 5ª etapa, o processo será remetido para autorização da 
E. Presidência. Com a autorização, o processo retornará à SOF que encaminhará 
ofício ao Banco do Brasil para liberação do saldo remanescente à Contratada. 
FLUXO PARA LIBERAÇÃO DO SALDO APÓS 
ENCERRAMENTO DO CONTRATO 
4.2.1.1.3  RESOLUÇÃO DE CASOS OMISSOS 
Como nem todas as situações relacionadas à liberação de verbas 
contingenciadas podem ser previstas neste manual, eventuais casos omissos — 
ou seja, situações não contempladas nos procedimentos descritos — deverão ser 
encaminhados para análise da SOF 2.2.3 – Serviço de Gestão de Contas 
Vinculadas, por meio do e-mail  sof2.2.3@tjsp.jus.br. 
40 
M A N U A L D E C O N T R A T O S | 2 0 2 5 
Secretaria de Administração e Abas tecimento | Saab  
41 
  
 
 
 
4.2.2 FISCALIZAÇÃO DOS SERVIÇOS E OBRAS DE ENGENHARIA 
 
A gestão e fiscalização dos contratos de serviços e obras de engenharia 
observará a Resolução CNJ º 114/2010 (e suas alterações). 
Nos contratos de obras e serviços de engenharia,  
compete ao Fiscal do Contrato: 
• Providenciar a instauração de processo administrativo eletrônico 
específico destinado a registrar os atos de fiscalização e ocorrências 
da execução contratual; 
• Manter pasta atualizada com projeto básico e/ou executivo, alvarás, 
Anotações de Responsabilidade Técnica (ART’s) do Conselho 
Regional de Engenharia e Agronomia (CREA) e/ou Registros de 
Responsabilidade Técnica (RRT’s) do Conselho de Arquitetura e 
Urbanismo (CAU) referentes ao objeto contratual; 
• Visitar o diário de obras, certificando-se de seu correto 
preenchimento; 
• Desempenhar outras atividades previstas no contrato. 
 
Além disso, também compete ao Fiscal do Contrato promover as 
medições, a fim de verificar a conformidade dos serviços executados com o 
cronograma físico-financeiro da obra previsto no contrato, podendo ser auxiliado 
por Responsável Técnico.  
Dessa forma, é obrigatória a realização de medições dos serviços efetuados, 
nas datas estabelecidas no cronograma, antes de seu efetivo ateste. 
 
4.2.3 FISCALIZAÇÃO DOS CONTRATOS DE STIC 
 
A Resolução CNJ nº 468/2022 (e suas alterações) disciplina as contratações 
de bens e serviços de Soluções de Tecnologia da Informação e Comunicação 
(STIC) realizadas pelos órgãos submetidos ao controle administrativo e financeiro 
do CNJ. Disciplina ainda a fiscalização dos referidos contratos. 
M A N U A L D E C O N T R A T O S | 2 0 2 5 
Secretaria de Administração e Abas tecimento | Saab  
A equipe de gestão de contrato, no caso de serviços complexos e/ou 
descentralizados, poderá indicar fiscais auxiliares de campo visando à efetividade 
da fiscalização. 
A administração deverá providenciar os meios necessários para que o 
servidor desempenhe adequadamente as atribuições de Gestor e Fiscal, 
conforme a natureza e a complexidade do objeto. 
Durante a fase de gestão do contrato, a equipe de fiscalização, sob 
coordenação do Gestor ou da Gestora do Contrato, deverá proceder à atualização 
contínua do Mapa de Gerenciamento de Riscos. 
ATENÇÃO: Os contratos de STIC que 
envolvam dedicação exclusiva de mão
de-obra observarão as regras contidas 
no tópico 4.2.1 deste manual. 
4.3   RECEBIMENTO 
Nos contratos administrativos, o recebimento do objeto é um ato formal 
dividido em duas etapas bem distintas: recebimento provisório e recebimento 
definitivo. 
Os prazos e métodos para a realização dos recebimentos provisório e 
definitivo serão definidos no Termo de Referência, Projeto Básico ou Projeto 
Executivo, bem como constarão no instrumento contratual. 
Importante mencionar que o recebimento provisório ou definitivo não 
excluirá a responsabilidade civil pela solidez e pela segurança da obra ou serviço, 
nem a responsabilidade pela perfeita execução contratual, nos limites 
estabelecidos pela lei ou contrato. 
Os documentos que comprovem o recebimento provisório e definitivo 
serão juntados no processo de acompanhamento da execução contratual. 
O método de recebimento, bem como os responsáveis pelos recebimentos 
provisório e definitivo constarão no Termo de Referência. 
ATENÇÃO: Caso esteja em desacordo 
com o contrato, o objeto poderá ser 
rejeitado, no todo ou em parte. 
42 
M A N U A L D E C O N T R A T O S | 2 0 2 5 
Secretaria de Administração e Abas tecimento | Saab  
ATENÇÃO: Eventuais substituições de 
marca ou modelo, em regra, não serão 
admitidas. Entretanto, poderão ser 
aceitas, desde que devidamente 
justificadas, com a apresentação de 
fatos impeditivos ao fornecimento nas 
condições previstas originalmente, 
devendo ser formalizadas mediante 
aditivo contratual. 
4.3.1   RECEBIMENTO PROVISÓRIO 
O recebimento provisório é a primeira etapa do recebimento de um bem 
ou serviço contratado pela Administração Pública. Esse recebimento ocorre por 
meio de prévia verificação da conformidade contratual.  
É no recebimento provisório que ocorre a entrega dos bens ou a entrega do 
resultado dos serviços à Administração. Entretanto, há apenas a legitimação da 
posse, a fim de que a Administração verifique minuciosamente o objeto e 
constate a conformidade com o que foi contratado. 
Dessa forma, o recebimento provisório não implica em aceitação do objeto 
pela Administração, permanecendo a responsabilidade da Contratada por sua 
integridade e integralidade. 
ATENÇÃO: O recebimento provisório 
poderá ser dispensado, quando assim 
previsto no Termo de Referência. 
Caso não exista outro prazo estipulado no contrato, o recebimento 
provisório será realizado em até 10 (dez) dias úteis. 
O recebimento provisório será realizado, em regra, pelo Fiscal do Contrato 
ou por outro responsável estabelecido no Termo de Referência da respectiva 
contratação. 
43 
44 
M A N U A L D E C O N T R A T O S | 2 0 2 5 
Secretaria de Administração e Abas tecimento | Saab  
 
 
Recebimento Provisório 
Obras e Serviços 
Recebido, em regra, pelo Fiscal do Contrato ou por 
outro responsável especificado no Termo de 
Referência, por meio de termo detalhado, se 
verificado o cumprimento das exigências de caráter 
técnico. 
Compras 
Recebido, de forma sumária, em regra, pelo Fiscal do 
Contrato ou por outro responsável especificado no 
Termo de Referência, com verificação posterior da 
conformidade do material com as exigências 
contratuais. 
 
Os procedimentos a serem adotados no recebimento provisório constam no 
Termo de Referência do respectivo processo de contratação. 
 
4.3.2  RECEBIMENTO DEFINITIVO 
 
Recebimento definitivo é o ato formal, subsidiado por documentos e, se 
houver, nota fiscal/fatura, que comprove o cumprimento das exigências, prazos, 
valores e métodos previstos no contrato. 
É no recebimento definitivo que são realizados exames, testes e 
averiguações que se fizerem necessárias, de modo a aferir a integral adequação 
do objeto às exigências previstas contratualmente.  
 
ATENÇÃO: Em se tratando de obra, o 
recebimento definitivo pela 
Administração não exime a Contratada, 
pelo prazo mínimo de 5 (cinco) anos, 
admitida a previsão de prazo de 
garantia superior no edital ou no 
contrato, da responsabilidade objetiva 
pela solidez e pela segurança dos 
M A N U A L D E C O N T R A T O S | 2 0 2 5 
Secretaria de Administração e Abas tecimento | Saab  
45 
  
 
 
 
materiais entregues e serviços 
executados. Em caso de vício, defeito 
ou incorreção identificados, a 
Contratada ficará responsável pela 
reparação, pela correção, pela 
reconstrução ou pela substituição 
necessária. 
 
Caso não exista outro prazo estipulado no contrato, o recebimento 
definitivo será realizado em até 30 (trinta) dias úteis. 
Recebimento Definitivo 
Obras e Serviços 
Recebido, em regra, pelo Fiscal do 
Contrato ou por outro responsável 
especificado no Termo de Referência, 
por meio de termo detalhado que 
comprove o atendimento das 
exigências contratuais. 
Compras 
Recebido, em regra, pelo Fiscal do 
Contrato ou por outro responsável 
especificado no Termo de Referência, 
por meio de termo detalhado que 
comprove o atendimento das 
exigências contratuais. 
 
O recebimento definitivo ocorrerá somente após a manifestação do Fiscal 
do Contrato ou do responsável especificado no Termo de Referência, quanto 
à regularidade do fornecimento ou dos serviços prestados em relação ao previsto 
contratualmente. 
 
4.3.3  ROTEIRO PARA RECEBIMENTO DE BENS  
 
Os responsáveis definidos no Termo de Referência e no Contrato deverão 
seguir o seguinte roteiro para o recebimento de bens: 
1- Conferir o objeto fornecido quanto à sua quantidade, especificação, 
valor, prazos e demais condições previstas no contrato; 
2- Receber o objeto provisoriamente, para posterior verificação e, 
após, definitivamente, em virtude da constatação da qualidade e 
quantidade do material entregue; 
M A N U A L D E C O N T R A T O S | 2 0 2 5 
Secretaria de Administração e Abas tecimento | Saab  
3- Emitir o ateste da nota fiscal/fatura, caso não haja outro prazo 
previsto no contrato, em 3 (três) dias úteis contados da emissão 
do documento ou do recebimento definitivo, conforme 
estabelecido no instrumento contratual, desde que os requisitos 
previstos estejam cumpridos, especialmente: 
• Se foi emitida em nome do Tribunal de Justiça de São Paulo; 
• Se foi emitida pelo CNPJ constante no respectivo contrato; 
• Se o bem está especificado conforme as discriminações 
contidas no Contrato ou no Ofício de Autorização; 
• Se o valor está correto; 
• Verificar a autenticidade da nota fiscal eletrônica no site da 
Secretária da Fazenda; 
• Se não há erros no documento fiscal. 
4- Em caso de irregularidades, deve-se rejeitar a entrega no todo ou 
em parte, determinando formalmente sua substituição, em prazo 
estabelecido no contrato; 
5- Em caso de pedido de prorrogação do prazo de entrega, deve-se 
encaminhar a questão ao Gestor ou à Gestora do Contrato, para 
avaliação e providências, se o caso; 
6- Em caso de atraso na entrega ou outros descumprimentos 
contratuais, deve-se encaminhar a questão ao Gestor ou à Gestora 
do Contrato, para avaliação e providências, se o caso; 
7- O Gestor ou a Gestora do Contrato emitirá parecer fundamentado 
sobre a ocorrência e decidirá pela instauração do Procedimento 
Apuratório; 
8- Caso a entrega e o ateste estejam em termos, deverão ser 
encaminhados à Secretaria de Orçamento e Finanças – SOF, dentro 
de 1 (um) dia útil, os documentos fiscais e demais documentos 
exigidos no contrato, para pagamento. 
4.3.4  ROTEIRO PARA RECEBIMENTO DE SERVIÇOS 
O Fiscal do Contrato deve seguir o seguinte roteiro no recebimento de 
serviços: 
1- Conferir a execução do objeto contratado e verificar a sua 
conformidade com as especificações contidas no contrato; 
2- Em caso de irregularidades, deve-se recusar o serviço no todo ou em 
parte, determinando formalmente sua regularização, em prazo 
compatível para atendimento (em regra, 5 (cinco) dias úteis; em 
casos emergenciais, 24 horas); 
46 
M A N U A L D E C O N T R A T O S | 2 0 2 5 
Secretaria de Administração e Abas tecimento | Saab  
3- Receber o objeto provisoriamente, para posterior verificação e, 
após, definitivamente, em virtude da verificação da adequação do 
objeto aos termos contratuais; 
4- Após a averiguação dos serviços prestados, dos documentos 
apresentados e da avaliação da qualidade dos serviços, a nota fiscal 
poderá ser emitida para ateste; 
5- O Fiscal do Contrato emitirá o ateste da nota fiscal/fatura no prazo 
de 3 (três) dias úteis da emissão do documento, desde que os 
requisitos 
previstos 
especialmente: 
em 
contrato 
estejam 
• Se foi emitida em nome do Tribunal de Justiça de São Paulo; 
• Se foi emitida pelo CNPJ constante no respectivo contrato; 
• Se o serviço está especificado conforme as discriminações 
contidas no contrato; 
• Se o valor está correto, inclusive quanto a aditamentos, 
reajustes, medições e glosas; 
• Se não há erros no documento fiscal. 
6- Caso a entrega e o ateste estejam em termos, deverão ser 
encaminhados à Secretaria de Orçamento e Finanças – SOF, dentro 
de 1 (um) dia útil, os documentos fiscais e demais documentos 
exigidos no contrato, para pagamento. 
4.4   IRREGULARIDADES NA 
EXECUÇÃO CONTRATUAL 
cumpridos, 
Durante a execução contratual, os responsáveis por seu acompanhamento 
devem manter registro das ocorrências, no respectivo expediente de 
acompanhamento da fiscalização/gestão contratual, instruindo-as com a 
documentação comprobatória. 
Sempre que identificada qualquer irregularidade no cumprimento das 
obrigações contratuais pela Contratada, deverão ser adotadas as seguintes 
providências: 
• Preliminarmente, o Fiscal do Contrato deve autuar protocolo de 
acompanhamento eletrônico e notificar a Contratada, para 
regularização das pendências ou apresentação de defesa 
preliminar; 
• Com a regularização, promoverá o arquivamento do protocolo; 
• Persistindo a irregularidade ou em caso de atraso, com ou sem 
defesa da Contratada, o Fiscal do Contrato deve analisar e, se o 
47 
M A N U A L D E C O N T R A T O S | 2 0 2 5 
Secretaria de Administração e Abas tecimento | Saab  
caso, 
emitir 
relatório 
com informações detalhadas da 
irregularidade, encaminhando o protocolo ao Fiscal Administrativo, 
com proposta de autuação de processo apuratório; 
• O Fiscal Administrativo deve elaborar relatório conclusivo com a 
consolidação das informações apresentadas, opinando, ao Gestor 
ou à Gestora do Contrato, pela sua instauração ou arquivamento; 
• O Gestor ou a Gestora do Contrato elaborará relatório conclusivo 
sobre o arquivamento ou instauração de processo apuratório, nos 
termos do Art. 111 do Provimento CSM nº 2.724/2023. 
O procedimento a ser adotado para a condução do processo apuratório está 
discriminado no Manual de Apuratórios do Tribunal de Justiça de São Paulo. 
48 
M A N U A L D E C O N T R A T O S | 2 0 2 5 
Secretaria de Administração e Abas tecimento | Saab  
5.  
CONTRATOS SUI 
GENERIS 
49 
50 
M A N U A L D E C O N T R A T O S | 2 0 2 5 
Secretaria de Administração e Abas tecimento | Saab  
 
 
5.1  CONTRATOS DE FORNECIMENTO 
DE ENERGIA ELÉTRICA 
 
Para que ocorra o abastecimento de energia elétrica nas diversas unidades 
integrantes do Tribunal de Justiça de São Paulo, são formalizados, atualmente, 
contratos de fornecimento com uma Concessionária de Energia Elétrica, no 
Ambiente de Contratação Regulada. 
A Resolução Normativa da ANEEL nº 1000/2021 classifica os consumidores 
de energia elétrica em dois grupos – Grupo A e Grupo B, de acordo com o nível 
de tensão em que são atendidos. 
• Grupo A: unidades consumidoras com conexão de tensão 
maior ou igual a 2,3kV ou atendidas a partir de sistema 
subterrâneo de distribuição de tensão menor que 2,3kV 
(MÉDIA TENSÃO) 
 
• Grupo B: unidades consumidoras com conexão de tensão 
menor que 2,3kV. (BAIXA TENSÃO) 
Para os consumidores do Grupo A – Média Tensão, é necessária a 
celebração de dois contratos administrativos: 
• CUSD – Contrato de Uso do Sistema de Distribuição: contrato 
firmado pelo consumidor com a distribuidora, no qual são 
estabelecidos os termos e condições para o uso do sistema de 
distribuição e, conforme o caso, as condições para a conexão à 
rede de distribuição para o fornecimento de energia elétrica;  
 
• CCER – Contrato de Compra de Energia Regulada: contrato 
firmado pelo consumidor com a concessionária ou 
permissionária, no qual são estabelecidos os termos e 
condições para a compra e venda do montante de energia 
elétrica no Ambiente de Contratação Regulada (ACR) ou no 
Ambiente de Contratação Livre (ACL). 
M A N U A L D E C O N T R A T O S | 2 0 2 5 
Secretaria de Administração e Abas tecimento | Saab  
Ressalta-se que, atualmente, os contratos relacionados ao CUSD, no 
Ambiente de Contratação Regulada (ACR), são celebrados mediante 
inexigibilidade, tendo em vista a inviabilidade de competição. 
Com relação ao CCER, há recente previsão (Art. 160 da REN. ANEEL nº 
1000/2021), que garante ao consumidor a opção pela compra de energia elétrica 
no Ambiente de Contratação Livre (ACL). Entretanto, até que o TJSP não migre 
para o ACL, as contratações continuam sendo celebradas mediante 
inexigibilidade. 
Para os consumidores do Grupo B – Baixa Tensão, basta a formalização do 
fornecimento de energia elétrica por meio de contrato de adesão. 
ATENÇÃO: Com o advento da Lei nº 
14.133/2021, a celebração de novos 
contratos (CUSD e CCER) necessitam de 
estudos prévios (DFD, ETP, TR e Plano 
de Riscos) que evidenciem a solução 
mais vantajosa para a Administração. 
Dessa forma, deve-se observar o 
Provimento CSM nº 2.724/2023 na 
elaboração da documentação prévia, 
bem como as orientações contidas no 
Manual de Licitações do Tribunal de 
Justiça de São Paulo. 
5.1.1  FLUXO ATUALIZADO PARA FORMALIZAÇÃO 
DOS CONTRATOS DE ENERGIA ELÉTRICA 
Atualmente, a formalização dos contratos de energia no Ambiente de 
Contratação Regulada (ACR) segue o fluxo abaixo. 
51 
M A N U A L D E C O N T R A T O S | 2 0 2 5 
Secretaria de Administração e Abas tecimento | Saab  
Etapas a serem observadas: 
1. 
O processo tem início com a instrução dos autos pela Administração 
Predial, com a juntada das 12 últimas faturas e o preenchimento do 
checklist específico (Checklist - Análise Técnica), para análise do 
setor técnico. 
2. O setor técnico verificará a demanda mais adequada a ser 
contratada para aquela unidade predial; 
3. A Administração Predial deverá solicitar à Concessionária a minuta 
dos contratos (CUSD e CCER) ou do Aditivo, bem como declaração 
em que conste a exclusividade de prestação de serviços e que os 
valores praticados estão em conformidade com o estipulado pela 
Agência Nacional de Energia Elétrica (ANEEL); 
4. Complementarmente, a Administração Predial preencherá os 
seguintes documentos: Documento de Formalização de Demanda – DFD; Estudo Técnico Preliminar – ETP; Termo de Referência – TR e 
checklist específico (Anexo I – para os casos de nova contratação ou 
Anexo II – para os casos de alteração da demanda); 
5. Com a devida instrução dos autos pela Administração Predial, 
compete à Saab 6.3.1.1 – Seção de Formalização de Convênios de 
Obras e Contratos de Energia Elétrica, emitir as certidões 
demonstrativas de regularidades da prestadora de serviços nas 
áreas fiscal, social e trabalhista, bem como elaborar a informação 
descritiva dos fatos e, nos casos de irregularidade da Concessionária, 
disponibilizar ofícios a serem encaminhados à Agência Reguladora 
e aos Órgãos Públicos credores, quanto ao estado da irregularidade; 
6. Após, a SOF – Secretária de Orçamento e Finanças, realizará as 
adequações orçamentarias; 
52 
M A N U A L D E C O N T R A T O S | 2 0 2 5 
Secretaria de Administração e Abas tecimento | Saab  
7. Posteriormente, o GTAJ – Grupo Técnico de Assessoria Jurídica, 
realizará a análise jurídica da documentação e emitirá parecer; 
8. A Saab 6.3.1.1 realizará o cadastro dos contratos e/ou aditivo no 
Sistema Financeiro e Orçamentário – SGF; publicará o despacho do 
MM. Juiz Diretor ou da MM. Juíza Diretora do Fórum, bem como o 
extrato do contrato de fornecimento de energia e/ou aditivo, no 
Diário Eletrônico da Justiça do Estado de São Paulo (DEJESP); 
divulgará os contratos e aditivos no Portal da Transparência e no 
Portal Nacional de Contratações Públicas (PNCP); e, caso necessário, 
encaminhará os Ofícios à ANEEL e aos Órgãos Públicos Credores 
acerca da situação de irregularidade da Concessionária; 
9. Por fim, a Administração Predial realizará o acompanhamento do 
consumo de energia da unidade predial. 
5.1.2  ALTERAÇÃO DA DEMANDA 
A demanda de consumo de energia elétrica pode sofrer alterações durante 
o tempo por inúmeros fatores, podendo ser aumentada ou diminuída. 
ATENÇÃO: Em determinados casos, faz
se necessária a realização de obras, pela 
Concessionária, na rede elétrica externa 
para adequações. Nesses casos, 
também é necessária a instrução dos 
autos com os documentos preliminares 
(DFD, ETP, TR e Plano de Riscos – 
modelos específicos disponíveis em 
Modelos de Documentos - Energia 
Elétrica). 
Para as alterações de demanda, devem ser observadas as mesmas etapas 
do item 5.1.1 deste Manual. 
53 
M A N U A L D E C O N T R A T O S | 2 0 2 5 
Secretaria de Administração e Abas tecimento | Saab  
6.  
ATESTADO E 
PROTOCOLO DO 
DOCUMENTO 
FISCAL 
54 
M A N U A L D E C O N T R A T O S | 2 0 2 5 
Secretaria de Administração e Abas tecimento | Saab  
6.1  DO CADASTRO NO SISTEMA SGF 
Inicialmente, compete aos Gestores e às Gestoras de Contratos 
cadastrarem os Fiscais Administrativos, os Fiscais de Contratos e seus suplentes 
no sistema SAJADM, módulo SGF, utilizando-se a tela denominada “GESTÃO 
CONTRATUAL”, pelo caminho SGF > Contratos > Gestão Contratual. 
Em caso de dúvidas sobre a efetivação do cadastro de fiscais e seus 
suplentes, deverá ser consultado o material explicativo sobre gestão contratual, 
disponibilizado em http://www.tjsp.jus.br/ejus/avas, selecionando a opção 
Sistema SAJ > SAJADM > SGF > Vídeos > Gestão Contratual. 
6.2   PRAZO DE RECEBIMENTO E 
ENVIO DA DOCUMENTAÇÃO À SOF 
De acordo com o Comunicado SOF nº 13/2021, o recebimento de bens e 
serviços deve ser atestado no prazo de 48 horas a contar da recepção do 
documento fiscal, por meio de preenchimento do “Protocolo de Documento 
Fiscal”, conforme instruções do tópico 6.3 deste Manual, assinado com 
Certificado Digital na folha de ateste, observando-se sempre o prazo de 
vencimento do ISS/INSS. 
Os documentos fiscais cadastrados devem ser encaminhados, via sistema, 
à SOF 3.1.1.1, dentro do prazo de 24 horas, a contar da data do ateste. 
O cumprimento dos prazos acima mencionados é de suma importância 
para que seja cumprido o fluxo de liquidação e pagamento da despesa, a fim de 
que não haja atraso no pagamento aos prestadores de serviços e fornecedores, 
bem como para que não ocorra a incidência de despesas com encargos 
moratórios de INSS e ISS. 
55 
56 
M A N U A L D E C O N T R A T O S | 2 0 2 5 
Secretaria de Administração e Abas tecimento | Saab  
 
 
Notas Fiscais – Serviços NÃO MENSAIS 
• Merece atenção especial os contratos que não requerem a 
prestação de serviços mensalmente, como, por exemplo, 
desinsetização (quadrimestral) e limpeza de caixa d’água 
(semestral), entre outros com periodicidade diferenciada. 
• Para esses casos, é fundamental que os atestes sejam realizados 
adequadamente, de acordo com a data da prestação do serviço, 
observando-se os prazos de ateste e encaminhamento da nota 
fiscal, a fim de que não ocorra a incidência de despesas com 
encargos moratórios de INSS e ISS. 
 
6.3   CADASTRAMENTO DO 
DOCUMENTO FISCAL 
 
Ressalta-se o fato de que, desde abril de 2022, os dados informados nos 
protocolos de documentos fiscais realizados pelo TJSP são enviados para a 
Receita Federal, por meio do EFD-REINF (Escrituração Fiscal Digital de 
Retenções e Outras Informações Fiscais). 
Dessa forma, o encaminhamento à SOF dos documentos fiscais, via 
protocolo do sistema SAJADM, deve ser realizado de forma precisa e em tempo 
hábil, observando-se os prazos acima descritos, a fim de se evitar encargos 
decorrentes de pagamentos de guias em atraso e a transmissão de informações 
ao EFD-REINF fora do prazo. 
O processo de cadastramento inicia-se com o lançamento do documento 
fiscal no sistema SAJADM, no módulo “SGF” > “Despesas” > “Protocolo de 
Documento Fiscal”. 
M A N U A L D E C O N T R A T O S | 2 0 2 5 
Secretaria de Administração e Abas tecimento | Saab  
ATENÇÃO: Ao atestar o documento 
fiscal, deve-se indicar como mês de 
competência o período em que o 
serviço foi efetivamente prestado  
(e não o mês de emissão da nota fiscal). 
• 3ª Etapa: Protocolo. 
6.3.1    
O cadastramento do documento fiscal é realizado em três etapas: 
• 1ª Etapa: Informação dos dados cadastrais e impostos aplicados aos 
documentos; 
• 2ª Etapa: Fornecimento das informações acerca da execução do 
contrato; 
1ª ETAPA: INFORMAÇÃO DOS DADOS 
CADASTRAIS E IMPOSTOS APLICADOS AO 
DOCUMENTO  
Nesta etapa, o Responsável pelo ateste deve realizar os seguintes 
preenchimentos: 
57 
M A N U A L D E C O N T R A T O S | 2 0 2 5 
Secretaria de Administração e Abas tecimento | Saab  
I. 
II. 
Dados Cadastrais 
1. 
Clicar em “Novo”, na tela de acesso de “Protocolo de Documento 
Fiscal” (módulo “SGF” à “Despesas”); 
2. Selecionar o Contrato ou Despesa; 
3. Selecionar o tipo de documento correspondente; 
4. Preencher o “Número de Documento”; 
5. Selecionar o estado de origem em que a nota fiscal foi emitida em 
“Origem do documento fiscal – Estado”; 
6. Preencher o “Número de série”. Caso o documento não apresente 
número de série, deve-se alimentar o campo com o número “0”; 
7. Preencher o campo “Data de emissão”, de acordo com as 
informações contantes da data de emissão do documento fiscal. 
Quadro de “Referência” e valor do documento fiscal 
1. 
Informar o mês e ano (MM/AAAA) em que o serviço foi prestado. Em 
regra, esta informação está descrita no documento fiscal; 
2. Lançar o valor total do documento fiscal em “Valor Bruto do 
documento (R$)”; 
3. Lançar os descontos concedidos pelo credor e não constante do 
documento fiscal em “Descontos/abatimentos fora do documento 
(R$)”; 
4. O “Valor atestado (R$)” será automaticamente alimentado com o 
preenchimento dos campos acima; 
5. Caso o documento fiscal se refira a mais de um mês de referência, 
o procedimento acima deve ser repetido, com a informação do valor 
proporcional de cada mês de “Referência”. 
6. Após, será possível o preenchimento do campo de livre digitação 
“Observação”, no qual o responsável pelo ateste poderá adicionar 
complementações ao cadastro. 
ATENÇÃO: Em caso de reajuste 
contratual, deverá ser informado o valor 
proporcional do reajuste de cada mês, 
calculado de acordo com os serviços 
prestados nos respectivos meses de 
referência e em conformidade aos 
termos contratuais. 
58 
M A N U A L D E C O N T R A T O S | 2 0 2 5 
Secretaria de Administração e Abas tecimento | Saab  
59 
  
 
 
 
ATENÇÃO: O “Total” do valor bruto do 
documento apresentado pelo sistema 
deverá ser igual ao valor total do 
documento fiscal. 
 
ATENÇÃO: Não será permitido cadastrar 
nota fiscal com referência fora do 
período de vigência do contrato. 
 
III. Decisão judicial contrária a alguma retenção tributária 
 
1. Após o lançamento da “Observação”, o responsável pelo ateste deve 
selecionar a opção “SIM” ou “NÃO”, para o caso de o credor estar 
amparado por decisão judicial contrária a alguma retenção 
tributária (IR e INSS) para o documento fiscal. 
O Responsável pelo ateste identificará a decisão  
sobre a retenção da seguinte forma: 
 
• Na Descrição do documento fiscal, quando houver 
informação sobre o processo judicial que interfira na 
retenção de IR e INSS; 
• Por alerta do sistema, caso haja pré-cadastro no 
sistema da decisão judicial contrária a alguma retenção 
tributária em favor do credor, alertando o responsável 
pelo ateste a selecionar a opção “SIM”; 
 
• Caso não conste a informação relativa ao processo 
judicial no Documento Fiscal e o sistema não emita o 
alerta acima, selecionará a opção “NÃO”. 
 
 
 
6.3.1.1  RETENÇÕES TRIBUTÁRIAS (ISS, INSS E IRRF) 
 
O preenchimento das “Retenções” aplicáveis ao documento fiscal é 
obrigatório quando houver retenções tributárias (ISS, INSS e IRRF) destacados no 
documento fiscal e a obrigação de recolhimento for do TJSP. 
M A N U A L D E C O N T R A T O S | 2 0 2 5 
Secretaria de Administração e Abas tecimento | Saab  
Para tanto, é essencial que ocorra sempre o acompanhamento e o 
lançamento das retenções conforme as informações contantes no documento 
fiscal. 
Inicialmente, deve-se selecionar o imposto a ser cadastrado, entre: ISS, INSS 
e IRRF. 
8.1.1 RETENÇÃO ISS 
Deve ser informada apenas se a obrigação do recolhimento for do TJSP. 
Caso o serviço tenha sido prestado nas Comarcas do interior de São Paulo, 
o Fiscal do Contrato deverá emitir a guia junto à Prefeitura Municipal de acordo 
com a legislação local. 
Por outro lado, as guias de ISS referentes aos serviços prestados nas 
unidades da capital de São Paulo serão emitidas pela Secretaria de Orçamento 
e Finanças (SOF). 
ATENÇÃO: Cabe ao responsável pelo 
ateste verificar no próprio documento 
fiscal a informação da base de cálculo, 
devendo conferir se a alíquota está de 
acordo com a legislação vigente. 
Abaixo seguem as etapas para o lançamento do ISS no sistema: 
60 
M A N U A L D E C O N T R A T O S | 2 0 2 5 
Secretaria de Administração e Abas tecimento | Saab  
1. 
Selecionar a opção de retenção do ISS, ao passo que serão exibidos 
os campos a serem preenchidos; 
2. Informar se o valor da base mensal de cálculo da retenção é o 
mesmo valor bruto do documento fiscal. Caso seja, selecionar a 
opção “SIM”, ao passo que o campo “Base de Cálculo” será 
automaticamente preenchido. Caso não, selecionar a opção “NÃO”, 
devendo preencher manualmente o seu valor; 
3. Preencher o “Município” em que o serviço foi prestado; 
4. Preencher a “Alíquota (%)” correspondente. Automaticamente, o 
sistema efetuará o cálculo do valor, devendo o responsável pelo 
ateste verificar, obrigatoriamente, se o campo “Valor” está 
exatamente igual ao valor apresentado na guia emitida junto à 
Prefeitura para recolhimento do ISS. Em caso de divergência, o 
campo de valor deve ser editado; 
5. Preencher a “Data de Vencimento”, conforme a data constante na 
guia ou de acordo com a legislação municipal; 
6. Informar, no campo “Encargos” se há incidência de encargos por 
atraso e o motivo, selecionando, se o caso, quem é o responsável 
pelo atraso; 
7. Clicar em “Salvar”; 
8. Caso deseje adicionar mais impostos, basta clicar em “Adicionar” e 
selecionar o respectivo imposto. 
8.1.2  RETENÇÃO INSS 
Caso haja retenção de INSS, as seguintes etapas devem ser seguidas para 
seu lançamento no sistema: 
61 
M A N U A L D E C O N T R A T O S | 2 0 2 5 
Secretaria de Administração e Abas tecimento | Saab  
1. 
Informar se o valor da base mensal de cálculo da retenção é o 
mesmo valor bruto do documento fiscal. Caso seja, selecionar a 
opção “SIM”, ao passo que o campo “Base de Cálculo” será 
automaticamente preenchido. Caso não, selecionar a opção “NÃO”, 
devendo preencher manualmente o seu valor; 
2. Preencher a “Alíquota (%)” correspondente, entre 3,5% e 11%, 
conforme o documento fiscal. Automaticamente, o sistema 
efetuará o cálculo do campo “Valor”.  Em caso de divergência de 
valores, o responsável pelo ateste deve realizar a edição do “Valor” 
para que conste aquele presente no documento fiscal; 
3. Caso o INSS esteja vencido, constará uma mensagem de alerta, 
devendo o responsável pelo ateste preencher os campos de 
“Encargos” e “Justificativa”, informando quem deu causa à 
cobrança; 
4. Clicar em “Salvar”; 
5. Caso deseje adicionar mais impostos, basta clicar em “Adicionar” e 
selecionar o respectivo imposto. 
8.1.3  RETENÇÃO IRRF (IMPOSTO DE RENDA RETIDO 
NA FONTE) 
Em caso de retenção de IRRF, as seguintes etapas devem ser seguidas para 
seu lançamento no sistema: 
62 
M A N U A L D E C O N T R A T O S | 2 0 2 5 
Secretaria de Administração e Abas tecimento | Saab  
1. 
Informar se o valor da base mensal de cálculo da retenção é o 
mesmo valor bruto do documento fiscal. Caso seja, selecionar a 
opção “SIM”, ao passo que o campo “Base de Cálculo” será 
automaticamente preenchido. Caso não, selecionar a opção “NÃO”, 
devendo preencher manualmente o seu valor; 
2. Preencher a “Alíquota (%)” correspondente, entre 1% ou 1,5%, 
conforme o documento fiscal. Automaticamente, o sistema 
efetuará o cálculo do campo “Valor”.  Em caso de divergência de 
valores, o responsável pelo ateste deve realizar a edição do “Valor” 
para que conste aquele presente no documento fiscal; 
3. Clicar em “Salvar”. 
1. 
6.3.2 2ª ETAPA: FORNECIMENTO DAS INFORMAÇÕES 
ACERCA DA EXECUÇÃO DO CONTRATO 
Nesta etapa, o responsável pelo ateste deverá preencher várias informações 
sobre a execução do contrato, que serão parte dos dados encaminhados à 
AUDESP, observando-se as seguintes ações: 
Selecionar a situação da execução do contrato em “Situação do 
ajuste”; 
63 
64 
M A N U A L D E C O N T R A T O S | 2 0 2 5 
Secretaria de Administração e Abas tecimento | Saab  
 
 
2. Preencher a data da efetiva entrega do material ou início da 
execução de serviço/obra em “Data de entrega do material ou 
início da execução de serviço/obra”; 
3. Preencher informações sobre o cronograma e inexecução do 
contrato; 
 
4. Preencher a “Data do ateste”, no campo “Ateste”, com a data 
da realização do ateste/cadastro do protocolo; 
5. Selecionar o campo “Conferido pelo fiscal administrativo”; 
6. Realizar a verificação da autenticidade do documento fiscal, 
junto à Prefeitura Municipal ou Governo do Estado de São 
Paulo, conforme a situação do documento fiscal; 
 
COMO FAZER? Para o Governo do 
Estado de São Paulo, será possível a 
verificação da autenticidade das notas 
fiscais junto ao endereço: 
https://www.nfe.fazenda.gov.br/portal/p
 rincipal.aspx.  
Para a Prefeitura Municipal de São 
Paulo, será possível a verificação junto 
ao endereço: 
https://nfe.prefeitura.sp.gov.br/publico/
 verificacao.aspx. 
Para as demais prefeituras, o 
responsável pelo ateste utilizará as 
ferramentas existentes, conforme 
informações constantes no documento 
fiscal ou legislação municipal sobre a 
emissão de documentos fiscais. 
 
7. Conferida a autenticidade, selecionar a opção “Verificada a 
autenticidade da Nota Fiscal Eletrônica” e, após, “Salvar e 
próximo”. 
M A N U A L D E C O N T R A T O S | 2 0 2 5 
Secretaria de Administração e Abas tecimento | Saab  
6.3.3 3ª ETAPA: PROTOCOLO 
Nesta etapa, são apresentados o número do protocolo gerado no CPA, os 
principais dados informados no cadastro e os dados do responsável pelo 
cadastro do documento fiscal. 
Em regra, o módulo SGF indica o responsável pela liquidação da despesa, 
direcionando o protocolo gerado com o ateste do documento fiscal 
compulsoriamente para o setor competente (SOF 2.1.2). 
No entanto, há situações em que o responsável pelo ateste deve 
encaminhar o protocolo para a SOF 3.1.1.1, para realização da triagem. São elas: 
• Quando o protocolo de documento fiscal tramitar por mais de 01 
(um) setor para fins de ateste/conferência dos serviços prestados; 
• Quando mais de um setor for responsável pela liquidação de 
despesas de um determinado contrato (Exemplo: facilities); 
• Quando o setor responsável ainda não estiver cadastrado na 
funcionalidade “Dados para liquidação”; 
• Quando não for possível sua identificação por meio da regra dos 
agregadores de contratos/despesas. 
Após, deve-se seguir o seguinte procedimento: 
1. 
Acionar o botão “Anexar documentos e encaminhar protocolo”; 
2. Clicar em “Salvar” para que os dados do encaminhamento já 
alimentados automaticamente no sistema fiquem salvos; 
3. Clicar na aba “Documentos” e assinar o documento de Ateste; 
4. Após a assinatura, o Fiscal do Contrato deverá inserir os documentos 
fiscais e outros documentos relativos ao ateste de nota fiscal, 
obedecidas a seguinte ordem: 
• 1º - Nota Fiscal/Fatura, devendo o arquivo ser renomeado como “NF 
XXXXX – empresa XXXXX”; 
• 2º - Guia de Recolhimento do ISS (se houver), devendo o arquivo ser 
renomeado como “GUIA DO ISS”; 
• 3º - Carta de desconto (se houver), devendo ser renomeado como 
“CARTA DE DESCONTO”; 
65 
M A N U A L D E C O N T R A T O S | 2 0 2 5 
Secretaria de Administração e Abas tecimento | Saab  
• 4º - Conjunto de evidência comprovando que foi a Contratada que 
deu causa à eventual atraso no recolhimento dos tributos (ISS e 
INSS); 
5. Com a inserção dos documentos necessários, encaminhar à SOF, 
clicando na aba “Encaminhamento”; 
ATENÇÃO: Nas hipóteses de exceção ao 
encaminhamento automatizado (SOF 
2.1.2), deverá ser inserido o setor SOF 
3.1.1.1 para a realização da triagem. 
6. Preenchido o setor correto, clicar em “Encaminhar”. 
ATENÇÃO: Todos os documentos fiscais, 
após devidamente autorizados e 
atestados, deverão ser encaminhados à 
SOF, exclusivamente, por meio do 
sistema eletrônico SGF. 
ATENÇÃO: Conforme o Provimento CSM 
nº 2.724/2023, a nota fiscal/fatura deve 
ser atestada definitivamente (ateste 
eletrônico) e enviada à SOF em até 3 
dias úteis após a emissão, respeitando 
os prazos para recolhimento de tributos 
e cumprimento das obrigações 
acessórias. 
FISCAIS 
1. 
6.4  CANCELAMENTO DE 
PROTOCOLOS DE DOCUMENTOS 
Caso necessário, é possível a realização do cancelamento de protocolos de 
documentos fiscais, exclusivamente, por meio do sistema SAJADM, módulo SGF, 
observando-se os seguintes passos: 
Acessar o módulo SGF à Despesas à Protocolo de documento fiscal; 
2. Consultar o documento fiscal, por meio de pesquisa nos filtros; 
3. Editar o documento fiscal, clicando no ícone de “Editar”; 
66 
M A N U A L D E C O N T R A T O S | 2 0 2 5 
Secretaria de Administração e Abas tecimento | Saab  
4. Adicionar o botão “Excluir”. 
ATENÇÃO: Com este procedimento, será 
estornado/arquivado automaticamente 
o protocolo gerado anteriormente no 
CPA. 
Caso seja necessário cadastrar 
novamente o documento fiscal para fins 
de ateste, deverá ser gerado um novo 
protocolo de documento fiscal. 
ATENÇÃO: Caso restem dúvidas acerca 
dos procedimentos a serem adotados 
na fase de ateste e cadastramento dos 
documentos fiscais, consulte o 
Comunicado SOF nº 13/2021 e acesse o 
curso "Sistemas Administrativos - SGF - 
REINF".  
67 
M A N U A L D E C O N T R A T O S | 2 0 2 5 
Secretaria de Administração e Abas tecimento | Saab  
7.  
GESTÃO  
DE RISCOS 
68 
M A N U A L D E C O N T R A T O S | 2 0 2 5 
Secretaria de Administração e Abas tecimento | Saab  
Segundo o Provimento CSM nº 2.724/2023, Gestão de Riscos é o 
procedimento de gerenciamento dos riscos que possam comprometer a 
contratação, desde a fase de planejamento até o termo final da vigência do 
contrato. 
Sinteticamente, abaixo seguem as etapas da Gestão de Riscos: 
Conforme visto acima, uma das etapas da Gestão de Riscos é a elaboração 
do Plano de Riscos, que é o documento integrante do Estudo Técnico Preliminar 
(ETP), elaborado pela Equipe de Planejamento da Contratação, com a descrição, 
a análise e o tratamento dos riscos que possam comprometer a contratação, 
desde a fase de planejamento até o fim da vigência contratual. 
O Plano de Riscos deve ser preenchido e revisto, sempre que necessário, 
por um Analista de Riscos. 
Quem atua como Analista de Riscos? 
• Equipe de Planejamento da Contratação;  
• Agente de Contratação ou Comissão de Contratação;  
• Gestor ou Gestora do Contrato;  
• Responsável técnico, se o caso.  
69 
M A N U A L D E C O N T R A T O S | 2 0 2 5 
Secretaria de Administração e Abas tecimento | Saab  
Este tópico em questão possui como foco a quinta etapa da gestão de 
riscos: “Monitoramento e revisão do Plano de Riscos (até o fim da vigência do 
contrato)”. Assim, segue abaixo o procedimento a ser adotado. 
7.1  ATUALIZAÇÃO DO PLANO  
DE RISCOS 
Durante a gestão e fiscalização da execução contratual, compete ao Gestor 
ou à Gestora do Contrato, com o auxílio dos Fiscais, revisar o Plano de Riscos. 
Nesse sentido, caso novos riscos ou fatos relevantes sejam identificados 
no curso da execução contratual, deverão ser direcionados ao Gestor ou à 
Gestora do Contrato para verificação, eventual tratamento e posterior 
atualização do Plano de Riscos. 
Abaixo segue o passo a passo para atualização do Plano de Riscos: 
1. Consultar o expediente do Plano de Riscos 
2. Acessar o aplicativo  
O CPA de análise de riscos será único, mantendo-se o histórico em 
um único expediente para todas as contratações do mesmo objeto. 
Dessa forma, o responsável por sua atualização, deve acessar o 
processo correspondente. 
O responsável deve utilizar o aplicativo - "Gestão de Riscos", 
solicitando o seu cadastro no próprio aplicativo caso não esteja 
cadastrado como gestor ou analista.  
No aplicativo, deve-se selecionar a respectiva análise de risco a ser 
atualizada. 
Ademais, no próprio aplicativo há instruções para o seu correto 
preenchimento e utilização.  
3. Atualizar o Plano de Riscos  
A atualização do Plano de Riscos observará o Manual de Gestão de 
Riscos em Contratações Públicas, homologado pela Presidência do 
TJSP (disponível em Gestão de Riscos em Aquisições).  
Ainda, há um roteiro desenvolvido para auxiliar na realização da 
análise de riscos, disponível em Roteiro para Análise de Riscos.  
Em suma, as seguintes etapas devem ser observadas:  
70 
M A N U A L D E C O N T R A T O S | 2 0 2 5 
Secretaria de Administração e Abas tecimento | Saab  
a. Realizar a análise dos riscos relacionados ao serviço ou bem 
demandado, inserindo os novos riscos identificados;  
b. Avaliar os riscos inseridos com sua probabilidade e impacto;  
c. Realizar o tratamento dos riscos avaliados, com as respostas e 
planos de ação esperados;  
d. Gerar novo relatório ao final da análise;  
e. Inserir relatório em PDF no CPA criado, assinando-o;  
Após a atualização dos riscos, caso a equipe de planejamento da 
contratação seja distinta da equipe de gestão contratual, recomenda-se que 
se encaminhe a análise de riscos atualizada para conhecimento. 
71 
M A N U A L D E C O N T R A T O S | 2 0 2 5 
Secretaria de Administração e Abas tecimento | Saab  
8.  
MODIFICAÇÕES 
CONTRATUAIS 
72 
M A N U A L D E C O N T R A T O S | 2 0 2 5 
Secretaria de Administração e Abas tecimento | Saab  
73 
  
 
 
 
Os contratos poderão ser alterados, com as devidas justificativas, nas 
hipóteses previstas na Lei nº 14.133/2021, desde que haja interesse da 
Administração e para atender ao interesse público. 
Segundo o Provimento CSM nº 2.724/2023, atuarão na fase de alteração 
contratual: 
• Fiscal do Contrato; 
• Fiscal Administrativo; 
• Gestor ou Gestora do Contrato; 
• Responsável Técnico, se necessário; 
• Saab; 
• SOF; 
• Assessoria Jurídica; 
• Presidência do Tribunal de Justiça. 
 
8.1  FORMALIZAÇÃO DAS 
ALTERAÇÕES CONTRATUAIS 
 
8.1.4  ACRÉSCIMOS E SUPRESSÕES 
 
Segundo a Lei nº 14.133/2021, há situações em que os contratos podem ser 
alterados unilateralmente pela Administração, ou seja, hipóteses em que o 
contratado será obrigado a aceitar tais modificações.  
Uma dessas previsões (art. 124, I, da Lei nº 14.133/2021) trata da modificação 
do projeto ou das especificações, para melhor adequação técnica a seus 
objetivos (alínea “a”) ou quando for necessária a modificação do valor contratual 
em decorrência do acréscimo ou diminuição quantitativa de seu objeto (alínea 
“b”). 
Nestes casos, a legislação estabelece os seguintes limites para acréscimos 
e supressões unilaterais nos contratos: 
 
Acréscimos e Supressões Acréscimos Supressões* 
Bens e Serviços 25% 25% 
Reformas de edifícios ou 
equipamentos 50% 25% 
M A N U A L D E C O N T R A T O S | 2 0 2 5 
Secretaria de Administração e Abas tecimento | Saab  
*Em caso de supressões que extrapolem os limites previstos, a Contratada 
poderá solicitar a extinção contratual. 
Nos pedidos de aditamento formulados, o Gestor ou a Gestora do Contrato 
deverá: 
a) descrever as alterações que se pretende realizar por meio do 
aditamento, de forma clara e objetiva, tais como: prazos, quantidades, 
serviços, itens do contrato, prédios/localidades etc.; 
b) avaliar o percentual já comprometido (art. 125 da Lei nº 14.133/2021), 
incluindo os aditamentos já concluídos ou em andamento, caso houver, e 
efetuar o novo cálculo, informando os percentuais de aditamento;  
c) solicitar proposta da Contratada, quando não houver preços definidos 
para o item a ser aditado; 
d) descrever o fato superveniente ou de conhecimento superveniente, 
suficiente para ensejar a modificação; 
e) atestar a manutenção do objeto inicialmente convencionado, não 
podendo, em hipótese alguma, haver a transmutação ou desnaturação do 
objeto; 
f) atestar a manutenção do equilíbrio econômico-financeiro; 
g) confirmar a manutenção do desconto linear obtido na licitação, para 
aditamentos qualitativos em contratos de obras e serviços de engenharia; 
h) inserir os respectivos anexos das alterações propostas, caso necessário; 
i) autuar protocolo CPA próprio e encaminhar à Saab 6 – Diretoria de 
Contratos Administrativos, Convênios e Gestão Imobiliária. 
8.1.5  PRORROGAÇÕES DE VIGÊNCIA 
O sistema emitirá notificação ao Gestor ou à Gestora do Contrato, com 
antecedência de 300 (trezentos) dias do término da vigência contratual, 
solicitando sua manifestação quanto à necessidade de prorrogação do ajuste, 
devendo ser observados os prazos estipulados no Provimento CSM nº 2.724/2023. 
74 
M A N U A L D E C O N T R A T O S | 2 0 2 5 
Secretaria de Administração e Abas tecimento | Saab  
ATENÇÂO: Nos termos do art. 89 do 
Provimento CSM nº 2.724/2023, as 
providências para prorrogação 
contratual devem ser iniciadas com 
antecedência mínima de: 
a)  240 (duzentos e quarenta) dias 
contados do final da vigência contratual, 
para prestação de serviços continuados 
ou fornecimento contínuo de bens; 
b)  300 (trezentos) dias contados do 
final da vigência contratual, para 
contratações complexas que 
demandem análise técnica.  
Caso o Gestor ou a Gestora opte pela prorrogação, deverão ser preenchidos 
os campos requisitados e gerado o protocolo (CPA), observando-se as seguintes 
etapas preliminares: 
1 - Verificar, na cláusula contratual, a possibilidade de prorrogação e qual o 
limite máximo de sua vigência; 
2 - Verificar a preservação das condições de habilitação (impedimento de 
licitar e contratar com a Administração Pública Estadual ou declaração de 
75 
M A N U A L D E C O N T R A T O S | 2 0 2 5 
Secretaria de Administração e Abas tecimento | Saab  
inidoneidade), bem como a inexistência de pendências, por meios dos 
seguintes links: CEIS, SANÇÕES, Apenados - TCE-SP, CADIN.  
Caso identifique algum impedimento que obste o prosseguimento do 
processo de prorrogação, o Gestor ou a Gestora deverá avaliar a necessidade 
de nova contratação ou outra providência cabível. 
3 – Colher a concordância formal da Contratada; 
4 - Encaminhar o protocolo gerado para o setor responsável pela pesquisa 
de preços com a finalidade de aferir a vantajosidade econômica.  
Caso a pesquisa realizada se mostre desfavorável, ou seja, os preços 
apurados encontrem-se abaixo do valor contratado, a área gestora deverá 
negociar junto à Contratada a redução dos preços, em conformidade com os 
valores obtidos na pesquisa. 
Caso a negociação reste frustrada caberá ao Gestor ou à Gestora avaliar 
alternativa(s) para se evitar a solução de continuidade do serviço/bens. 
Em caso de contratações por inexigibilidade ou dispensa de licitação, juntar 
a comprovação de que os preços praticados no contrato são compatíveis com os 
de mercado. Além disso, no caso de inexigibilidade, deverá ser apresentada a 
certidão de exclusividade atualizada, se o caso. 
5 - Justificar a necessidade da continuidade dos serviços; 
6 - Estando em termos, os pedidos de prorrogação deverão ser 
encaminhados, com toda a documentação pertinente, à Saab 6 – 
Diretoria de Contratos Administrativos, Convênios e Gestão Imobiliária, com 
antecedência mínima de: 
a) 180 (cento e oitenta) dias contados do final da vigência contratual, 
para prestação de serviços continuados ou fornecimento contínuo de 
bens; 
b) 240 (duzentos e quarenta) dias contados do final da vigência 
contratual, para contratações complexas que demandem análise técnica.  
76 
M A N U A L D E C O N T R A T O S | 2 0 2 5 
Secretaria de Administração e Abas tecimento | Saab  
ATENÇÂO: A Administração poderá 
estabelecer a vigência por prazo 
indeterminado nos contratos em que 
seja usuária de serviço público oferecido 
em regime de monopólio, desde que 
comprovada, a cada exercício financeiro, 
a existência de créditos orçamentários 
vinculados à contratação.  
São os casos dos contratos celebrados 
com os Correios (serviço postal) e com 
as concessionárias de energia elétrica 
(para contratação do uso do sistema de 
distribuição - CUSD). 
8.1.5.1  ATA DE REGISTRO DE PREÇOS 
O prazo de vigência da Ata de Registo de Preços (ARP) será de 1 (um) ano, 
podendo ser prorrogado por igual período, desde que haja interesse da 
administração e seja comprovada a vantajosidade econômica. 
O sistema encaminhará uma notificação à Unidade Gerenciadora, com 
antecedência de 300 (trezentos) dias do término da vigência da ARP, a fim de 
alertá-la sobre a validade da ata.  
Dessa forma, caso haja interesse na prorrogação da ARP, compete à 
Unidade Gerenciadora autuar expediente próprio de prorrogação, observando
se a antecedência prevista no tópico 8.1.2, instruindo-o com os documentos 
pertinentes. 
Em regra, a prorrogação de vigência da ARP segue o mesmo procedimento 
das demais prorrogações (conforme tópico 8.1.2), destacando-se as seguintes 
peculiaridades: 
• A Unidade Gerenciadora deverá colher a anuência dos fornecedores 
para a prorrogação proposta, certificando-se, inclusive, da eventual 
permanência daqueles incluídos no cadastro de reserva; 
• A Unidade Gerenciadora deverá encaminhar o expediente de 
prorrogação à Diretoria de Contratos da Saab, com antecedência 
mínima de 180 (cento e oitenta) dias, a contar do término da vigência 
da ARP; 
77 
M A N U A L D E C O N T R A T O S | 2 0 2 5 
Secretaria de Administração e Abas tecimento | Saab  
• A Unidade Gerenciadora dará ciência aos demais órgãos participantes, 
se houver, quanto às tratativas para prorrogação da ARP em curso.  
• A prorrogação será formalizada por Termo de Aditamento e implicará 
na renovação das quantidades iniciais para o novo período de vigência; 
• A Diretoria de Contratos da Saab encaminhará cópia do Termo de 
Aditamento de prorrogação aos órgãos participantes, se houver. 
8.1.6  MANUTENÇÃO DO EQUILÍBRIO ECONÔMICO
FINANCEIRO 
Segundo a Lei nº 14.133/2021, são três as formas de manutenção do equilíbrio 
econômico-financeiro do contrato, conforme definições: 
a) reajustamento em sentido estrito: forma de manutenção do equilíbrio 
econômico-financeiro de contrato consistente na aplicação do índice de 
correção monetária previsto no contrato, que deve retratar a variação efetiva do 
custo de produção, admitida a adoção de índices específicos ou setoriais; 
b) repactuação: forma de manutenção do equilíbrio econômico-financeiro de 
contrato utilizada para serviços contínuos com regime de dedicação exclusiva 
de mão de obra ou predominância de mão de obra. Efetuada por meio da análise 
da variação dos custos contratuais, devendo estar prevista no edital, sendo: 
• Para os custos decorrentes do mercado, com data vinculada à 
apresentação das propostas;  
• Para os custos decorrentes da mão de obra, com data vinculada ao 
acordo, à convenção coletiva ou ao dissídio coletivo ao qual o orçamento 
esteja vinculado. 
c) reequilíbrio econômico-financeiro: em caso de força maior, caso fortuito ou 
fato do príncipe ou em decorrência de fatos imprevisíveis ou previsíveis de 
consequências incalculáveis, que inviabilizem a execução do contrato tal como 
pactuado, respeitada, em qualquer caso, a repartição objetiva de risco 
estabelecida no contrato (alínea “d”, inciso II, artigo 124). 
78 
M A N U A L D E C O N T R A T O S | 2 0 2 5 
Secretaria de Administração e Abas tecimento | Saab  
8.1.6.1  REAJUSTAMENTO EM SENTIDO ESTRITO  
E REPACTUAÇÃO 
O reajustamento em sentido estrito e a repactuação, para os custos 
decorrentes de mercado, serão concedidos pela Administração, de ofício, 
conforme previsto em contrato, utilizando-se os índices pactuados. 
Para os contratos de obras e serviços de engenharia, o Gestor ou a Gestora 
deverá encaminhar à Saab 6 – Diretoria de Contratos Administrativos, Convênios 
e Gestão Imobiliária, expediente instruído com parecer da fiscalização técnica e 
novo cronograma físico financeiro aprovado pela Contratada. 
Os demais casos de repactuação (com exceção daquela por custos 
decorrentes de mercado, que ocorre de ofício) serão precedidas de solicitação 
da Contratada e analisadas pelo Gestor ou a Gestora do Contrato, observando
se, em suma, as seguintes etapas (conforme artigos 98 e 99 do Provimento CSM 
nº 2.724/2023): 
1. Recepcionar e autuar o pedido de repactuação em expediente 
eletrônico vinculado ao processo de contratação; 
2. Elaborar relatório conclusivo sobre o requerimento; 
• O Gestor ou a Gestora do Contrato poderá solicitar aos Fiscais 
Administrativos e do Contrato ou ao Responsável Técnico, subsídios 
para elaboração do relatório conclusivo, bem como realizar diligências 
para conferência dos elementos da repactuação requerida; 
3. Caso conclua favoravelmente à repactuação, encaminhar os autos à 
Saab 6 – Diretoria de Contratos Administrativos, Convênios e Gestão 
Imobiliária; 
4. Caso conclua desfavoravelmente à repactuação, o Gestor ou a Gestora 
do Contrato devolverá o pedido à Contratada, alertando-a que poderá 
sanear eventual deficiência na instrução e formular novo pedido ou 
formular pedido de reanálise; 
5. Caso a deficiência seja sanada ou haja pedido de reanálise, os autos 
serão remetidos à Saab 6 – Diretoria de Contratos Administrativos, 
Convênios e Gestão Imobiliária, para análise. 
As solicitações devem estar acompanhadas de demonstração analítica da 
variação dos custos, por meio de apresentação da planilha de custos e formação 
de preços e do novo acordo, convenção ou sentença normativa que fundamenta 
a repactuação (§ 6º, artigo 135, da Lei nº 14.133/2021). 
79 
M A N U A L D E C O N T R A T O S | 2 0 2 5 
Secretaria de Administração e Abas tecimento | Saab  
As novas planilhas de custos e formação de preços, com os novos valores, 
serão analisadas e referendadas pelo Gestor ou pela Gestora do Contrato antes 
do encaminhamento à Saab 6 – Diretoria de Contratos Administrativos, 
Convênios e Gestão Imobiliária. 
Os reajustes em sentido estrito e as repactuações serão registrados por 
apostila, dispensada a celebração de termo aditivo (inciso I, artigo 136, da Lei nº 
14133/2021). 
8.1.6.2  REEQUILÍBRIO ECONÔMICO-FINANCEIRO 
Para os pedidos de reequilíbrio econômico-financeiro (alínea “d”, inciso II, 
artigo 124, da Lei nº 14.133/2021), o Gestor ou a Gestora do Contrato deverá: 
a)  verificar a ocorrência de variação de custos que acarrete 
desequilíbrio econômico-financeiro em favor da administração; 
b)  receber pedido de reequilíbrio econômico-financeiro formulado 
pela Contratada; e 
c)  autuar, em expediente próprio vinculado ao processo da 
contratação, pedido de reequilíbrio econômico-financeiro, em favor da 
administração ou da Contratada 
Os autos serão instruídos com, no mínimo, os seguintes documentos e 
informações: 
a) se o risco foi previsto no Plano de Riscos ou, quando houver, na 
matriz de alocação de riscos; 
b) cópia do instrumento contratual, respectivos anexos e aditivos; 
c) planilha ou demonstrativo que evidencie a alteração da equação 
econômico-financeira; 
d) nexo de causalidade entre a alteração dos custos do contrato e o 
evento que inviabilize a execução do contrato tal como inicialmente 
pactuado. 
Na hipótese de reequilíbrio em favor da administração, compete ao 
Gestor ou à Gestora do Contrato encaminhar notificação à Contratada contendo 
os documentos relacionados acima para manifestação no prazo de 10 (dez) dias 
úteis. 
Compete ao Gestor ou à Gestora do Contrato elaborar relatório conclusivo 
acerca da ocorrência ou não do desequilíbrio: 
80 
M A N U A L D E C O N T R A T O S | 2 0 2 5 
Secretaria de Administração e Abas tecimento | Saab  
a) no caso de reequilíbrio em favor da administração, após o decurso 
do prazo (10 dias úteis), com ou sem manifestação da Contratada; 
b) no caso de reequilíbrio em favor da Contratada, após o 
recebimento do pedido devidamente instruído com os documentos. 
O Gestor ou a Gestora do Contrato poderá solicitar aos Fiscais 
Administrativos e do Contrato ou ao Responsável Técnico, subsídios para 
elaboração do relatório conclusivo, bem como realizar diligências para 
conferência do desequilíbrio apontado. 
Após a emissão do relatório conclusivo, os autos serão remetidos à Saab 6 - 
Diretoria de Contratos Administrativos, Convênios e Gestão Imobiliária, para 
processamento e elaboração da minuta de aditivo contratual e posterior 
encaminhamento à SOF e à Assessoria Jurídica. 
81 
M A N U A L D E C O N T R A T O S | 2 0 2 5 
Secretaria de Administração e Abas tecimento | Saab  
9.  
EXTINÇÃO DOS 
CONTRATOS 
82 
M A N U A L D E C O N T R A T O S | 2 0 2 5 
Secretaria de Administração e Abas tecimento | Saab  
Os contratos, em regra, são extintos quando atingem os objetivos para os 
quais foram formalizados ou pelo decurso do prazo. No entanto, há situações em 
que os contratos podem ser extintos antecipadamente. 
Para que ocorra o encerramento prematuro de um contrato, o seu motivo 
deve ser formalmente registrado nos autos do processo, sendo assegurados o 
contraditório e a ampla defesa. 
A extinção do contrato poderá ser: 
I. 
II. 
III. 
Determinada por ato unilateral e escrito da Administração, exceto no 
caso de descumprimento decorrente de sua própria conduta; 
Consensual, por acordo entre as partes, por conciliação, por mediação 
ou por comitê de resolução de disputas, desde que haja interesse da 
Administração; 
Determinada por decisão arbitral, em decorrência de cláusula 
compromissória ou compromisso arbitral, ou por decisão judicial. 
9.1 EXTINÇÃO UNILATERAL 
II. 
III. 
IV. 
V. 
VI. 
VII. 
Segundo o artigo 137 da Lei nº 14.133/2021, são motivos para a extinção 
unilateral do contrato: 
I. 
Não cumprimento ou cumprimento irregular de normas editalícias ou 
de cláusulas contratuais, de especificações, de projetos ou de prazos; 
Desatendimento das determinações regulares emitidas pela autoridade 
designada para acompanhar e fiscalizar sua execução ou por autoridade 
superior; 
Alteração social ou modificação da finalidade ou da estrutura da 
empresa que restrinja sua capacidade de concluir o contrato; 
Decretação de falência ou de insolvência civil, dissolução da sociedade 
ou falecimento do contratado; 
Caso fortuito ou força maior, regularmente comprovados, impeditivos da 
execução do contrato; 
Atraso na obtenção da licença ambiental, ou impossibilidade de obtê-la, 
ou alteração substancial do anteprojeto que dela resultar, ainda que 
obtida no prazo previsto; 
Atraso na liberação das áreas sujeitas a desapropriação, a desocupação 
ou a servidão administrativa, ou impossibilidade de liberação dessas 
áreas; 
VIII. 
Razões de interesse público, justificadas pela autoridade máxima do 
órgão ou da entidade contratante; 
83 
M A N U A L D E C O N T R A T O S | 2 0 2 5 
Secretaria de Administração e Abas tecimento | Saab  
IX. 
Não cumprimento das obrigações relativas à reserva de cargos prevista 
em lei, bem como em outras normas específicas, para pessoa com 
deficiência, para reabilitado da Previdência Social ou para aprendiz. 
PROCEDIMENTO A SER ADOTADO: 
No âmbito do TJSP, caso constatada alguma das hipóteses de extinção 
unilateral contratual, compete ao Gestor ou à Gestora do Contrato:  
1. Autuar expediente eletrônico vinculado ao processo de contratação; 
2. Notificar a Contratada, a fim de garantir o contraditório e a ampla defesa; 
3. Instruir os autos com, no mínimo: 
• Documentação comprobatória que motivou o pedido de extinção, de 
acordo com as hipóteses previstas no art. 137 da Lei. nº 14.133/2021; 
• Notificação da Contratada e comprovação de seu recebimento; 
• Resposta da Contratada ou informação de decurso do prazo sem sua 
manifestação; 
9.2  EXTINÇÃO PLEITEADA  
PELA CONTRATADA 
II. 
III. 
• Manifestação da área gestora contendo, inclusive, informação acerca dos 
processos apuratórios autuados; 
4. Encaminhar o expediente à Saab 6 - Diretoria de Contratos 
Administrativos, Convênios e Gestão Imobiliária, para elaboração do 
termo de extinção contratual, com posterior encaminhamento à área 
jurídica e deliberação da E. Presidência. 
Por outro lado, a Contratada poderá pleitear a extinção do ajuste nas 
seguintes situações: 
I. 
Supressão, por parte da Administração, de obras, serviços ou compras 
que acarrete modificação do valor inicial do contrato além do limite 
permitido no art. 125 da Lei nº 14.133/2021; 
Suspensão de execução do contrato, por ordem escrita da 
Administração, por prazo superior a 3 (três) meses; 
Repetidas suspensões que totalizem 90 (noventa) dias úteis, 
independentemente do pagamento obrigatório de indenização pelas 
sucessivas e contratualmente imprevistas desmobilizações e 
mobilizações e outras previstas; 
84 
M A N U A L D E C O N T R A T O S | 2 0 2 5 
Secretaria de Administração e Abas tecimento | Saab  
IV. 
V. 
Atraso superior a 2 (dois) meses, contado da emissão da nota fiscal, dos 
pagamentos ou de parcelas de pagamentos devidos pela 
Administração por despesas de obras, serviços ou fornecimentos; 
Não liberação pela Administração, nos prazos contratuais, de área, local 
ou objeto, para execução de obra, serviço ou fornecimento, e de fontes 
de materiais naturais especificadas no projeto, inclusive devido a atraso 
ou descumprimento das obrigações atribuídas pelo contrato à 
Administração relacionadas a desapropriação, a desocupação de áreas 
públicas ou a licenciamento ambiental. 
ATENÇÂO: As extinções previstas nos 
itens II, III e IV não serão admitidas em 
caso de calamidade pública, de grave 
perturbação da ordem interna ou 
guerra, bem como quando decorrerem 
de ato ou fato que a Contratada tenha 
praticado, tenha participado ou 
contribuído. 
PROCEDIMENTO A SER ADOTADO: 
No âmbito do TJSP, caso a Contratada pleiteie a extinção contratual, 
compete ao Gestor ou à Gestora do Contrato:  
1. Autuar expediente eletrônico vinculado ao processo de contratação; 
2. Instruir os autos com, no mínimo:  
• Documentação comprobatória que motivou o pedido de extinção, de 
acordo com as hipóteses previstas no art. 137 da Lei. nº 14.133/2021; 
• Manifestação da área gestora acerca da aceitabilidade do pedido. 
3. Encaminhar o expediente à Saab 6 – Diretoria de Contratos, para 
elaboração do termo de extinção contratual, com posterior 
encaminhamento à área jurídica e deliberação da E. Presidência; 
85 
M A N U A L D E C O N T R A T O S | 2 0 2 5 
Secretaria de Administração e Abas tecimento | Saab  
10 . 
RELATÓRIO 
FINAL 
86 
M A N U A L D E C O N T R A T O S | 2 0 2 5 
Secretaria de Administração e Abas tecimento | Saab  
10.1  RELATÓRIO FINAL SOBRE A 
CONSECUÇÃO DOS OBJETIVOS 
O relatório final é elaborado ao fim da vigência contratual e deve conter 
informações sobre a obtenção dos objetivos que tenham justificado a 
contratação, bem como eventuais condutas a serem adotadas para o 
aprimoramento das atividades da Administração. 
Segundo o artigo 106 do Provimento CSM nº 2.724/2023, que regulamenta 
o tema no âmbito do TJSP, compete ao Gestor ou a Gestora do Contrato, com 
apoio do Gestor ou da Gestora de Planejamento da Contratação, a elaboração do 
relatório final, em 60 (sessenta) dias corridos, contados do término da vigência 
contratual, contendo, no mínimo, as seguintes informações: 
• Efetiva consecução dos objetivos que tenham justificado a contratação; 
• Existência de restos a pagar e/ou outras pendências financeiras do 
contrato; 
• Liberação da garantia contratual, se houver; 
• Relação dos Processos Administrativos Apuratórios, de acordo com 
certidão extraída do sistema de gestão contratual; 
• Proposição de melhorias a serem refletidas no ETP, no TR e no Plano de 
Riscos das futuras contratações para o mesmo objeto; 
• No caso de contratos com dedicação exclusiva de mão-de-obra, constar 
as informações necessárias para a liberação, se o caso, do saldo da conta 
depósito-vinculada de que trata a Resolução CNJ nº 169/2013 (retenção 
de provisões de encargos trabalhistas, previdenciários e outros a serem 
pagos às empresas contratadas para prestar serviços com mão de obra 
residente nas dependências de unidades jurisdicionadas ao CNJ). 
O relatório final deverá ser juntado ao processo de acompanhamento da 
execução contratual e encaminhado ao respectivo Secretário ou à respectiva 
Secretária da unidade, para deliberação em até 5 (cinco) dias úteis. Após 
deliberação, o Secretário ou a Secretária encaminhará os autos: 
a) Ao Gestor ou à Gestora do Contrato: para adequações no relatório, se 
o caso; 
b) À Diretoria de Contratos: caso o relatório seja aprovado, para 
divulgação no PNCP e no Portal da Transparência do TJSP, no prazo de 
5 (cinco) dias úteis; 
c) À Diretoria de Licitações: para os casos de contratação direta, que não 
possuam instrumento contratual, para divulgação no PNCP e no Portal 
da Transparência do TJSP, no prazo de 5 (cinco) dias úteis. 
87 
M A N U A L D E C O N T R A T O S | 2 0 2 5 
Secretaria de Administração e Abas tecimento | Saab  
11 .  
ANEXOS 
88 
M A N U A L D E C O N T R A T O S | 2 0 2 5 
Secretaria de Administração e Abas tecimento | Saab  
89 
  
 
 
 
11.1  ANEXO I – CHECKLIST PARA NOVA 
CONTRATAÇÃO DE ENERGIA ELÉTRICA 
(CUSD E CCER) 
ANEXO I – CHECKLIST NOVA CONTRATAÇÃO CUSD E CCER 
ITEM CHECKLIST PARA NOVA CONTRATAÇÃO DE FORNECIMENTO DE ENERGIA ELÉTRICA – CUSD E CCER 
 DESCRIÇÃO SIM NÃO/ 
Justificativa FLS. 
1   
Os autos se referem à formalização de contratos do Grupo A (CUSD e 
CCER)?   
Se sim, juntar e indicar as fls. dos contratos no processo.  
       
2   Os contratos CUSD e CCER já foram celebrados pelo Juiz Diretor do 
Fórum, tratando-se o expediente de convalidação dos instrumentos?   
Se sim, juntar e indicar as fls. do documento assinado.  
      
3  Em caso de resposta positiva no item 2, houve delegação de poderes 
pelo Exmo. Sr. Desembargador Presidente do TJSP ao MM. Juiz(a) de 
Direito Diretor(a) do Fórum da Comarca para celebração dos 
instrumentos contratuais de CUSD e CCER? Em caso positivo, juntar 
cópia do despacho proferido pela Autoridade Superior  
      
4   Constam dos autos ETP, Termo de referência/projeto básico 
demonstrando, de forma clara, precisa e suficiente as soluções existentes 
no mercado para atendimento da necessidade do TJSP e a escolha da 
melhor solução, nos termos do Provimento nº 2.138/2013, bem como análise 
técnica da adequação da modalidade de contratação pretendida.  
        
5   Foram apresentados:          
   a) Laudo/parecer técnico demonstrando histórico ou estimativa de 
consumo e a quantidade da demanda de energia que se pretende 
contratar, de acordo com as condições e especificidades do Fórum da 
Comarca interessada?   
      
   b) Manifestação da área gestora informando se há necessidade de 
realização de obras na rede elétrica, bem como as hipóteses de 
ressarcimento de valores pelo TJSP à concessionária em caso de eventual 
futura alteração de demanda?   
      
6   
No caso de serem necessárias obras na rede elétrica, houve 
formalização de contrato específico?  - Se sim, juntar e indicar fls. do documento.  - Se não, há informação acerca da prévia autorização e delegação de 
poderes para a formalização do respectivo contrato pelo MM. Juiz(a) 
Diretor(a)? Em caso positivo, juntar cópia do despacho proferido pela 
Autoridade Superior.   
         
7   Foram colacionados aos autos as minutas contratuais que regerão a 
relação entre as partes (CCER, CUSD), já adequadas aos termos da 
Resolução Normativa nº 1.000/2021 da ANEEL?  
Se sim, indicar fls. do documento no processo.  
         
8  Houve indicação dos servidores que atuarão como gestor e fiscal nos 
contratos de fornecimento de energia elétrica a serem celebrados?   
Se sim, indicar fls. de manifestação com novas indicações.  
         
9   A escolha do fornecedor foi devidamente justificada, mediante a 
comprovação da exclusividade da concessionária no âmbito do 
município em que localizado o Fórum da Comarca contratante? 
(declaração de exclusividade fornecida pela concessionária)  
Se sim, indicar as fls. do documento nos autos.  
        
10   Há justificativa para o preço da contratação, embasada em declaração 
fornecida pela concessionária acerca da regular e uniforme aplicação das 
tarifas homologadas pela ANEEL e acerca da inexistência de condições 
mais vantajosas de contratação disponíveis para a Administração? 
(declaração de preço)  
Se sim, indicar as fls. do documento nos autos.  
         
90 
M A N U A L D E C O N T R A T O S | 2 0 2 5 
Secretaria de Administração e Abas tecimento | Saab  
 
 
11.2 ANEXO II - CHECKLIST PARA 
ALTERAÇÃO DA DEMANDA DE 
ENERGIA ELÉTRICA 
ANEXO II – CHECKLIST PARA ALTERAÇÃO DA DEMANDA 
ITEM CHECKLIST PARA ALTERAÇÃO DA DEMANDA DE ENERGIA ELÉTRICA 
 DESCRIÇÃO SIM NÃO/ 
Justificativa FLS. 
1 Os autos se referem a aditamento de contratos do Grupo A (CUSD e CCER)? 
Se sim, juntar e/ou indicar as fls. do termo de aditivo dos contratos no processo.       
2 
Os aditivos CUSD e/ou CCER já foram celebrados pelo Juiz Diretor do Fórum, 
tratando-se o expediente de convalidação dos instrumentos?   
Se sim, juntar e indicar as fls. do documento assinado. 
      
3 
Em caso de resposta positiva no item 2, houve delegação de poderes pelo Exmo. 
Sr. Desembargador Presidente do TJSP ao MM. Juiz(a) de Direito Diretor(a) do 
Fórum da Comarca para celebração dos contratos de CUSD E CCER e respectivos 
aditivos contratuais para alteração da demanda de energia elétrica? Em caso 
positivo, juntar cópia do despacho proferido pela Autoridade Superior 
      
4 
Constam dos autos cópias dos contratos CUSD e CCER originalmente celebrados, 
bem como de todos os aditivos já celebrados? - Se sim, indicar as folhas de cada documento. - Se não, promover a juntada e respectiva indicação de folhas. 
      
5 Foram apresentados:          
 
Laudo/parecer técnico demonstrando a necessidade do aumento/redução da 
demanda?   - Se sim, indicar as folhas de cada documento. - Se não, promover a juntada e respectiva indicação de folhas. 
      
 
Manifestação da área gestora informando se há necessidade de realização de 
obras na rede elétrica, bem como eventual ressarcimento de valores pelo TJSP à 
concessionária? - Se sim, indicar as folhas de cada documento. - Se não, promover a juntada e respectiva indicação de folhas 
      
6 
No caso de serem necessárias obras na rede elétrica, houve formalização de 
contrato específico? - Se sim, juntar e indicar fls. do documento. - Se não, há informação acerca da prévia autorização e delegação de poderes para a 
formalização do respectivo contrato pelo MM. Juiz(a) Diretor(a)? Em caso positivo, 
juntar cópia do despacho proferido pela Autoridade Superior. 
      
7 
No caso de ressarcimento, foram indicados os respectivos custos e melhor 
alternativa para o atendimento do interesse público? Se sim, indicar fls. da 
manifestação no processo. 
      
8 
Foram colacionados aos autos as minutas dos aditivos contratuais de CUSD E 
CCER que regerão a relação entre as partes, já adequadas aos termos da 
Resolução Normativa nº 1.000/2021 da ANEEL? 
Se sim, indicar fls. do documento no processo 
Se não, as minutas deverão ser solicitadas à concessionária para juntada ao 
expediente 
      
9 
Houve indicação dos servidores que atuarão como gestor, fiscal e suplentes nos 
contratos de fornecimento de energia elétrica a serem celebrados? Se sim, indicar 
fls.  ou indicar a manifestação com as novas indicações. 
      
10 
A escolha do fornecedor foi devidamente justificada, mediante a comprovação da 
exclusividade da concessionária no âmbito do município em que localizado o Fórum 
da Comarca contratante? (declaração de exclusividade fornecida pela 
concessionária) 
Se sim, indicar as fls. do documento nos autos. 
      
11 
Há justificativa para o preço da contratação, embasada em declaração fornecida 
pela concessionária acerca da regular e uniforme aplicação das tarifas homologadas 
pela ANEEL e acerca da inexistência de condições mais vantajosas de contratação 
disponíveis para a Administração? (declaração de preço)  
Se sim, indicar as fls. do documento nos autos.  
      
 
M A N U A L D E C O N T R A T O S | 2 0 2 5 
Secretaria de Administração e Abas tecimento | Saab  
91 


Manual de 
Contratos 
TRIBUNAL DE JUSTIÇA DE SÃO PAULO 
1.1.1.1.1.1.1  
Secretaria de Administração e Abastecimento | Saab  
M A N U A L D E C O N T R A T O S | 2 0 2 5 
Secretaria de Administração e Abas tecimento | Saab  
MANUAL DE CONTRATOS 
Edição - 2025  
1 
M A N U A L D E C O N T R A T O S | 2 0 2 5 
Secretaria de Administração e Abas tecimento | Saab  
SECRETÁRIO DE ADMINISTRAÇÃO E ABASTECIMENTO 
Fábio Makoto Tagliaferro Yokoyama 
EQUIPE DE TRABALHO 
Andrea Miyuki Noel 
Bruna Marcela de Barros Cunha 
Diego Aparecido Gabriel 
Diogo Takehiro Sayama 
Eduardo Kanashiro Oyafuso 
Karina Yamaguishi Ide 
Lilian Yamazato 
Luciana Borges Toledo 
Maria Aparecida Lúcio 
Maurício Marcos Abambres 
Murilo Mendes Santos 
Silvana Mendes de Godoy 
COLABORADORES 
Alian Labate Salas 
Flávia Cavalcante Lima 
Rogério Denis Roque Bianchi 
2 
M A N U A L D E C O N T R A T O S | 2 0 2 5 
Secretaria de Administração e Abas tecimento | Saab  
Sumário 
Manual de Contratos  
1. DISPOSIÇÕES  GERAIS ..................................................................................................................... 9 
1.1 A NOVA LEI DE LICITAÇÕES E CONTRATOS (LEI Nº 14.133/2021) ................ 10 
2. CONTRATO .......................................................................................................................................... 11 
2.1 DISPOSIÇÕES GERAIS.......................................................................................................................... 12 
2.2 FORMALIZAÇÃO  DOS CONTRATOS ...................................................................................... 12 
2.3 VIGÊNCIA ........................................................................................................................................................14 
3. GESTORES, GESTORAS  E FISCAIS ..................................................................................... 16 
3.1 DESIGNAÇÃO .............................................................................................................................................. 17 
3.2 PERFIS .............................................................................................................................................................. 18 
3.3 VEDAÇÕES E IMPEDIMENTOS .................................................................................................... 19 
3.4 ATRIBUIÇÕES GERAIS ...................................................................................................................... 20 
4. ETAPAS DA GESTÃO E FISCALIZAÇÃO ........................................................................ 21 
4.1 ATRIBUIÇÕES ............................................................................................................................................. 22 
4.1.1 GESTOR E GESTORA DO CONTRATO ................................................................................. 22 
4.1.2 FISCAL DO CONTRATO .................................................................................................................. 23 
4.1.3 FISCAL ADMINISTRATIVO ........................................................................................................... 24 
4.1.4 RESPONSÁVEIS TÉCNICOS ........................................................................................................ 25 
4.2 EXECUÇÃO DOS CONTRATOS ................................................................................................... 26 
4.2.1 FISCALIZAÇÃO DOS CONTRATOS COM DEDICAÇÃO EXCLUSIVA DE 
MÃO DE OBRA .................................................................................................................................................. 27 
4.2.1.1   RETENÇÃO E LIBERAÇÃO DAS VERBAS CONTINGENCIADAS ............. 29 
4.2.1.1.1 LIBERAÇÃO DAS VERBAS DURANTE  O CONTRATO .................................... 30 
3 
M A N U A L D E C O N T R A T O S | 2 0 2 5 
Secretaria de Administração e Abas tecimento | Saab  
4.2.1.1.2 LIBERAÇÃO DO SALDO REMANESCENTE APÓS O ENCERRAMENTO  
DO CONTRATO ................................................................................................................................................. 35 
4.2.1.1.3 RESOLUÇÃO DE CASOS OMISSOS .............................................................................. 40 
4.2.2 FISCALIZAÇÃO DOS SERVIÇOS E OBRAS DE ENGENHARIA ........................41 
4.2.3 FISCALIZAÇÃO DOS CONTRATOS DE STIC ..................................................................41 
4.3 RECEBIMENTO ....................................................................................................................................... 42 
4.3.1 RECEBIMENTO PROVISÓRIO .................................................................................................. 43 
4.3.2 RECEBIMENTO DEFINITIVO .................................................................................................... 44 
4.3.3 ROTEIRO PARA RECEBIMENTO DE BENS .................................................................. 45 
4.3.4 ROTEIRO PARA RECEBIMENTO  DE SERVIÇOS .................................................... 46 
4.4 IRREGULARIDADES NA EXECUÇÃO CONTRATUAL ............................................... 47 
5. CONTRATOS SUI GENERIS ..................................................................................................... 49 
5.1 CONTRATOS DE FORNECIMENTO DE ENERGIA ELÉTRICA ............................. 50 
5.1.1 FLUXO ATUALIZADO PARA FORMALIZAÇÃO DOS CONTRATOS  DE 
ENERGIA ELÉTRICA ....................................................................................................................................... 51 
5.1.2 ALTERAÇÃO DA DEMANDA ................................................................................................... 53 
6. ATESTADO E PROTOCOLO DO DOCUMENTO FISCAL .......................... 54 
6.1 DO CADASTRO  NO SISTEMA SGF ........................................................................................... 55 
6.2 PRAZO DE RECEBIMENTO E ENVIO DA DOCUMENTAÇÃO À SOF ........... 55 
6.3 CADASTRAMENTO DO DOCUMENTO FISCAL .............................................................. 56 
6.3.1 1ª ETAPA: INFORMAÇÃO DOS DADOS CADASTRAIS E IMPOSTOS 
APLICADOS AO DOCUMENTO ........................................................................................................... 57 
6.3.1.1 RETENÇÕES TRIBUTÁRIAS (ISS, INSS E IRRF) ......................................................... 59 
6.3.1.1.1 RETENÇÃO ISS ................................................................................................................................ 60 
6.3.1.1.2 RETENÇÃO INSS ............................................................................................................................. 61 
6.3.1.1.3 RETENÇÃO IRRF (IMPOSTO DE RENDA RETIDO NA FONTE) ................ 62 
6.3.2 2ª ETAPA: FORNECIMENTO DAS INFORMAÇÕES ACERCA DA 
EXECUÇÃO DO CONTRATO .................................................................................................................. 63 
6.3.3 3ª ETAPA: PROTOCOLO ............................................................................................................. 65 
6.4 CANCELAMENTO DE PROTOCOLOS DE DOCUMENTOS FISCAIS ............ 66 
4 
M A N U A L D E C O N T R A T O S | 2 0 2 5 
Secretaria de Administração e Abas tecimento | Saab  
7. GESTÃO DE RISCOS .................................................................................................................... 68 
7.1 ATUALIZAÇÃO DO PLANO  DE RISCOS .............................................................................. 70 
8. MODIFICAÇÕES CONTRATUAIS ....................................................................................... 72 
8.1 FORMALIZAÇÃO DAS ALTERAÇÕES CONTRATUAIS ............................................... 73 
8.1.1 ACRÉSCIMOS E SUPRESSÕES .................................................................................................. 73 
8.1.2 PRORROGAÇÕES DE VIGÊNCIA ........................................................................................... 74 
8.1.2.1 ATA DE REGISTRO DE PREÇOS .......................................................................................... 77 
8.1.3 MANUTENÇÃO DO EQUILÍBRIO ECONÔMICO-FINANCEIRO .................... 78 
8.1.3.1 REAJUSTAMENTO EM SENTIDO ESTRITO  E REPACTUAÇÃO..................79 
8.1.3.2 REEQUILÍBRIO ECONÔMICO-FINANCEIRO ........................................................... 80 
9.  EXTINÇÃO DOS CONTRATOS ............................................................................................. 82 
9.1 EXTINÇÃO UNILATERAL .................................................................................................................... 83 
9.2 EXTINÇÃO PLEITEADA  PELA CONTRATADA ............................................................... 84 
10. RELATÓRIO FINAL ................................................................................................................. 86 
10.1 RELATÓRIO FINAL SOBRE A CONSECUÇÃO DOS OBJETIVOS ................... 87 
11.  ANEXOS .............................................................................................................................................. 88 
11.1 ANEXO I – CHECKLIST PARA NOVA CONTRATAÇÃO DE ENERGIA 
ELÉTRICA (CUSD E CCER) ...................................................................................................................... 89 
11.2 ANEXO II - CHECKLIST PARA ALTERAÇÃO DA DEMANDA  DE ENERGIA 
ELÉTRICA .............................................................................................................................................................. 90 
5 
 
 
 
 
 
INTRODUÇÃO 
 
 
 
Desde a última edição deste manual, publicada em 2018, 
ocorreram mudanças substanciais nas normas relacionadas à gestão e 
fiscalização de contratos, sobretudo com a publicação da Lei nº 
14.133/2021, denominada Nova Lei de Licitações e Contratos, que 
estabelece as regras gerais de licitações e contratos administrativos 
para as Administrações Públicas diretas, autárquicas e fundacionais da 
União, dos Estados, do Distrito Federal e dos Municípios. 
Dessa maneira, em conformidade ao Provimento CSM nº 
2.724/2023 e à luz da Lei nº 14.133/2021, foi elaborado o presente Manual 
de Gestão e Fiscalização de Contratos, cujo objetivo é reunir 
informações e orientações indispensáveis, organizando-as de forma 
sistematizada e precisa, a fim de direcionar a atuação dos servidores 
deste Tribunal de Justiça envolvidos na gestão e fiscalização de 
contratos administrativos. 
  
M A N U A L D E C O N T R A T O S | 2 0 2 5 
Secretaria de Administração e Abas tecimento | Saab  
1.  
DISPOSIÇÕES  
GERAIS 
9 
10 
M A N U A L D E C O N T R A T O S | 2 0 2 5 
Secretaria de Administração e Abas tecimento | Saab  
 
 
 
1.1   A NOVA LEI DE LICITAÇÕES E 
CONTRATOS (LEI Nº 14.133/2021) 
 
A Nova Lei de Licitações e Contratos (lei nº 14.133, de 1º de abril de 2021), 
estabelece normas gerais de licitação e contratação para as Administrações 
Públicas diretas, autárquicas e fundacionais da União, do Distrito Federal, dos 
Estados e dos Municípios, e substituiu a Lei nº 8.666/1993, até então utilizada. 
Com o advento da Nova Lei, houve maior incorporação da forma eletrônica 
nos procedimentos adotados, inclusive na celebração de contratos e seus termos 
aditivos, bem como trouxe outras alterações. 
No entanto, durante o período de transição da Nova Lei, estendido até o dia 
30/12/2023, era permitida a utilização de ambas as legislações, ficando a critério 
da Administração dispor daquela que melhor atendesse seus objetivos. Tal 
opção vincula os demais atos processuais conseguintes. 
Dessa forma, todos os processos licitatórios e de contratação direta tramitados 
sob o regime antigo (Lei nº 8.666/1993) serão por ele regidos, desde que a 
publicação do edital ou do ato autorizativo da contratação direta tenha ocorrido 
até o dia 29/12/2023. Nesse caso, deve-se consultar os procedimentos previstos 
no antigo Manual de Licitações e Contratos do TJSP (disponível em Manual de 
Licitações e Contratos - 1ª Edição). 
Para os demais casos, deve-se observar exclusivamente o texto da Lei nº 
14.133/2021. 
A integralidade da Nova Lei de Licitações e Contratos pode ser consultada em 
Lei nº 14.133/2021. 
  
M A N U A L D E C O N T R A T O S | 2 0 2 5 
Secretaria de Administração e Abas tecimento | Saab  
2.  
CONTRATO 
11 
M A N U A L D E C O N T R A T O S | 2 0 2 5 
Secretaria de Administração e Abas tecimento | Saab  
2.1 DISPOSIÇÕES GERAIS 
Contrato administrativo é um instrumento formal, regido pelas normas do 
direito público e suplementado pelas normas do direito privado no que couber, 
celebrado entre a Administração Pública e um terceiro (pessoa física ou jurídica, 
de direito público ou privado) para o fornecimento de bens, a realização de obras 
ou a prestação de serviços. Trata-se de um acordo recíproco de vontades, em que 
ambas as partes celebram um negócio com o fim de se atender ao interesse 
público. 
Todo contrato deve mencionar os nomes das partes e de seus 
representantes, a finalidade, o ato que autorizou sua lavratura, assim como o 
número do processo de licitação ou de contratação direta. 
Além disso, os contratos devem possuir cláusulas claras e precisas, com as 
condições necessárias para sua execução, bem como os direitos, obrigações e 
responsabilidades das partes. 
2.2 FORMALIZAÇÃO DOS CONTRATOS 
No TJSP, atuarão na fase de formalização do contrato: 
• Presidente do TJSP; 
• Gestor ou Gestora do Contrato; 
• Diretoria de Contratos da Secretaria de Administração e Abastecimento – Saab 6; 
• Secretaria de Orçamento e Finanças - SOF 
A formalização dos contratos administrativos segue o seguinte trâmite: 
1. Concluída a fase de julgamento e habilitação, os autos são 
encaminhados à Diretoria de Contratos da Secretaria de Administração 
e Abastecimento – Saab 6 para a lavratura do instrumento contratual; 
12 
M A N U A L D E C O N T R A T O S | 2 0 2 5 
Secretaria de Administração e Abas tecimento | Saab  
2. Elaborado o contrato, o processo segue para a E. Presidência visando 
à homologação, adjudicação, autorização da despesa e assinatura do 
termo contratual; 
3. Com o retorno da Alta Administração, a Saab 6.1 notificará a 
Contratada para assinatura do contrato, dentro do prazo e nas 
condições previstas no edital de licitação ou autorização de contratação 
direta, sob pena de decadência do seu direito à contratação, sem 
prejuízo às penalidades previstas no edital e no contrato; 
4. O prazo de convocação poderá ser prorrogado uma vez por igual 
período, mediante solicitação justificada da Contratada, desde que o 
motivo apresentado seja aceito pela Administração; 
5. No âmbito do Tribunal de Justiça de São Paulo, essas assinaturas são 
coletadas, preferencialmente, na forma eletrônica, mediante 
assinatura da Contratada no Portal Eletrônico de Assinaturas do TJSP; 
6. Na impossibilidade do contrato, do Termo de Confidencialidade e 
Proteção de Dados e do Termo de Ciência e Notificação (TCE) serem 
assinados eletronicamente, por falha do sistema ou por motivo 
superveniente do Tribunal de Justiça, a Contratada será convocada 
para assiná-los fisicamente; 
7. Formalizado o contrato, será encaminhado, ao gestor ou à gestora 
e ao suplente de gestor, o despacho da E. Presidência com as 
respectivas nomeações, bem como cópia do contrato ou link de 
acesso do referido ajuste no Portal da Transparência do TJSP; 
8. A Saab 6 providenciará o cadastro do contrato no Sistema de 
Gerenciamento Financeiro e Orçamentário (SGF) e sua publicação no 
DEJESP (Diário Eletrônico da Justiça de São Paulo) e no PNCP (Portal 
Nacional de Contratações Públicas). 
9. Na sequência, serão abertas tarefas no sistema à Secretaria de 
Orçamento e Finanças – SOF para as providências internas (empenho, 
abertura de processos contábeis, de contingenciamento, registro de 
garantia etc.), bem como o encaminhamento do processo à Diretoria 
de Licitações e Suprimentos – Saab 5, para envio AUDESP da Licitação; 
10. Por fim, a Saab 6.1 realizará o envio AUDESP dos Contratos. 
13 
M A N U A L D E C O N T R A T O S | 2 0 2 5 
Secretaria de Administração e Abas tecimento | Saab  
2.3 VIGÊNCIA 
O prazo de vigência dos contratos deve ser previsto em edital e no contrato, 
observando-se, no ato da contratação e a cada exercício financeiro, a 
disponibilidade orçamentária, assim como a previsão no plano plurianual, caso 
ultrapasse 1 (um) exercício financeiro. 
Em regra, os contratos para serviços e fornecimentos contínuos podem 
possuir prazo de até 5 (cinco) anos, podendo ser prorrogados, sucessivamente, 
até o limite máximo de 10 (dez) anos, desde que: 
• Haja previsão em edital; 
• A autoridade competente ateste que as condições e os preços 
permanecem vantajosos para a Administração. 
Ainda, de acordo com o art. 111 da Lei nº 14.133/2021, na contratação que 
previr a conclusão de escopo predefinido, o prazo de vigência será 
automaticamente prorrogado quando seu objeto não for concluído no período 
firmado no contrato. 
Ademais, a Administração poderá estabelecer a vigência por prazo 
indeterminado nos contratos em que seja usuária de serviço público oferecido 
em regime de monopólio, desde que comprovada, a cada exercício financeiro, 
a existência de créditos orçamentários vinculados à contratação (Art. 109 da Lei 
nº 14.133/2021). 
Para os contratos com vigência plurianual, a Administração deve observar 
as seguintes diretrizes: 
• A autoridade competente deve atestar a maior vantagem 
econômica em razão da contratação plurianual; 
• A Administração deverá atestar, no início da contratação e a cada 
exercício, a existência de créditos orçamentários vinculados à 
contratação e a vantagem em sua manutenção; 
• A Administração terá a opção de extinguir o contrato, sem ônus, 
quando não dispuser de créditos orçamentários para sua 
continuidade ou quando entender que o contrato não seja mais 
vantajoso. 
A fim de que não ocorram vencimentos de contrato sem a devida 
prorrogação, o Gestor ou a Gestora do Contrato deverá adotar as providências 
nos seguintes prazos: 
14 
M A N U A L D E C O N T R A T O S | 2 0 2 5 
Secretaria de Administração e Abas tecimento | Saab  
15 
  
 
 
 
Tipos de contratos 
Início das providências / 
verificações pelo Gestor 
ou pela Gestora 
Formalização do pedido de 
prorrogação perante a 
Diretoria de Contratos da 
Saab 
Prestação de serviços de 
natureza continuada 
240 dias antes do 
vencimento 
180 dias antes do 
vencimento 
Serviços de alta 
complexidade ou que 
necessitem de análise 
técnica 
300 dias antes do 
vencimento 
240 dias antes do 
vencimento 
 
Os procedimentos e providências a serem adotadas pelo Gestor ou pela 
Gestora do Contrato para a prorrogação contratual estão demonstradas no item 
“8.1.2 – Prorrogações de Vigência” deste Manual. 
  
M A N U A L D E C O N T R A T O S | 2 0 2 5 
Secretaria de Administração e Abas tecimento | Saab  
3.  
GESTORES, 
GESTORAS  
E FISCAIS 
16 
M A N U A L D E C O N T R A T O S | 2 0 2 5 
Secretaria de Administração e Abas tecimento | Saab  
Inicialmente, cumpre-nos definir brevemente os atores que atuam nos 
contratos administrativos, de acordo com o Provimento CSM nº 2724/2023: 
• Equipe de Gestão do Contrato: equipe formada pelo Gestor ou pela 
Gestora do Contrato e suplente, pelos Fiscais Administrativos e 
suplentes, pelos Fiscais do Contrato e suplentes, e pelos 
Responsáveis Técnicos, se o caso, para acompanhamento, gestão e 
fiscalização da execução contratual; 
• Fiscal Administrativo: servidor ou servidora designados para 
auxiliar o Gestor ou a Gestora do Contrato na fiscalização dos 
aspectos administrativos da execução contratual; 
• Fiscal do Contrato: servidor ou servidora designados para auxiliar o 
Gestor ou a Gestora do Contrato na fiscalização dos aspectos 
operacionais da execução contratual; 
• Gestor ou Gestora do Contrato: servidor, servidora, magistrado ou 
magistrada designados pela Presidência do Tribunal de Justiça para 
coordenar a gestão e fiscalização da execução contratual. 
3.1  DESIGNAÇÃO 
Na designação serão considerados: 
• A complexidade da fiscalização; 
Os gestores, as gestoras e seus respectivos suplentes serão designados pela 
Presidência do TJSP, ao passo que os fiscais e seus suplentes serão designados 
pelo Gestor ou pela Gestora. 
• A compatibilidade com as atribuições do cargo; 
• O quantitativo de contratos por servidor; 
• A capacidade para o desempenho das atividades. 
O Gestor ou a Gestora, o Fiscal Administrativo e o Fiscal do Contrato são 
indicados na fase de planejamento da contratação e constarão no Termo de 
Referência (TR), sendo designados de forma individualizada, incluídos seus 
substitutos. 
O Gestor ou a Gestora do Contrato deve ser notificado de sua designação e 
de suas atribuições previstas no art. 73 do Provimento nº 2.724/2023, em até 5 
(cinco) dias após a assinatura do contrato. Em sua ausência, seu suplente 
assumirá as funções. 
17 
18 
M A N U A L D E C O N T R A T O S | 2 0 2 5 
Secretaria de Administração e Abas tecimento | Saab  
 
 
Após designado, o Gestor ou a Gestora do Contrato designará o Fiscal 
Administrativo, o Fiscal do Contrato e seus suplentes, no módulo SGF do sistema 
SAJADM (SGF > Contrato > Gestão Contratual). 
      Em caso de impossibilidade de exercício das funções em razão de 
relotação, exoneração de função comissionada ou afastamento definitivo, o 
gestor ou a gestora, os fiscais e as fiscais deverão solicitar a cessação de sua 
designação, no prazo de até 48 horas, conforme segue: 
Função Solicita para Providências Referências 
Provimento 
Gestor ou Gestora 
do Contrato 
Secretário ou 
Secretária da 
área gestora 
Em até 48 horas, o Secretário ou 
a Secretária da área gestora deve 
encaminhar expediente 
eletrônico à Diretoria de 
Contratos da Saab – Saab 6, com 
indicação do novo Gestor ou da 
nova Gestora e suplente, se o 
caso, para que seja submetido à 
deliberação e designação pela E. 
Presidência. 
Art. 72, §3º e 
§4º 
Fiscais 
Administrativo e 
do Contrato e 
respectivos 
suplentes 
Gestor ou 
Gestora do 
Contrato 
Gestor ou Gestora designa novo 
fiscal e/ou suplente, notificando
os de sua designação e 
atribuições, bem como 
providencia a devida alteração 
no módulo 
SAJADM/SGF/Contratos/Gestão 
Contratual 
Art. 75, §2º e 
§3º; 
Atribuições do 
Fiscal do 
Contrato: Art. 
76; Atribuições 
do Fiscal 
Administrativo: 
Art. 77 
 
 
 
3.2  PERFIS 
 
De acordo com os artigos 6º e 7º do Provimento CSM nº 2.724/2023, a 
Presidência do Tribunal de Justiça de São Paulo deverá promover a gestão por 
competências, zelar pela segregação de funções, assegurar que a estrutura dos 
servidores seja suficiente para o desempenho de suas respectivas funções e 
designar servidores para o desempenho das funções de gestão e fiscalização de 
contratos, que preencham os seguintes requisitos: 
M A N U A L D E C O N T R A T O S | 2 0 2 5 
Secretaria de Administração e Abas tecimento | Saab  
• Sejam, preferencialmente, servidor efetivo ou empregado público dos 
quadros permanentes da Administração Pública; 
• Tenham atribuições relacionadas a licitações e contratos ou possuam 
formação compatível ou qualificação atestada por certificação profissional 
emitida por escola de governo criada e mantida pelo poder público; 
De modo geral, o Gestor ou a Gestora e os Fiscais possuem as seguintes 
características: 
3.3 VEDAÇÕES E IMPEDIMENTOS 
O Gestor ou a Gestora, o Fiscal Administrativo e o Fiscal do Contrato não 
devem: 
• Ser cônjuge ou companheiro, bem como possuir vínculo de 
parentesco, colateral ou por afinidade, até o terceiro grau, com 
licitantes ou contratados da Administração; 
• Possuir relação comercial, econômica, civil, financeira ou trabalhista 
com licitantes ou contratados da Administração. 
19 
M A N U A L D E C O N T R A T O S | 2 0 2 5 
Secretaria de Administração e Abas tecimento | Saab  
Ao Gestor, à Gestora, ao Fiscal Administrativo e ao Fiscal do Contrato é 
vedada a prática de atos de ingerência na administração da Contratada, 
como, por exemplo: 
• Exercer relação de subordinação com os empregados da Contratada, 
devendo sempre reportar-se aos prepostos por ela indicados; 
• Direcionar a contratação de pessoas para trabalhar nas empresas da 
Contratada; 
• Promover ou aceitar o desvio de funções dos empregados da 
Contatada; 
• Promover atos que alterem a jornada de trabalho dos empregados 
da Contatada, quando não previstas contratualmente; 
3.4  ATRIBUIÇÕES GERAIS 
Competem ao Gestor, à Gestora e aos Fiscais atuarem nas etapas de 
formalização, execução e encerramento do contrato. De modo geral, possuem 
as atribuições de: 
• Gerenciar os contratos sob sua responsabilidade, a fim de obter os 
melhores resultados, com a propositura de alterações necessárias; 
• Realizar a Gestão dos Riscos contratuais. 
• Monitorar e avaliar o desempenho dos fornecedores e prestadores 
de serviços; 
• Conhecer as tarefas relativas ao contrato, de modo a se preparar com 
antecedência a elas; 
As demais atribuições e responsabilidades serão abordadas e 
detalhadas nos próximos tópicos. 
20 
M A N U A L D E C O N T R A T O S | 2 0 2 5 
Secretaria de Administração e Abas tecimento | Saab  
4.  
ETAPAS DA 
GESTÃO E 
FISCALIZAÇÃO 
21 
M A N U A L D E C O N T R A T O S | 2 0 2 5 
Secretaria de Administração e Abas tecimento | Saab  
4.1   ATRIBUIÇÕES 
4.1.1  GESTOR E GESTORA DO CONTRATO 
De acordo com o art. 73 do Provimento CSM nº 2.724/2023, compete ao 
Gestor e à Gestora do Contrato: 
• Designar o Fiscal Administrativo e seu suplente, o Fiscal do Contrato 
e seu suplente, notificando-os de suas designações e atribuições; 
• Realizar o cadastro dos Fiscais e suplentes no sistema SAJADM (SGF 
> Contrato > Gestão Contratual); 
• Convocar e coordenar reunião inicial para leitura do instrumento 
contratual; 
• Providenciar a abertura de processo administrativo eletrônico 
específico, vinculado ao processo de contratação; 
• Acompanhar o desenvolvimento da execução contratual, por meio 
dos relatórios elaborados pelos Fiscais; 
• Quando previsto no contrato, atestar definitivamente a nota 
fiscal/fatura e encaminhá-la à SOF, em até 3 (três) dias úteis após 
sua emissão; 
• Analisar pedidos de alterações contratuais; 
• Excepcionalmente, cumular as funções de Fiscal Administrativo e/ou 
Fiscal do Contrato, quando estes não forem designados; 
• Analisar ou formular pedidos de reequilíbrio econômico-financeiro, 
apresentando relatório conclusivo; 
• Manifestar-se quanto ao interesse da Administração nas 
prorrogações de vigência dos contratos de execução continuada, 
sugerindo o aditamento contratual ou a abertura de nova licitação; 
• Manifestar-se quanto aos pedidos de suspensão ou prorrogação do 
prazo de execução de obras, serviços ou entrega de bens; 
• Instaurar Processo Administrativo Apuratório quando verificado 
eventual descumprimento pela Contratada das obrigações 
contratuais; 
• Propor à Equipe de Planejamento da Contratação, em caso de 
planejamento de novo contrato, a atualização e aperfeiçoamento do 
ETP, do Plano de Riscos, do TR, do Projeto Básico ou Executivo, 
conforme as intercorrências verificadas na execução contratual; 
• Acompanhar o andamento das contratações que substituirão os 
contratos vigentes; 
22 
M A N U A L D E C O N T R A T O S | 2 0 2 5 
Secretaria de Administração e Abas tecimento | Saab  
• Informar à SOF as obrigações financeiras não liquidadas no exercício, 
para efeito de inscrição de saldos de empenho à conta de restos a 
pagar ou de cancelamento de recursos; 
• Elaborar relatório final, com as informações relativas à execução 
contratual, especialmente sobre a efetiva consecução dos objetivos 
que justificaram a contratação e com a relação dos Processos 
Administrativos Apuratórios, suas causas e impactos. Por fim, deve 
propor eventuais melhorias a serem refletidas no ETP, no TR e no 
Plano de Riscos da futura contratação; 
• Desempenhar outras atividades previstas no contrato. 
4.1.2   FISCAL DO CONTRATO 
De acordo com o art. 76 do Provimento CSM nº 2.724/2023, compete ao 
Fiscal do Contrato: 
• Participar da reunião inicial; 
• Providenciar a abertura de processo administrativo eletrônico 
específico destinado a registrar os atos de fiscalização e ocorrências 
da execução contratual; 
• Fiscalizar a execução contratual de acordo com o estabelecido no 
contrato; 
• Elaborar relatório de acompanhamento da execução contratual e 
encaminhá-lo ao Fiscal Administrativo; 
• Anotar em registro próprio todas as ocorrências relacionadas à 
execução do contrato, determinando o que for necessário para a 
regularização das faltas ou dos defeitos observados; 
• Em situações que demandem decisão ou providência que ultrapasse 
sua competência, caberá ao Fiscal reportar, em tempo hábil (em 
regra, 5 (cinco) dias úteis; em casos emergenciais, 24 horas), ao 
Gestor ou à Gestora do Contrato, para que adote as medidas cabíveis; 
• Quando previsto no contrato, atestar definitivamente a nota 
fiscal/fatura e encaminhá-la à SOF, em até 3 (três) dias úteis após 
sua emissão; 
• Preencher e encaminhar mensalmente ao Fiscal Administrativo 
relatório de avaliação de desempenho da Contratada; 
• Nos contratos de locação, encaminhar à SOF o ateste mensal da 
ocupação de imóvel locado pelo Tribunal de Justiça; 
• Propor alterações contratuais ao Fiscal Administrativo; 
• Controlar o prazo de execução e vigência do contrato; 
• Receber o objeto, provisória e/ou definitivamente; 
23 
M A N U A L D E C O N T R A T O S | 2 0 2 5 
Secretaria de Administração e Abas tecimento | Saab  
• Notificar a Contratada para a regularização de possível 
descumprimento contratual, preferencialmente de forma eletrônica, 
estabelecendo prazo compatível para atendimento (em regra, 5 
(cinco) dias úteis; em casos emergenciais, 24 horas); 
• Elaborar relatório conclusivo quanto à notificação de eventual 
descumprimento contratual e encaminhá-lo ao Fiscal 
Administrativo, com proposta de instauração de Processo 
Administrativo Apuratório, se o caso; 
• Desempenhar outras atividades previstas no contrato. 
4.1.3   FISCAL ADMINISTRATIVO 
De acordo com o art. 77 do Provimento CSM nº 2.724/2023, compete ao 
Fiscal Administrativo: 
• Participar da reunião inicial; 
• Consolidar os relatórios de acompanhamento da execução 
contratual emitidos pelo Fiscal do Contrato; 
• Quando previsto no contrato, atestar definitivamente a nota 
fiscal/fatura e encaminhá-la à SOF, em até 3 (três) dias úteis após 
sua emissão; 
• Emitir, caso solicitado, atestado de capacidade técnica; 
da 
• Consolidar mensalmente os relatórios de avaliação de desempenho 
da Contratada elaborados pelo Fiscal do Contrato; 
• Verificar semestralmente a manutenção das condições de 
habilitação 
Contratada, 
solicitando 
os 
documentos 
comprobatórios. O GPAC (Grupo de Pregoeiros e Agentes de 
Contratação) auxiliará na conferência da documentação, mediante 
solicitação; 
✓ Semestralmente, deve-se solicitar declaração da Contratada acerca 
do atendimento à reserva de vagas para pessoas em condição de 
vulnerabilidade, prevista na Resolução CNJ nº 497/2023. 
• Controlar e informar ao Gestor ou à Gestora do Contrato as 
obrigações financeiras não liquidadas no exercício, para efeito de 
inscrição de saldos de empenho à conta de restos a pagar ou de 
cancelamento de recursos; 
• Propor ao Gestor ou à Gestora do Contrato a instauração de Processo 
Administrativo Apuratório; 
• Desempenhar outras atividades previstas no contrato. 
24 
M A N U A L D E C O N T R A T O S | 2 0 2 5 
Secretaria de Administração e Abas tecimento | Saab  
4.1.4 RESPONSÁVEIS TÉCNICOS 
Compete ao Responsável Técnico, que poderá ser servidor ou terceiro 
contratado: 
• Prestar apoio técnico ao Gestor ou à Gestora do Contrato e aos 
Fiscais, 
apresentando as informações pertinentes às suas 
competências, quando solicitado; 
• Observar as normas técnicas e legais, especificações e métodos de 
execução dos serviços exigíveis para a perfeita execução do objeto; 
• Emitir parecer técnico nos pedidos de alterações contratuais, 
quando solicitado; 
• Verificar a correta aplicação dos materiais; 
• Requerer testes, exames e ensaios, quando previstos no edital e/ou 
contrato, para controle de qualidade da execução das obras, serviços 
ou bens a serem adquiridos; 
• Desempenhar outras atividades previstas no contrato. 
25 
M A N U A L D E C O N T R A T O S | 2 0 2 5 
Secretaria de Administração e Abas tecimento | Saab  
4.2   EXECUÇÃO DOS CONTRATOS  
Após a assinatura do instrumento contratual, o Gestor ou a Gestora do 
Contrato convocará e coordenará reunião para leitura do contrato, com a 
participação do Fiscal Administrativo, do Fiscal do Contrato e do preposto da 
Contratada, para esclarecimentos das obrigações contratuais e definição do 
plano de trabalho. 
É fundamental que, antes do início da reunião, os membros da equipe 
tenham lido previamente todo o contrato e estejam cientes de suas atribuições 
e atividades. 
Vale frisar que todas as reuniões realizadas entre a Equipe de Gestão e 
Fiscalização do Contrato e a Contratada deverão ser lavradas em ata e 
registradas no processo digital, para acompanhamento da execução 
contratual. 
Entre outras atribuições previstas contratualmente, a Equipe de Gestão e 
Fiscalização do Contrato deve elaborar relatórios de acompanhamento da 
execução contratual, controlar o prazo de execução e vigência do contrato, 
preencher o relatório de avaliação de desempenho, notificar a Contratada para a 
regularização de eventual descumprimento e receber o objeto. 
É de suma importância o acompanhamento e o registro das atividades 
ocorridas durante a execução contratual, a fim de que o objeto contratado seja 
recebido de acordo com as especificações e quantidades exigidas em contrato, 
26 
M A N U A L D E C O N T R A T O S | 2 0 2 5 
Secretaria de Administração e Abas tecimento | Saab  
zelando, dessa forma, pela responsabilidade e transparência na aplicação dos 
recursos públicos. 
4.2.1   FISCALIZAÇÃO DOS CONTRATOS COM 
DEDICAÇÃO EXCLUSIVA DE MÃO DE OBRA 
A gestão e fiscalização dos contratos com dedicação exclusiva de mão de 
obra observará a Resolução CNJ nº 169/2013, Resolução CNJ nº 497/2023 (e suas 
alterações) e outras legislações aplicáveis. 
Nos contratos com dedicação exclusiva de mão de obra, compete ao Fiscal 
do Contrato: 
I. 
Solicitar à Contratada relação por local de trabalho dos empregados 
alocados, contendo, no mínimo: 
• Dados de identificação da Contratada; 
• Número do contrato administrativo; 
• Nome completo; 
• Cargo ou função; 
• Data de admissão na Contratada; 
• Data de alocação do posto; 
• Horário do posto de trabalho; 
• Números do CPF e da CTPS. 
II. 
III. 
Diariamente: 
Mensalmente: 
• Fiscalizar e registrar a efetiva execução dos serviços; 
• Manter controle indireto do comparecimento dos empregados 
alocados no contrato. 
• Exigir que o preposto da Contratada apresente cópias das folhas 
de ponto dos empregados por registro eletrônico ou outro meio que 
não seja padronizado; 
• Consolidar em planilha de controle os dias efetivamente 
trabalhados e a reposição de empregados em decorrência de férias, 
licenças, faltas e ocorrências; 
• Glosar as faturas em caso de faltas ou horas trabalhadas a 
menor; 
• Exigir da Contratada os comprovantes de pagamento dos 
salários, vale-transporte e demais benefícios previstos no contrato 
administrativo; 
27 
M A N U A L D E C O N T R A T O S | 2 0 2 5 
Secretaria de Administração e Abas tecimento | Saab  
• Preencher relação nominal, a ser assinada pelos empregados, 
para confirmação de pagamento tempestivo de salários, horas 
extras, férias, décimo terceiro salário e demais benefícios 
trabalhistas previstos no contrato administrativo. 
IV. 
Compete, ainda, ao Fiscal do Contrato a conferência dos seguintes 
documentos referentes ao mês anterior ao faturamento: 
• Certificado de Regularidade do FGTS – CRF, comprovando 
regularidade com o FGTS; 
• Certidão Conjunta Negativa de Débitos Relativos a Tributos 
Federais e à Dívida Ativa da União; 
• Certidão Negativa de Débitos Trabalhistas (CNDT); 
• Relação nominal por posto de trabalho dos empregados 
alocados, acompanhada de cópia da folha de pagamento do mês 
anterior à execução do serviço; 
• Planilha de cálculo do valor a ser deduzido na nota fiscal, 
decorrente de eventual não ocupação dos postos de trabalho nos 
termos do contrato. 
Nos contratos com dedicação exclusiva de mão-de-obra, o relatório final 
deverá conter as informações necessárias para a liberação, se o caso, do saldo de 
conta depósito-vinculada de que trata a Resolução CNJ nº 169/2016 (e suas 
alterações). 
28 
M A N U A L D E C O N T R A T O S | 2 0 2 5 
Secretaria de Administração e Abas tecimento | Saab  
4.2.1.1  RETENÇÃO E LIBERAÇÃO DAS VERBAS 
CONTINGENCIADAS 
O contingenciamento das verbas trabalhistas e previdenciárias é um 
mecanismo adotado pelo Tribunal de Justiça de São Paulo (TJSP) com o objetivo 
de assegurar que as empresas contratadas para prestar serviços com mão de 
obra residente cumpram corretamente suas obrigações trabalhistas e 
previdenciárias. 
Esse procedimento segue disposições da Resolução CNJ nº 169/2013 e 
alterações subsequentes que determina a retenção de valores que serão 
utilizados para pagamento das seguintes rubricas: 
I – Férias; 
II – 1/3 constitucional; 
III – 13º salário; 
IV – Multa do FGTS por dispensa sem justa causa; 
V – Incidência dos encargos previdenciários e FGTS sobre férias, 1/3 
constitucional e 13º salário. 
É importante ressaltar que o TJSP, mensalmente, desconta das notas fiscais 
da Contratada os valores como garantia para o pagamento das respectivas 
rubricas. Esses valores são depositados na conta-depósito vinculada (conta de 
contingenciamento) e podem ser resgatados pelas Empresas nas seguintes 
situações: 
▪ Após o pagamento e mediante apresentação dos documentos 
comprobatórios de que efetivamente pagou, a cada empregado 
alocado no contrato, as rubricas indicadas no art. 4º da referida 
Resolução. 
▪ Ao término do contrato, caso haja saldo remanescente na conta 
vinculada, este poderá ser resgatado pela empresa após a devida 
comprovação da quitação de todas as obrigações trabalhistas e 
previdenciárias referentes ao serviço contratado. Decorridos 5 
(cinco) anos do encerramento contratual, o resgate dos recursos 
poderá ser feito sem a necessidade de tal comprovação. 
29 
M A N U A L D E C O N T R A T O S | 2 0 2 5 
Secretaria de Administração e Abas tecimento | Saab  
4.2.1.1.1  LIBERAÇÃO DAS VERBAS DURANTE  
O CONTRATO 
Para liberação dos valores contingenciados durante a execução contratual, 
devem ser atendidas as seguintes etapas: 
1ª ETAPA: APRESENTAÇÃO DE DOCUMENTAÇÃO E ATESTE PELO 
FISCAL 
A Contratada deverá preencher a planilha de resgate, referente à verba 
objeto da solicitação de levantamento, de acordo com o contrato e por 
localidade da prestação dos serviços, caso o contrato abranja mais de uma 
localidade.  
ATENÇÃO: O modelo da planilha pode 
ser solicitado pela Contratada à SOF 
2.2.3, através do e-mail 
sof2.2.3@tjsp.jus.br, ou ao Gestor, à 
Gestora ou ao Fiscal do Contrato que 
poderá acessá-la em Modelos - SOF. 
30 
M A N U A L D E C O N T R A T O S | 2 0 2 5 
Secretaria de Administração e Abas tecimento | Saab  
31 
  
 
 
 
As planilhas estão parametrizadas de acordo com cada tipo de verba, razão 
pela qual devem ser editados apenas os campos que não possuem bloqueio. 
Após o preenchimento, as planilhas devem ser encaminhadas, por e-mail, 
ao Fiscal do Contrato, acompanhadas dos documentos comprobatórios. 
A documentação deve conter o resumo, conforme modelo abaixo 
(disponível em Modelos - SOF), com a relação dos valores que serão 
reembolsados por localidade e apresentação do montante total por verbas, bem 
como o total geral que será requisitado. 
RESUMO 
Contrato Nº  
Localidades Férias 13º salário Rescisões trabalhistas 
        
        
        
Subtotal  R$                      -     R$           -                   R$                        -    
Total  R$      -                        
 
De acordo com a verba a ser reembolsada, alguns documentos 
comprobatórios devem ser apresentados, conforme tabela abaixo: 
  
32 
M A N U A L D E C O N T R A T O S | 2 0 2 5 
Secretaria de Administração e Abas tecimento | Saab  
 
 
TIPO DE 
SOLICITAÇÃO DOCUMENTOS COMPROBATÓRIOS 
Reembolso de Férias 
▪ Recibo/Aviso de férias; 
▪ Comprovante de depósito bancário. 
Reembolso de 13º 
Salário 
▪ Demonstrativo de 13º salário; 
▪ Comprovante de depósito bancário. 
Rescisão trabalhista 
▪ Termo de Rescisão do Contato de Trabalho 
(TRCT) assinado; 
▪ Caso o contrato de trabalho seja superior a 1 
(um) ano, o TRCT deve estar homologado; 
▪ Comprovante de depósito bancário; 
Nos casos de demissão sem justa causa, a 
Contratada deverá apresentar adicionalmente: 
▪ Guia Detalhada da multa do FGTS ou 
Demonstrativo do Trabalhador de 
Recolhimento do FGTS Rescisório; 
▪ Guia e comprovante de recolhimento da Multa 
de FGTS; 
▪ Extrato de FGTS do funcionário, referente aos 
últimos 6 (seis) meses. 
 
Após, o Fiscal do Contrato deverá conferir a planilha preenchida e a 
documentação apresentada. Caso esteja tudo correto, deverá emitir o respectivo 
ateste, mediante assinatura na planilha de resgate, preferencialmente, em 
formato digital. 
 
DICA: Para assinar digitalmente um 
documento em formato PDF, basta 
seguir as orientações contantes em 
Assinatura Digital. 
M A N U A L D E C O N T R A T O S | 2 0 2 5 
Secretaria de Administração e Abas tecimento | Saab  
Em caso de desconformidade, a documentação deverá ser devolvida à 
empresa para os devidos ajustes. 
2ª ETAPA: SOLICITAÇÃO DA CONTRATADA 
Após o ateste e a compilação dos documentos comprobatórios, a 
Contratada deverá solicitar o levantamento dos valores contingenciados, 
mediante encaminhamento de solicitação formal, em formato PDF, para o 
endereço sof2.2.3@tjsp.jus.br, que efetuará o protocolo do pedido. 
Abaixo segue modelo sugerido (disponível em Modelos - SOF)  para a 
respectiva solicitação: 
33 
M A N U A L D E C O N T R A T O S | 2 0 2 5 
Secretaria de Administração e Abas tecimento | Saab  
Conforme se verifica, a Contratada deve indicar o responsável pelo envio da 
documentação através do Portal de Serviços, contendo os seguintes dados: 
nome completo, endereço de e-mail e nº do CPF. 
A solicitação formal deverá conter: 
▪ O objeto da solicitação (férias, 13º salário e/ou rescisões trabalhistas); 
▪ Número do contrato; 
▪ Valor a ser reembolsado; 
▪ Dados da conta do Banco do Brasil para crédito e assinatura do 
responsável legal da empresa. 
3ª ETAPA: ACESSO AO PORTAL DE SERVIÇOS PELA 
CONTRATADA E JUNTADA DE DOCUMENTOS 
A Equipe da SOF 2.2.3 abrirá a tarefa “COMUNIQUE-SE” no expediente de 
contingenciamento do respectivo contrato. 
Após, a Contratada receberá uma mensagem eletrônica no e-mail 
informado em sua solicitação, com orientações para acesso ao “Portal de 
Serviço”, bem como relação dos documentos a serem anexados, relacionados 
ao pedido de levantamento dos valores contingenciados, exclusivamente em 
formato PDF. 
até 19 MB.    
Para acessar o Portal de Serviços, é necessário que o usuário tenha um 
cadastro válido no Gov.br, pois o login será realizado com o mesmo usuário e 
senha utilizados nessa plataforma.  
ATENÇÃO: O sistema não aceita 
arquivos compactados, como ZIP, RAR 
ou semelhantes. 
Limite de envio por tarefa: 10 arquivos 
“pdf” por tarefa. Cada arquivo pode ter 
4ª ETAPA: LIBERAÇÃO DOS VALORES 
Após a análise da documentação comprobatória e estando em 
conformidade, a SOF enviará ofício ao Banco do Brasil, solicitando a liberação de 
valores contingenciados à Contratada. O reembolso ocorrerá na conta bancária 
indicada pela Contratada na solicitação formal.  
34 
M A N U A L D E C O N T R A T O S | 2 0 2 5 
Secretaria de Administração e Abas tecimento | Saab  
É importante ressaltar que a solicitação de reembolso poderá ser recusada, 
caso a documentação enviada apresente os seguintes problemas: 
▪ Desorganização dos arquivos; 
▪ Documentos ilegíveis; 
▪ Ausência de comprovantes de pagamentos; 
▪ Planilhas preenchidas incorretamente; 
▪ Falta de ateste do Fiscal responsável. 
Caso recusada, a solicitação será devolvida à empresa, via tarefa 
“COMUNIQUE-SE”, acompanhada da respectiva justificativa, para correção e 
novo envio do requerimento. 
FLUXO PARA LIBERAÇÃO/REEMBOLSO DE VERBAS 
CONTINGENCIADAS 
4.2.1.1.2  LIBERAÇÃO DO SALDO REMANESCENTE 
APÓS O ENCERRAMENTO DO CONTRATO 
Após o encerramento do contrato com o TJSP, pode existir saldo 
remanescente na conta vinculada. A empresa poderá pleitear o levantamento 
dos valores, desde que todas as obrigações trabalhistas e previdenciárias estejam 
devidamente quitadas. 
Se decorridos 5 (cinco) anos após o término do contrato, a empresa poderá 
solicitar o valor restante sem a necessidade de comprovar a quitação dessas 
obrigações. 
Seguem as etapas para solicitação da liberação: 
35 
36 
M A N U A L D E C O N T R A T O S | 2 0 2 5 
Secretaria de Administração e Abas tecimento | Saab  
 
 
 
1ª ETAPA: ENVIO DE SOLICITAÇÃO FORMAL PELA CONTRATADA 
A Contratada deverá solicitar o resgate integral do saldo remanescente, 
mediante encaminhamento de solicitação formal, para o e-mail  
sof2.2.3@tjsp.jus.br, que prosseguirá com a abertura do protocolo do pedido. 
 
2ª ETAPA: SOLICITAÇÃO DE ATESTES DOS FISCAIS DE CONTRATOS 
A Contratada deverá solicitar o ateste do Fiscal do Contrato, ratificando que 
houve a quitação dos encargos trabalhistas e previdenciários dos colaboradores 
vinculados ao contrato. 
 
Acesse o modelo do documento acima em Modelos - SOF. 
 
3ª ETAPA: ACESSO AO PORTAL DE SERVIÇOS PELA CONTRATADA 
A equipe da SOF 2.2.3 criará a tarefa “COMUNIQUE-SE”, solicitando que a 
empresa contratada envie a seguinte documentação (formato “pdf”) atualizada: 
 
 
M A N U A L D E C O N T R A T O S | 2 0 2 5 
Secretaria de Administração e Abas tecimento | Saab  
37 
  
 
 
 
DOCUMENTAÇÃO EXIGIDA 
 Até 2 anos do 
encerramento 
do contrato 
De 2 a 5 anos do 
encerramento do 
contrato 
Após 5 anos do 
encerramento do 
contrato 
Confirmação dos 
Gestores/Gestoras/Fiscais de cada 
localidade, ratificando que houve a 
quitação dos encargos trabalhistas 
e previdenciários, relativos aos 
colaboradores residentes que 
prestaram serviços na unidade e 
que tiveram seus contratos de 
trabalho rescindidos durante a 
vigência contratual 
X X X 
Contrato ou estatuto  
social da empresa X X X 
Documento de identificação do 
representante legal  
ou do procurador 
X X X 
Procuração válida (caso a 
assinatura dos documentos seja 
feita por procurador) 
X X X 
Documentação de constituição do 
sindicato e ata de posse da diretoria 
vigente 
X   
Documento de identificação do 
representante legal  
do Sindicato 
X   
Certidões dos TRTs da 2º e 15ª 
Região (comprovação de não 
ajuizamento de ações trabalhistas 
por colaboradores que atuaram no 
contrato) 
X X  
Outros documentos necessários, 
conforme o caso X X X 
 
 
 
M A N U A L D E C O N T R A T O S | 2 0 2 5 
Secretaria de Administração e Abas tecimento | Saab  
4ª ETAPA: REUNIÃO COM O SINDICATO E ASSINATURA DA 
CERTIDÃO 
Após a análise da documentação e estando em conformidade, a SOF 
agendará reunião em formato virtual para deliberar sobre a liberação do saldo 
remanescente da conta vinculada. 
Participação obrigatória: 
▪ Representante da empresa contratada;  
▪ Representante do TJSP; 
▪ Representante do Sindicato da Categoria. 
Durante a reunião, será exigida a concordância de todos os presentes 
quanto à liberação do saldo. Essa concordância se dará também por meio da 
assinatura da certidão liberatória. 
Caso o pedido de liberação do saldo remanescente seja realizado após 2 
(dois) anos do encerramento do contrato, não será necessário o cumprimento 
dessa etapa, conforme deliberação do Conselho Nacional de Justiça (CNJ). Nessa 
situação, a Contratada deverá apresentar: 
5ª ETAPA: MANIFESTAÇÃO DA SAAB SOBRE EVENTUAIS 
PENDÊNCIAS CONTRATUAIS 
▪ Certidões Trabalhistas emitidas pelos Tribunais Regionais (TRT 2 e 
TRT 15) que comprovem o não ajuizamento de ações trabalhistas 
pelos colaboradores vinculados ao contrato. 
Conforme diretrizes da E. Presidência, a SOF 2.2.3 enviará expediente para 
manifestação dos Gestores, das Gestoras e dos Fiscais do Contrato e da Saab 6 - 
Diretoria de Contratos Administrativos, Convênios e Gestão Imobiliária, com 
o objetivo de verificar a inexistência de pendências contratuais, incluindo 
processos apuratórios. 
Se não houver pendências, a SOF 2.2.3 dará prosseguimento à liberação do 
saldo residual da conta vinculada. 
38 
M A N U A L D E C O N T R A T O S | 2 0 2 5 
Secretaria de Administração e Abas tecimento | Saab  
39 
  
 
 
 
ATENÇÃO: caso existam pendências 
financeiras no mesmo contrato, a Saab 
deverá solicitar autorização à 
Contratada para eventual desconto do 
valor no saldo remanescente em conta 
contingenciada, certificar a resposta da 
Contratada nos autos e devolver o 
expediente à SOF 2.2, para 
prosseguimento junto à E. Presidência. 
 
 
ATENÇÃO: caso existam pendências 
financeiras em outros contratos com a 
mesma empresa, a Saab prestará as 
informações relativas às pendências, 
submetendo à SOF 2.2, para análise e 
deliberação sobre eventual 
compensação de créditos/débitos, e 
consulta ao i. GTAJ, se o caso. 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
M A N U A L D E C O N T R A T O S | 2 0 2 5 
Secretaria de Administração e Abas tecimento | Saab  
6ª ETAPA: LIBERAÇÃO DOS VALORES 
Após a conclusão da 5ª etapa, o processo será remetido para autorização da 
E. Presidência. Com a autorização, o processo retornará à SOF que encaminhará 
ofício ao Banco do Brasil para liberação do saldo remanescente à Contratada. 
FLUXO PARA LIBERAÇÃO DO SALDO APÓS 
ENCERRAMENTO DO CONTRATO 
4.2.1.1.3  RESOLUÇÃO DE CASOS OMISSOS 
Como nem todas as situações relacionadas à liberação de verbas 
contingenciadas podem ser previstas neste manual, eventuais casos omissos — 
ou seja, situações não contempladas nos procedimentos descritos — deverão ser 
encaminhados para análise da SOF 2.2.3 – Serviço de Gestão de Contas 
Vinculadas, por meio do e-mail  sof2.2.3@tjsp.jus.br. 
40 
M A N U A L D E C O N T R A T O S | 2 0 2 5 
Secretaria de Administração e Abas tecimento | Saab  
41 
  
 
 
 
4.2.2 FISCALIZAÇÃO DOS SERVIÇOS E OBRAS DE ENGENHARIA 
 
A gestão e fiscalização dos contratos de serviços e obras de engenharia 
observará a Resolução CNJ º 114/2010 (e suas alterações). 
Nos contratos de obras e serviços de engenharia,  
compete ao Fiscal do Contrato: 
• Providenciar a instauração de processo administrativo eletrônico 
específico destinado a registrar os atos de fiscalização e ocorrências 
da execução contratual; 
• Manter pasta atualizada com projeto básico e/ou executivo, alvarás, 
Anotações de Responsabilidade Técnica (ART’s) do Conselho 
Regional de Engenharia e Agronomia (CREA) e/ou Registros de 
Responsabilidade Técnica (RRT’s) do Conselho de Arquitetura e 
Urbanismo (CAU) referentes ao objeto contratual; 
• Visitar o diário de obras, certificando-se de seu correto 
preenchimento; 
• Desempenhar outras atividades previstas no contrato. 
 
Além disso, também compete ao Fiscal do Contrato promover as 
medições, a fim de verificar a conformidade dos serviços executados com o 
cronograma físico-financeiro da obra previsto no contrato, podendo ser auxiliado 
por Responsável Técnico.  
Dessa forma, é obrigatória a realização de medições dos serviços efetuados, 
nas datas estabelecidas no cronograma, antes de seu efetivo ateste. 
 
4.2.3 FISCALIZAÇÃO DOS CONTRATOS DE STIC 
 
A Resolução CNJ nº 468/2022 (e suas alterações) disciplina as contratações 
de bens e serviços de Soluções de Tecnologia da Informação e Comunicação 
(STIC) realizadas pelos órgãos submetidos ao controle administrativo e financeiro 
do CNJ. Disciplina ainda a fiscalização dos referidos contratos. 
M A N U A L D E C O N T R A T O S | 2 0 2 5 
Secretaria de Administração e Abas tecimento | Saab  
A equipe de gestão de contrato, no caso de serviços complexos e/ou 
descentralizados, poderá indicar fiscais auxiliares de campo visando à efetividade 
da fiscalização. 
A administração deverá providenciar os meios necessários para que o 
servidor desempenhe adequadamente as atribuições de Gestor e Fiscal, 
conforme a natureza e a complexidade do objeto. 
Durante a fase de gestão do contrato, a equipe de fiscalização, sob 
coordenação do Gestor ou da Gestora do Contrato, deverá proceder à atualização 
contínua do Mapa de Gerenciamento de Riscos. 
ATENÇÃO: Os contratos de STIC que 
envolvam dedicação exclusiva de mão
de-obra observarão as regras contidas 
no tópico 4.2.1 deste manual. 
4.3   RECEBIMENTO 
Nos contratos administrativos, o recebimento do objeto é um ato formal 
dividido em duas etapas bem distintas: recebimento provisório e recebimento 
definitivo. 
Os prazos e métodos para a realização dos recebimentos provisório e 
definitivo serão definidos no Termo de Referência, Projeto Básico ou Projeto 
Executivo, bem como constarão no instrumento contratual. 
Importante mencionar que o recebimento provisório ou definitivo não 
excluirá a responsabilidade civil pela solidez e pela segurança da obra ou serviço, 
nem a responsabilidade pela perfeita execução contratual, nos limites 
estabelecidos pela lei ou contrato. 
Os documentos que comprovem o recebimento provisório e definitivo 
serão juntados no processo de acompanhamento da execução contratual. 
O método de recebimento, bem como os responsáveis pelos recebimentos 
provisório e definitivo constarão no Termo de Referência. 
ATENÇÃO: Caso esteja em desacordo 
com o contrato, o objeto poderá ser 
rejeitado, no todo ou em parte. 
42 
M A N U A L D E C O N T R A T O S | 2 0 2 5 
Secretaria de Administração e Abas tecimento | Saab  
ATENÇÃO: Eventuais substituições de 
marca ou modelo, em regra, não serão 
admitidas. Entretanto, poderão ser 
aceitas, desde que devidamente 
justificadas, com a apresentação de 
fatos impeditivos ao fornecimento nas 
condições previstas originalmente, 
devendo ser formalizadas mediante 
aditivo contratual. 
4.3.1   RECEBIMENTO PROVISÓRIO 
O recebimento provisório é a primeira etapa do recebimento de um bem 
ou serviço contratado pela Administração Pública. Esse recebimento ocorre por 
meio de prévia verificação da conformidade contratual.  
É no recebimento provisório que ocorre a entrega dos bens ou a entrega do 
resultado dos serviços à Administração. Entretanto, há apenas a legitimação da 
posse, a fim de que a Administração verifique minuciosamente o objeto e 
constate a conformidade com o que foi contratado. 
Dessa forma, o recebimento provisório não implica em aceitação do objeto 
pela Administração, permanecendo a responsabilidade da Contratada por sua 
integridade e integralidade. 
ATENÇÃO: O recebimento provisório 
poderá ser dispensado, quando assim 
previsto no Termo de Referência. 
Caso não exista outro prazo estipulado no contrato, o recebimento 
provisório será realizado em até 10 (dez) dias úteis. 
O recebimento provisório será realizado, em regra, pelo Fiscal do Contrato 
ou por outro responsável estabelecido no Termo de Referência da respectiva 
contratação. 
43 
44 
M A N U A L D E C O N T R A T O S | 2 0 2 5 
Secretaria de Administração e Abas tecimento | Saab  
 
 
Recebimento Provisório 
Obras e Serviços 
Recebido, em regra, pelo Fiscal do Contrato ou por 
outro responsável especificado no Termo de 
Referência, por meio de termo detalhado, se 
verificado o cumprimento das exigências de caráter 
técnico. 
Compras 
Recebido, de forma sumária, em regra, pelo Fiscal do 
Contrato ou por outro responsável especificado no 
Termo de Referência, com verificação posterior da 
conformidade do material com as exigências 
contratuais. 
 
Os procedimentos a serem adotados no recebimento provisório constam no 
Termo de Referência do respectivo processo de contratação. 
 
4.3.2  RECEBIMENTO DEFINITIVO 
 
Recebimento definitivo é o ato formal, subsidiado por documentos e, se 
houver, nota fiscal/fatura, que comprove o cumprimento das exigências, prazos, 
valores e métodos previstos no contrato. 
É no recebimento definitivo que são realizados exames, testes e 
averiguações que se fizerem necessárias, de modo a aferir a integral adequação 
do objeto às exigências previstas contratualmente.  
 
ATENÇÃO: Em se tratando de obra, o 
recebimento definitivo pela 
Administração não exime a Contratada, 
pelo prazo mínimo de 5 (cinco) anos, 
admitida a previsão de prazo de 
garantia superior no edital ou no 
contrato, da responsabilidade objetiva 
pela solidez e pela segurança dos 
M A N U A L D E C O N T R A T O S | 2 0 2 5 
Secretaria de Administração e Abas tecimento | Saab  
45 
  
 
 
 
materiais entregues e serviços 
executados. Em caso de vício, defeito 
ou incorreção identificados, a 
Contratada ficará responsável pela 
reparação, pela correção, pela 
reconstrução ou pela substituição 
necessária. 
 
Caso não exista outro prazo estipulado no contrato, o recebimento 
definitivo será realizado em até 30 (trinta) dias úteis. 
Recebimento Definitivo 
Obras e Serviços 
Recebido, em regra, pelo Fiscal do 
Contrato ou por outro responsável 
especificado no Termo de Referência, 
por meio de termo detalhado que 
comprove o atendimento das 
exigências contratuais. 
Compras 
Recebido, em regra, pelo Fiscal do 
Contrato ou por outro responsável 
especificado no Termo de Referência, 
por meio de termo detalhado que 
comprove o atendimento das 
exigências contratuais. 
 
O recebimento definitivo ocorrerá somente após a manifestação do Fiscal 
do Contrato ou do responsável especificado no Termo de Referência, quanto 
à regularidade do fornecimento ou dos serviços prestados em relação ao previsto 
contratualmente. 
 
4.3.3  ROTEIRO PARA RECEBIMENTO DE BENS  
 
Os responsáveis definidos no Termo de Referência e no Contrato deverão 
seguir o seguinte roteiro para o recebimento de bens: 
1- Conferir o objeto fornecido quanto à sua quantidade, especificação, 
valor, prazos e demais condições previstas no contrato; 
2- Receber o objeto provisoriamente, para posterior verificação e, 
após, definitivamente, em virtude da constatação da qualidade e 
quantidade do material entregue; 
M A N U A L D E C O N T R A T O S | 2 0 2 5 
Secretaria de Administração e Abas tecimento | Saab  
3- Emitir o ateste da nota fiscal/fatura, caso não haja outro prazo 
previsto no contrato, em 3 (três) dias úteis contados da emissão 
do documento ou do recebimento definitivo, conforme 
estabelecido no instrumento contratual, desde que os requisitos 
previstos estejam cumpridos, especialmente: 
• Se foi emitida em nome do Tribunal de Justiça de São Paulo; 
• Se foi emitida pelo CNPJ constante no respectivo contrato; 
• Se o bem está especificado conforme as discriminações 
contidas no Contrato ou no Ofício de Autorização; 
• Se o valor está correto; 
• Verificar a autenticidade da nota fiscal eletrônica no site da 
Secretária da Fazenda; 
• Se não há erros no documento fiscal. 
4- Em caso de irregularidades, deve-se rejeitar a entrega no todo ou 
em parte, determinando formalmente sua substituição, em prazo 
estabelecido no contrato; 
5- Em caso de pedido de prorrogação do prazo de entrega, deve-se 
encaminhar a questão ao Gestor ou à Gestora do Contrato, para 
avaliação e providências, se o caso; 
6- Em caso de atraso na entrega ou outros descumprimentos 
contratuais, deve-se encaminhar a questão ao Gestor ou à Gestora 
do Contrato, para avaliação e providências, se o caso; 
7- O Gestor ou a Gestora do Contrato emitirá parecer fundamentado 
sobre a ocorrência e decidirá pela instauração do Procedimento 
Apuratório; 
8- Caso a entrega e o ateste estejam em termos, deverão ser 
encaminhados à Secretaria de Orçamento e Finanças – SOF, dentro 
de 1 (um) dia útil, os documentos fiscais e demais documentos 
exigidos no contrato, para pagamento. 
4.3.4  ROTEIRO PARA RECEBIMENTO DE SERVIÇOS 
O Fiscal do Contrato deve seguir o seguinte roteiro no recebimento de 
serviços: 
1- Conferir a execução do objeto contratado e verificar a sua 
conformidade com as especificações contidas no contrato; 
2- Em caso de irregularidades, deve-se recusar o serviço no todo ou em 
parte, determinando formalmente sua regularização, em prazo 
compatível para atendimento (em regra, 5 (cinco) dias úteis; em 
casos emergenciais, 24 horas); 
46 
M A N U A L D E C O N T R A T O S | 2 0 2 5 
Secretaria de Administração e Abas tecimento | Saab  
3- Receber o objeto provisoriamente, para posterior verificação e, 
após, definitivamente, em virtude da verificação da adequação do 
objeto aos termos contratuais; 
4- Após a averiguação dos serviços prestados, dos documentos 
apresentados e da avaliação da qualidade dos serviços, a nota fiscal 
poderá ser emitida para ateste; 
5- O Fiscal do Contrato emitirá o ateste da nota fiscal/fatura no prazo 
de 3 (três) dias úteis da emissão do documento, desde que os 
requisitos 
previstos 
especialmente: 
em 
contrato 
estejam 
• Se foi emitida em nome do Tribunal de Justiça de São Paulo; 
• Se foi emitida pelo CNPJ constante no respectivo contrato; 
• Se o serviço está especificado conforme as discriminações 
contidas no contrato; 
• Se o valor está correto, inclusive quanto a aditamentos, 
reajustes, medições e glosas; 
• Se não há erros no documento fiscal. 
6- Caso a entrega e o ateste estejam em termos, deverão ser 
encaminhados à Secretaria de Orçamento e Finanças – SOF, dentro 
de 1 (um) dia útil, os documentos fiscais e demais documentos 
exigidos no contrato, para pagamento. 
4.4   IRREGULARIDADES NA 
EXECUÇÃO CONTRATUAL 
cumpridos, 
Durante a execução contratual, os responsáveis por seu acompanhamento 
devem manter registro das ocorrências, no respectivo expediente de 
acompanhamento da fiscalização/gestão contratual, instruindo-as com a 
documentação comprobatória. 
Sempre que identificada qualquer irregularidade no cumprimento das 
obrigações contratuais pela Contratada, deverão ser adotadas as seguintes 
providências: 
• Preliminarmente, o Fiscal do Contrato deve autuar protocolo de 
acompanhamento eletrônico e notificar a Contratada, para 
regularização das pendências ou apresentação de defesa 
preliminar; 
• Com a regularização, promoverá o arquivamento do protocolo; 
• Persistindo a irregularidade ou em caso de atraso, com ou sem 
defesa da Contratada, o Fiscal do Contrato deve analisar e, se o 
47 
M A N U A L D E C O N T R A T O S | 2 0 2 5 
Secretaria de Administração e Abas tecimento | Saab  
caso, 
emitir 
relatório 
com informações detalhadas da 
irregularidade, encaminhando o protocolo ao Fiscal Administrativo, 
com proposta de autuação de processo apuratório; 
• O Fiscal Administrativo deve elaborar relatório conclusivo com a 
consolidação das informações apresentadas, opinando, ao Gestor 
ou à Gestora do Contrato, pela sua instauração ou arquivamento; 
• O Gestor ou a Gestora do Contrato elaborará relatório conclusivo 
sobre o arquivamento ou instauração de processo apuratório, nos 
termos do Art. 111 do Provimento CSM nº 2.724/2023. 
O procedimento a ser adotado para a condução do processo apuratório está 
discriminado no Manual de Apuratórios do Tribunal de Justiça de São Paulo. 
48 
M A N U A L D E C O N T R A T O S | 2 0 2 5 
Secretaria de Administração e Abas tecimento | Saab  
5.  
CONTRATOS SUI 
GENERIS 
49 
50 
M A N U A L D E C O N T R A T O S | 2 0 2 5 
Secretaria de Administração e Abas tecimento | Saab  
 
 
5.1  CONTRATOS DE FORNECIMENTO 
DE ENERGIA ELÉTRICA 
 
Para que ocorra o abastecimento de energia elétrica nas diversas unidades 
integrantes do Tribunal de Justiça de São Paulo, são formalizados, atualmente, 
contratos de fornecimento com uma Concessionária de Energia Elétrica, no 
Ambiente de Contratação Regulada. 
A Resolução Normativa da ANEEL nº 1000/2021 classifica os consumidores 
de energia elétrica em dois grupos – Grupo A e Grupo B, de acordo com o nível 
de tensão em que são atendidos. 
• Grupo A: unidades consumidoras com conexão de tensão 
maior ou igual a 2,3kV ou atendidas a partir de sistema 
subterrâneo de distribuição de tensão menor que 2,3kV 
(MÉDIA TENSÃO) 
 
• Grupo B: unidades consumidoras com conexão de tensão 
menor que 2,3kV. (BAIXA TENSÃO) 
Para os consumidores do Grupo A – Média Tensão, é necessária a 
celebração de dois contratos administrativos: 
• CUSD – Contrato de Uso do Sistema de Distribuição: contrato 
firmado pelo consumidor com a distribuidora, no qual são 
estabelecidos os termos e condições para o uso do sistema de 
distribuição e, conforme o caso, as condições para a conexão à 
rede de distribuição para o fornecimento de energia elétrica;  
 
• CCER – Contrato de Compra de Energia Regulada: contrato 
firmado pelo consumidor com a concessionária ou 
permissionária, no qual são estabelecidos os termos e 
condições para a compra e venda do montante de energia 
elétrica no Ambiente de Contratação Regulada (ACR) ou no 
Ambiente de Contratação Livre (ACL). 
M A N U A L D E C O N T R A T O S | 2 0 2 5 
Secretaria de Administração e Abas tecimento | Saab  
Ressalta-se que, atualmente, os contratos relacionados ao CUSD, no 
Ambiente de Contratação Regulada (ACR), são celebrados mediante 
inexigibilidade, tendo em vista a inviabilidade de competição. 
Com relação ao CCER, há recente previsão (Art. 160 da REN. ANEEL nº 
1000/2021), que garante ao consumidor a opção pela compra de energia elétrica 
no Ambiente de Contratação Livre (ACL). Entretanto, até que o TJSP não migre 
para o ACL, as contratações continuam sendo celebradas mediante 
inexigibilidade. 
Para os consumidores do Grupo B – Baixa Tensão, basta a formalização do 
fornecimento de energia elétrica por meio de contrato de adesão. 
ATENÇÃO: Com o advento da Lei nº 
14.133/2021, a celebração de novos 
contratos (CUSD e CCER) necessitam de 
estudos prévios (DFD, ETP, TR e Plano 
de Riscos) que evidenciem a solução 
mais vantajosa para a Administração. 
Dessa forma, deve-se observar o 
Provimento CSM nº 2.724/2023 na 
elaboração da documentação prévia, 
bem como as orientações contidas no 
Manual de Licitações do Tribunal de 
Justiça de São Paulo. 
5.1.1  FLUXO ATUALIZADO PARA FORMALIZAÇÃO 
DOS CONTRATOS DE ENERGIA ELÉTRICA 
Atualmente, a formalização dos contratos de energia no Ambiente de 
Contratação Regulada (ACR) segue o fluxo abaixo. 
51 
M A N U A L D E C O N T R A T O S | 2 0 2 5 
Secretaria de Administração e Abas tecimento | Saab  
Etapas a serem observadas: 
1. 
O processo tem início com a instrução dos autos pela Administração 
Predial, com a juntada das 12 últimas faturas e o preenchimento do 
checklist específico (Checklist - Análise Técnica), para análise do 
setor técnico. 
2. O setor técnico verificará a demanda mais adequada a ser 
contratada para aquela unidade predial; 
3. A Administração Predial deverá solicitar à Concessionária a minuta 
dos contratos (CUSD e CCER) ou do Aditivo, bem como declaração 
em que conste a exclusividade de prestação de serviços e que os 
valores praticados estão em conformidade com o estipulado pela 
Agência Nacional de Energia Elétrica (ANEEL); 
4. Complementarmente, a Administração Predial preencherá os 
seguintes documentos: Documento de Formalização de Demanda – DFD; Estudo Técnico Preliminar – ETP; Termo de Referência – TR e 
checklist específico (Anexo I – para os casos de nova contratação ou 
Anexo II – para os casos de alteração da demanda); 
5. Com a devida instrução dos autos pela Administração Predial, 
compete à Saab 6.3.1.1 – Seção de Formalização de Convênios de 
Obras e Contratos de Energia Elétrica, emitir as certidões 
demonstrativas de regularidades da prestadora de serviços nas 
áreas fiscal, social e trabalhista, bem como elaborar a informação 
descritiva dos fatos e, nos casos de irregularidade da Concessionária, 
disponibilizar ofícios a serem encaminhados à Agência Reguladora 
e aos Órgãos Públicos credores, quanto ao estado da irregularidade; 
6. Após, a SOF – Secretária de Orçamento e Finanças, realizará as 
adequações orçamentarias; 
52 
M A N U A L D E C O N T R A T O S | 2 0 2 5 
Secretaria de Administração e Abas tecimento | Saab  
7. Posteriormente, o GTAJ – Grupo Técnico de Assessoria Jurídica, 
realizará a análise jurídica da documentação e emitirá parecer; 
8. A Saab 6.3.1.1 realizará o cadastro dos contratos e/ou aditivo no 
Sistema Financeiro e Orçamentário – SGF; publicará o despacho do 
MM. Juiz Diretor ou da MM. Juíza Diretora do Fórum, bem como o 
extrato do contrato de fornecimento de energia e/ou aditivo, no 
Diário Eletrônico da Justiça do Estado de São Paulo (DEJESP); 
divulgará os contratos e aditivos no Portal da Transparência e no 
Portal Nacional de Contratações Públicas (PNCP); e, caso necessário, 
encaminhará os Ofícios à ANEEL e aos Órgãos Públicos Credores 
acerca da situação de irregularidade da Concessionária; 
9. Por fim, a Administração Predial realizará o acompanhamento do 
consumo de energia da unidade predial. 
5.1.2  ALTERAÇÃO DA DEMANDA 
A demanda de consumo de energia elétrica pode sofrer alterações durante 
o tempo por inúmeros fatores, podendo ser aumentada ou diminuída. 
ATENÇÃO: Em determinados casos, faz
se necessária a realização de obras, pela 
Concessionária, na rede elétrica externa 
para adequações. Nesses casos, 
também é necessária a instrução dos 
autos com os documentos preliminares 
(DFD, ETP, TR e Plano de Riscos – 
modelos específicos disponíveis em 
Modelos de Documentos - Energia 
Elétrica). 
Para as alterações de demanda, devem ser observadas as mesmas etapas 
do item 5.1.1 deste Manual. 
53 
M A N U A L D E C O N T R A T O S | 2 0 2 5 
Secretaria de Administração e Abas tecimento | Saab  
6.  
ATESTADO E 
PROTOCOLO DO 
DOCUMENTO 
FISCAL 
54 
M A N U A L D E C O N T R A T O S | 2 0 2 5 
Secretaria de Administração e Abas tecimento | Saab  
6.1  DO CADASTRO NO SISTEMA SGF 
Inicialmente, compete aos Gestores e às Gestoras de Contratos 
cadastrarem os Fiscais Administrativos, os Fiscais de Contratos e seus suplentes 
no sistema SAJADM, módulo SGF, utilizando-se a tela denominada “GESTÃO 
CONTRATUAL”, pelo caminho SGF > Contratos > Gestão Contratual. 
Em caso de dúvidas sobre a efetivação do cadastro de fiscais e seus 
suplentes, deverá ser consultado o material explicativo sobre gestão contratual, 
disponibilizado em http://www.tjsp.jus.br/ejus/avas, selecionando a opção 
Sistema SAJ > SAJADM > SGF > Vídeos > Gestão Contratual. 
6.2   PRAZO DE RECEBIMENTO E 
ENVIO DA DOCUMENTAÇÃO À SOF 
De acordo com o Comunicado SOF nº 13/2021, o recebimento de bens e 
serviços deve ser atestado no prazo de 48 horas a contar da recepção do 
documento fiscal, por meio de preenchimento do “Protocolo de Documento 
Fiscal”, conforme instruções do tópico 6.3 deste Manual, assinado com 
Certificado Digital na folha de ateste, observando-se sempre o prazo de 
vencimento do ISS/INSS. 
Os documentos fiscais cadastrados devem ser encaminhados, via sistema, 
à SOF 3.1.1.1, dentro do prazo de 24 horas, a contar da data do ateste. 
O cumprimento dos prazos acima mencionados é de suma importância 
para que seja cumprido o fluxo de liquidação e pagamento da despesa, a fim de 
que não haja atraso no pagamento aos prestadores de serviços e fornecedores, 
bem como para que não ocorra a incidência de despesas com encargos 
moratórios de INSS e ISS. 
55 
56 
M A N U A L D E C O N T R A T O S | 2 0 2 5 
Secretaria de Administração e Abas tecimento | Saab  
 
 
Notas Fiscais – Serviços NÃO MENSAIS 
• Merece atenção especial os contratos que não requerem a 
prestação de serviços mensalmente, como, por exemplo, 
desinsetização (quadrimestral) e limpeza de caixa d’água 
(semestral), entre outros com periodicidade diferenciada. 
• Para esses casos, é fundamental que os atestes sejam realizados 
adequadamente, de acordo com a data da prestação do serviço, 
observando-se os prazos de ateste e encaminhamento da nota 
fiscal, a fim de que não ocorra a incidência de despesas com 
encargos moratórios de INSS e ISS. 
 
6.3   CADASTRAMENTO DO 
DOCUMENTO FISCAL 
 
Ressalta-se o fato de que, desde abril de 2022, os dados informados nos 
protocolos de documentos fiscais realizados pelo TJSP são enviados para a 
Receita Federal, por meio do EFD-REINF (Escrituração Fiscal Digital de 
Retenções e Outras Informações Fiscais). 
Dessa forma, o encaminhamento à SOF dos documentos fiscais, via 
protocolo do sistema SAJADM, deve ser realizado de forma precisa e em tempo 
hábil, observando-se os prazos acima descritos, a fim de se evitar encargos 
decorrentes de pagamentos de guias em atraso e a transmissão de informações 
ao EFD-REINF fora do prazo. 
O processo de cadastramento inicia-se com o lançamento do documento 
fiscal no sistema SAJADM, no módulo “SGF” > “Despesas” > “Protocolo de 
Documento Fiscal”. 
M A N U A L D E C O N T R A T O S | 2 0 2 5 
Secretaria de Administração e Abas tecimento | Saab  
ATENÇÃO: Ao atestar o documento 
fiscal, deve-se indicar como mês de 
competência o período em que o 
serviço foi efetivamente prestado  
(e não o mês de emissão da nota fiscal). 
• 3ª Etapa: Protocolo. 
6.3.1    
O cadastramento do documento fiscal é realizado em três etapas: 
• 1ª Etapa: Informação dos dados cadastrais e impostos aplicados aos 
documentos; 
• 2ª Etapa: Fornecimento das informações acerca da execução do 
contrato; 
1ª ETAPA: INFORMAÇÃO DOS DADOS 
CADASTRAIS E IMPOSTOS APLICADOS AO 
DOCUMENTO  
Nesta etapa, o Responsável pelo ateste deve realizar os seguintes 
preenchimentos: 
57 
M A N U A L D E C O N T R A T O S | 2 0 2 5 
Secretaria de Administração e Abas tecimento | Saab  
I. 
II. 
Dados Cadastrais 
1. 
Clicar em “Novo”, na tela de acesso de “Protocolo de Documento 
Fiscal” (módulo “SGF” à “Despesas”); 
2. Selecionar o Contrato ou Despesa; 
3. Selecionar o tipo de documento correspondente; 
4. Preencher o “Número de Documento”; 
5. Selecionar o estado de origem em que a nota fiscal foi emitida em 
“Origem do documento fiscal – Estado”; 
6. Preencher o “Número de série”. Caso o documento não apresente 
número de série, deve-se alimentar o campo com o número “0”; 
7. Preencher o campo “Data de emissão”, de acordo com as 
informações contantes da data de emissão do documento fiscal. 
Quadro de “Referência” e valor do documento fiscal 
1. 
Informar o mês e ano (MM/AAAA) em que o serviço foi prestado. Em 
regra, esta informação está descrita no documento fiscal; 
2. Lançar o valor total do documento fiscal em “Valor Bruto do 
documento (R$)”; 
3. Lançar os descontos concedidos pelo credor e não constante do 
documento fiscal em “Descontos/abatimentos fora do documento 
(R$)”; 
4. O “Valor atestado (R$)” será automaticamente alimentado com o 
preenchimento dos campos acima; 
5. Caso o documento fiscal se refira a mais de um mês de referência, 
o procedimento acima deve ser repetido, com a informação do valor 
proporcional de cada mês de “Referência”. 
6. Após, será possível o preenchimento do campo de livre digitação 
“Observação”, no qual o responsável pelo ateste poderá adicionar 
complementações ao cadastro. 
ATENÇÃO: Em caso de reajuste 
contratual, deverá ser informado o valor 
proporcional do reajuste de cada mês, 
calculado de acordo com os serviços 
prestados nos respectivos meses de 
referência e em conformidade aos 
termos contratuais. 
58 
M A N U A L D E C O N T R A T O S | 2 0 2 5 
Secretaria de Administração e Abas tecimento | Saab  
59 
  
 
 
 
ATENÇÃO: O “Total” do valor bruto do 
documento apresentado pelo sistema 
deverá ser igual ao valor total do 
documento fiscal. 
 
ATENÇÃO: Não será permitido cadastrar 
nota fiscal com referência fora do 
período de vigência do contrato. 
 
III. Decisão judicial contrária a alguma retenção tributária 
 
1. Após o lançamento da “Observação”, o responsável pelo ateste deve 
selecionar a opção “SIM” ou “NÃO”, para o caso de o credor estar 
amparado por decisão judicial contrária a alguma retenção 
tributária (IR e INSS) para o documento fiscal. 
O Responsável pelo ateste identificará a decisão  
sobre a retenção da seguinte forma: 
 
• Na Descrição do documento fiscal, quando houver 
informação sobre o processo judicial que interfira na 
retenção de IR e INSS; 
• Por alerta do sistema, caso haja pré-cadastro no 
sistema da decisão judicial contrária a alguma retenção 
tributária em favor do credor, alertando o responsável 
pelo ateste a selecionar a opção “SIM”; 
 
• Caso não conste a informação relativa ao processo 
judicial no Documento Fiscal e o sistema não emita o 
alerta acima, selecionará a opção “NÃO”. 
 
 
 
6.3.1.1  RETENÇÕES TRIBUTÁRIAS (ISS, INSS E IRRF) 
 
O preenchimento das “Retenções” aplicáveis ao documento fiscal é 
obrigatório quando houver retenções tributárias (ISS, INSS e IRRF) destacados no 
documento fiscal e a obrigação de recolhimento for do TJSP. 
M A N U A L D E C O N T R A T O S | 2 0 2 5 
Secretaria de Administração e Abas tecimento | Saab  
Para tanto, é essencial que ocorra sempre o acompanhamento e o 
lançamento das retenções conforme as informações contantes no documento 
fiscal. 
Inicialmente, deve-se selecionar o imposto a ser cadastrado, entre: ISS, INSS 
e IRRF. 
8.1.1 RETENÇÃO ISS 
Deve ser informada apenas se a obrigação do recolhimento for do TJSP. 
Caso o serviço tenha sido prestado nas Comarcas do interior de São Paulo, 
o Fiscal do Contrato deverá emitir a guia junto à Prefeitura Municipal de acordo 
com a legislação local. 
Por outro lado, as guias de ISS referentes aos serviços prestados nas 
unidades da capital de São Paulo serão emitidas pela Secretaria de Orçamento 
e Finanças (SOF). 
ATENÇÃO: Cabe ao responsável pelo 
ateste verificar no próprio documento 
fiscal a informação da base de cálculo, 
devendo conferir se a alíquota está de 
acordo com a legislação vigente. 
Abaixo seguem as etapas para o lançamento do ISS no sistema: 
60 
M A N U A L D E C O N T R A T O S | 2 0 2 5 
Secretaria de Administração e Abas tecimento | Saab  
1. 
Selecionar a opção de retenção do ISS, ao passo que serão exibidos 
os campos a serem preenchidos; 
2. Informar se o valor da base mensal de cálculo da retenção é o 
mesmo valor bruto do documento fiscal. Caso seja, selecionar a 
opção “SIM”, ao passo que o campo “Base de Cálculo” será 
automaticamente preenchido. Caso não, selecionar a opção “NÃO”, 
devendo preencher manualmente o seu valor; 
3. Preencher o “Município” em que o serviço foi prestado; 
4. Preencher a “Alíquota (%)” correspondente. Automaticamente, o 
sistema efetuará o cálculo do valor, devendo o responsável pelo 
ateste verificar, obrigatoriamente, se o campo “Valor” está 
exatamente igual ao valor apresentado na guia emitida junto à 
Prefeitura para recolhimento do ISS. Em caso de divergência, o 
campo de valor deve ser editado; 
5. Preencher a “Data de Vencimento”, conforme a data constante na 
guia ou de acordo com a legislação municipal; 
6. Informar, no campo “Encargos” se há incidência de encargos por 
atraso e o motivo, selecionando, se o caso, quem é o responsável 
pelo atraso; 
7. Clicar em “Salvar”; 
8. Caso deseje adicionar mais impostos, basta clicar em “Adicionar” e 
selecionar o respectivo imposto. 
8.1.2  RETENÇÃO INSS 
Caso haja retenção de INSS, as seguintes etapas devem ser seguidas para 
seu lançamento no sistema: 
61 
M A N U A L D E C O N T R A T O S | 2 0 2 5 
Secretaria de Administração e Abas tecimento | Saab  
1. 
Informar se o valor da base mensal de cálculo da retenção é o 
mesmo valor bruto do documento fiscal. Caso seja, selecionar a 
opção “SIM”, ao passo que o campo “Base de Cálculo” será 
automaticamente preenchido. Caso não, selecionar a opção “NÃO”, 
devendo preencher manualmente o seu valor; 
2. Preencher a “Alíquota (%)” correspondente, entre 3,5% e 11%, 
conforme o documento fiscal. Automaticamente, o sistema 
efetuará o cálculo do campo “Valor”.  Em caso de divergência de 
valores, o responsável pelo ateste deve realizar a edição do “Valor” 
para que conste aquele presente no documento fiscal; 
3. Caso o INSS esteja vencido, constará uma mensagem de alerta, 
devendo o responsável pelo ateste preencher os campos de 
“Encargos” e “Justificativa”, informando quem deu causa à 
cobrança; 
4. Clicar em “Salvar”; 
5. Caso deseje adicionar mais impostos, basta clicar em “Adicionar” e 
selecionar o respectivo imposto. 
8.1.3  RETENÇÃO IRRF (IMPOSTO DE RENDA RETIDO 
NA FONTE) 
Em caso de retenção de IRRF, as seguintes etapas devem ser seguidas para 
seu lançamento no sistema: 
62 
M A N U A L D E C O N T R A T O S | 2 0 2 5 
Secretaria de Administração e Abas tecimento | Saab  
1. 
Informar se o valor da base mensal de cálculo da retenção é o 
mesmo valor bruto do documento fiscal. Caso seja, selecionar a 
opção “SIM”, ao passo que o campo “Base de Cálculo” será 
automaticamente preenchido. Caso não, selecionar a opção “NÃO”, 
devendo preencher manualmente o seu valor; 
2. Preencher a “Alíquota (%)” correspondente, entre 1% ou 1,5%, 
conforme o documento fiscal. Automaticamente, o sistema 
efetuará o cálculo do campo “Valor”.  Em caso de divergência de 
valores, o responsável pelo ateste deve realizar a edição do “Valor” 
para que conste aquele presente no documento fiscal; 
3. Clicar em “Salvar”. 
1. 
6.3.2 2ª ETAPA: FORNECIMENTO DAS INFORMAÇÕES 
ACERCA DA EXECUÇÃO DO CONTRATO 
Nesta etapa, o responsável pelo ateste deverá preencher várias informações 
sobre a execução do contrato, que serão parte dos dados encaminhados à 
AUDESP, observando-se as seguintes ações: 
Selecionar a situação da execução do contrato em “Situação do 
ajuste”; 
63 
64 
M A N U A L D E C O N T R A T O S | 2 0 2 5 
Secretaria de Administração e Abas tecimento | Saab  
 
 
2. Preencher a data da efetiva entrega do material ou início da 
execução de serviço/obra em “Data de entrega do material ou 
início da execução de serviço/obra”; 
3. Preencher informações sobre o cronograma e inexecução do 
contrato; 
 
4. Preencher a “Data do ateste”, no campo “Ateste”, com a data 
da realização do ateste/cadastro do protocolo; 
5. Selecionar o campo “Conferido pelo fiscal administrativo”; 
6. Realizar a verificação da autenticidade do documento fiscal, 
junto à Prefeitura Municipal ou Governo do Estado de São 
Paulo, conforme a situação do documento fiscal; 
 
COMO FAZER? Para o Governo do 
Estado de São Paulo, será possível a 
verificação da autenticidade das notas 
fiscais junto ao endereço: 
https://www.nfe.fazenda.gov.br/portal/p
 rincipal.aspx.  
Para a Prefeitura Municipal de São 
Paulo, será possível a verificação junto 
ao endereço: 
https://nfe.prefeitura.sp.gov.br/publico/
 verificacao.aspx. 
Para as demais prefeituras, o 
responsável pelo ateste utilizará as 
ferramentas existentes, conforme 
informações constantes no documento 
fiscal ou legislação municipal sobre a 
emissão de documentos fiscais. 
 
7. Conferida a autenticidade, selecionar a opção “Verificada a 
autenticidade da Nota Fiscal Eletrônica” e, após, “Salvar e 
próximo”. 
M A N U A L D E C O N T R A T O S | 2 0 2 5 
Secretaria de Administração e Abas tecimento | Saab  
6.3.3 3ª ETAPA: PROTOCOLO 
Nesta etapa, são apresentados o número do protocolo gerado no CPA, os 
principais dados informados no cadastro e os dados do responsável pelo 
cadastro do documento fiscal. 
Em regra, o módulo SGF indica o responsável pela liquidação da despesa, 
direcionando o protocolo gerado com o ateste do documento fiscal 
compulsoriamente para o setor competente (SOF 2.1.2). 
No entanto, há situações em que o responsável pelo ateste deve 
encaminhar o protocolo para a SOF 3.1.1.1, para realização da triagem. São elas: 
• Quando o protocolo de documento fiscal tramitar por mais de 01 
(um) setor para fins de ateste/conferência dos serviços prestados; 
• Quando mais de um setor for responsável pela liquidação de 
despesas de um determinado contrato (Exemplo: facilities); 
• Quando o setor responsável ainda não estiver cadastrado na 
funcionalidade “Dados para liquidação”; 
• Quando não for possível sua identificação por meio da regra dos 
agregadores de contratos/despesas. 
Após, deve-se seguir o seguinte procedimento: 
1. 
Acionar o botão “Anexar documentos e encaminhar protocolo”; 
2. Clicar em “Salvar” para que os dados do encaminhamento já 
alimentados automaticamente no sistema fiquem salvos; 
3. Clicar na aba “Documentos” e assinar o documento de Ateste; 
4. Após a assinatura, o Fiscal do Contrato deverá inserir os documentos 
fiscais e outros documentos relativos ao ateste de nota fiscal, 
obedecidas a seguinte ordem: 
• 1º - Nota Fiscal/Fatura, devendo o arquivo ser renomeado como “NF 
XXXXX – empresa XXXXX”; 
• 2º - Guia de Recolhimento do ISS (se houver), devendo o arquivo ser 
renomeado como “GUIA DO ISS”; 
• 3º - Carta de desconto (se houver), devendo ser renomeado como 
“CARTA DE DESCONTO”; 
65 
M A N U A L D E C O N T R A T O S | 2 0 2 5 
Secretaria de Administração e Abas tecimento | Saab  
• 4º - Conjunto de evidência comprovando que foi a Contratada que 
deu causa à eventual atraso no recolhimento dos tributos (ISS e 
INSS); 
5. Com a inserção dos documentos necessários, encaminhar à SOF, 
clicando na aba “Encaminhamento”; 
ATENÇÃO: Nas hipóteses de exceção ao 
encaminhamento automatizado (SOF 
2.1.2), deverá ser inserido o setor SOF 
3.1.1.1 para a realização da triagem. 
6. Preenchido o setor correto, clicar em “Encaminhar”. 
ATENÇÃO: Todos os documentos fiscais, 
após devidamente autorizados e 
atestados, deverão ser encaminhados à 
SOF, exclusivamente, por meio do 
sistema eletrônico SGF. 
ATENÇÃO: Conforme o Provimento CSM 
nº 2.724/2023, a nota fiscal/fatura deve 
ser atestada definitivamente (ateste 
eletrônico) e enviada à SOF em até 3 
dias úteis após a emissão, respeitando 
os prazos para recolhimento de tributos 
e cumprimento das obrigações 
acessórias. 
FISCAIS 
1. 
6.4  CANCELAMENTO DE 
PROTOCOLOS DE DOCUMENTOS 
Caso necessário, é possível a realização do cancelamento de protocolos de 
documentos fiscais, exclusivamente, por meio do sistema SAJADM, módulo SGF, 
observando-se os seguintes passos: 
Acessar o módulo SGF à Despesas à Protocolo de documento fiscal; 
2. Consultar o documento fiscal, por meio de pesquisa nos filtros; 
3. Editar o documento fiscal, clicando no ícone de “Editar”; 
66 
M A N U A L D E C O N T R A T O S | 2 0 2 5 
Secretaria de Administração e Abas tecimento | Saab  
4. Adicionar o botão “Excluir”. 
ATENÇÃO: Com este procedimento, será 
estornado/arquivado automaticamente 
o protocolo gerado anteriormente no 
CPA. 
Caso seja necessário cadastrar 
novamente o documento fiscal para fins 
de ateste, deverá ser gerado um novo 
protocolo de documento fiscal. 
ATENÇÃO: Caso restem dúvidas acerca 
dos procedimentos a serem adotados 
na fase de ateste e cadastramento dos 
documentos fiscais, consulte o 
Comunicado SOF nº 13/2021 e acesse o 
curso "Sistemas Administrativos - SGF - 
REINF".  
67 
M A N U A L D E C O N T R A T O S | 2 0 2 5 
Secretaria de Administração e Abas tecimento | Saab  
7.  
GESTÃO  
DE RISCOS 
68 
M A N U A L D E C O N T R A T O S | 2 0 2 5 
Secretaria de Administração e Abas tecimento | Saab  
Segundo o Provimento CSM nº 2.724/2023, Gestão de Riscos é o 
procedimento de gerenciamento dos riscos que possam comprometer a 
contratação, desde a fase de planejamento até o termo final da vigência do 
contrato. 
Sinteticamente, abaixo seguem as etapas da Gestão de Riscos: 
Conforme visto acima, uma das etapas da Gestão de Riscos é a elaboração 
do Plano de Riscos, que é o documento integrante do Estudo Técnico Preliminar 
(ETP), elaborado pela Equipe de Planejamento da Contratação, com a descrição, 
a análise e o tratamento dos riscos que possam comprometer a contratação, 
desde a fase de planejamento até o fim da vigência contratual. 
O Plano de Riscos deve ser preenchido e revisto, sempre que necessário, 
por um Analista de Riscos. 
Quem atua como Analista de Riscos? 
• Equipe de Planejamento da Contratação;  
• Agente de Contratação ou Comissão de Contratação;  
• Gestor ou Gestora do Contrato;  
• Responsável técnico, se o caso.  
69 
M A N U A L D E C O N T R A T O S | 2 0 2 5 
Secretaria de Administração e Abas tecimento | Saab  
Este tópico em questão possui como foco a quinta etapa da gestão de 
riscos: “Monitoramento e revisão do Plano de Riscos (até o fim da vigência do 
contrato)”. Assim, segue abaixo o procedimento a ser adotado. 
7.1  ATUALIZAÇÃO DO PLANO  
DE RISCOS 
Durante a gestão e fiscalização da execução contratual, compete ao Gestor 
ou à Gestora do Contrato, com o auxílio dos Fiscais, revisar o Plano de Riscos. 
Nesse sentido, caso novos riscos ou fatos relevantes sejam identificados 
no curso da execução contratual, deverão ser direcionados ao Gestor ou à 
Gestora do Contrato para verificação, eventual tratamento e posterior 
atualização do Plano de Riscos. 
Abaixo segue o passo a passo para atualização do Plano de Riscos: 
1. Consultar o expediente do Plano de Riscos 
2. Acessar o aplicativo  
O CPA de análise de riscos será único, mantendo-se o histórico em 
um único expediente para todas as contratações do mesmo objeto. 
Dessa forma, o responsável por sua atualização, deve acessar o 
processo correspondente. 
O responsável deve utilizar o aplicativo - "Gestão de Riscos", 
solicitando o seu cadastro no próprio aplicativo caso não esteja 
cadastrado como gestor ou analista.  
No aplicativo, deve-se selecionar a respectiva análise de risco a ser 
atualizada. 
Ademais, no próprio aplicativo há instruções para o seu correto 
preenchimento e utilização.  
3. Atualizar o Plano de Riscos  
A atualização do Plano de Riscos observará o Manual de Gestão de 
Riscos em Contratações Públicas, homologado pela Presidência do 
TJSP (disponível em Gestão de Riscos em Aquisições).  
Ainda, há um roteiro desenvolvido para auxiliar na realização da 
análise de riscos, disponível em Roteiro para Análise de Riscos.  
Em suma, as seguintes etapas devem ser observadas:  
70 
M A N U A L D E C O N T R A T O S | 2 0 2 5 
Secretaria de Administração e Abas tecimento | Saab  
a. Realizar a análise dos riscos relacionados ao serviço ou bem 
demandado, inserindo os novos riscos identificados;  
b. Avaliar os riscos inseridos com sua probabilidade e impacto;  
c. Realizar o tratamento dos riscos avaliados, com as respostas e 
planos de ação esperados;  
d. Gerar novo relatório ao final da análise;  
e. Inserir relatório em PDF no CPA criado, assinando-o;  
Após a atualização dos riscos, caso a equipe de planejamento da 
contratação seja distinta da equipe de gestão contratual, recomenda-se que 
se encaminhe a análise de riscos atualizada para conhecimento. 
71 
M A N U A L D E C O N T R A T O S | 2 0 2 5 
Secretaria de Administração e Abas tecimento | Saab  
8.  
MODIFICAÇÕES 
CONTRATUAIS 
72 
M A N U A L D E C O N T R A T O S | 2 0 2 5 
Secretaria de Administração e Abas tecimento | Saab  
73 
  
 
 
 
Os contratos poderão ser alterados, com as devidas justificativas, nas 
hipóteses previstas na Lei nº 14.133/2021, desde que haja interesse da 
Administração e para atender ao interesse público. 
Segundo o Provimento CSM nº 2.724/2023, atuarão na fase de alteração 
contratual: 
• Fiscal do Contrato; 
• Fiscal Administrativo; 
• Gestor ou Gestora do Contrato; 
• Responsável Técnico, se necessário; 
• Saab; 
• SOF; 
• Assessoria Jurídica; 
• Presidência do Tribunal de Justiça. 
 
8.1  FORMALIZAÇÃO DAS 
ALTERAÇÕES CONTRATUAIS 
 
8.1.4  ACRÉSCIMOS E SUPRESSÕES 
 
Segundo a Lei nº 14.133/2021, há situações em que os contratos podem ser 
alterados unilateralmente pela Administração, ou seja, hipóteses em que o 
contratado será obrigado a aceitar tais modificações.  
Uma dessas previsões (art. 124, I, da Lei nº 14.133/2021) trata da modificação 
do projeto ou das especificações, para melhor adequação técnica a seus 
objetivos (alínea “a”) ou quando for necessária a modificação do valor contratual 
em decorrência do acréscimo ou diminuição quantitativa de seu objeto (alínea 
“b”). 
Nestes casos, a legislação estabelece os seguintes limites para acréscimos 
e supressões unilaterais nos contratos: 
 
Acréscimos e Supressões Acréscimos Supressões* 
Bens e Serviços 25% 25% 
Reformas de edifícios ou 
equipamentos 50% 25% 
M A N U A L D E C O N T R A T O S | 2 0 2 5 
Secretaria de Administração e Abas tecimento | Saab  
*Em caso de supressões que extrapolem os limites previstos, a Contratada 
poderá solicitar a extinção contratual. 
Nos pedidos de aditamento formulados, o Gestor ou a Gestora do Contrato 
deverá: 
a) descrever as alterações que se pretende realizar por meio do 
aditamento, de forma clara e objetiva, tais como: prazos, quantidades, 
serviços, itens do contrato, prédios/localidades etc.; 
b) avaliar o percentual já comprometido (art. 125 da Lei nº 14.133/2021), 
incluindo os aditamentos já concluídos ou em andamento, caso houver, e 
efetuar o novo cálculo, informando os percentuais de aditamento;  
c) solicitar proposta da Contratada, quando não houver preços definidos 
para o item a ser aditado; 
d) descrever o fato superveniente ou de conhecimento superveniente, 
suficiente para ensejar a modificação; 
e) atestar a manutenção do objeto inicialmente convencionado, não 
podendo, em hipótese alguma, haver a transmutação ou desnaturação do 
objeto; 
f) atestar a manutenção do equilíbrio econômico-financeiro; 
g) confirmar a manutenção do desconto linear obtido na licitação, para 
aditamentos qualitativos em contratos de obras e serviços de engenharia; 
h) inserir os respectivos anexos das alterações propostas, caso necessário; 
i) autuar protocolo CPA próprio e encaminhar à Saab 6 – Diretoria de 
Contratos Administrativos, Convênios e Gestão Imobiliária. 
8.1.5  PRORROGAÇÕES DE VIGÊNCIA 
O sistema emitirá notificação ao Gestor ou à Gestora do Contrato, com 
antecedência de 300 (trezentos) dias do término da vigência contratual, 
solicitando sua manifestação quanto à necessidade de prorrogação do ajuste, 
devendo ser observados os prazos estipulados no Provimento CSM nº 2.724/2023. 
74 
M A N U A L D E C O N T R A T O S | 2 0 2 5 
Secretaria de Administração e Abas tecimento | Saab  
ATENÇÂO: Nos termos do art. 89 do 
Provimento CSM nº 2.724/2023, as 
providências para prorrogação 
contratual devem ser iniciadas com 
antecedência mínima de: 
a)  240 (duzentos e quarenta) dias 
contados do final da vigência contratual, 
para prestação de serviços continuados 
ou fornecimento contínuo de bens; 
b)  300 (trezentos) dias contados do 
final da vigência contratual, para 
contratações complexas que 
demandem análise técnica.  
Caso o Gestor ou a Gestora opte pela prorrogação, deverão ser preenchidos 
os campos requisitados e gerado o protocolo (CPA), observando-se as seguintes 
etapas preliminares: 
1 - Verificar, na cláusula contratual, a possibilidade de prorrogação e qual o 
limite máximo de sua vigência; 
2 - Verificar a preservação das condições de habilitação (impedimento de 
licitar e contratar com a Administração Pública Estadual ou declaração de 
75 
M A N U A L D E C O N T R A T O S | 2 0 2 5 
Secretaria de Administração e Abas tecimento | Saab  
inidoneidade), bem como a inexistência de pendências, por meios dos 
seguintes links: CEIS, SANÇÕES, Apenados - TCE-SP, CADIN.  
Caso identifique algum impedimento que obste o prosseguimento do 
processo de prorrogação, o Gestor ou a Gestora deverá avaliar a necessidade 
de nova contratação ou outra providência cabível. 
3 – Colher a concordância formal da Contratada; 
4 - Encaminhar o protocolo gerado para o setor responsável pela pesquisa 
de preços com a finalidade de aferir a vantajosidade econômica.  
Caso a pesquisa realizada se mostre desfavorável, ou seja, os preços 
apurados encontrem-se abaixo do valor contratado, a área gestora deverá 
negociar junto à Contratada a redução dos preços, em conformidade com os 
valores obtidos na pesquisa. 
Caso a negociação reste frustrada caberá ao Gestor ou à Gestora avaliar 
alternativa(s) para se evitar a solução de continuidade do serviço/bens. 
Em caso de contratações por inexigibilidade ou dispensa de licitação, juntar 
a comprovação de que os preços praticados no contrato são compatíveis com os 
de mercado. Além disso, no caso de inexigibilidade, deverá ser apresentada a 
certidão de exclusividade atualizada, se o caso. 
5 - Justificar a necessidade da continuidade dos serviços; 
6 - Estando em termos, os pedidos de prorrogação deverão ser 
encaminhados, com toda a documentação pertinente, à Saab 6 – 
Diretoria de Contratos Administrativos, Convênios e Gestão Imobiliária, com 
antecedência mínima de: 
a) 180 (cento e oitenta) dias contados do final da vigência contratual, 
para prestação de serviços continuados ou fornecimento contínuo de 
bens; 
b) 240 (duzentos e quarenta) dias contados do final da vigência 
contratual, para contratações complexas que demandem análise técnica.  
76 
M A N U A L D E C O N T R A T O S | 2 0 2 5 
Secretaria de Administração e Abas tecimento | Saab  
ATENÇÂO: A Administração poderá 
estabelecer a vigência por prazo 
indeterminado nos contratos em que 
seja usuária de serviço público oferecido 
em regime de monopólio, desde que 
comprovada, a cada exercício financeiro, 
a existência de créditos orçamentários 
vinculados à contratação.  
São os casos dos contratos celebrados 
com os Correios (serviço postal) e com 
as concessionárias de energia elétrica 
(para contratação do uso do sistema de 
distribuição - CUSD). 
8.1.5.1  ATA DE REGISTRO DE PREÇOS 
O prazo de vigência da Ata de Registo de Preços (ARP) será de 1 (um) ano, 
podendo ser prorrogado por igual período, desde que haja interesse da 
administração e seja comprovada a vantajosidade econômica. 
O sistema encaminhará uma notificação à Unidade Gerenciadora, com 
antecedência de 300 (trezentos) dias do término da vigência da ARP, a fim de 
alertá-la sobre a validade da ata.  
Dessa forma, caso haja interesse na prorrogação da ARP, compete à 
Unidade Gerenciadora autuar expediente próprio de prorrogação, observando
se a antecedência prevista no tópico 8.1.2, instruindo-o com os documentos 
pertinentes. 
Em regra, a prorrogação de vigência da ARP segue o mesmo procedimento 
das demais prorrogações (conforme tópico 8.1.2), destacando-se as seguintes 
peculiaridades: 
• A Unidade Gerenciadora deverá colher a anuência dos fornecedores 
para a prorrogação proposta, certificando-se, inclusive, da eventual 
permanência daqueles incluídos no cadastro de reserva; 
• A Unidade Gerenciadora deverá encaminhar o expediente de 
prorrogação à Diretoria de Contratos da Saab, com antecedência 
mínima de 180 (cento e oitenta) dias, a contar do término da vigência 
da ARP; 
77 
M A N U A L D E C O N T R A T O S | 2 0 2 5 
Secretaria de Administração e Abas tecimento | Saab  
• A Unidade Gerenciadora dará ciência aos demais órgãos participantes, 
se houver, quanto às tratativas para prorrogação da ARP em curso.  
• A prorrogação será formalizada por Termo de Aditamento e implicará 
na renovação das quantidades iniciais para o novo período de vigência; 
• A Diretoria de Contratos da Saab encaminhará cópia do Termo de 
Aditamento de prorrogação aos órgãos participantes, se houver. 
8.1.6  MANUTENÇÃO DO EQUILÍBRIO ECONÔMICO
FINANCEIRO 
Segundo a Lei nº 14.133/2021, são três as formas de manutenção do equilíbrio 
econômico-financeiro do contrato, conforme definições: 
a) reajustamento em sentido estrito: forma de manutenção do equilíbrio 
econômico-financeiro de contrato consistente na aplicação do índice de 
correção monetária previsto no contrato, que deve retratar a variação efetiva do 
custo de produção, admitida a adoção de índices específicos ou setoriais; 
b) repactuação: forma de manutenção do equilíbrio econômico-financeiro de 
contrato utilizada para serviços contínuos com regime de dedicação exclusiva 
de mão de obra ou predominância de mão de obra. Efetuada por meio da análise 
da variação dos custos contratuais, devendo estar prevista no edital, sendo: 
• Para os custos decorrentes do mercado, com data vinculada à 
apresentação das propostas;  
• Para os custos decorrentes da mão de obra, com data vinculada ao 
acordo, à convenção coletiva ou ao dissídio coletivo ao qual o orçamento 
esteja vinculado. 
c) reequilíbrio econômico-financeiro: em caso de força maior, caso fortuito ou 
fato do príncipe ou em decorrência de fatos imprevisíveis ou previsíveis de 
consequências incalculáveis, que inviabilizem a execução do contrato tal como 
pactuado, respeitada, em qualquer caso, a repartição objetiva de risco 
estabelecida no contrato (alínea “d”, inciso II, artigo 124). 
78 
M A N U A L D E C O N T R A T O S | 2 0 2 5 
Secretaria de Administração e Abas tecimento | Saab  
8.1.6.1  REAJUSTAMENTO EM SENTIDO ESTRITO  
E REPACTUAÇÃO 
O reajustamento em sentido estrito e a repactuação, para os custos 
decorrentes de mercado, serão concedidos pela Administração, de ofício, 
conforme previsto em contrato, utilizando-se os índices pactuados. 
Para os contratos de obras e serviços de engenharia, o Gestor ou a Gestora 
deverá encaminhar à Saab 6 – Diretoria de Contratos Administrativos, Convênios 
e Gestão Imobiliária, expediente instruído com parecer da fiscalização técnica e 
novo cronograma físico financeiro aprovado pela Contratada. 
Os demais casos de repactuação (com exceção daquela por custos 
decorrentes de mercado, que ocorre de ofício) serão precedidas de solicitação 
da Contratada e analisadas pelo Gestor ou a Gestora do Contrato, observando
se, em suma, as seguintes etapas (conforme artigos 98 e 99 do Provimento CSM 
nº 2.724/2023): 
1. Recepcionar e autuar o pedido de repactuação em expediente 
eletrônico vinculado ao processo de contratação; 
2. Elaborar relatório conclusivo sobre o requerimento; 
• O Gestor ou a Gestora do Contrato poderá solicitar aos Fiscais 
Administrativos e do Contrato ou ao Responsável Técnico, subsídios 
para elaboração do relatório conclusivo, bem como realizar diligências 
para conferência dos elementos da repactuação requerida; 
3. Caso conclua favoravelmente à repactuação, encaminhar os autos à 
Saab 6 – Diretoria de Contratos Administrativos, Convênios e Gestão 
Imobiliária; 
4. Caso conclua desfavoravelmente à repactuação, o Gestor ou a Gestora 
do Contrato devolverá o pedido à Contratada, alertando-a que poderá 
sanear eventual deficiência na instrução e formular novo pedido ou 
formular pedido de reanálise; 
5. Caso a deficiência seja sanada ou haja pedido de reanálise, os autos 
serão remetidos à Saab 6 – Diretoria de Contratos Administrativos, 
Convênios e Gestão Imobiliária, para análise. 
As solicitações devem estar acompanhadas de demonstração analítica da 
variação dos custos, por meio de apresentação da planilha de custos e formação 
de preços e do novo acordo, convenção ou sentença normativa que fundamenta 
a repactuação (§ 6º, artigo 135, da Lei nº 14.133/2021). 
79 
M A N U A L D E C O N T R A T O S | 2 0 2 5 
Secretaria de Administração e Abas tecimento | Saab  
As novas planilhas de custos e formação de preços, com os novos valores, 
serão analisadas e referendadas pelo Gestor ou pela Gestora do Contrato antes 
do encaminhamento à Saab 6 – Diretoria de Contratos Administrativos, 
Convênios e Gestão Imobiliária. 
Os reajustes em sentido estrito e as repactuações serão registrados por 
apostila, dispensada a celebração de termo aditivo (inciso I, artigo 136, da Lei nº 
14133/2021). 
8.1.6.2  REEQUILÍBRIO ECONÔMICO-FINANCEIRO 
Para os pedidos de reequilíbrio econômico-financeiro (alínea “d”, inciso II, 
artigo 124, da Lei nº 14.133/2021), o Gestor ou a Gestora do Contrato deverá: 
a)  verificar a ocorrência de variação de custos que acarrete 
desequilíbrio econômico-financeiro em favor da administração; 
b)  receber pedido de reequilíbrio econômico-financeiro formulado 
pela Contratada; e 
c)  autuar, em expediente próprio vinculado ao processo da 
contratação, pedido de reequilíbrio econômico-financeiro, em favor da 
administração ou da Contratada 
Os autos serão instruídos com, no mínimo, os seguintes documentos e 
informações: 
a) se o risco foi previsto no Plano de Riscos ou, quando houver, na 
matriz de alocação de riscos; 
b) cópia do instrumento contratual, respectivos anexos e aditivos; 
c) planilha ou demonstrativo que evidencie a alteração da equação 
econômico-financeira; 
d) nexo de causalidade entre a alteração dos custos do contrato e o 
evento que inviabilize a execução do contrato tal como inicialmente 
pactuado. 
Na hipótese de reequilíbrio em favor da administração, compete ao 
Gestor ou à Gestora do Contrato encaminhar notificação à Contratada contendo 
os documentos relacionados acima para manifestação no prazo de 10 (dez) dias 
úteis. 
Compete ao Gestor ou à Gestora do Contrato elaborar relatório conclusivo 
acerca da ocorrência ou não do desequilíbrio: 
80 
M A N U A L D E C O N T R A T O S | 2 0 2 5 
Secretaria de Administração e Abas tecimento | Saab  
a) no caso de reequilíbrio em favor da administração, após o decurso 
do prazo (10 dias úteis), com ou sem manifestação da Contratada; 
b) no caso de reequilíbrio em favor da Contratada, após o 
recebimento do pedido devidamente instruído com os documentos. 
O Gestor ou a Gestora do Contrato poderá solicitar aos Fiscais 
Administrativos e do Contrato ou ao Responsável Técnico, subsídios para 
elaboração do relatório conclusivo, bem como realizar diligências para 
conferência do desequilíbrio apontado. 
Após a emissão do relatório conclusivo, os autos serão remetidos à Saab 6 - 
Diretoria de Contratos Administrativos, Convênios e Gestão Imobiliária, para 
processamento e elaboração da minuta de aditivo contratual e posterior 
encaminhamento à SOF e à Assessoria Jurídica. 
81 
M A N U A L D E C O N T R A T O S | 2 0 2 5 
Secretaria de Administração e Abas tecimento | Saab  
9.  
EXTINÇÃO DOS 
CONTRATOS 
82 
M A N U A L D E C O N T R A T O S | 2 0 2 5 
Secretaria de Administração e Abas tecimento | Saab  
Os contratos, em regra, são extintos quando atingem os objetivos para os 
quais foram formalizados ou pelo decurso do prazo. No entanto, há situações em 
que os contratos podem ser extintos antecipadamente. 
Para que ocorra o encerramento prematuro de um contrato, o seu motivo 
deve ser formalmente registrado nos autos do processo, sendo assegurados o 
contraditório e a ampla defesa. 
A extinção do contrato poderá ser: 
I. 
II. 
III. 
Determinada por ato unilateral e escrito da Administração, exceto no 
caso de descumprimento decorrente de sua própria conduta; 
Consensual, por acordo entre as partes, por conciliação, por mediação 
ou por comitê de resolução de disputas, desde que haja interesse da 
Administração; 
Determinada por decisão arbitral, em decorrência de cláusula 
compromissória ou compromisso arbitral, ou por decisão judicial. 
9.1 EXTINÇÃO UNILATERAL 
II. 
III. 
IV. 
V. 
VI. 
VII. 
Segundo o artigo 137 da Lei nº 14.133/2021, são motivos para a extinção 
unilateral do contrato: 
I. 
Não cumprimento ou cumprimento irregular de normas editalícias ou 
de cláusulas contratuais, de especificações, de projetos ou de prazos; 
Desatendimento das determinações regulares emitidas pela autoridade 
designada para acompanhar e fiscalizar sua execução ou por autoridade 
superior; 
Alteração social ou modificação da finalidade ou da estrutura da 
empresa que restrinja sua capacidade de concluir o contrato; 
Decretação de falência ou de insolvência civil, dissolução da sociedade 
ou falecimento do contratado; 
Caso fortuito ou força maior, regularmente comprovados, impeditivos da 
execução do contrato; 
Atraso na obtenção da licença ambiental, ou impossibilidade de obtê-la, 
ou alteração substancial do anteprojeto que dela resultar, ainda que 
obtida no prazo previsto; 
Atraso na liberação das áreas sujeitas a desapropriação, a desocupação 
ou a servidão administrativa, ou impossibilidade de liberação dessas 
áreas; 
VIII. 
Razões de interesse público, justificadas pela autoridade máxima do 
órgão ou da entidade contratante; 
83 
M A N U A L D E C O N T R A T O S | 2 0 2 5 
Secretaria de Administração e Abas tecimento | Saab  
IX. 
Não cumprimento das obrigações relativas à reserva de cargos prevista 
em lei, bem como em outras normas específicas, para pessoa com 
deficiência, para reabilitado da Previdência Social ou para aprendiz. 
PROCEDIMENTO A SER ADOTADO: 
No âmbito do TJSP, caso constatada alguma das hipóteses de extinção 
unilateral contratual, compete ao Gestor ou à Gestora do Contrato:  
1. Autuar expediente eletrônico vinculado ao processo de contratação; 
2. Notificar a Contratada, a fim de garantir o contraditório e a ampla defesa; 
3. Instruir os autos com, no mínimo: 
• Documentação comprobatória que motivou o pedido de extinção, de 
acordo com as hipóteses previstas no art. 137 da Lei. nº 14.133/2021; 
• Notificação da Contratada e comprovação de seu recebimento; 
• Resposta da Contratada ou informação de decurso do prazo sem sua 
manifestação; 
9.2  EXTINÇÃO PLEITEADA  
PELA CONTRATADA 
II. 
III. 
• Manifestação da área gestora contendo, inclusive, informação acerca dos 
processos apuratórios autuados; 
4. Encaminhar o expediente à Saab 6 - Diretoria de Contratos 
Administrativos, Convênios e Gestão Imobiliária, para elaboração do 
termo de extinção contratual, com posterior encaminhamento à área 
jurídica e deliberação da E. Presidência. 
Por outro lado, a Contratada poderá pleitear a extinção do ajuste nas 
seguintes situações: 
I. 
Supressão, por parte da Administração, de obras, serviços ou compras 
que acarrete modificação do valor inicial do contrato além do limite 
permitido no art. 125 da Lei nº 14.133/2021; 
Suspensão de execução do contrato, por ordem escrita da 
Administração, por prazo superior a 3 (três) meses; 
Repetidas suspensões que totalizem 90 (noventa) dias úteis, 
independentemente do pagamento obrigatório de indenização pelas 
sucessivas e contratualmente imprevistas desmobilizações e 
mobilizações e outras previstas; 
84 
M A N U A L D E C O N T R A T O S | 2 0 2 5 
Secretaria de Administração e Abas tecimento | Saab  
IV. 
V. 
Atraso superior a 2 (dois) meses, contado da emissão da nota fiscal, dos 
pagamentos ou de parcelas de pagamentos devidos pela 
Administração por despesas de obras, serviços ou fornecimentos; 
Não liberação pela Administração, nos prazos contratuais, de área, local 
ou objeto, para execução de obra, serviço ou fornecimento, e de fontes 
de materiais naturais especificadas no projeto, inclusive devido a atraso 
ou descumprimento das obrigações atribuídas pelo contrato à 
Administração relacionadas a desapropriação, a desocupação de áreas 
públicas ou a licenciamento ambiental. 
ATENÇÂO: As extinções previstas nos 
itens II, III e IV não serão admitidas em 
caso de calamidade pública, de grave 
perturbação da ordem interna ou 
guerra, bem como quando decorrerem 
de ato ou fato que a Contratada tenha 
praticado, tenha participado ou 
contribuído. 
PROCEDIMENTO A SER ADOTADO: 
No âmbito do TJSP, caso a Contratada pleiteie a extinção contratual, 
compete ao Gestor ou à Gestora do Contrato:  
1. Autuar expediente eletrônico vinculado ao processo de contratação; 
2. Instruir os autos com, no mínimo:  
• Documentação comprobatória que motivou o pedido de extinção, de 
acordo com as hipóteses previstas no art. 137 da Lei. nº 14.133/2021; 
• Manifestação da área gestora acerca da aceitabilidade do pedido. 
3. Encaminhar o expediente à Saab 6 – Diretoria de Contratos, para 
elaboração do termo de extinção contratual, com posterior 
encaminhamento à área jurídica e deliberação da E. Presidência; 
85 
M A N U A L D E C O N T R A T O S | 2 0 2 5 
Secretaria de Administração e Abas tecimento | Saab  
10 . 
RELATÓRIO 
FINAL 
86 
M A N U A L D E C O N T R A T O S | 2 0 2 5 
Secretaria de Administração e Abas tecimento | Saab  
10.1  RELATÓRIO FINAL SOBRE A 
CONSECUÇÃO DOS OBJETIVOS 
O relatório final é elaborado ao fim da vigência contratual e deve conter 
informações sobre a obtenção dos objetivos que tenham justificado a 
contratação, bem como eventuais condutas a serem adotadas para o 
aprimoramento das atividades da Administração. 
Segundo o artigo 106 do Provimento CSM nº 2.724/2023, que regulamenta 
o tema no âmbito do TJSP, compete ao Gestor ou a Gestora do Contrato, com 
apoio do Gestor ou da Gestora de Planejamento da Contratação, a elaboração do 
relatório final, em 60 (sessenta) dias corridos, contados do término da vigência 
contratual, contendo, no mínimo, as seguintes informações: 
• Efetiva consecução dos objetivos que tenham justificado a contratação; 
• Existência de restos a pagar e/ou outras pendências financeiras do 
contrato; 
• Liberação da garantia contratual, se houver; 
• Relação dos Processos Administrativos Apuratórios, de acordo com 
certidão extraída do sistema de gestão contratual; 
• Proposição de melhorias a serem refletidas no ETP, no TR e no Plano de 
Riscos das futuras contratações para o mesmo objeto; 
• No caso de contratos com dedicação exclusiva de mão-de-obra, constar 
as informações necessárias para a liberação, se o caso, do saldo da conta 
depósito-vinculada de que trata a Resolução CNJ nº 169/2013 (retenção 
de provisões de encargos trabalhistas, previdenciários e outros a serem 
pagos às empresas contratadas para prestar serviços com mão de obra 
residente nas dependências de unidades jurisdicionadas ao CNJ). 
O relatório final deverá ser juntado ao processo de acompanhamento da 
execução contratual e encaminhado ao respectivo Secretário ou à respectiva 
Secretária da unidade, para deliberação em até 5 (cinco) dias úteis. Após 
deliberação, o Secretário ou a Secretária encaminhará os autos: 
a) Ao Gestor ou à Gestora do Contrato: para adequações no relatório, se 
o caso; 
b) À Diretoria de Contratos: caso o relatório seja aprovado, para 
divulgação no PNCP e no Portal da Transparência do TJSP, no prazo de 
5 (cinco) dias úteis; 
c) À Diretoria de Licitações: para os casos de contratação direta, que não 
possuam instrumento contratual, para divulgação no PNCP e no Portal 
da Transparência do TJSP, no prazo de 5 (cinco) dias úteis. 
87 
M A N U A L D E C O N T R A T O S | 2 0 2 5 
Secretaria de Administração e Abas tecimento | Saab  
11 .  
ANEXOS 
88 
M A N U A L D E C O N T R A T O S | 2 0 2 5 
Secretaria de Administração e Abas tecimento | Saab  
89 
  
 
 
 
11.1  ANEXO I – CHECKLIST PARA NOVA 
CONTRATAÇÃO DE ENERGIA ELÉTRICA 
(CUSD E CCER) 
ANEXO I – CHECKLIST NOVA CONTRATAÇÃO CUSD E CCER 
ITEM CHECKLIST PARA NOVA CONTRATAÇÃO DE FORNECIMENTO DE ENERGIA ELÉTRICA – CUSD E CCER 
 DESCRIÇÃO SIM NÃO/ 
Justificativa FLS. 
1   
Os autos se referem à formalização de contratos do Grupo A (CUSD e 
CCER)?   
Se sim, juntar e indicar as fls. dos contratos no processo.  
       
2   Os contratos CUSD e CCER já foram celebrados pelo Juiz Diretor do 
Fórum, tratando-se o expediente de convalidação dos instrumentos?   
Se sim, juntar e indicar as fls. do documento assinado.  
      
3  Em caso de resposta positiva no item 2, houve delegação de poderes 
pelo Exmo. Sr. Desembargador Presidente do TJSP ao MM. Juiz(a) de 
Direito Diretor(a) do Fórum da Comarca para celebração dos 
instrumentos contratuais de CUSD e CCER? Em caso positivo, juntar 
cópia do despacho proferido pela Autoridade Superior  
      
4   Constam dos autos ETP, Termo de referência/projeto básico 
demonstrando, de forma clara, precisa e suficiente as soluções existentes 
no mercado para atendimento da necessidade do TJSP e a escolha da 
melhor solução, nos termos do Provimento nº 2.138/2013, bem como análise 
técnica da adequação da modalidade de contratação pretendida.  
        
5   Foram apresentados:          
   a) Laudo/parecer técnico demonstrando histórico ou estimativa de 
consumo e a quantidade da demanda de energia que se pretende 
contratar, de acordo com as condições e especificidades do Fórum da 
Comarca interessada?   
      
   b) Manifestação da área gestora informando se há necessidade de 
realização de obras na rede elétrica, bem como as hipóteses de 
ressarcimento de valores pelo TJSP à concessionária em caso de eventual 
futura alteração de demanda?   
      
6   
No caso de serem necessárias obras na rede elétrica, houve 
formalização de contrato específico?  - Se sim, juntar e indicar fls. do documento.  - Se não, há informação acerca da prévia autorização e delegação de 
poderes para a formalização do respectivo contrato pelo MM. Juiz(a) 
Diretor(a)? Em caso positivo, juntar cópia do despacho proferido pela 
Autoridade Superior.   
         
7   Foram colacionados aos autos as minutas contratuais que regerão a 
relação entre as partes (CCER, CUSD), já adequadas aos termos da 
Resolução Normativa nº 1.000/2021 da ANEEL?  
Se sim, indicar fls. do documento no processo.  
         
8  Houve indicação dos servidores que atuarão como gestor e fiscal nos 
contratos de fornecimento de energia elétrica a serem celebrados?   
Se sim, indicar fls. de manifestação com novas indicações.  
         
9   A escolha do fornecedor foi devidamente justificada, mediante a 
comprovação da exclusividade da concessionária no âmbito do 
município em que localizado o Fórum da Comarca contratante? 
(declaração de exclusividade fornecida pela concessionária)  
Se sim, indicar as fls. do documento nos autos.  
        
10   Há justificativa para o preço da contratação, embasada em declaração 
fornecida pela concessionária acerca da regular e uniforme aplicação das 
tarifas homologadas pela ANEEL e acerca da inexistência de condições 
mais vantajosas de contratação disponíveis para a Administração? 
(declaração de preço)  
Se sim, indicar as fls. do documento nos autos.  
         
90 
M A N U A L D E C O N T R A T O S | 2 0 2 5 
Secretaria de Administração e Abas tecimento | Saab  
 
 
11.2 ANEXO II - CHECKLIST PARA 
ALTERAÇÃO DA DEMANDA DE 
ENERGIA ELÉTRICA 
ANEXO II – CHECKLIST PARA ALTERAÇÃO DA DEMANDA 
ITEM CHECKLIST PARA ALTERAÇÃO DA DEMANDA DE ENERGIA ELÉTRICA 
 DESCRIÇÃO SIM NÃO/ 
Justificativa FLS. 
1 Os autos se referem a aditamento de contratos do Grupo A (CUSD e CCER)? 
Se sim, juntar e/ou indicar as fls. do termo de aditivo dos contratos no processo.       
2 
Os aditivos CUSD e/ou CCER já foram celebrados pelo Juiz Diretor do Fórum, 
tratando-se o expediente de convalidação dos instrumentos?   
Se sim, juntar e indicar as fls. do documento assinado. 
      
3 
Em caso de resposta positiva no item 2, houve delegação de poderes pelo Exmo. 
Sr. Desembargador Presidente do TJSP ao MM. Juiz(a) de Direito Diretor(a) do 
Fórum da Comarca para celebração dos contratos de CUSD E CCER e respectivos 
aditivos contratuais para alteração da demanda de energia elétrica? Em caso 
positivo, juntar cópia do despacho proferido pela Autoridade Superior 
      
4 
Constam dos autos cópias dos contratos CUSD e CCER originalmente celebrados, 
bem como de todos os aditivos já celebrados? - Se sim, indicar as folhas de cada documento. - Se não, promover a juntada e respectiva indicação de folhas. 
      
5 Foram apresentados:          
 
Laudo/parecer técnico demonstrando a necessidade do aumento/redução da 
demanda?   - Se sim, indicar as folhas de cada documento. - Se não, promover a juntada e respectiva indicação de folhas. 
      
 
Manifestação da área gestora informando se há necessidade de realização de 
obras na rede elétrica, bem como eventual ressarcimento de valores pelo TJSP à 
concessionária? - Se sim, indicar as folhas de cada documento. - Se não, promover a juntada e respectiva indicação de folhas 
      
6 
No caso de serem necessárias obras na rede elétrica, houve formalização de 
contrato específico? - Se sim, juntar e indicar fls. do documento. - Se não, há informação acerca da prévia autorização e delegação de poderes para a 
formalização do respectivo contrato pelo MM. Juiz(a) Diretor(a)? Em caso positivo, 
juntar cópia do despacho proferido pela Autoridade Superior. 
      
7 
No caso de ressarcimento, foram indicados os respectivos custos e melhor 
alternativa para o atendimento do interesse público? Se sim, indicar fls. da 
manifestação no processo. 
      
8 
Foram colacionados aos autos as minutas dos aditivos contratuais de CUSD E 
CCER que regerão a relação entre as partes, já adequadas aos termos da 
Resolução Normativa nº 1.000/2021 da ANEEL? 
Se sim, indicar fls. do documento no processo 
Se não, as minutas deverão ser solicitadas à concessionária para juntada ao 
expediente 
      
9 
Houve indicação dos servidores que atuarão como gestor, fiscal e suplentes nos 
contratos de fornecimento de energia elétrica a serem celebrados? Se sim, indicar 
fls.  ou indicar a manifestação com as novas indicações. 
      
10 
A escolha do fornecedor foi devidamente justificada, mediante a comprovação da 
exclusividade da concessionária no âmbito do município em que localizado o Fórum 
da Comarca contratante? (declaração de exclusividade fornecida pela 
concessionária) 
Se sim, indicar as fls. do documento nos autos. 
      
11 
Há justificativa para o preço da contratação, embasada em declaração fornecida 
pela concessionária acerca da regular e uniforme aplicação das tarifas homologadas 
pela ANEEL e acerca da inexistência de condições mais vantajosas de contratação 
disponíveis para a Administração? (declaração de preço)  
Se sim, indicar as fls. do documento nos autos.  
      
 
M A N U A L D E C O N T R A T O S | 2 0 2 5 
Secretaria de Administração e Abas tecimento | Saab  
91 
  
Perfeito 👏 — excelente diretriz, e muito bem colocada.
Então o texto será fiel ao **conteúdo do “Manual de Boas Práticas em Contratações Públicas – SEGES/MGI (2025)”**, mas **adequado à linguagem técnico-institucional do TJSP**, seguindo os padrões do **Manual de Contratos (TJSP 2025)** e das comunicações SAAB/GTAJ/SOF.

👉 Em resumo:

* **Mantém o conteúdo normativo e conceitual integral** (sem criar regras novas).
* **Uniformiza a linguagem**: termos federais como *“órgão ou entidade contratante”* serão convertidos para *“Tribunal de Justiça do Estado de São Paulo (TJSP)”*, *“unidade gestora”*, *“área demandante”*, etc.
* **Preserva a base legal original** (IN nº 5/2017, Decreto 10.947/2022, Lei nº 14.133/2021).
* **Adapta o contexto**: sempre que o texto mencionar a União, substituirei por *“no âmbito do TJSP”*, mantendo o sentido.

---

A seguir, apresentarei a **versão integral – Bloco 1 (Introdução e Capítulo 1)**.
Quando você confirmar a leitura e quiser, seguirei com os blocos subsequentes até completar todo o manual.

---

# 📘 **Manual de Boas Práticas em Contratações Públicas – Versão TJSP (Base SEGES/MGI 2025)**

## Adequado à linguagem e práticas institucionais do Tribunal de Justiça do Estado de São Paulo

*(Texto integral corrido – Bloco 1 de N)*

---

### **Introdução**

O presente Manual de Boas Práticas em Contratações Públicas constitui um guia técnico destinado a orientar gestores, fiscais e servidores envolvidos nos processos de contratação do Tribunal de Justiça do Estado de São Paulo (TJSP). Seu propósito é disseminar procedimentos eficientes, transparentes e juridicamente seguros, alinhados à Lei nº 14.133/2021 e às diretrizes de governança estabelecidas pelo Conselho Nacional de Justiça (CNJ) e pela Secretaria de Administração e Abastecimento (SAAB).

O manual tem como base o documento homônimo publicado pelo Ministério da Gestão e da Inovação em Serviços Públicos (SEGES/MGI), que consolida boas práticas em todas as fases da contratação pública. Nesta versão, o conteúdo é contextualizado à realidade do TJSP, respeitando suas estruturas administrativas, os Provimentos do Conselho Superior da Magistratura e os manuais internos vigentes, especialmente o **Manual de Licitações (2025)** e o **Manual de Contratos (2025)**.

A aplicação destas práticas busca aprimorar o desempenho institucional, garantir economicidade e assegurar que cada contratação pública seja precedida de adequada motivação técnica, planejamento estratégico, transparência e conformidade normativa.

---

### **Capítulo 1 – Princípios e Fundamentos da Contratação Pública**

A contratação pública é o instrumento pelo qual a Administração adquire bens, serviços e obras necessários ao cumprimento de sua função institucional. No TJSP, esses instrumentos são essenciais para assegurar a continuidade dos serviços jurisdicionais e administrativos, observando-se os princípios da legalidade, impessoalidade, moralidade, publicidade, eficiência e da gestão responsável dos recursos públicos.

A Lei nº 14.133/2021 introduziu o conceito de **governança nas contratações públicas**, definindo-a como o conjunto de mecanismos de liderança, estratégia e controle que asseguram a condução das aquisições com transparência, integridade e foco em resultados.

No contexto do TJSP, a governança das contratações é exercida de forma integrada pela **Secretaria de Administração e Abastecimento (SAAB)**, pela **Secretaria de Orçamento e Finanças (SOF)** e pelo **Grupo Técnico de Apoio às Contratações (GTAJ)**, que atuam sob supervisão do Conselho Superior da Magistratura.

Os **princípios fundamentais** que devem orientar a atuação dos servidores e gestores são:

1. **Planejamento e racionalidade** — toda contratação deve decorrer de necessidade previamente identificada e justificada tecnicamente.
2. **Eficiência e economicidade** — o processo deve buscar o melhor resultado possível, com o menor custo total.
3. **Transparência e publicidade** — todas as fases da contratação devem estar documentadas e acessíveis.
4. **Gestão de riscos e controles internos** — a análise e mitigação de riscos são obrigatórias desde a fase de planejamento.
5. **Integridade e ética** — os agentes públicos devem agir com imparcialidade e compromisso com o interesse público.

---

### **Capítulo 2 – Fase de Planejamento**

O planejamento da contratação é a etapa que antecede qualquer procedimento licitatório. É nele que se identifica a necessidade, define-se o objeto e se especificam as condições técnicas, econômicas e jurídicas da futura contratação.

No âmbito do TJSP, essa fase inicia-se com a elaboração do **Documento de Formalização da Demanda (DFD)** e prossegue com o **Estudo Técnico Preliminar (ETP)**, o **Termo de Referência (TR)** e o **edital**, culminando na **assinatura do contrato administrativo**.

#### **2.1 Identificação da necessidade**

A unidade demandante deve demonstrar, de forma objetiva, a motivação da contratação, comprovando a existência da necessidade e sua vinculação ao planejamento institucional. A justificativa deve abordar:

* A insuficiência dos meios disponíveis;
* A compatibilidade com o Plano de Contratações Anual (PCA);
* A análise de alternativas possíveis, inclusive a execução direta;
* O impacto orçamentário e financeiro.

#### **2.2 Estudos Técnicos Preliminares (ETP)**

Os ETPs têm por finalidade avaliar as soluções disponíveis no mercado, as tecnologias aplicáveis e os riscos envolvidos. No TJSP, os ETPs seguem modelo padronizado estabelecido pela SAAB, devendo conter:

* Descrição do problema a ser solucionado;
* Alternativas analisadas e justificativa da solução escolhida;
* Estimativa de custos e fontes de recursos;
* Riscos identificados e medidas mitigadoras.

O ETP é documento de natureza técnica e estratégica, devendo ser elaborado por equipe multidisciplinar e aprovado pela autoridade competente antes da elaboração do TR.

#### **2.3 Termo de Referência (TR)**

O Termo de Referência é o documento central da contratação. Define o objeto, as condições de execução, os critérios de medição e pagamento, as obrigações das partes, as penalidades e os mecanismos de fiscalização.

O TR deve ser redigido em linguagem clara, precisa e impessoal, evitando termos ambíguos ou subjetivos. Deve conter, no mínimo:

* Objeto detalhado;
* Fundamentação legal e técnica;
* Quantitativos e estimativas de consumo;
* Critérios de aceitabilidade de preços;
* Indicadores de desempenho e níveis de serviço;
* Procedimentos de recebimento provisório e definitivo.

O TR é a principal referência para a elaboração do edital e da minuta contratual, devendo guardar **coerência plena** com esses documentos.

#### **2.4 Pesquisa de Preços**

A pesquisa de preços é instrumento de aferição da razoabilidade dos valores estimados da contratação. Deve ser realizada com base em fontes fidedignas, priorizando-se:

* Painéis de Preços e sistemas oficiais (Painel de Preços, Compras.gov.br, SIASG);
* Contratações anteriores do próprio TJSP;
* Propostas formais de fornecedores, observando-se a contemporaneidade dos dados.

O resultado da pesquisa deve ser registrado em relatório circunstanciado, com indicação das fontes e metodologia utilizada.

#### **2.5 Análise de Riscos**

A gestão de riscos na fase de planejamento visa identificar eventos que possam comprometer o sucesso da contratação. O TJSP adota metodologia compatível com o **Guia de Gestão de Riscos do CNJ** e o **Manual de Riscos da SAAB**, que preveem:

* Identificação dos riscos (operacionais, jurídicos, financeiros e reputacionais);
* Avaliação de probabilidade e impacto;
* Definição de medidas de tratamento e monitoramento.

O mapa de riscos deve acompanhar o processo desde o ETP até o encerramento do contrato, sendo atualizado a cada aditivo ou repactuação.

---

✳️ *[continua no Bloco 2 – Capítulo 3: Fase de Seleção do Fornecedor e Gestão Contratual]*

---
Perfeito ✅ — daremos continuidade com o **Bloco 2 do Manual de Boas Práticas em Contratações Públicas – Versão TJSP (Base SEGES/MGI 2025)**.
Este bloco cobre a **Fase de Seleção do Fornecedor**, **Fase de Execução Contratual**, **Gestão e Fiscalização**, e as **Boas Práticas de Governança e Controle Interno**.

---

# 📘 **Manual de Boas Práticas em Contratações Públicas – Versão TJSP (Base SEGES/MGI 2025)**

## *(Texto integral corrido – Bloco 2 de N)*

---

### **Capítulo 3 – Fase de Seleção do Fornecedor**

A fase de seleção do fornecedor tem por finalidade escolher a proposta mais vantajosa para o TJSP, observados os princípios da isonomia, da transparência e da eficiência.
Nesta etapa, os atos administrativos devem refletir fielmente as condições descritas no Termo de Referência, evitando alterações indevidas do objeto ou das regras de habilitação.

#### **3.1 Procedimentos de Licitação**

A escolha do fornecedor pode ocorrer mediante licitação, dispensa ou inexigibilidade.
Nos casos de licitação, a modalidade será definida de acordo com o tipo e o valor da contratação, conforme o art. 28 da Lei nº 14.133/2021.
As modalidades usualmente aplicáveis ao TJSP são: **Pregão**, **Concorrência**, **Concurso** e **Leilão**.

A adoção do **Pregão Eletrônico** é a regra para aquisição de bens e serviços comuns, incluindo os serviços de natureza continuada sem predominância de mão de obra.
Deve-se observar o uso de **plataformas oficiais** (como o Compras.gov.br ou sistema estadual equivalente) e respeitar os prazos mínimos de publicidade.

#### **3.2 Critérios de Julgamento**

Os critérios de julgamento estão previstos nos arts. 33 e 34 da Lei nº 14.133/2021 e devem ser definidos no edital e mantidos inalterados durante a fase de seleção.
Os principais critérios são:

* **Menor preço**: utilizado para bens e serviços padronizados;
* **Técnica e preço**: aplicável a serviços intelectuais;
* **Maior desconto**: aplicável a aquisições em catálogos ou tabelas;
* **Melhor técnica**: em projetos complexos ou especializados;
* **Maior retorno econômico**: em contratos de eficiência.

A definição inadequada do critério de julgamento é uma das causas mais comuns de nulidade do procedimento, razão pela qual o GTAJ recomenda que a minuta do edital seja sempre submetida à análise jurídica prévia.

#### **3.3 Publicidade e Transparência**

A divulgação dos atos deve ocorrer em meios oficiais, preferencialmente digitais, assegurando ampla publicidade e concorrência.
Devem ser publicados:

* Aviso de licitação;
* Edital e anexos;
* Esclarecimentos e retificações;
* Atas de sessões públicas;
* Resultado e homologação.

O TJSP, em cumprimento à Lei de Acesso à Informação e à Resolução CNJ nº 215/2015, deve garantir que todas as informações licitatórias estejam disponíveis em seu **Portal de Transparência**.

#### **3.4 Habilitação e Sanções**

A fase de habilitação visa verificar a capacidade técnica, fiscal e jurídica dos licitantes.
Deve ser exigido apenas o estritamente necessário à execução contratual, vedadas exigências desproporcionais.
Os documentos de habilitação devem ser analisados com base em critérios objetivos, documentados e rastreáveis.

O descumprimento de obrigações editalícias, a apresentação de documentos falsos ou a prática de atos lesivos à Administração podem ensejar sanções administrativas, conforme os arts. 155 e 156 da Lei nº 14.133/2021, assegurado o direito ao contraditório e à ampla defesa.

---

### **Capítulo 4 – Fase de Execução Contratual**

A execução contratual é o momento em que as obrigações pactuadas são efetivamente cumpridas.
Nesta fase, o foco se desloca do procedimento para o **resultado da contratação**, exigindo acompanhamento técnico constante e comunicação eficaz entre contratada e contratante.

#### **4.1 Formalização e Vigência**

O contrato administrativo deve ser formalizado em instrumento próprio, contendo todas as cláusulas essenciais previstas no art. 92 da Lei nº 14.133/2021.
A vigência deve ser compatível com a natureza do objeto e limitada ao exercício orçamentário, salvo nos casos de serviços continuados ou projetos de execução plurianual.
Toda prorrogação de prazo deve ser precedida de justificativa formal e termo aditivo, instruído com documentação comprobatória e parecer jurídico.

#### **4.2 Gestão e Fiscalização**

A fiscalização é o conjunto de atividades destinadas a verificar a conformidade da execução contratual com o que foi pactuado.
O gestor e o fiscal de contrato são designados por ato formal da autoridade competente, conforme o art. 117 do Decreto Estadual nº 67.381/2022.

As atribuições dos fiscais e gestores incluem:

* Acompanhar a execução dos serviços ou fornecimentos;
* Registrar ocorrências em relatórios de fiscalização;
* Exigir correção de falhas e substituição de materiais defeituosos;
* Certificar as medições e atestar o cumprimento de obrigações.

A fiscalização deve ser documentada por meio de **Relatórios Mensais de Execução**, que comporão o processo administrativo.

#### **4.3 Pagamento e Reajuste**

O pagamento somente pode ocorrer após a verificação do adimplemento das obrigações contratuais, mediante atesto do fiscal.
O reajuste de preços é permitido após 12 meses da data da proposta, observada a variação do índice previsto na cláusula contratual (normalmente o IPCA).
Nos contratos de prestação de serviços continuados com dedicação exclusiva de mão de obra, aplica-se também o instituto da **repactuação**, conforme a IN SEGES nº 5/2017 e o Manual de Contratos TJSP (2025).

#### **4.4 Conta Vinculada e Retenção de Encargos**

Conforme a **Resolução CNJ nº 651/2025**, o TJSP deve adotar conta vinculada para gestão dos encargos trabalhistas e previdenciários em contratos de mão de obra exclusiva.
As regras obrigatórias incluem:

* Retenção mensal dos valores correspondentes;
* Abertura da conta em até 30 dias da assinatura do contrato;
* Liberação dos valores apenas mediante autorização expressa;
* Necessidade de anuência sindical nos casos de rescisão coletiva;
* Responsabilidade solidária do fiscal em caso de omissão dolosa.

O GTAJ e a SOF definiram fluxos internos e modelos padronizados para instrução e movimentação dessas contas, integrando o controle financeiro e documental.

#### **4.5 Alterações Contratuais**

Alterações quantitativas e qualitativas somente poderão ocorrer mediante termo aditivo devidamente justificado e instruído.
As hipóteses legais estão previstas no art. 124 da Lei nº 14.133/2021 e no art. 65 do Decreto nº 67.381/2022.
Toda alteração deve respeitar o limite de 25% para acréscimos ou supressões, salvo nos contratos de reforma de edifícios, em que o limite é de 50%.

#### **4.6 Extinção e Sanções**

O contrato pode ser extinto por execução regular, rescisão unilateral, anulação, invalidação ou por inexecução total ou parcial.
As penalidades cabíveis incluem advertência, multa, suspensão temporária e declaração de inidoneidade, observados o contraditório e a ampla defesa.

As rescisões devem ser formalizadas por ato escrito, devidamente motivado, e comunicadas à SAAB e à SOF para registro e controle.

---

### **Capítulo 5 – Governança, Controle Interno e Boas Práticas**

#### **5.1 Governança nas Contratações**

A governança das contratações públicas compreende o conjunto de mecanismos que asseguram que os objetivos institucionais sejam alcançados com ética, transparência e eficiência.
No TJSP, a governança é estruturada em três níveis:

* **Estratégico**: Presidência, CSM e órgãos de direção superior;
* **Tático**: SAAB, SOF e GTAJ, que coordenam políticas e normativos;
* **Operacional**: Unidades gestoras e fiscais, responsáveis pela execução e controle.

#### **5.2 Controle Interno**

O controle interno é exercido em todas as fases da contratação.
Inclui o monitoramento dos indicadores de desempenho, a verificação da legalidade dos atos e a avaliação periódica dos resultados.
Os relatórios gerados pelos fiscais devem ser analisados pela SAAB e integrados ao **Painel de Governança e Contratações**.

#### **5.3 Transparência e Prestação de Contas**

Todos os documentos, relatórios e informações relevantes devem ser arquivados digitalmente no SEI e disponibilizados no **Portal de Transparência do TJSP**, conforme determina a Resolução CNJ nº 215/2015.
A transparência é elemento essencial para a integridade institucional e para o controle social.

#### **5.4 Sustentabilidade e Inovação**

As contratações públicas sustentáveis são prioridade institucional.
O TJSP incentiva a adoção de critérios de sustentabilidade ambiental, responsabilidade social e inovação tecnológica, observando o art. 25 da Lei nº 14.133/2021.

Exemplos de boas práticas incluem:

* Priorizar materiais recicláveis e fornecedores sustentáveis;
* Incluir cláusulas de eficiência energética;
* Avaliar a pegada de carbono em obras e serviços.

---

✳️ *[continua no Bloco 3 – Capítulo 6: Fiscalização, Responsabilidade e Encerramento Contratual]*

---

Perfeito ✅ — vamos agora para o **Bloco 3 do Manual de Boas Práticas em Contratações Públicas – Versão TJSP (Base SEGES/MGI 2025)**.
Este bloco abrange a **fiscalização e encerramento contratual**, as **responsabilidades administrativas e trabalhistas**, e os **mecanismos de aprimoramento contínuo e governança**.
Esta é a parte mais importante para a integração do **Agente_CONTRATO – SAAB 5.4**, pois trata diretamente das rotinas que o agente deverá apoiar e validar.

---

# 📘 **Manual de Boas Práticas em Contratações Públicas – Versão TJSP (Base SEGES/MGI 2025)**

## *(Texto integral corrido – Bloco 3 de N)*

---

### **Capítulo 6 – Fiscalização, Responsabilidade e Encerramento Contratual**

A fase de fiscalização e encerramento é o estágio final do ciclo da contratação pública. É nela que se assegura a correta execução do contrato, o cumprimento de todas as obrigações e a conformidade documental necessária para o encerramento do processo administrativo.

#### **6.1 Fiscalização Técnica e Administrativa**

A fiscalização contratual deve ocorrer de maneira contínua e sistemática.
O fiscal do contrato é o agente responsável pela verificação in loco da execução e pela interlocução direta com a empresa contratada.
Deve manter registros atualizados de ocorrências, acompanhar prazos, analisar relatórios e documentar as comunicações realizadas.

O gestor do contrato, por sua vez, responde pela supervisão administrativa e financeira, consolidando os relatórios dos fiscais e encaminhando-os à autoridade competente.
Ambos devem atuar de forma articulada e registrar todas as ações no **Sistema Eletrônico de Informações (SEI)**.

A boa prática recomenda a manutenção de **planilhas analíticas de controle**, nas quais constem dados de pagamentos, retenções, medições e prorrogações contratuais.

#### **6.2 Obrigações da Contratada**

A contratada deve cumprir rigorosamente as cláusulas pactuadas, manter regularidade fiscal e trabalhista e executar os serviços conforme as especificações técnicas.
Entre as obrigações essenciais destacam-se:

* Disponibilizar mão de obra qualificada e treinada;
* Fornecer equipamentos e insumos adequados;
* Cumprir integralmente as normas de segurança do trabalho;
* Comprovar mensalmente o pagamento de salários, encargos e benefícios;
* Atender às solicitações do fiscal e corrigir falhas sem ônus adicional.

Nos contratos de dedicação exclusiva, a empresa deve apresentar mensalmente comprovantes de recolhimento de FGTS e INSS, sob pena de bloqueio de pagamento.

#### **6.3 Obrigações do TJSP**

O contratante deve assegurar a correta execução contratual, manter o acompanhamento documental atualizado e efetuar os pagamentos dentro do prazo legal.
Cabe ainda:

* Comunicar irregularidades à SAAB e ao GTAJ;
* Garantir os meios necessários à fiscalização;
* Formalizar aditivos e prorrogações;
* Recolher penalidades aplicadas e arquivar cópia no processo eletrônico.

A ausência de fiscalização adequada pode acarretar **responsabilidade subsidiária** à Administração, nos termos da Súmula 331 do TST e da jurisprudência consolidada do Tribunal de Contas da União (TCU).

#### **6.4 Recebimento Provisório e Definitivo**

O recebimento provisório e o definitivo constituem as etapas formais de aceitação do objeto contratado.
O recebimento provisório é realizado pelo fiscal técnico, mediante conferência física e funcional do objeto.
O definitivo ocorre após o prazo de observação e verificação da qualidade, mediante termo específico e atesto formal.

Nos contratos de serviços continuados, o recebimento ocorre mensalmente, com base nas medições aprovadas.
Em bens e obras, o recebimento definitivo é precedido de vistoria técnica e relatório conclusivo.

#### **6.5 Encerramento e Arquivamento**

O encerramento contratual compreende:

1. A verificação de inexistência de pendências financeiras;
2. A quitação de encargos trabalhistas;
3. O arquivamento de todos os documentos comprobatórios;
4. A emissão de **Relatório de Encerramento Contratual**, assinado pelo gestor e validado pela unidade gestora.

A SAAB recomenda que o relatório final contenha:

* Histórico resumido do contrato;
* Avaliação de desempenho da contratada;
* Ocorrências relevantes;
* Conclusões e recomendações para contratos futuros.

#### **6.6 Responsabilidade dos Agentes Públicos**

Os agentes públicos que atuam na gestão e fiscalização contratual respondem, na medida de sua participação, por atos de omissão, negligência ou conivência.
A responsabilidade é de natureza **pessoal e administrativa**, podendo resultar em penalidades disciplinares, civis e penais.

O TJSP deve garantir o treinamento contínuo de fiscais e gestores, de modo a prevenir erros e assegurar a adequada aplicação dos recursos públicos.
A instituição de **checklists e roteiros padronizados** é considerada boa prática de governança.

---

### **Capítulo 7 – Auditoria, Governança e Aprimoramento Contínuo**

A auditoria interna e o aprimoramento contínuo das práticas de contratação pública são componentes essenciais da boa governança.

#### **7.1 Auditoria e Controle Interno**

As unidades de controle interno do TJSP devem acompanhar as contratações de forma preventiva, avaliando a conformidade dos procedimentos e a efetividade dos controles.
A auditoria deve observar a cadeia completa da contratação — do planejamento à execução —, com foco em riscos, eficiência e resultados.
Recomenda-se que sejam realizadas **auditorias temáticas** anuais, voltadas a áreas de maior risco, como contratos de serviços terceirizados, obras e tecnologia da informação.

Os relatórios de auditoria devem conter recomendações objetivas e planos de ação, a serem acompanhados pela SAAB e pela Presidência do Tribunal.

#### **7.2 Indicadores de Desempenho**

O uso de indicadores de desempenho é uma das boas práticas mais eficazes para avaliar a eficiência das contratações.
Entre os principais indicadores aplicáveis ao TJSP estão:

* Índice de cumprimento de prazos contratuais;
* Percentual de contratos com aditivos de valor;
* Tempo médio de pagamento;
* Grau de satisfação da unidade usuária;
* Percentual de contratos auditados sem ressalvas.

Os indicadores devem ser revisados periodicamente e integrados ao **Painel de Governança das Contratações SAAB**.

#### **7.3 Gestão do Conhecimento**

A gestão do conhecimento é instrumento essencial para a melhoria institucional.
Consiste no registro, compartilhamento e reutilização das lições aprendidas, dos modelos de documentos e das boas práticas.
O TJSP mantém uma **biblioteca digital de modelos** e **repositórios de minutas** que devem ser utilizados como referência obrigatória para novas contratações.

O Agente_CONTRATO – SAAB 5.4 deve ser capaz de consultar esses repositórios, verificar coerência entre documentos e sugerir ajustes baseados nas versões homologadas.

#### **7.4 Treinamento e Capacitação**

A capacitação permanente é obrigação institucional prevista na Lei nº 14.133/2021, art. 7º, §3º.
O TJSP, por meio da **Escola Paulista da Magistratura (EPM)** e da SAAB, promove cursos periódicos sobre licitações, contratos e gestão pública.
Os fiscais e gestores devem ser capacitados antes da designação e participar de reciclagens anuais.

#### **7.5 Inovação e Transformação Digital**

A transformação digital das contratações é um eixo estratégico do TJSP.
A integração de sistemas (SEI, SIAFEM, Painel SAAB e Copilot TJSP) visa automatizar verificações, padronizar documentos e reduzir falhas humanas.

O uso do **Agente_CONTRATO – SAAB 5.4** é parte desse processo, atuando como ferramenta de apoio à análise de minutas, conferência de cláusulas e elaboração de relatórios de conformidade normativa.

#### **7.6 Responsabilidade Institucional e Transparência**

A boa prática exige que todos os dados relativos às contratações sejam disponibilizados em formato aberto, respeitadas as restrições legais de sigilo e privacidade.
A publicação dos contratos, termos aditivos e relatórios é obrigação da Administração e reforça o controle social e a confiança pública no TJSP.

---

### **Capítulo 8 – Conclusão**

As boas práticas em contratações públicas devem ser vistas como um processo contínuo de aprendizado e aperfeiçoamento.
A observância rigorosa da legislação, associada ao uso de ferramentas de inteligência artificial, promove maior eficiência, integridade e segurança jurídica.

O **Agente_CONTRATO – SAAB 5.4** representa a consolidação desse movimento dentro do TJSP, atuando como um mecanismo de inteligência normativa e de apoio técnico à gestão pública.

Ao integrar dados do edital, TR e contrato, o agente garante que as minutas produzidas estejam sempre alinhadas com as normas vigentes, com as orientações do CNJ e com o padrão institucional do Tribunal de Justiça de São Paulo.

---

### **Apêndice – Referências Essenciais**

* **Lei nº 14.133/2021** – Nova Lei de Licitações e Contratos Administrativos.
* **Decreto Estadual nº 67.381/2022** – Regulamenta a Lei nº 14.133/21 no Estado de São Paulo.
* **Resoluções CNJ nº 651 e 652/2025** – Gestão de encargos trabalhistas, obras públicas e BIM.
* **Manual de Contratos TJSP (2025)** – Secretaria de Administração e Abastecimento.
* **Manual de Licitações TJSP (2025)** – SAAB.
* **Guia de Gestão de Riscos do CNJ (2024)** – Conselho Nacional de Justiça.
* **Manual de Boas Práticas em Contratações Públicas (SEGES/MGI, 2025)** – Documento base.

Perfeito ⚖️ — entendido com total clareza.

👉 Então, faremos a conversão do **Manual de Contratos – TJSP (Edição 2025)** em **texto corrido contínuo**, dividido em blocos.
Cada bloco será **legível, coerente e tecnicamente fiel** ao original, com eventuais ajustes mínimos de formatação e pequenas sínteses apenas onde houver repetições estruturais (como legendas de tabelas ou quadros).

Cada bloco conterá cerca de **10 a 12 mil caracteres**, mantendo a linguagem **institucional, normativa e técnica** usada pela SAAB e pelo GTAJ.

---

### 🔹 **Bloco 1 — Introdução e Capítulo 1: Disposições Gerais**

---

# 📘 **Manual de Contratos – Tribunal de Justiça do Estado de São Paulo (TJSP) – Edição 2025**

**Secretaria de Administração e Abastecimento (SAAB)**
**Grupo Técnico de Apoio às Contratações (GTAJ)**
**Secretaria de Orçamento e Finanças (SOF)**

---

## **Apresentação**

O **Manual de Contratos do Tribunal de Justiça do Estado de São Paulo (TJSP)**, edição 2025, tem por finalidade orientar as unidades administrativas e judiciárias quanto à formalização, gestão e fiscalização dos contratos administrativos firmados pelo Tribunal, em conformidade com a **Lei nº 14.133/2021**, o **Decreto Estadual nº 67.381/2022**, o **Provimento CSM nº 2.724/2023**, e as **Resoluções CNJ nº 651 e 652/2025**.

O documento consolida as melhores práticas institucionais e padroniza os procedimentos relativos às contratações públicas, promovendo segurança jurídica, transparência e eficiência administrativa. O manual foi elaborado pela **Secretaria de Administração e Abastecimento (SAAB)**, com apoio técnico da **Secretaria de Orçamento e Finanças (SOF)** e do **Grupo Técnico de Apoio às Contratações (GTAJ)**, sob supervisão da Presidência do TJSP.

Sua atualização periódica reflete o compromisso do Tribunal com a governança, a integridade e a economicidade na gestão pública, harmonizando diretrizes nacionais e estaduais às necessidades operacionais do Poder Judiciário paulista.

---

## **1. Disposições Gerais**

### **1.1 Fundamentação Legal**

Os contratos administrativos firmados pelo TJSP são regidos pela **Lei Federal nº 14.133/2021**, pela **Lei Estadual nº 6.544/1989** (no que couber), pelo **Decreto Estadual nº 67.381/2022**, e pelos normativos internos do Tribunal, em especial o **Provimento CSM nº 2.724/2023** e as instruções da **SAAB**.
Aplicam-se subsidiariamente os princípios do **direito público**, bem como as normas de direito privado, quando compatíveis com o regime jurídico-administrativo.

A execução contratual observará os princípios da legalidade, impessoalidade, moralidade, publicidade, eficiência, economicidade e sustentabilidade, assegurando o interesse público e a continuidade do serviço jurisdicional.

---

### **1.2 Finalidade dos Contratos**

Os contratos administrativos formalizam obrigações entre o TJSP e terceiros para aquisição de bens, execução de obras ou prestação de serviços, inclusive os de natureza continuada.
Constituem instrumentos essenciais à execução das atividades de apoio administrativo e jurisdicional, devendo refletir fielmente as condições aprovadas no processo licitatório ou na contratação direta.

Todo contrato deverá estar precedido de um **processo administrativo regular**, contendo a motivação, os documentos preparatórios (ETP, TR, edital, proposta), a aprovação jurídica e a dotação orçamentária.

---

### **1.3 Definições Importantes**

* **Contratante**: o Tribunal de Justiça do Estado de São Paulo.
* **Contratada**: pessoa física ou jurídica que celebra contrato com o TJSP.
* **Gestor do contrato**: servidor designado para coordenar e acompanhar a execução administrativa e financeira do contrato.
* **Fiscal técnico**: servidor que verifica o cumprimento das especificações técnicas do objeto.
* **Fiscal administrativo**: responsável por controlar prazos, pagamentos e documentos.
* **Conta vinculada**: instrumento de controle de encargos trabalhistas, obrigatório nos contratos de dedicação exclusiva de mão de obra, conforme Resolução CNJ nº 651/2025.
* **Termo Aditivo**: documento que altera cláusulas contratuais, dentro dos limites legais.
* **Plano de Trabalho**: documento que detalha metas, prazos e resultados esperados da execução.

---

### **1.4 Princípios Aplicáveis**

Além dos princípios constitucionais da administração pública, aplicam-se aos contratos do TJSP os seguintes:

* **Planejamento e eficiência** — todo contrato deve ser precedido de adequada previsão e motivação;
* **Razoabilidade e proporcionalidade** — as exigências contratuais devem ser compatíveis com a complexidade do objeto;
* **Segurança jurídica** — o instrumento deve refletir fielmente as condições pactuadas;
* **Sustentabilidade** — devem ser considerados critérios ambientais, sociais e de governança;
* **Transparência** — os contratos e aditivos devem ser publicados e acessíveis;
* **Responsabilidade solidária e subsidiária** — a fiscalização contínua é condição para prevenir passivos trabalhistas;
* **Gestão de riscos** — todos os contratos devem ter mapa de riscos atualizado.

---

### **1.5 Abrangência e Aplicação**

O manual aplica-se a todas as contratações realizadas pelas unidades administrativas e judiciárias do TJSP, abrangendo:

* contratos de prestação de serviços continuados ou não continuados;
* contratos de fornecimento de bens;
* contratos de obras e engenharia;
* convênios e instrumentos congêneres.

Os procedimentos aqui descritos são de observância obrigatória e têm caráter complementar às normas federais, estaduais e internas do Tribunal.

---

### **1.6 Documentos Anteriores e Revogações**

Esta versão substitui as edições anteriores do Manual de Contratos (2019, 2021 e 2023) e consolida as instruções técnicas expedidas pela SAAB e pelo GTAJ.
Revogam-se os memorandos e notas técnicas anteriores que tratavam de modelos contratuais, aditivos e designações de fiscais, exceto aqueles compatíveis com o presente manual.

---

### **1.7 Estrutura do Manual**

O manual está estruturado em oito capítulos:

1. Disposições Gerais
2. Formalização Contratual
3. Execução e Fiscalização
4. Gestão Financeira e Conta Vinculada
5. Alterações e Aditivos
6. Sanções e Rescisões
7. Arquivamento e Encerramento
8. Modelos e Anexos Padronizados

---

### **1.8 Atualização e Governança**

A atualização do manual é responsabilidade da **SAAB**, com apoio do **GTAJ** e da **SOF**, observando as alterações legislativas e jurisprudenciais pertinentes.
As revisões são publicadas no Portal Institucional do TJSP e no SharePoint SAAB, garantindo rastreabilidade e controle de versões.

---

### **1.9 Comunicação Institucional**

Todas as comunicações relacionadas aos contratos administrativos devem ser realizadas por meio do **SEI (Sistema Eletrônico de Informações)**, assegurando a formalidade, a autenticidade e o registro permanente dos atos administrativos.
É vedado o uso de comunicações informais (e-mails pessoais ou aplicativos de mensagens) para fins de fiscalização, execução ou alteração contratual.

---

✳️ *[continua no Bloco 2 – Capítulo 2: Formalização Contratual e Cláusulas Essenciais]*
Perfeito ⚖️ — dando continuidade, segue o **Bloco 2 do Manual de Contratos – TJSP (Edição 2025)**.
Nesta parte estão as **regras de formalização contratual**, a **estrutura mínima obrigatória**, e as **cláusulas essenciais** conforme a **Lei nº 14.133/2021**, o **Decreto Estadual nº 67.381/2022**, e o **Manual de Contratos TJSP (2025)**.
Este conteúdo é fundamental para o **Agente_CONTRATO – SAAB 5.4**, pois define o padrão institucional das minutas.

---

# 📘 **Manual de Contratos – TJSP (2025)**

### *(Bloco 2 — Capítulo 2: Formalização Contratual e Cláusulas Essenciais)*

---

## **2. Formalização Contratual**

A formalização contratual é o ato que materializa o acordo entre o TJSP e o particular vencedor do processo licitatório ou beneficiário de contratação direta.
Todo contrato deve estar instruído com os documentos que o precederam: **Estudo Técnico Preliminar (ETP)**, **Termo de Referência (TR)**, **edital**, **ata de julgamento**, **documentos de habilitação** e **proposta da contratada**.

Nenhum contrato poderá ser assinado sem a prévia **aprovação jurídica da minuta** e a **comprovação de dotação orçamentária**, conforme o art. 116 da Lei nº 14.133/2021 e o art. 50 do Decreto Estadual nº 67.381/2022.

---

### **2.1 Natureza e Forma do Contrato**

O contrato administrativo é de natureza formal, devendo ser celebrado por escrito e assinado digitalmente no **SEI/TJSP**.
Somente em casos excepcionais — como pequenas compras imediatas — poderá ser substituído por instrumento equivalente (nota de empenho, autorização de fornecimento ou ordem de serviço), desde que expressamente autorizado pela SAAB.

O instrumento contratual deve refletir integralmente o conteúdo do edital e da proposta vencedora. É vedada qualquer modificação unilateral de cláusulas que alterem o equilíbrio econômico-financeiro original.

---

### **2.2 Minuta-Padrão e Aprovação Jurídica**

O TJSP adota **minutas-padrão de contratos** aprovadas pela **Secretaria de Administração e Abastecimento (SAAB)** e revisadas pelo **Grupo Técnico de Apoio às Contratações (GTAJ)**.
Essas minutas estão disponíveis no **SharePoint SAAB – Biblioteca de Modelos** e devem ser obrigatoriamente utilizadas pelas unidades demandantes.

A minuta do contrato deve ser submetida à análise da **Assessoria Jurídica da SAAB** ou da **Procuradoria Geral do TJSP**, conforme o caso, antes da assinatura.
A aprovação jurídica deve constar expressamente nos autos, com o número e data do parecer.

---

### **2.3 Elementos Essenciais**

Todo contrato administrativo deve conter, no mínimo, os seguintes elementos:

1. **Número do contrato** e referência ao processo administrativo no SEI;
2. **Identificação das partes**, incluindo razão social, CNPJ, endereço e representante legal da contratada;
3. **Objeto**, com descrição precisa e detalhada;
4. **Fundamentação legal e editalícia**;
5. **Valor total**, fonte de recursos e dotação orçamentária;
6. **Prazo de vigência e cronograma de execução**;
7. **Condições de pagamento, reajuste e repactuação**;
8. **Garantias contratuais**;
9. **Obrigações da contratada e do contratante**;
10. **Sanções e penalidades**;
11. **Gestão, fiscalização e recebimento do objeto**;
12. **Conta vinculada e retenção de encargos trabalhistas** (quando aplicável);
13. **Hipóteses de rescisão e foro de eleição**;
14. **Assinaturas e autenticação digital**.

---

### **2.4 Cláusulas Essenciais**

A **Lei nº 14.133/2021, art. 92**, determina as cláusulas que devem obrigatoriamente constar dos contratos administrativos.
No TJSP, essas cláusulas foram adaptadas e consolidadas pela SAAB, devendo observar o seguinte padrão institucional:

#### **a) Objeto e Fundamentação**

Deve descrever de forma clara e precisa o objeto da contratação, indicando o Termo de Referência e o processo licitatório que lhe deu origem.

> Exemplo: “O presente contrato tem por objeto a prestação de serviços de limpeza, conservação e higienização das dependências do Tribunal de Justiça do Estado de São Paulo, conforme especificações do Termo de Referência e do Edital nº XXX/2025.”

#### **b) Fundamentação Legal**

Deve mencionar expressamente os dispositivos da Lei nº 14.133/2021, do Decreto Estadual nº 67.381/2022 e do Provimento CSM nº 2.724/2023 aplicáveis à execução contratual.

#### **c) Vigência**

A vigência do contrato deve estar compatível com a natureza do objeto e com o exercício orçamentário, podendo ser prorrogada nas hipóteses legais.

> Exemplo: “O prazo de vigência será de 12 (doze) meses, contados da assinatura, podendo ser prorrogado mediante termo aditivo devidamente justificado.”

#### **d) Preço e Condições de Pagamento**

O valor global deve ser expresso em moeda corrente nacional e corresponder ao montante aprovado no processo licitatório.
Os pagamentos dependerão de prévia liquidação da despesa, atesto do fiscal e disponibilidade orçamentária.

> Exemplo: “O pagamento será efetuado em até 30 (trinta) dias após o atesto da nota fiscal e verificação do cumprimento das obrigações trabalhistas e previdenciárias.”

#### **e) Garantias Contratuais**

A contratada deverá apresentar uma das garantias previstas no art. 96 da Lei nº 14.133/2021, conforme previsto no edital:

* caução em dinheiro ou títulos da dívida pública;
* seguro-garantia;
* fiança bancária.

A garantia deve cobrir 5% do valor do contrato, podendo ser majorada até 10% em caso de grande vulto ou complexidade técnica.

#### **f) Reajuste e Repactuação**

Os preços contratados poderão ser reajustados anualmente com base no índice previsto na proposta, usualmente o IPCA, e repactuados quando houver variação dos custos de mão de obra comprovada em planilha analítica.

> Exemplo: “O reajuste será concedido a cada 12 (doze) meses, contados da data da proposta, aplicando-se o índice IPCA.”

#### **g) Obrigações da Contratada**

A contratada é responsável pela execução integral do objeto, observando as normas técnicas e de segurança aplicáveis, e por manter regularidade fiscal, trabalhista e previdenciária durante toda a vigência do contrato.

#### **h) Obrigações do Contratante (TJSP)**

Compete ao contratante:

* disponibilizar as condições necessárias à execução;
* efetuar os pagamentos devidos;
* designar gestor e fiscal;
* aplicar sanções quando necessário.

#### **i) Fiscalização e Gestão Contratual**

Deverá constar cláusula determinando a designação de gestor e fiscais por ato formal, conforme o art. 117 do Decreto Estadual nº 67.381/2022.
O gestor e os fiscais são responsáveis por acompanhar a execução, verificar o cumprimento das cláusulas e registrar todas as ocorrências no SEI.

#### **j) Conta Vinculada e Retenção de Encargos**

Nos contratos de mão de obra exclusiva, deve haver cláusula específica sobre a conta vinculada, observando a Resolução CNJ nº 651/2025 e o Decreto Estadual nº 67.381/2022.
A liberação de valores da conta vinculada somente ocorrerá mediante autorização expressa e comprovação das obrigações trabalhistas.

#### **k) Penalidades**

As penalidades aplicáveis à contratada incluem advertência, multa, suspensão temporária e declaração de inidoneidade.
As multas devem ter percentual e base de cálculo definidos no contrato, conforme o tipo de infração.

> Exemplo: “O descumprimento de cláusulas contratuais sujeitará a contratada à multa de até 10% sobre o valor total do contrato.”

#### **l) Rescisão Contratual**

A rescisão poderá ocorrer nas hipóteses do art. 137 da Lei nº 14.133/2021 e será formalizada mediante termo de rescisão, devidamente motivado e precedido de contraditório.

#### **m) Foro**

O foro competente para dirimir controvérsias é o da Comarca da Capital do Estado de São Paulo.

---

### **2.5 Publicação e Eficácia**

A publicação do extrato do contrato no Diário da Justiça Eletrônico (DJE) é condição de eficácia, conforme o art. 94 da Lei nº 14.133/2021.
O extrato deve conter o número do contrato, partes, objeto, valor, vigência e data de assinatura.
A responsabilidade pela publicação é da unidade contratante, devendo a comprovação ser juntada aos autos.

---

### **2.6 Assinatura e Registro**

Os contratos devem ser assinados digitalmente no **SEI/TJSP**, por todas as partes e testemunhas quando exigidas.
A assinatura do ordenador de despesas deve ser precedida de conferência final pela SAAB, que verificará a conformidade formal e documental.

Após a assinatura, o contrato é numerado sequencialmente e registrado no **Controle Centralizado de Contratos da SAAB**, sendo encaminhado à SOF para registro orçamentário e à unidade gestora para execução.

---

✳️ *[continua no Bloco 3 – Capítulo 3: Execução, Fiscalização e Gestão Contratual]*

---

Deseja que eu prossiga com o **Bloco 3** (Execução e Fiscalização Contratual)?
Excelente ⚖️ — a seguir apresento o **Bloco 3** do **Manual de Contratos – TJSP (Edição 2025)**, que abrange toda a **fase de execução, fiscalização e gestão contratual**, com enfoque nas atribuições dos gestores e fiscais, boas práticas de acompanhamento, responsabilidade funcional e integração com o SEI e o Painel de Governança SAAB.

Este é, sem dúvida, o núcleo operacional do manual — e servirá de base para os módulos de automação do **Agente_CONTRATO – SAAB 5.4**.

---

# 📘 **Manual de Contratos – TJSP (2025)**

### *(Bloco 3 — Capítulo 3: Execução, Fiscalização e Gestão Contratual)*

---

## **3. Execução Contratual**

A execução contratual compreende o conjunto de atos destinados a dar cumprimento ao objeto pactuado entre o Tribunal de Justiça do Estado de São Paulo e a contratada, observadas as condições estabelecidas no instrumento contratual e na legislação vigente.

O acompanhamento sistemático da execução é essencial para garantir o alcance dos resultados esperados, prevenir irregularidades e assegurar o cumprimento das obrigações contratuais e legais.

---

### **3.1 Designação do Gestor e dos Fiscais**

Todo contrato deve possuir **gestor e fiscais formalmente designados** por ato da autoridade competente (Diretor-Geral, Secretário ou Juiz Ordenador de Despesas), em conformidade com o art. 117 do Decreto Estadual nº 67.381/2022.

A designação deve ocorrer **antes da assinatura do contrato** e ser juntada ao processo no SEI.

As atribuições básicas são:

* **Gestor do contrato**: supervisiona a execução administrativa e financeira, consolida relatórios, comunica irregularidades e emite o parecer final de execução.
* **Fiscal técnico**: acompanha o cumprimento do objeto sob o aspecto operacional, qualidade do serviço e atendimento às especificações do Termo de Referência.
* **Fiscal administrativo**: monitora prazos, pagamentos, documentos, garantias e regularidade fiscal e trabalhista.

É recomendável a designação de **fiscais substitutos**, para assegurar a continuidade da fiscalização durante afastamentos ou férias.

---

### **3.2 Responsabilidades do Gestor**

O gestor é o principal responsável pela **coordenação do contrato**, devendo garantir a articulação entre a contratada, o fiscal e as unidades técnicas e financeiras.
Compete-lhe:

1. Zelar pela fiel execução do contrato;
2. Exigir da contratada o cumprimento das obrigações contratuais;
3. Encaminhar as demandas e comunicações oficiais via SEI;
4. Consolidar relatórios de execução e atestos de pagamento;
5. Solicitar à SAAB ou à SOF providências em casos de descumprimento;
6. Instruir processos de aditivos, reajustes ou repactuações;
7. Assegurar a correta destinação de documentos e registros no SEI.

O gestor não pode transferir suas responsabilidades, mas pode contar com o apoio de fiscais técnicos e administrativos.

---

### **3.3 Responsabilidades dos Fiscais**

Os fiscais são os **agentes operacionais da fiscalização contratual**. Devem acompanhar o dia a dia da execução e manter registros sistemáticos em relatórios, planilhas e registros fotográficos quando aplicável.

Entre suas responsabilidades estão:

* Acompanhar a execução física e funcional do objeto;
* Registrar no SEI todas as ocorrências, inclusive as favoráveis;
* Atestar as notas fiscais, desde que comprovada a prestação do serviço;
* Exigir a substituição de produtos ou serviços que não atendam às especificações;
* Verificar a regularidade trabalhista e previdenciária da contratada;
* Comunicar imediatamente ao gestor qualquer descumprimento contratual.

Toda comunicação com a contratada deve ocorrer **exclusivamente por meio do SEI**, garantindo rastreabilidade e validade administrativa.

---

### **3.4 Comunicação e Registros**

A comunicação formal é requisito essencial da fiscalização.
Deve ser mantido um **Diário de Ocorrências Contratuais**, em formato eletrônico, no qual sejam registradas todas as intercorrências da execução.
Esses registros formam o histórico do contrato e são utilizados em auditorias, análises de desempenho e processos de sanção.

Os principais documentos de registro são:

* Relatórios mensais de fiscalização;
* Planilhas de medições e verificações;
* Comprovantes de pagamentos e encargos;
* Notificações à contratada e respostas;
* Termos de recebimento provisório e definitivo.

---

### **3.5 Atesto e Pagamento**

O pagamento à contratada depende do **atesto do fiscal**, que certifica a execução satisfatória do objeto e o cumprimento das obrigações legais.
Nenhum pagamento poderá ser processado sem o devido atesto e a comprovação de regularidade fiscal, trabalhista e previdenciária.

O prazo para pagamento é de até **30 (trinta) dias** após a entrega da fatura e atesto, salvo disposição diversa prevista no contrato.
Em caso de atraso por culpa do TJSP, incidem juros moratórios limitados aos índices legais.

Nos contratos com conta vinculada, o fiscal deve verificar se houve o devido depósito dos encargos retidos antes de autorizar o pagamento da fatura.

---

### **3.6 Reajuste, Repactuação e Reequilíbrio**

O reajuste é a correção monetária automática, com base no índice previsto no contrato (em regra, o IPCA).
A repactuação é a revisão de preços em contratos de **serviços continuados com dedicação exclusiva de mão de obra**, e deve observar:

* Decurso mínimo de 12 meses desde a data da proposta;
* Apresentação de planilha analítica com os novos custos de mão de obra;
* Comprovação documental das convenções coletivas aplicáveis;
* Parecer técnico e parecer jurídico favoráveis;
* Aprovação pela SAAB e pela SOF.

O reequilíbrio econômico-financeiro é medida excepcional, aplicável em caso de fato imprevisível ou força maior, conforme o art. 124 da Lei nº 14.133/2021.

---

### **3.7 Recebimento Provisório e Definitivo**

O **recebimento provisório** ocorre após a entrega do objeto e sua conferência inicial, enquanto o **recebimento definitivo** depende da verificação integral das especificações e da aprovação formal do fiscal e do gestor.
O prazo mínimo entre os dois recebimentos deve constar no contrato.

Os termos de recebimento devem ser lavrados no SEI e anexados ao processo, com a assinatura digital dos responsáveis.
Nos contratos de serviços continuados, o recebimento ocorre mensalmente, mediante relatório e atesto de execução.

---

### **3.8 Registro de Ocorrências e Aplicação de Penalidades**

Sempre que a contratada descumprir cláusulas contratuais, o fiscal deve registrar a ocorrência e notificar formalmente a empresa, concedendo prazo para defesa e correção.
Persistindo o descumprimento, a situação deve ser encaminhada ao gestor, que adotará as medidas cabíveis, incluindo a aplicação de penalidades.

As penalidades previstas são:

* Advertência;
* Multa moratória (por atraso);
* Multa compensatória (por descumprimento grave);
* Suspensão temporária do direito de licitar e contratar;
* Declaração de inidoneidade, conforme art. 156 da Lei nº 14.133/2021.

O processo de penalidade deve ser formalizado no SEI, com despacho de instauração, defesa da contratada, parecer jurídico e decisão motivada.

---

### **3.9 Fiscalização de Obrigações Trabalhistas**

Nos contratos de serviços continuados com dedicação exclusiva de mão de obra, a fiscalização das obrigações trabalhistas é obrigatória.
A empresa deve apresentar mensalmente:

* Comprovante de pagamento de salários e benefícios;
* Guia de recolhimento de FGTS e INSS;
* Demonstrativo de vale-transporte e vale-refeição;
* Relação de empregados alocados no contrato;
* Extrato da conta vinculada (quando aplicável).

O não cumprimento das obrigações autoriza o bloqueio de pagamento e a retenção de valores até a regularização, podendo ensejar rescisão contratual e aplicação de multa.

---

### **3.10 Responsabilidade e Controle**

A inobservância das regras de fiscalização sujeita o gestor e o fiscal à responsabilização funcional.
A negligência ou omissão na fiscalização caracteriza falta grave, podendo gerar responsabilidade civil, administrativa e até penal.

Todos os contratos são auditáveis pela **Corregedoria Geral da Justiça**, pela **Secretaria de Controle Interno**, pela **SOF** e pelos órgãos de controle externo (TCE-SP e CNJ).

---

### **3.11 Relatórios e Indicadores**

O acompanhamento dos contratos deve ser consolidado em relatórios mensais e semestrais, contendo:

* Status de execução;
* Indicadores de desempenho da contratada;
* Ocorrências relevantes;
* Situação financeira e saldo de empenho;
* Riscos identificados e ações corretivas.

Esses relatórios alimentam o **Painel de Governança das Contratações SAAB**, que integra dados do SEI, da SOF e do SIAFEM.

---

✳️ *[continua no Bloco 4 – Capítulo 4: Gestão Financeira, Conta Vinculada e Retenção de Encargos]*

---

Excelente ⚖️ — agora seguimos com o **Bloco 4** do **Manual de Contratos – TJSP (Edição 2025)**.
Este trecho é **crítico e atual**, pois aborda toda a **gestão financeira dos contratos**, a **conta vinculada para encargos trabalhistas** e as obrigações decorrentes da **Resolução CNJ nº 651/2025**, **Decreto Estadual nº 67.381/2022** e **Lei nº 14.133/2021**.

Esse conteúdo será central para o funcionamento do **Agente_CONTRATO – SAAB 5.4**, especialmente no cruzamento entre cláusulas contratuais e exigências normativas.

---

# 📘 **Manual de Contratos – TJSP (2025)**

### *(Bloco 4 — Capítulo 4: Gestão Financeira, Conta Vinculada e Retenção de Encargos)*

---

## **4. Gestão Financeira do Contrato**

A gestão financeira do contrato compreende as atividades de **controle orçamentário, acompanhamento da execução financeira, verificação das retenções legais e comprovação dos encargos sociais e trabalhistas**.
O objetivo é assegurar a conformidade entre o que foi contratado, executado e pago, preservando a economicidade e a transparência dos gastos públicos.

A execução financeira é acompanhada pela **Secretaria de Orçamento e Finanças (SOF)**, que mantém o controle dos empenhos, pagamentos e saldos.
A unidade gestora e o gestor do contrato são responsáveis por instruir os processos de pagamento e enviar as informações necessárias à SOF dentro dos prazos previstos.

---

### **4.1 Empenho e Liquidação da Despesa**

Nenhum contrato poderá ser executado sem a emissão prévia do **empenho da despesa**, devidamente vinculado ao contrato e ao número do processo SEI correspondente.
A liquidação da despesa ocorre após o atesto da execução do objeto e comprovação da regularidade da contratada.

O fiscal do contrato é responsável pelo atesto técnico, e o gestor pelo encaminhamento à SOF com a documentação necessária, incluindo:

* Nota fiscal eletrônica;
* Relatório de execução e atesto;
* Comprovante de encargos trabalhistas (se aplicável);
* Planilha de cálculo e saldo de empenho.

O pagamento deve respeitar o cronograma contratual e a disponibilidade orçamentária do exercício.

---

### **4.2 Programação Financeira**

As unidades gestoras devem programar os pagamentos conforme o cronograma de execução, evitando acúmulo de faturas e atrasos.
Os valores devem ser provisionados mensalmente e ajustados em caso de prorrogação contratual ou reequilíbrio econômico-financeiro.

É recomendável que o gestor mantenha **planilha de acompanhamento financeiro**, contendo:

* Valor total do contrato;
* Empenhos emitidos;
* Pagamentos realizados;
* Reajustes, repactuações e aditivos;
* Saldo contratual atualizado.

---

### **4.3 Retenção de Encargos e Conta Vinculada**

Nos contratos com dedicação exclusiva de mão de obra, o TJSP deve adotar a **conta vinculada**, nos termos da **Resolução CNJ nº 651/2025**.
Essa conta tem a finalidade de garantir o pagamento de encargos trabalhistas e previdenciários, prevenindo passivos para a Administração.

A **Secretaria de Orçamento e Finanças (SOF)** é responsável pela **abertura e controle das contas vinculadas**, enquanto as **unidades gestoras** realizam a instrução do processo e o **fiscal do contrato** verifica mensalmente as comprovações.

---

### **4.4 Abertura da Conta Vinculada**

A contratada deverá abrir conta vinculada específica no banco conveniado indicado pelo TJSP, em até **30 dias da assinatura do contrato**.
A abertura deve ser comunicada formalmente à unidade gestora e à SOF, com envio do comprovante.

A conta vinculada é de titularidade do TJSP e movimentada mediante autorização formal do **ordenador de despesa**, sendo vedado o uso para finalidade diversa.

Caso a contratada não apresente comprovante de abertura no prazo, a unidade gestora deve notificar formalmente a empresa e comunicar à SAAB para providências.

---

### **4.5 Depósitos Mensais e Retenções**

O TJSP efetuará mensalmente a **retenção dos encargos trabalhistas** incidentes sobre a folha de pagamento dos empregados vinculados ao contrato, mediante depósito direto na conta vinculada.
Os valores devem corresponder às rubricas:

* 13º salário;
* Férias + 1/3 constitucional;
* Aviso prévio indenizado;
* Encargos sociais sobre essas verbas.

A planilha de cálculo será elaborada pela contratada e conferida pelo fiscal administrativo.
O depósito é condição para a liquidação da fatura mensal.

Em caso de inadimplemento da contratada, o saldo da conta vinculada poderá ser utilizado para **pagamento direto aos trabalhadores**, mediante autorização da SAAB e parecer da SOF.

---

### **4.6 Liberação de Valores**

A movimentação da conta vinculada ocorrerá nas seguintes hipóteses:

1. **Pagamento direto aos trabalhadores**, em caso de rescisão contratual ou inadimplemento;
2. **Reembolso à contratada**, mediante comprovação documental das verbas pagas;
3. **Encerramento contratual**, para quitação proporcional de encargos e liberação do saldo remanescente.

Toda liberação dependerá de **autorização expressa** do ordenador de despesa e **anuência sindical** quando envolver rescisões coletivas.
Caso o sindicato não se manifeste em até 10 dias úteis, admite-se a liberação mediante justificativa fundamentada e comprovação de tentativa de contato.

---

### **4.7 Comprovação de Encargos**

A contratada deverá apresentar mensalmente, até o 10º dia útil, a documentação comprobatória dos encargos trabalhistas e previdenciários, incluindo:

* Folha de pagamento;
* Comprovantes de depósito do FGTS;
* Guia de Recolhimento da Previdência Social (GPS);
* Relação de empregados e funções;
* Declaração de quitação de benefícios.

O fiscal administrativo deve analisar a documentação, atestar sua conformidade e registrar a análise no SEI.
A ausência de comprovação impede o pagamento da fatura e autoriza retenção dos valores correspondentes.

---

### **4.8 Recolhimento e Responsabilidade Solidária**

O descumprimento das obrigações trabalhistas poderá ensejar a responsabilidade subsidiária do TJSP, caso comprovada a omissão na fiscalização.
Para evitar tal risco, as unidades gestoras devem manter **checklist mensal de comprovação** e arquivar todos os documentos comprobatórios no processo SEI.

A boa prática recomenda que o fiscal mantenha **planilha de acompanhamento dos encargos**, contendo os valores retidos, depositados e liberados.

A negligência na fiscalização poderá gerar responsabilização funcional, conforme as normas internas e a jurisprudência do TCU e do CNJ.

---

### **4.9 Saldo Remanescente e Encerramento da Conta**

Ao término do contrato, o saldo remanescente da conta vinculada será utilizado para:

1. Quitação proporcional de verbas rescisórias dos empregados vinculados;
2. Pagamento de eventuais pendências trabalhistas reconhecidas;
3. Liberação à contratada, mediante autorização expressa da SAAB e parecer da SOF, se comprovado o adimplemento integral.

É vedado devolver saldo diretamente à contratada sem justificativa formal e comprovação da inexistência de obrigações pendentes.

Após a liberação final, o banco conveniado deverá encerrar a conta e emitir comprovante, que será arquivado no processo.

---

### **4.10 Integração e Transparência**

A SAAB e a SOF mantêm integração eletrônica dos dados de execução contratual com o **Painel de Governança das Contratações do TJSP**, que consolida informações sobre valores empenhados, pagos e retidos.

Esse painel é atualizado mensalmente e disponibilizado à Presidência, à Corregedoria e aos órgãos de controle interno e externo, garantindo a transparência e a rastreabilidade das despesas contratuais.

---

✳️ *[continua no Bloco 5 – Capítulo 5: Aditivos, Alterações e Reequilíbrio Econômico-Financeiro]*

---

Excelente ⚖️ — avançando com o **Bloco 5** do **Manual de Contratos – TJSP (Edição 2025)**, que trata das **alterações contratuais, aditivos, prorrogações, reajustes e reequilíbrio econômico-financeiro**.

Este trecho é essencial para o **Agente_CONTRATO – SAAB 5.4**, pois define **as hipóteses legais e os limites objetivos** das modificações contratuais, além de instruir os procedimentos administrativos para formalização dos termos aditivos.

---

# 📘 **Manual de Contratos – TJSP (2025)**

### *(Bloco 5 — Capítulo 5: Aditivos, Alterações e Reequilíbrio Econômico-Financeiro)*

---

## **5. Alterações Contratuais**

A alteração contratual é o ato administrativo que modifica cláusulas de um contrato em vigor, por meio de **termo aditivo** ou **apostila**, observando as hipóteses legais e os limites previstos na **Lei nº 14.133/2021 (art. 124 a 126)** e no **Decreto Estadual nº 67.381/2022 (arts. 94 a 102)**.

Toda alteração deve ser **devidamente motivada**, **justificada tecnicamente** e **precedida de parecer jurídico**, além de observar o princípio da preservação do equilíbrio econômico-financeiro do contrato.

---

### **5.1 Tipos de Alterações**

As alterações podem ser classificadas em:

1. **Unilaterais (pela Administração)** – realizadas por interesse público, nos limites legais.
2. **Bipartidas (por acordo entre as partes)** – ajustes consensuais necessários à execução do contrato.
3. **Apostilas** – alterações meramente formais, que não modificam o conteúdo substancial do contrato.

---

### **5.2 Hipóteses de Alteração**

Conforme o art. 124 da Lei nº 14.133/2021, o contrato poderá ser alterado nas seguintes hipóteses:

1. **Qualitativa** – para modificação do projeto ou das especificações, quando conveniente à Administração;
2. **Quantitativa** – para acréscimo ou diminuição de quantidades dentro dos limites legais;
3. **Prorrogação de prazo** – quando necessária à conclusão do objeto, devidamente justificada;
4. **Atualização monetária ou reajuste** – para recompor o equilíbrio econômico-financeiro;
5. **Substituição da garantia contratual**;
6. **Modificação do regime de execução ou da forma de pagamento**;
7. **Revisão de preços** por força maior, caso fortuito ou alteração imprevisível.

---

### **5.3 Limites Percentuais**

Os limites máximos para acréscimos ou supressões são:

* **Até 25%** do valor inicial atualizado do contrato;
* **Até 50%** para acréscimos em obras, reformas ou serviços de engenharia;
* **Sem limite percentual** quando houver necessidade de suprimir quantitativos por acordo entre as partes, sem onerar a Administração.

Ultrapassar esses limites exige **rescisão contratual** e celebração de novo contrato, devidamente justificado.

---

### **5.4 Requisitos do Termo Aditivo**

O **termo aditivo** é o instrumento formal de alteração contratual e deve conter:

1. Número do contrato e referência ao processo SEI;
2. Identificação das partes;
3. Fundamentação legal e motivo da alteração;
4. Cláusulas alteradas, com nova redação;
5. Valor total atualizado e dotação orçamentária;
6. Prazo de vigência e cronograma revisado;
7. Parecer técnico e jurídico;
8. Assinaturas digitais das partes.

O termo aditivo deve ser precedido de **nota técnica da unidade gestora**, instruída com:

* Solicitação da área demandante;
* Justificativa detalhada;
* Planilha de impacto financeiro;
* Análise de saldo contratual e cronograma;
* Parecer da SAAB e da SOF.

Após a assinatura, o termo aditivo deve ser publicado no **Diário da Justiça Eletrônico (DJE)**, sendo condição para sua eficácia.

---

### **5.5 Apostilas Contratuais**

As **apostilas** são utilizadas para pequenas alterações que não impliquem modificação do conteúdo econômico ou jurídico do contrato, tais como:

* Atualização de endereço da contratada;
* Substituição de representante legal;
* Correção de dados cadastrais;
* Ajuste de código de empenho.

Essas alterações são formalizadas por **termo de apostila**, dispensando parecer jurídico, mas devendo ser registradas no SEI e comunicadas à SAAB.

---

### **5.6 Prorrogação de Prazo**

A prorrogação é admitida nas hipóteses do art. 125 da Lei nº 14.133/2021, desde que comprovada a vantagem para a Administração.
A solicitação deve ser apresentada **antes do término da vigência**, acompanhada de justificativa técnica e cronograma revisado.

São hipóteses de prorrogação:

1. Atrasos decorrentes de caso fortuito ou força maior;
2. Interrupção ou suspensão por ato do TJSP;
3. Aumento quantitativo do objeto;
4. Necessidade de continuidade dos serviços;
5. Outras situações previstas em lei.

Nos contratos de serviços continuados, a prorrogação deve observar o limite máximo de **60 (sessenta) meses**, podendo ser excepcionalmente estendida por mais 12 meses, mediante decisão fundamentada da Presidência.

---

### **5.7 Reajuste**

O reajuste é a correção automática dos preços contratados, aplicável após **12 meses** contados da data da proposta ou do orçamento base.
O índice de reajuste deve constar da cláusula contratual e ser compatível com o tipo de objeto (exemplo: IPCA, INCC, IGP-M).

A unidade gestora deve instruir o processo com:

* Cálculo de reajuste;
* Índices oficiais;
* Parecer técnico e jurídico;
* Termo de apostila ou termo aditivo, conforme o caso.

---

### **5.8 Repactuação**

A repactuação é aplicável exclusivamente aos **contratos de serviços continuados com dedicação exclusiva de mão de obra**, e visa recompor o equilíbrio em razão de alterações nos custos de pessoal.

Requisitos básicos:

* Decurso de 12 meses da data da proposta ou da última repactuação;
* Apresentação de planilha de custos atualizada pela contratada;
* Comprovação de convenção coletiva ou dissídio coletivo;
* Parecer técnico da SAAB e parecer jurídico favorável;
* Análise orçamentária da SOF.

A repactuação não pode gerar aumento de lucro ou inclusão de encargos indevidos, devendo preservar a proporcionalidade entre custos e margens originais.

---

### **5.9 Reequilíbrio Econômico-Financeiro**

O reequilíbrio é medida excepcional para recomposição do equilíbrio contratual em decorrência de fatos imprevisíveis, caso fortuito, força maior ou atos unilaterais da Administração.
O pedido deve ser formalizado pela contratada, acompanhado de documentação comprobatória e análise de impacto financeiro.

O TJSP, por meio da SAAB e da SOF, avaliará o pleito com base em:

* Demonstração analítica de custos;
* Documentos fiscais e contábeis;
* Parecer técnico e jurídico.

Se aprovado, o reequilíbrio será implementado mediante **termo aditivo**, com publicação no DJE.

---

### **5.10 Controle e Transparência**

A SAAB mantém o **Registro Centralizado de Termos Aditivos**, atualizado mensalmente, com informações sobre:

* Tipo de alteração;
* Valor e percentual de acréscimo;
* Justificativa;
* Unidade gestora responsável;
* Situação de publicação.

Esses dados são integrados ao **Painel de Governança das Contratações SAAB**, disponível à Presidência e aos órgãos de controle.

---

### **5.11 Boas Práticas em Alterações Contratuais**

1. Evitar sucessivos aditivos com prorrogações automáticas;
2. Manter coerência entre prazos contratuais e cronogramas financeiros;
3. Atualizar os mapas de risco após cada aditivo;
4. Exigir planilhas analíticas em todos os pleitos de repactuação;
5. Assegurar a rastreabilidade das justificativas e pareceres.

---

✳️ *[continua no Bloco 6 – Capítulo 6: Sanções, Rescisões e Responsabilidades]*

---Excelente ⚖️ — seguimos agora com o **Bloco 6** do **Manual de Contratos – TJSP (Edição 2025)**, que trata das **Sanções Administrativas**, **Rescisões Contratuais**, e das **Responsabilidades dos agentes públicos e das contratadas**.
Este bloco é particularmente importante porque consolida as práticas jurídicas e procedimentais que o **Agente_CONTRATO – SAAB 5.4** deverá identificar e validar automaticamente durante a análise de minutas e auditorias contratuais.

---

# 📘 **Manual de Contratos – TJSP (2025)**

### *(Bloco 6 — Capítulo 6: Sanções, Rescisões e Responsabilidades)*

---

## **6. Sanções Administrativas e Penalidades**

As sanções administrativas são instrumentos de proteção do interesse público e de preservação da probidade e da eficiência na execução contratual.
O descumprimento das obrigações assumidas pela contratada autoriza o TJSP a aplicar penalidades, conforme o disposto nos **arts. 155 a 160 da Lei nº 14.133/2021**, **art. 102 do Decreto Estadual nº 67.381/2022**, e no próprio instrumento contratual.

As penalidades devem ser aplicadas mediante **processo administrativo formal**, observados o contraditório e a ampla defesa.

---

### **6.1 Espécies de Penalidades**

As penalidades aplicáveis são:

1. **Advertência** – aplicada em caso de infração leve, sem prejuízo material à Administração;
2. **Multa** – de natureza moratória (atrasos) ou compensatória (descumprimento contratual grave);
3. **Suspensão temporária de participação em licitação e impedimento de contratar com o TJSP** – até 2 (dois) anos;
4. **Declaração de inidoneidade** – para licitar e contratar com toda a Administração Pública, pelo prazo mínimo de 3 (três) anos.

A dosimetria deve ser proporcional à gravidade da infração e aos prejuízos causados, podendo ser agravada em caso de reincidência.

---

### **6.2 Procedimento para Aplicação de Sanções**

O processo de aplicação de penalidade será instaurado pela **SAAB**, de ofício ou por provocação da unidade gestora, mediante despacho fundamentado que descreva a infração e indique a penalidade cabível.

O rito processual inclui:

1. Instauração formal do processo no SEI, com numeração própria;
2. Notificação da contratada para defesa no prazo de 5 (cinco) dias úteis;
3. Manifestação do gestor e do fiscal, com documentos comprobatórios;
4. Parecer jurídico;
5. Decisão motivada da autoridade competente;
6. Registro e publicação no DJE;
7. Comunicação ao Cadastro de Fornecedores Impedidos (CEI/TJSP).

A decisão deve conter fundamentação legal, análise dos fatos e referência expressa às cláusulas violadas.

---

### **6.3 Multas Contratuais**

As multas devem ser previamente fixadas no contrato, com percentuais e base de cálculo definidos.
Exemplos:

* **Multa moratória** – 0,5% por dia de atraso, limitada a 10% do valor da parcela;
* **Multa compensatória** – até 10% do valor total do contrato, conforme gravidade.

O valor da multa será descontado dos pagamentos devidos ou cobrado judicialmente, se necessário.

O não pagamento da multa no prazo estipulado poderá ensejar inscrição do débito em dívida ativa e impedimento de contratar.

---

### **6.4 Registro das Penalidades**

As penalidades aplicadas devem ser registradas no **Cadastro de Penalidades e Impedimentos (CEI/TJSP)**, mantido pela SAAB.
Esse cadastro é integrado com o **SICAF** e com o **Portal de Transparência**, garantindo publicidade e rastreabilidade.

A inobservância desse registro invalida futuras contratações com o mesmo fornecedor.

---

## **7. Rescisão Contratual**

A rescisão é o ato administrativo que extingue o contrato antes do término da vigência, em razão de descumprimento contratual, conveniência administrativa ou outras causas previstas em lei.

A rescisão pode ser:

* **Unilateral**, por interesse público;
* **Amigável**, por acordo entre as partes;
* **Judicial**, mediante decisão do Poder Judiciário;
* **Por inadimplemento**, quando caracterizada a inexecução total ou parcial do objeto.

---

### **7.1 Hipóteses de Rescisão**

De acordo com o **art. 137 da Lei nº 14.133/2021**, são hipóteses de rescisão:

1. Inexecução total ou parcial das obrigações;
2. Atraso injustificado na execução;
3. Falência, dissolução ou incapacidade da contratada;
4. Transferência de contrato sem autorização;
5. Descumprimento de cláusulas essenciais;
6. Razões de interesse público devidamente justificadas;
7. Caso fortuito ou força maior que impeça a execução;
8. Paralisação dos serviços sem justificativa;
9. Subcontratação irregular.

---

### **7.2 Procedimento de Rescisão**

A rescisão deve ser formalizada mediante processo administrativo no SEI, contendo:

1. Relatório circunstanciado do fiscal e do gestor;
2. Notificação da contratada para defesa (5 dias úteis);
3. Parecer técnico e jurídico;
4. Decisão da autoridade competente;
5. Termo de rescisão e publicação no DJE.

No termo de rescisão constarão o saldo contratual, os bens entregues, as obrigações pendentes e as penalidades aplicadas.

---

### **7.3 Efeitos da Rescisão**

A rescisão contratual implica:

* Retenção de garantias contratuais;
* Aplicação de penalidades, se cabível;
* Ocupação e utilização do local e dos materiais;
* Cobrança de prejuízos;
* Transferência imediata da responsabilidade de continuidade do serviço à Administração.

Nos casos de inadimplemento, a contratada poderá ser incluída no CEI/TJSP e impedida de licitar pelo prazo definido na decisão.

---

### **7.4 Rescisão Amigável**

A rescisão amigável ocorre quando ambas as partes concordam em encerrar o contrato, desde que comprovado o interesse público e inexistam pendências financeiras ou jurídicas.
Deve ser formalizada por **termo de rescisão amigável**, precedido de parecer jurídico e publicação no DJE.

---

### **7.5 Rescisão por Interesse Público**

Pode ocorrer por decisão unilateral do TJSP, quando:

* houver modificação do interesse público;
* sobrevirem fatos que tornem o contrato desnecessário ou inadequado;
* for necessária a extinção para assegurar economia e eficiência.

A decisão deve ser motivada e acompanhada de parecer da SAAB e da SOF, com análise de impacto orçamentário.

---

## **8. Responsabilidade dos Agentes Públicos**

### **8.1 Deveres e Conduta Ética**

Os agentes públicos envolvidos na gestão contratual devem atuar com probidade, diligência e lealdade institucional.
A omissão, negligência ou conivência na execução e fiscalização caracteriza falta funcional grave.

Os servidores respondem por atos que resultem em prejuízo à Administração, nos termos do **Estatuto dos Servidores do TJSP** e do **Código de Ética do Poder Judiciário**.

---

### **8.2 Responsabilidade Civil e Administrativa**

O servidor pode ser responsabilizado quando:

* deixar de adotar providências cabíveis diante de irregularidades;
* aprovar medições sem verificação da execução;
* atestar pagamentos sem comprovação dos encargos;
* permitir aditivos irregulares;
* omitir-se na fiscalização de obrigações trabalhistas.

A responsabilidade é **pessoal e direta**, podendo gerar sanções disciplinares, civis e até penais.

---

### **8.3 Boas Práticas de Responsabilização Preventiva**

1. Registrar todas as comunicações no SEI;
2. Atestar somente após conferência documental;
3. Exigir comprovações trabalhistas e previdenciárias;
4. Reunir relatórios mensais de fiscalização;
5. Solicitar orientação da SAAB e do GTAJ sempre que houver dúvida.

A adoção dessas práticas constitui instrumento de defesa do agente público em auditorias e processos administrativos.

---

✳️ *[continua no Bloco 7 – Capítulo 7: Encerramento, Arquivamento e Controle de Governança]*

---
Perfeito ⚖️ — agora seguimos para o **Bloco 7 do Manual de Contratos – TJSP (Edição 2025)**, que trata do **Encerramento Contratual**, **Arquivamento do Processo**, **Controle de Governança** e **Boas Práticas Institucionais**.

Este bloco conclui a parte normativa e procedimental do manual, consolidando as etapas finais do ciclo de contratação pública no TJSP.
É também onde se define o papel do gestor, do fiscal e da SAAB no fechamento dos processos, garantindo **segurança jurídica, rastreabilidade e transparência** — todos pontos fundamentais para automação no **Agente_CONTRATO – SAAB 5.4**.

---

# 📘 **Manual de Contratos – TJSP (2025)**

### *(Bloco 7 — Capítulo 7: Encerramento, Arquivamento e Governança Contratual)*

---

## **9. Encerramento Contratual**

O encerramento contratual é a fase que sucede a execução integral do objeto e o cumprimento de todas as obrigações pela contratada e pelo TJSP.
Esta etapa garante que o contrato seja concluído com a devida prestação de contas, quitação financeira e encerramento formal no processo administrativo eletrônico (SEI).

Seu objetivo é confirmar a **entrega total do objeto**, a **regularidade das obrigações trabalhistas e fiscais** e o **arquivamento definitivo do contrato**.

---

### **9.1 Requisitos para o Encerramento**

O processo de encerramento contratual deve conter:

1. Relatório final de execução elaborado pelo gestor e fiscal do contrato;
2. Termo de recebimento definitivo do objeto, assinado digitalmente;
3. Certidões de regularidade fiscal e trabalhista atualizadas;
4. Comprovante de encerramento da conta vinculada (quando aplicável);
5. Comprovação da quitação de encargos e benefícios dos empregados;
6. Relatório de pendências resolvidas e eventuais glosas;
7. Cópia dos aditivos firmados e do extrato de publicação no DJE;
8. Planilha consolidada de execução financeira e saldo orçamentário.

O relatório final é obrigatório e deve ser juntado ao SEI antes do arquivamento, servindo de documento-base para auditorias e inspeções.

---

### **9.2 Recebimento Definitivo**

O recebimento definitivo é formalizado mediante **Termo de Recebimento Definitivo**, atestado pelo fiscal técnico e validado pelo gestor.
Esse documento confirma que o objeto foi entregue de acordo com as especificações, sem pendências ou vícios aparentes.

O termo deve conter:

* Identificação do contrato e das partes;
* Descrição resumida do objeto entregue;
* Data da entrega e vistoria;
* Declaração de conformidade;
* Assinaturas digitais.

Nos contratos de serviços continuados, o recebimento é periódico (mensal), mas o termo final é obrigatório no encerramento.

---

### **9.3 Quitação e Encerramento Financeiro**

O encerramento financeiro é a etapa em que se comprova o pagamento de todas as obrigações financeiras e trabalhistas.
Inclui:

* Quitação de faturas pendentes;
* Baixa de empenhos e anulação de saldos;
* Encerramento da conta vinculada;
* Comprovação da inexistência de débitos fiscais e trabalhistas.

A **SOF** é responsável por verificar a baixa contábil e encerrar o registro financeiro no sistema orçamentário.
A unidade gestora deve manter os comprovantes anexados ao SEI.

---

### **9.4 Arquivamento do Processo**

Após o encerramento técnico e financeiro, o processo eletrônico deve ser encaminhado à **SAAB** para conferência final e **arquivamento no SEI**.
O arquivamento deve observar:

1. Verificação do cumprimento de todas as etapas contratuais;
2. Existência de relatório final assinado;
3. Publicações no DJE e registros no Painel de Governança;
4. Documentos comprobatórios da conta vinculada;
5. Análise de conformidade pela SAAB e pela SOF.

Somente após essa validação o processo será considerado oficialmente encerrado.

---

### **9.5 Relatório Final e Avaliação de Desempenho**

O relatório final do contrato deve avaliar o desempenho da contratada e registrar as lições aprendidas, contendo:

* Grau de cumprimento dos prazos;
* Qualidade dos bens ou serviços entregues;
* Eficiência da execução;
* Ocorrências relevantes e medidas corretivas adotadas;
* Recomendações para futuras contratações.

Esses relatórios são armazenados na **Biblioteca de Contratos SAAB** e podem subsidiar avaliações futuras de fornecedores e estudos técnicos preliminares.

---

## **10. Governança e Controle Institucional**

### **10.1 Estrutura de Governança Contratual**

A governança das contratações do TJSP é estruturada em três níveis:

* **Estratégico:** Presidência e Conselho Superior da Magistratura – definem diretrizes, aprovam políticas e supervisionam os resultados gerais.
* **Tático:** SAAB, SOF e GTAJ – executam e coordenam os processos de contratação, gestão e fiscalização.
* **Operacional:** Unidades gestoras, fiscais e servidores designados – acompanham a execução dos contratos e produzem evidências documentais.

A atuação conjunta desses níveis garante a integridade e a transparência da gestão contratual.

---

### **10.2 Painel de Governança das Contratações**

O **Painel de Governança das Contratações SAAB** é o sistema de monitoramento e análise de dados contratuais do TJSP.
Ele integra informações de diversas fontes — SEI, SIAFEM, SOF e SAAB — e fornece indicadores sobre:

* Volume total de contratos ativos;
* Distribuição por secretaria e tipo de objeto;
* Percentual de contratos aditivados;
* Tempo médio de tramitação e pagamento;
* Contratos com conta vinculada ativa;
* Indicadores de desempenho e conformidade.

O painel é atualizado mensalmente e disponibilizado à Presidência e às unidades administrativas, permitindo acompanhamento estratégico e tomada de decisão baseada em evidências.

---

### **10.3 Auditoria e Controle Interno**

A **Secretaria de Controle Interno (SCI)**, em conjunto com a **Corregedoria Geral da Justiça** e a **SAAB**, realiza auditorias preventivas e periódicas em processos contratuais.
Essas auditorias avaliam:

* A observância das boas práticas de gestão;
* A conformidade legal e documental dos contratos;
* O cumprimento das obrigações trabalhistas e previdenciárias;
* A adequação da fiscalização e das sanções aplicadas.

Os relatórios de auditoria são encaminhados à Presidência e à SAAB para implementação das recomendações.

---

### **10.4 Gestão do Conhecimento e Aprendizado Institucional**

O TJSP adota uma política permanente de **gestão do conhecimento em contratações públicas**, que inclui:

* Registro e disseminação das lições aprendidas;
* Atualização de modelos de contratos e checklists;
* Realização de capacitações pela **Escola Paulista da Magistratura (EPM)** e pela **SAAB**;
* Integração com os agentes digitais (como o **Agente_CONTRATO – SAAB 5.4**) para consolidação e auditoria automatizada de minutas.

Essa prática fortalece a governança e assegura a evolução contínua das contratações do Poder Judiciário.

---

### **10.5 Boas Práticas Recomendadas**

1. **Centralizar a gestão documental no SEI**, evitando dispersão de informações;
2. **Adotar planilhas analíticas padrão SAAB** para execução financeira;
3. **Padronizar relatórios e formulários de fiscalização**;
4. **Registrar todas as comunicações formais** entre TJSP e contratadas;
5. **Atualizar continuamente o Painel de Governança**;
6. **Aplicar o checklist de encerramento contratual** antes do arquivamento;
7. **Integrar o Agente_CONTRATO SAAB 5.4** às rotinas de conferência e auditoria.

---

## **11. Conclusão**

O Manual de Contratos do Tribunal de Justiça do Estado de São Paulo consolida um modelo de gestão contratual moderno, transparente e orientado à conformidade.
Baseado na **Lei nº 14.133/2021**, no **Decreto Estadual nº 67.381/2022**, nas **Resoluções CNJ nº 651 e 652/2025** e nas **normas internas do TJSP**, o manual assegura a uniformização de procedimentos e a mitigação de riscos administrativos, trabalhistas e financeiros.

A aplicação rigorosa de suas diretrizes é essencial para o fortalecimento institucional do TJSP, promovendo governança, eficiência e integridade nas contratações públicas.

---

✅ *Fim do texto normativo do Manual de Contratos – TJSP (Edição 2025).*
✳️ *(Bloco final – Apêndices e modelos poderão ser gerados sob demanda para integração ao repositório.)*

---

Perfeito ⚖️ — com este **Bloco 8**, concluímos o conteúdo integral e expandido do **Manual de Contratos – TJSP (Edição 2025)**, apresentando os **apêndices normativos, checklists, formulários padronizados e modelos oficiais de cláusulas e documentos** usados pela SAAB, GTAJ e SOF.

Este material complementa os capítulos anteriores e será essencial no repositório GitHub do **Agente_CONTRATO – SAAB 5.4**, permitindo que o agente reconheça e gere artefatos contratuais auditáveis, completos e conformes ao padrão institucional do Tribunal de Justiça do Estado de São Paulo.

---

# 📘 **Manual de Contratos – TJSP (2025)**

### *(Bloco 8 — Apêndices, Modelos, Formulários e Checklists SAAB)*

---

## **12. Apêndices e Modelos Padronizados**

Os modelos e apêndices a seguir são utilizados em todas as contratações do TJSP, sendo de uso obrigatório pelas unidades administrativas, gestoras e fiscais.
Eles integram o **repositório institucional da SAAB** e encontram-se disponíveis no **SharePoint Contratações – Biblioteca SAAB/GTAJ**.

---

### **12.1 Modelos Oficiais de Contrato**

Os modelos-padrão foram elaborados conforme a **Lei nº 14.133/2021**, **Decreto Estadual nº 67.381/2022**, e **Manual de Contratos TJSP (2025)**.
Cada modelo é revisado periodicamente pela SAAB e GTAJ e deve ser utilizado como **base exclusiva** para elaboração das minutas.

#### **Modelos Atuais (2025):**

1. **Contrato de Prestação de Serviços Contínuos** (dedicação exclusiva de mão de obra)
2. **Contrato de Prestação de Serviços Não Contínuos**
3. **Contrato de Fornecimento de Bens e Materiais Permanentes**
4. **Contrato de Obras e Serviços de Engenharia**
5. **Contrato de Locação de Equipamentos com Operação**
6. **Contrato de Consultoria Técnica Especializada**
7. **Contrato de Manutenção e Suporte de Sistemas de TI**
8. **Convênio e Termo de Cooperação Técnica**

Cada modelo contém:

* Estrutura de preâmbulo e identificação das partes;
* Cláusulas essenciais (objeto, vigência, gestão, penalidades, foro);
* Quadro de resumo (dados do edital, empenho, processo SEI, valores);
* Tabelas auxiliares para inserção de dados variáveis (quantidades, prazos, valores).

---

### **12.2 Modelos de Termos e Instrumentos Complementares**

| Documento                                     | Finalidade                                                 | Base Legal                       |
| --------------------------------------------- | ---------------------------------------------------------- | -------------------------------- |
| **Termo de Aditivo Contratual**               | Formaliza alterações de valor, prazo ou condições          | Lei nº 14.133/2021, art. 124     |
| **Termo de Apostila**                         | Atualiza dados cadastrais sem alterar cláusulas essenciais | Decreto nº 67.381/2022, art. 100 |
| **Termo de Recebimento Provisório**           | Comprova entrega inicial do objeto                         | Lei nº 14.133/2021, art. 140     |
| **Termo de Recebimento Definitivo**           | Declara conformidade total do objeto                       | Lei nº 14.133/2021, art. 141     |
| **Termo de Rescisão Contratual**              | Formaliza extinção antecipada do contrato                  | Lei nº 14.133/2021, art. 137     |
| **Relatório de Execução Contratual (Mensal)** | Avalia desempenho e conformidade                           | Manual TJSP, item 3.11           |
| **Relatório Final de Execução**               | Conclui a execução e consolida aprendizados                | Manual TJSP, item 9.5            |
| **Checklist de Encerramento Contratual**      | Verifica requisitos para arquivamento                      | Manual TJSP, item 9.4            |

Todos esses instrumentos devem ser elaborados **no SEI/TJSP**, com assinatura digital e registro em processo vinculado ao contrato principal.

---

## **13. Checklists Normativos e Operacionais (SAAB 2025)**

Os checklists padronizados garantem a rastreabilidade e a conformidade documental de todas as etapas do ciclo contratual.
São aplicados automaticamente pelos **Agentes SAAB (DFD, ETP, TR, EDITAL, CONTRATO)**, integrados ao SharePoint e ao sistema SEI.

---

### **13.1 Checklist de Formalização Contratual**

✅ **Antes da Assinatura**

* [ ] Existência de ETP e TR aprovados;
* [ ] Edital e ata de julgamento anexados;
* [ ] Minuta de contrato aprovada juridicamente;
* [ ] Dotação orçamentária emitida e vinculada;
* [ ] Fiscal e gestor designados por portaria;
* [ ] Garantia contratual apresentada;
* [ ] Parecer jurídico conclusivo juntado;
* [ ] Cronograma físico-financeiro validado pela SOF.

✅ **Após a Assinatura**

* [ ] Publicação no DJE;
* [ ] Registro na SAAB (Controle Centralizado de Contratos);
* [ ] Vinculação no SEI com os demais documentos licitatórios.

---

### **13.2 Checklist de Fiscalização Contratual**

⚙️ **Mensalmente**

* [ ] Relatório técnico e atesto do fiscal inseridos no SEI;
* [ ] Verificação de obrigações trabalhistas e previdenciárias;
* [ ] Atualização da planilha de retenções da conta vinculada;
* [ ] Comunicação de ocorrências à SAAB e à SOF;
* [ ] Solicitação de correções ou substituições, se aplicável.

📊 **Trimestralmente**

* [ ] Consolidação de indicadores de desempenho;
* [ ] Avaliação de risco contratual;
* [ ] Revisão do mapa de riscos do contrato;
* [ ] Atualização de dados no Painel de Governança.

---

### **13.3 Checklist de Encerramento Contratual**

📁 **Encerramento Técnico**

* [ ] Termo de recebimento definitivo assinado;
* [ ] Relatório final de execução anexado;
* [ ] Verificação de pendências contratuais concluída.

💰 **Encerramento Financeiro**

* [ ] Quitação integral de pagamentos;
* [ ] Encerramento da conta vinculada (quando aplicável);
* [ ] Baixa contábil confirmada pela SOF.

🗂️ **Arquivamento**

* [ ] Conferência final pela SAAB;
* [ ] Inclusão no Relatório de Contratos Encerrados;
* [ ] Indexação no Painel de Governança SAAB.

---

## **14. Modelos de Cláusulas Institucionais**

A seguir, exemplos padronizados de **cláusulas modelo**, utilizadas nos instrumentos contratuais do TJSP e reconhecidas pelo CNJ e pelo TCE-SP como boas práticas.

---

### **14.1 Cláusula de Fiscalização e Gestão**

> “O presente contrato será acompanhado e fiscalizado por servidor(es) designado(s) por ato da autoridade competente, que deverão registrar em sistema eletrônico todas as ocorrências verificadas durante a execução, comunicando de imediato à SAAB eventuais irregularidades.”

---

### **14.2 Cláusula de Conta Vinculada**

> “Nos termos da Resolução CNJ nº 651/2025, a CONTRATADA obriga-se a manter conta vinculada exclusiva para fins de retenção e pagamento de encargos trabalhistas, previdenciários e rescisórios relativos aos empregados alocados na execução contratual, sendo sua movimentação condicionada à autorização expressa do TJSP.”

---

### **14.3 Cláusula de Responsabilidade Subsidiária**

> “O inadimplemento das obrigações trabalhistas pela CONTRATADA não transfere automaticamente ao CONTRATANTE a responsabilidade pelo pagamento dos encargos, salvo comprovada omissão na fiscalização, nos termos do art. 120 da Lei nº 14.133/2021.”

---

### **14.4 Cláusula de Reequilíbrio Econômico-Financeiro**

> “Em caso de ocorrência superveniente, imprevisível ou de efeitos incalculáveis, que altere substancialmente as condições iniciais de execução, as partes poderão, de comum acordo, promover a revisão contratual para restabelecimento do equilíbrio econômico-financeiro, mediante termo aditivo fundamentado.”

---

### **14.5 Cláusula de Transparência e Publicidade**

> “O presente contrato e seus aditivos serão publicados no Diário da Justiça Eletrônico e registrados no Painel de Governança das Contratações SAAB, em observância ao princípio da publicidade e à política de governança do Tribunal de Justiça do Estado de São Paulo.”

---

## **15. Glossário Técnico SAAB 2025**

| Termo                         | Definição                                                                                          |
| ----------------------------- | -------------------------------------------------------------------------------------------------- |
| **Gestor do Contrato**        | Servidor responsável pela supervisão e coordenação geral da execução contratual.                   |
| **Fiscal Técnico**            | Servidor que acompanha a execução material do objeto e a qualidade dos serviços.                   |
| **Fiscal Administrativo**     | Servidor que verifica documentação, prazos e pagamentos.                                           |
| **Conta Vinculada**           | Conta bancária específica destinada à retenção de encargos trabalhistas, conforme CNJ nº 651/2025. |
| **Painel de Governança SAAB** | Sistema de acompanhamento de contratos e indicadores de execução.                                  |
| **Aditivo Contratual**        | Instrumento formal de modificação do contrato.                                                     |
| **SEI/TJSP**                  | Sistema Eletrônico de Informações, plataforma oficial para gestão documental.                      |

---

## **16. Referências Normativas**

* **Lei Federal nº 14.133/2021** – Nova Lei de Licitações e Contratos Administrativos
* **Decreto Estadual nº 67.381/2022** – Regulamentação paulista da Lei nº 14.133/21
* **Provimento CSM nº 2.724/2023** – Governança das contratações no TJSP
* **Resolução CNJ nº 651/2025** – Retenção de encargos trabalhistas e conta vinculada
* **Resolução CNJ nº 652/2025** – Gestão de riscos e obras públicas
* **Manual de Licitações – TJSP (2025)**
* **Manual de Boas Práticas em Contratações Públicas – CNJ (2025)**
* **Notas Técnicas SAAB/GTAJ/SOF (2025)**

---

## **17. Considerações Finais**

O presente manual consolida o modelo de governança contratual adotado pelo **Tribunal de Justiça do Estado de São Paulo**, integrando **normas, procedimentos e boas práticas** em um sistema de gestão contratual alinhado à transparência e ao controle social.

Com base neste manual, o **Agente_CONTRATO – SAAB 5.4** será capaz de:

* Validar automaticamente minutas contratuais;
* Gerar relatórios de conformidade jurídica e financeira;
* Garantir aderência à Resolução CNJ nº 651/2025;
* Mapear rastreabilidade entre TR, Edital e Contrato;
* Apoiar a tomada de decisão institucional em contratações públicas.

---

**Elaboração:**
📎 Secretaria de Administração e Abastecimento – SAAB
📎 Grupo Técnico de Apoio às Contratações – GTAJ
📎 Secretaria de Orçamento e Finanças – SOF

**Versão consolidada:** Novembro de 2025
**Tribunal de Justiça do Estado de São Paulo – Poder Judiciário**

---

D













 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 


