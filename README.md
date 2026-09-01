# FitManager

## Esboço do Projeto

O **FitManager** é um sistema de gestão para ginásios desenvolvido em Java.

O objetivo do sistema é facilitar a gestão dos clientes, funcionários, aulas, horários, mensalidades, pagamentos, treinos e acompanhamento da evolução dos clientes.

O sistema terá duas áreas principais:

- **Área do Cliente:** permite consultar informações pessoais, mensalidades, pagamentos, aulas, horários, treinos, alimentação e evolução.
- **Área do Funcionário:** permite gerir clientes, aulas, horários, pagamentos, treinos e acompanhar a evolução dos clientes.

## Objetivos

### Objetivo Geral

Desenvolver uma aplicação web para gerir de forma simples e organizada as principais atividades de um ginásio.

### Objetivos Específicos

- Registar e gerir clientes.
- Registar e gerir funcionários.
- Permitir o login dos utilizadores.
- Consultar aulas e horários disponíveis.
- Permitir agendar aulas.
- Permitir desagendar aulas.
- Permitir aos funcionários criar e reagendar aulas.
- Controlar a participação dos clientes nas aulas.
- Consultar o estado das mensalidades.
- Identificar mensalidades pagas, pendentes ou em atraso.
- Registar pagamentos.
- Disponibilizar informações sobre planos e mensalidades.
- Criar e consultar planos de treino.
- Registar informações relacionadas com alimentação e nutrição.
- Acompanhar a evolução física dos clientes.
- Organizar os dados numa base de dados.
- Aplicar regras de segurança e acesso conforme o tipo de utilizador.

## Principais Entidades

- Cliente
- Funcionário
- Aula
- Agendamento
- Mensalidade
- Pagamento
- Treino
- Plano de Treino
- Consulta de Nutrição
- Evolução

## Regras de Negócio Principais

1. Um cliente só pode agendar uma aula se existir vaga disponível.
2. Um cliente não pode agendar a mesma aula duas vezes.
3. Um cliente pode desagendar uma aula dentro do prazo definido pelo ginásio.
4. Os funcionários podem criar, alterar, reagendar e cancelar aulas.
5. O sistema deve controlar o estado das mensalidades.
6. O sistema deve indicar quando uma mensalidade está em atraso.
7. Apenas utilizadores autenticados podem aceder à área privada.
8. Clientes e funcionários possuem diferentes níveis de acesso.
9. O sistema deve impedir conflitos de horários nas aulas.
10. Os dados dos clientes devem ser armazenados de forma organizada na base de dados.

## Tecnologias

- Java 21
- Spring Boot
- Maven
- HTML
- CSS
- Thymeleaf
- Spring Security
- H2 Database
- Git e GitHub

## Estado do Projeto

Projeto em desenvolvimento.
