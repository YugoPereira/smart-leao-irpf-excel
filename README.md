<div align="center">
  <img src="images/banner.png" alt="Banner SmartLeão" width="100%">
</div>

<div align="center">

<a href="https://dio.me/">
    <img src="https://img.shields.io/badge/DIO-Bootcamp_Excel_IA-E60000?style=for-the-badge&logo=google-gemini&logoColor=white" alt="DIO - Bootcamp">
</a>
<a href="https://www.microsoft.com/pt-br/microsoft-365/excel">
    <img src="https://img.shields.io/badge/EXCEL-DATA_MANAGEMENT-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white" alt="Excel Skills">
</a>
<a href="#">
    <img src="https://img.shields.io/badge/STATUS-CONCLUÍDO-brightgreen?style=for-the-badge" alt="Status Concluído">
</a>

</div>

# SmartLeão: Gestão Inteligente de IRPF

> ℹ️ **NOTE:** Este projeto aplica conceitos de **Modelagem de Dados** e **UX Design** para transformar a caótica organização de documentos fiscais em um sistema estruturado e validado.

## 📥 Acesso ao Projeto

Você pode baixar a versão mais recente da ferramenta clicando no botão abaixo:

<div align="center">
  <a href="./SmartLeao.xlsx" target="_blank">
    <img src="https://img.shields.io/badge/⬇️_BAIXAR_PLANILHA_(.XLSX)-005A9C?style=for-the-badge&logo=microsoft-excel&logoColor=white" alt="Baixar SmartLeão">
  </a>
</div>

---

## 📱 A Solução (Preview)

*Interface sóbria ("Dark Blue"), focada na integridade dos dados e livre de poluição visual.*

<div align="center">
  <img src="images/preview.png" alt="Screenshot do SmartLeão" width="100%">
</div>

---

## 🕵️ O Desafio Técnico

*Como garantir que dados sensíveis de contabilidade sejam inseridos sem erros em uma planilha?*

### 🛠️ Hard Skills Aplicadas (Técnicas)

**💡 O QUE A FERRAMENTA FAZ:**
* **Modelagem de Dados (ETL):** Estruturação de Tabelas Fato (`NOTAS`) e Dimensão (`TABELAS`) para criar um banco de dados relacional dentro do Excel.
* **Validação Cruzada:** Uso de listas suspensas (Data Validation) que impedem o usuário de digitar categorias fora do padrão da Receita Federal.
* **Algoritmos de Agregação:** Substituição de filtros manuais pela função `=SOMASE()`, criando um resumo lateral que se atualiza em tempo real.
* **Design System:** Aplicação de uma paleta de cores personalizada (`#05377f`) para consistência visual.

### 🧠 Soft Skills (Negócio)

**⚖️ VISÃO DE ANALISTA:**
* **Compliance:** A estrutura foi pensada para espelhar a lógica do programa oficial da Receita Federal, facilitando a transcrição.
* **Prevenção de Erros:** O sistema guia o usuário (Poka-Yoke), evitando falhas comuns como datas inválidas ou valores em texto.

---

## ⚙️ Estrutura da Solução

*A lógica por trás das células.*

### 🧠 Matriz de Funcionalidades

| Funcionalidade 🔧 | Problema que Resolve 💡 | Técnica Principal Utilizada |
| :--- | :--- | :--- |
| **Input Controlado** | "Escrevi 'Médico' e depois 'Saúde', o Excel não soma junto." | **Validação de Dados (Listas)** |
| **Resumo Automático** | "Tenho que usar a calculadora para somar os recibos." | **Função `=SOMASE(intervalo;critério;soma)`** |
| **Navegação Rápida** | "Me perco no meio de tantas abas." | **Hiperlinks Internos (Menu)** |
| **Base Cadastral** | "Nunca acho o CNPJ do banco na hora de declarar." | **Tabela Dimensão (Aba TABELAS)** |

---

## 💻 Ferramentas & IA

Para potencializar o desenvolvimento, utilizei IA como copiloto de análise:

- **Microsoft Excel 365:** Motor de banco de dados e interface.
- **ChatGPT / Gemini:** Utilizados para refinar a lógica das categorias dedutíveis e gerar a paleta de cores "Dark Blue".
- **Image Generation:** Criação da logo (Leão Geométrico) e identidade visual.

---

## 👨‍💻 Autor

<table border="0">
  <tr>
    <td align="center">
      <img width="80px" style="border-radius: 50%" src="https://github.com/yugopereira.png?size=80"><br>
      <a href="https://github.com/yugopereira"><strong>Yugo Pereira</strong></a><br>
      <br>
      <a href="https://www.linkedin.com/in/yugopereira">
        <img src="https://img.shields.io/badge/-LinkedIn-blue?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn">
      </a>
      <a href="https://www.instagram.com/yugopereira/">
        <img src="https://img.shields.io/badge/-Instagram-E4405F?style=flat-square&logo=instagram&logoColor=white" alt="Instagram">
      </a>
    </td>
    <td>
      <strong>Sobre mim:</strong><br>
      Analista de Contabilidade migrando para a área de Dados. Focado em criar soluções que unem a conformidade contábil com a inteligência analítica. No projeto <strong>SmartLeão</strong>, busquei aplicar minha visão de negócio para transformar uma tarefa burocrática em um processo de dados eficiente.
    </td>
  </tr>
</table>

<br/>

<div align="center">
<sub>💙 Feito com foco em dados por <a href="https://github.com/YugoPereira">Yugo Pereira</a></sub>
</div>
