# Critérios de Aceitação

Os critérios de aceitação complementam a especificação dos requisitos ao definir condições que devem ser atendidas para que uma funcionalidade seja considerada corretamente implementada.

Conforme apresentado na apostila, os critérios são estruturados utilizando a abordagem **Dado – Quando – Então**:

* **Dado:** descreve o contexto ou estado inicial do sistema.
* **Quando:** representa a ação executada pelo ator.
* **Então:** descreve o comportamento esperado do sistema.

## CA-01 — Visualizar eventos disponíveis

| Dado                                        | Quando                                   | Então                                                         |
| ------------------------------------------- | ---------------------------------------- | ------------------------------------------------------------- |
| Existem eventos disponíveis para inscrição. | O participante acessa a área de eventos. | O sistema apresenta os eventos disponíveis em um único local. |

---

## CA-02 — Realizar inscrição em evento

| Dado                                     | Quando                                 | Então                           |
| ---------------------------------------- | -------------------------------------- | ------------------------------- |
| O evento está disponível para inscrição. | O participante solicita sua inscrição. | O sistema registra a inscrição. |

---

## CA-03 — Emitir comprovante de inscrição

| Dado                                   | Quando                   | Então                                          |
| -------------------------------------- | ------------------------ | ---------------------------------------------- |
| O participante realizou uma inscrição. | A inscrição é concluída. | O sistema fornece um comprovante de inscrição. |

---

## CA-04 — Cancelar inscrição

| Dado                                                                 | Quando                                     | Então                                 |
| -------------------------------------------------------------------- | ------------------------------------------ | ------------------------------------- |
| O participante possui uma inscrição e o evento permite cancelamento. | O participante solicita o cancelamento.    | O sistema cancela a inscrição.        |
| O evento não permite cancelamento.                                   | O participante tenta cancelar a inscrição. | O sistema não permite o cancelamento. |

---

## CA-05 — Emitir certificado

| Dado                                                                          | Quando                                 | Então                                  |
| ----------------------------------------------------------------------------- | -------------------------------------- | -------------------------------------- |
| O participante atende às condições estabelecidas para emissão do certificado. | O participante solicita o certificado. | O sistema disponibiliza o certificado. |

**Observação:** As condições para emissão do certificado ainda não estão completamente definidas na elicitação.

---

## CA-06 — Inscrever-se em workshops

| Dado                                          | Quando                                                     | Então                                                           |
| --------------------------------------------- | ---------------------------------------------------------- | --------------------------------------------------------------- |
| Existem workshops disponíveis para inscrição. | O participante solicita inscrição em um ou mais workshops. | O sistema registra as inscrições conforme as regras aplicáveis. |

**Observação:** O tratamento de atividades com horários conflitantes ainda não foi definido.

---

## CA-07 — Controlar vagas

| Dado                               | Quando                                        | Então                                                   |
| ---------------------------------- | --------------------------------------------- | ------------------------------------------------------- |
| O evento possui vagas disponíveis. | Um participante realiza uma inscrição.        | O sistema atualiza a quantidade de vagas disponíveis.   |
| O evento está lotado.              | Um participante tenta realizar uma inscrição. | O sistema aplica a regra definida para eventos lotados. |

**Observação:** As regras da lista de espera ainda não foram definidas.

---

## CA-08 — Gerenciar lista de espera

| Dado                                           | Quando                                           | Então                                                                    |
| ---------------------------------------------- | ------------------------------------------------ | ------------------------------------------------------------------------ |
| O evento está lotado e possui lista de espera. | Um participante solicita participação no evento. | O sistema registra o participante conforme as regras da lista de espera. |

**Observação:** As regras de funcionamento da lista de espera ainda não foram definidas.

---

## CA-09 — Acompanhar inscrições

| Dado                                          | Quando                                | Então                                                        |
| --------------------------------------------- | ------------------------------------- | ------------------------------------------------------------ |
| Existem participantes inscritos em um evento. | O organizador consulta as inscrições. | O sistema apresenta a quantidade de participantes inscritos. |

**Observação:** O conceito de "tempo real" ainda precisa ser refinado.

---

## CA-10 — Gerenciar eventos

| Dado                                                     | Quando                                    | Então                                         |
| -------------------------------------------------------- | ----------------------------------------- | --------------------------------------------- |
| O organizador possui acesso ao gerenciamento de eventos. | O organizador cria ou gerencia um evento. | O sistema registra as informações fornecidas. |

**Observação:** As informações que poderão ser cadastradas ou alteradas não foram definidas na elicitação.

---

## CA-11 — Gerenciar pagamentos

| Dado                                             | Quando                                    | Então                                        |
| ------------------------------------------------ | ----------------------------------------- | -------------------------------------------- |
| Existe uma inscrição associada a um evento pago. | A equipe financeira consulta o pagamento. | O sistema apresenta a situação do pagamento. |

---

## CA-12 — Confirmar pagamento

| Dado                                                                        | Quando                                    | Então                                          |
| --------------------------------------------------------------------------- | ----------------------------------------- | ---------------------------------------------- |
| Existe um pagamento relacionado a uma inscrição que depende de confirmação. | A equipe financeira confirma o pagamento. | O sistema registra a confirmação do pagamento. |

**Observação:** Quais inscrições dependem da confirmação do pagamento ainda não foi definido.

---

## CA-13 — Controlar reembolso

| Dado                                                | Quando                                    | Então                                                   |
| --------------------------------------------------- | ----------------------------------------- | ------------------------------------------------------- |
| Existe uma situação que pode resultar em reembolso. | A equipe financeira registra o reembolso. | O sistema registra o reembolso relacionado à inscrição. |

**Observação:** As situações que garantem ou impedem o direito ao reembolso ainda não foram definidas.

---

## CA-14 — Consultar programação

| Dado                                                    | Quando                                | Então                                              |
| ------------------------------------------------------- | ------------------------------------- | -------------------------------------------------- |
| O palestrante possui atividades associadas a um evento. | O palestrante consulta a programação. | O sistema apresenta as atividades correspondentes. |

---

## CA-15 — Consultar participantes

| Dado                                                             | Quando                                   | Então                                           |
| ---------------------------------------------------------------- | ---------------------------------------- | ----------------------------------------------- |
| Existem participantes inscritos em uma atividade do palestrante. | O palestrante consulta os participantes. | O sistema apresenta os participantes inscritos. |

**Observação:** As informações dos participantes que poderão ser visualizadas pelo palestrante ainda não foram definidas.

---

## Observações de premissas assumidas:

Os critérios de aceitação foram elaborados a partir das informações disponíveis no documento de elicitação e dos requisitos funcionais identificados.

Quando a elicitação não fornece informações suficientes para definir objetivamente um comportamento, essa limitação foi registrada como observação, sem introduzir critérios não presentes no material fornecido.

O refinamento desses critérios depende da resolução das ambiguidades e das demais informações pendentes identificadas durante a análise.
