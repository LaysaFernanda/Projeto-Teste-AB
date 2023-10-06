# Projeto-Teste-AB
Projeto de teste AB realizado 

Nesse projeto, uma loja online internacional iniciou uma tarefa analítica mas não completou: lançaram um teste A/B e desistiram (para começar uma fazenda de melancias no Brasil). Minha tarefa é completá-la.

### Descrição dos dados

**Tabela Eventos:**
- `name` — do nome dos eventos de marketing
- `regions` — das regiões onde a campanha será realizada
- `start_dt` — de data de início da campanha
- `finish_dt` — da data de término da campanha

**Tabela Cadastros**
- `user_id` - id do usuário
- `first_date` — da data de cadastro
- `region` - região
- `device` — do dispositivo usado para o cadastro

**Tabela  Eventos_usuários**
- `user_id` - id do usuário
- `event_dt` — da data e hora do evento
- `event_name` — do nome da fonte do evento
- `details` — dos dados adicionais sobre o evento (por exemplo, o total do pedido em USD para eventos `purchase`)

**Tabela Participantes**
- `user_id` - id do usuário
- `ab_test` — nome do teste
- `group` — o grupo de teste ao qual o usuário pertencia

### Bibliotecas usadas
- pandas
- matplotlib
- scipy
- math
- numpy
