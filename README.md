# SACA: Sistema Analista de Capacidade da Academia
## 1. Introdução 
### 1.1 Propósito
Este documento tem como objetivo descrever os requisitos funcionais e não funcionais do Sistema Analista de Capacidade da Academia (SACA), que será utilizado para analisar e gerenciar o fluxo de clientes/colaboradores em uma academia.
### 1.2 Escopo do Sistema
O SACA permitirá o registro eletrônico dos usuários na entrada/saída e fornecer  a média do fluxo por horário na academia.
### 1.3 Definições e Abreviações
SACA: Sistema Analista de Capacidade da Academia
## 2. Descrição Geral
### 2.1 Perspectiva do Produto
O sistema substituirá a contagem manual do fluxo de pessoas, automatizando a contagem de clientes/colaboradores que entram e saem da academia, integrando os registros ao sistema.
### 2.2 Funções Principais
- Registro de ponto (entrada e saída)
- Geração de relatórios de fluxo
- Consulta de relatórios de frequência
- Exportar os relatórios para o Gestor.
### 2.3 Tipos de Usuários
Clientes: acessam o perfil no aplicativo e informações sobre horários
Colaborador: registra e consulta o ponto
Gestor: aprova correções e visualiza relatórios de sua equipe
Administrador: configura o sistema e gerencia as permissões
### 2.4 Restrições
O sistema deve armazenar dados por no máximo 1 ano, atualizando-os. E em caso de entrada não autorizada.
### 2.5 Suposições e Dependências
O sistema depende de conexão com a internet e de integração com o banco de dados corporativo.


## Requisitos Funcionais
| Código | Descrição | Prioridade |
| --- | --- | --- |
| RF01 | O sistema deve permitir o registro de ponto de entrada e saída dos clientes e colaboradores da academia. | Alta |
| RF02 | O sistema deve registrar data, hora e localização do ponto. | Alta |
| RF03 | O sistema deve registrar e calcular a média do fluxo de clientes por horário e enviar para o gestor. | Média |
| RF04 | O sistema deve gerar relatórios mensais de frequência. | Alta |
