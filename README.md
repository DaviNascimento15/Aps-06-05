# Aps-06-05
06/05 - ANÁLISE  E PROJETO DE SISTEMAS (APS)<br>
~> TEMA: CRIAÇÃO DE UMA ARQUITERUA BASICA PARA SISTEMAS PEQUENOS<br>

Tipos de Arquitetura: Monolítica

[Interface  (Componentes Visuais)]<br>
---------------↧<br>
[Lógica de Negócio (Funções/Estados)]<br>
                ↧<br>
[Acesso a Dados (LocalStorage, ou API locais/simulados)]<br>
---
Imterface: JSX visível ao usuário.<br>
Lógica de Negócios; validações, manipulação de dados, regras.<br>
Acesso aos Dados: estados (useState()) ou comunicação com serviços/API<br>
---
Componentes:<br>
formularioCLiente, ListaCliente, App<br>
Lógica; evitar cadastro com campos vazio. Evitar emails duplicados <br>
Armazenar dados temporariamente no estado.<br>
