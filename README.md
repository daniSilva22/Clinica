# Documento do Projeto – HospCenter

## 1. Nome do Sistema

**HospCenter**

## 2. Integrantes

* Danilo e Julia R 2DS

## 3. Área de Atuação

Clínica Médica.

## 4. Objetivo do Sistema

Desenvolver um sistema para gerenciamento de consultas e informações hospitalares, permitindo que pacientes tenham acesso rápido e organizado aos seus dados de saúde.

## 5. Tecnologias Utilizadas

* C#
* SQL

## 6. Descrição do Projeto

O HospCenter tem como objetivo facilitar o acesso dos usuários às suas informações médicas, oferecendo recursos para agendamento de consultas, visualização de receitas, medicamentos, exames e demais documentos médicos. Buscando proporcionar praticidade, organização e segurança no gerenciamento das informações de saúde.


## 7. Requisitos Funcionais

1. Permitir o cadastro de pacientes.
2. Permitir que o paciente faça login no sistema.
3. Permitir agendar consultas.
4. Permitir consultar os horários disponíveis para atendimento.
5. Permitir visualizar as consultas agendadas.
6. Permitir remarcar consultas.
7. Permitir cancelar consultas.
8. Permitir consultar medicamentos prescritos.
9. Permitir visualizar receitas médicas.
10. Permitir consultar exames e atestados médicos.

## 8. Requisitos Não Funcionais

1. Os dados devem ser armazenados no banco de dados.
2. Sistema com login de usuário.
3. Sistema desenvolvido em C#.
4. Interface simples, intuitiva e de fácil utilização.
5. Responsividade para diferentes tamanhos de tela.


## 9. Público-Alvo

* Pacientes maiores de 18 anos.

## Fluxo
Ao iniciar o sistema, o usuário deverá realizar o login. Caso ainda não possua cadastro, deverá realizar seu cadastro antes de acessar o sistema. Após o login, o usuário será direcionado para a tela inicial do HospCenter.

Na tela inicial, o usuário poderá acessar as principais funções do sistema, como agendamento de consultas, visualização de consultas, medicamentos, receitas, exames, atestados e informações do perfil.

Para agendar uma consulta, o usuário deverá escolher a especialidade, o médico, a data e um horário disponível. Após a confirmação, o agendamento será armazenado no banco de dados SQL.

O usuário também poderá consultar suas consultas agendadas, podendo remarcar ou cancelar uma consulta quando necessário. Além disso, poderá acessar seus medicamentos, receitas, exames e atestados cadastrados no sistema.

Ao finalizar o uso, o usuário poderá sair do sistema, retornando à tela de login.
