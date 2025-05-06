# Aps-06-05
06/05 - ANÁLISE  E PROJETO DE SISTEMAS (APS)
~> TEMA: CRIAÇÃO DE UMA ARQUITERUA BASICA PARA SISTEMAS PEQUENOS

Tipos de Arquitetura: Monolítica

[Interface  (Componentes Visuais)]<br>
                 ↧
[Lógica de Negócio (Funções/Estados)]<br>
                ↧
[Acesso a Dados (LocalStorage, ou API locais/simulados)]
---
Imterface: JSX visível ao usuário.
Lógica de Negócios; validações, manipulação de dados, regras.
Acesso aos Dados: estados (useState()) ou comunicação com serviços/API
---
Componentes:
formularioCLiente, ListaCliente, App
Lógica; evitar cadastro com campos vazio. Evitar emails duplicados 
Armazenar dados temporariamente no estado.
