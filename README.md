# Trabalho Final — Análise e Projeto de Sistemas (APS)

**Disciplina:** Análise e Projeto de Sistemas (APS)  
**Professor:** Mateus de Freitas Invernisi  
**Aluno:** [O Teu Nome Completo]  

---

## 1. Descrição e Delimitação do Escopo

### Propósito e Contexto
O **BarberSys** é um sistema web de gestão de agendamentos e atendimento para barbearias. A solução visa resolver a desorganização de horários, filas de espera no estabelecimento e a dependência de agendamentos manuais via telefone ou mensagens, automatizando todo o processo de marcação.

### Público-Alvo
- **Clientes:** Consultam horários disponíveis, realizam e gerem os seus agendamentos.
- **Barbeiros:** Visualizam a sua agenda diária e marcam serviços executados.
- **Administrador / Gerente:** Gere a equipe de barbeiros, os serviços prestados, os preços e relatórios de atendimento.

### Escopo e Funcionalidades
O sistema contempla:
- Cadastro e autenticação de utilizadores (Clientes, Barbeiros e Administrador).
- Agendamento, alteração e cancelamento de serviços de barbearia.
- Consulta de disponibilidade de horários por barbeiro e por serviço.
- Gestão do catálogo de serviços (corte, barba, pigmentação, etc.) e respetivos preços e durações.
- Histórico de agendamentos e atendimentos do cliente.

---

## 2. Diagrama de Classes 



---

## 3. Documentação Completa
# Documentação do Projeto — BarberSys

## 1. Fase de Análise

### 1.1. Requisitos Funcionais (RF)
- **RF01:** O sistema deve permitir o cadastro e login de clientes, barbeiros e administradores.
- **RF02:** O sistema deve permitir que o cliente consulte os horários disponíveis por barbeiro e por serviço.
- **RF03:** O sistema deve permitir que o cliente realize o agendamento de um ou mais serviços.
- **RF04:** O sistema deve permitir que o cliente cancele ou remarque um agendamento com antecedência.
- **RF05:** O sistema deve permitir que o administrador gerencie (cadastrar, editar, inativar) o catálogo de serviços, incluindo nome, preço e duração.
- **RF06:** O sistema deve permitir que o administrador gerencie os perfis e jornadas de trabalho dos barbeiros.
- **RF07:** O sistema deve permitir que o barbeiro visualize a sua agenda diária e semanal de atendimentos.
- **RF08:** O sistema deve permitir que o barbeiro altere o status do agendamento (ex.: "Em atendimento", "Concluído", "Falta").
- **RF09:** O sistema deve manter o histórico de atendimentos e serviços realizados por cada cliente.
- **RF10:** O sistema deve gerar relatórios operacionais de atendimentos realizados e faturamento por período.

### 1.2. Requisitos Não Funcionais (RNF)
- **RNF01 (Usabilidade):** O sistema deve possuir uma interface responsiva, adaptada para navegação em dispositivos móveis e computadores.
- **RNF02 (Desempenho):** A consulta de disponibilidade de horários deve responder em menos de 2 segundos.
- **RNF03 (Segurança):** As senhas de todos os utilizadores devem ser armazenadas de forma criptografada na base de dados.
- **RNF04 (Disponibilidade):** O sistema deve estar disponível para agendamentos online 24 horas por dia, 7 dias por semana.
- **RNF05 (Manutenibilidade):** O sistema deve ser desenvolvido com arquitetura em camadas para facilitar futuras expansões e manutenções.

### 1.3. Regras de Negócio (RN)
- **RN01 (Cancelamento):** O cancelamento de um agendamento sem taxa de penalidade só pode ser efetuado pelo cliente com no mínimo 2 horas de antecedência em relação ao horário marcado.
- **RN02 (Sobreposição de Horários):** O sistema não deve permitir dois agendamentos no mesmo horário para o mesmo barbeiro.
- **RN03 (Tolerância de Atraso):** Se o cliente não comparecer até 15 minutos após o horário agendado, o status do atendimento muda automaticamente para "Falta".


---

## 4. Conclusão / Aprendizado



---

## 5. Declaração do Uso de IA

