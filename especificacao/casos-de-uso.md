# Casos de Uso

Os casos de uso descrevem como os usuários interagem com o sistema para atingir um determinado objetivo. Conforme apresentado na apostila, cada caso de uso deve identificar o nome, objetivo, ator principal, pré-condições, fluxo principal, fluxos alternativos e pós-condições.

## UC-01 — Visualizar Eventos

**Objetivo:** Permitir que o participante consulte os eventos disponíveis.

**Ator principal:** Participante

**Pré-condições:** Não identificadas no material de elicitação.

**Fluxo principal:**

1. O participante acessa a área de eventos.
2. O sistema apresenta os eventos disponíveis.
3. O participante consulta os eventos apresentados.

**Fluxo alternativo:** Não identificado no material de elicitação.

**Pós-condição:** Os eventos disponíveis são apresentados ao participante.

---

## UC-02 — Realizar Inscrição

**Objetivo:** Permitir que o participante realize sua inscrição em um evento.

**Ator principal:** Participante

**Pré-condições:** O evento deve estar disponível para inscrição.

**Fluxo principal:**

1. O participante seleciona um evento.
2. O participante solicita sua inscrição.
3. O sistema registra a inscrição.

**Fluxo alternativo:** As condições relacionadas ao pagamento, confirmação da vaga e disponibilidade de vagas ainda não estão completamente definidas.

**Pós-condição:** A inscrição é registrada, conforme as regras aplicáveis ao evento.

---

## UC-03 — Cancelar Inscrição

**Objetivo:** Permitir que o participante cancele sua inscrição quando o evento permitir o cancelamento.

**Ator principal:** Participante

**Pré-condições:** O participante deve possuir uma inscrição no evento e o cancelamento deve ser permitido.

**Fluxo principal:**

1. O participante acessa sua inscrição.
2. O participante solicita o cancelamento.
3. O sistema registra o cancelamento.

**Fluxo alternativo:** Caso o evento não permita o cancelamento, o sistema não deve permitir a operação.

**Pós-condição:** A inscrição é cancelada.

**Ponto a esclarecer:** O prazo e as condições para cancelamento não foram definidos na elicitação.

---

## UC-04 — Emitir Certificado

**Objetivo:** Permitir que o participante obtenha seu certificado após o evento.

**Ator principal:** Participante

**Pré-condições:** O participante deve ter participado do evento, conforme as regras estabelecidas.

**Fluxo principal:**

1. O participante solicita seu certificado.
2. O sistema verifica as condições aplicáveis.
3. O sistema disponibiliza o certificado.

**Fluxo alternativo:** Não definido no material de elicitação.

**Pós-condição:** O certificado é disponibilizado ao participante.

**Ponto a esclarecer:** Não foi definido se a emissão dependerá da confirmação da presença.

---

## UC-05 — Gerenciar Evento

**Objetivo:** Permitir que o organizador crie e gerencie eventos.

**Ator principal:** Organizador

**Pré-condições:** O organizador deve possuir acesso à funcionalidade de gerenciamento de eventos.

**Fluxo principal:**

1. O organizador acessa a funcionalidade de gerenciamento de eventos.
2. O organizador cria ou gerencia um evento.
3. O sistema registra as informações do evento.

**Fluxo alternativo:** Não identificado no material de elicitação.

**Pós-condição:** O evento é criado ou atualizado.

**Ponto a esclarecer:** As informações que poderão ser cadastradas ou alteradas não foram definidas.

---

## UC-06 — Controlar Vagas

**Objetivo:** Permitir que o organizador controle a quantidade de vagas disponíveis em um evento.

**Ator principal:** Organizador

**Pré-condições:** O evento deve possuir uma quantidade de vagas definida.

**Fluxo principal:**

1. O participante solicita uma inscrição.
2. O sistema verifica a disponibilidade de vagas.
3. O sistema atualiza a quantidade de vagas conforme a inscrição.

**Fluxo alternativo:** Caso o evento esteja lotado, o sistema deverá considerar a regra aplicável à lista de espera.

**Pós-condição:** A quantidade de vagas disponíveis é atualizada.

**Ponto a esclarecer:** As regras detalhadas para a lista de espera não foram definidas.

---

## UC-07 — Gerenciar Pagamento

**Objetivo:** Permitir que a equipe financeira gerencie os pagamentos relacionados às inscrições.

**Ator principal:** Equipe Financeira

**Pré-condições:** Deve existir uma inscrição associada a um evento que exija pagamento.

**Fluxo principal:**

1. A equipe financeira consulta os pagamentos.
2. A equipe financeira verifica o pagamento.
3. O sistema registra a situação do pagamento.

**Fluxo alternativo:** Não definido no material de elicitação.

**Pós-condição:** A situação do pagamento é registrada no sistema.

**Ponto a esclarecer:** O mecanismo de pagamento e os estados possíveis da transação não foram definidos.

---

## UC-08 — Controlar Reembolso

**Objetivo:** Permitir que a equipe financeira controle os reembolsos relacionados às inscrições.

**Ator principal:** Equipe Financeira

**Pré-condições:** Deve existir uma situação que possa resultar em reembolso.

**Fluxo principal:**

1. A equipe financeira consulta a solicitação relacionada ao reembolso.
2. A equipe financeira verifica a situação.
3. O sistema registra o reembolso.

**Fluxo alternativo:** Não definido no material de elicitação.

**Pós-condição:** O reembolso é registrado, quando aplicável.

**Ponto a esclarecer:** As situações em que o participante possui direito a reembolso não foram definidas.

---

## UC-09 — Consultar Programação

**Objetivo:** Permitir que o palestrante consulte a programação de suas atividades.

**Ator principal:** Palestrante

**Pré-condições:** O palestrante deve possuir atividades associadas ao evento.

**Fluxo principal:**

1. O palestrante acessa a programação.
2. O sistema apresenta suas atividades.
3. O palestrante consulta as informações apresentadas.

**Fluxo alternativo:** Não identificado no material de elicitação.

**Pós-condição:** A programação das atividades do palestrante é apresentada.

---

## UC-10 — Consultar Participantes

**Objetivo:** Permitir que o palestrante consulte os participantes inscritos em suas atividades.

**Ator principal:** Palestrante

**Pré-condições:** O palestrante deve possuir atividades com participantes inscritos.

**Fluxo principal:**

1. O palestrante acessa uma de suas atividades.
2. O palestrante solicita a consulta dos participantes.
3. O sistema apresenta os participantes inscritos.

**Fluxo alternativo:** Não identificado no material de elicitação.

**Pós-condição:** A lista de participantes é apresentada ao palestrante.

**Ponto a esclarecer:** Não foi definido quais informações dos participantes poderão ser visualizadas.

---

## Observações

Os casos de uso foram elaborados exclusivamente a partir das informações fornecidas no documento de elicitação.

Tomou-se como uma premissa: Quando o material não fornece informações suficientes para definir uma pré-condição, fluxo alternativo ou pós-condição, não introduzir por conta própria regras não presentes na elicitação.

Os casos de uso deverão ser refinados posteriormente à medida que as ambiguidades e informações pendentes sejam esclarecidas.
