# APS-06-05
## 06/05 - Análise e Projeto de Sistemas (APS)
### Tema: Criação de uma Arquitetura Básica para Sistemas Pequenos

---

### Tipos de Arquitetura: Monolítica

**Fluxo de Arquitetura:**  
📌 **Interface (Componentes Visuais)**  
⬇️ **Lógica de Negócio (Funções/Estados)**  
⬇️ **Acesso a Dados (LocalStorage ou API locais/simuladas)**  

---

### Descrição das Camadas

✅ **Interface:** JSX visível ao usuário.  
✅ **Lógica de Negócio:** Validações, manipulação de dados, regras.  
✅ **Acesso aos Dados:** Estados (`useState()`) ou comunicação com serviços/API.  

---

### Componentes Principais
- `FormularioCliente`
- `ListaCliente`
- `App`

### Regras de Lógica
✔️ Evitar cadastro com campos vazios  
✔️ Prevenir emails duplicados  
✔️ Armazenar dados temporariamente no estado  

---

📌 Esse é um esqueleto básico para uma aplicação monolítica utilizando React!
