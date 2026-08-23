## Requisitos Funcionais Identificados

A partir das informações fornecidas durante a elicitação, foram identificadas as seguintes funcionalidades potenciais.

### RF-01 — Visualizar eventos disponíveis

O sistema deve mostrar para os participantes todos os eventos disponíveis em um único local.

**Origem:** Participantes.

**Observação:** A elicitação não definiu quais são as informações que devem ser apresentadas para cada evento em que o participante está inscrito.

---

### RF-02 — Realizar inscrição em eventos

O sistema deve permitir que participantes realizem inscrições nos eventos disponíveis.

**Origem:** Participantes.

**Observação:** A elicitação não detalha completamente o fluxo de inscrição, especialmente as condições relacionadas a pagamento e confirmação da vaga. Também não detalha o prazo para que o evento que seja considerado disponível. Ex: 1 dia antes do evento, 1h?!

---

### RF-03 — Emitir comprovante de inscrição

O sistema deve fornecer um comprovante **único** após a realização da inscrição.

**Origem:** Participantes.

**Ponto para verificar:** A elicitação não define o formato do comprovante, no caso de pagamento, que ele deve ser emitido após confirmação do pagamento, nem o canal utilizado para disponibilizá-lo ou enviá-lo.

---

### RF-04 — Cancelar inscrição

O sistema deve permitir que participantes cancelem suas inscrições sem necessidade de contato direto com a organização, quando o cancelamento for permitido.

**Origem:** Participantes e Organizadores.

**Ponto para verificar:** Nem todos os eventos permitem cancelamento e as condições para isso ainda não foram definidas.

---

### RF-05 — Emitir certificado

O sistema deve permitir que participantes obtenham seus certificados após a participação no evento, conforme as regras estabelecidas.

**Origem:** Participantes.

**Ponto para verificar:** Não está definido se a emissão será automática ou dependerá da confirmação de presença.

---

### RF-06 — Inscrever-se em múltiplos workshops

O sistema deve permitir que participantes se inscrevam em múltiplos workshops que ocorram no mesmo dia, observadas as regras de horário e disponibilidade.

**Origem:** Participantes.

**Ponto para verificar:** A elicitação não define como serão tratadas atividades com horários conflitantes.

---

### RF-07 — Controlar automaticamente o número de vagas

O sistema deve controlar automaticamente a quantidade de vagas disponíveis nos eventos.

**Origem:** Organizadores.

---

### RF-08 — Gerenciar lista de espera

O sistema deve oferecer uma lista de espera para eventos que estejam lotados, conforme regras a serem definidas.

**Origem:** Organizadores.

**Ponto para verificar:** A elicitação não define como a lista de espera funcionará.

---

### RF-09 — Acompanhar quantidade de inscritos

O sistema deve permitir que organizadores acompanhem a quantidade de inscritos em tempo real.

**Origem:** Organizadores.

**Ponto para verificar:** O conceito de "tempo real" precisa ser refinado para permitir uma especificação verificável.

---

### RF-10 — Criar e gerenciar eventos

O sistema deve permitir que organizadores criem eventos e gerenciem suas informações.

**Origem:** Organizadores.

**Ponto para verificar:** A elicitação não detalha quais informações poderão ser cadastradas ou alteradas.

---

### RF-11 — Gerenciar pagamentos

O sistema deve permitir o controle dos pagamentos relacionados às inscrições de eventos pagos.

**Origem:** Equipe Financeira.

**Ponto para verificar:** A elicitação não define o mecanismo de pagamento nem todos os estados possíveis de uma transação.

---

### RF-12 — Confirmar pagamentos (adendo RF-03)

O sistema deve permitir que a equipe financeira confirme os pagamentos antes da liberação de determinadas inscrições.

**Origem:** Equipe Financeira.

**Ponto para verificar:** É necessário determinar em quais situações a confirmação financeira é obrigatória.

---

### RF-13 — Controlar reembolsos

O sistema deve permitir o controle dos reembolsos relacionados às inscrições.

**Origem:** Equipe Financeira.

**Ponto para verificar:** As situações em que o participante possui direito ao reembolso ainda não foram definidas.

---

### RF-14 — Consultar programação

O sistema deve permitir que palestrantes consultem a programação de suas atividades.

**Origem:** Palestrantes.

**Ponto para verificar:** se um participante cancelar um workshop e se inscrever em outro, qual o prazo e etapas para essa atualização poder ser consultada pelo participante? Isso ainda não foi definido.

---

### RF-15 — Consultar participantes das atividades

O sistema deve permitir que palestrantes consultem informações sobre os participantes inscritos em suas atividades.

**Origem:** Palestrantes.

**Ponto para verificar:** Quais informações dos participantes poderão ser visualizadas pelos palestrantes ainda não foram definidas. Deverá estar dentro da LGPD obrigatoriamente. 
