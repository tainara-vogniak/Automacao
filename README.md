# 📌 Projeto: Automação de Contratos – Reiters Productions (fictício)

Este projeto foi desenvolvido como uma solução automatizada para preenchimento, geração e organização de contratos de trabalho com base em dados fornecidos por um arquivo `.csv`.  
A interface gráfica foi construída com **Streamlit**, permitindo ao usuário executar todas as etapas de forma simples e intuitiva.

---

## 🚀 Funcionalidades

- 📝 Preenche contratos em formato Word com os dados do `.csv`
- 📄 Gera um PDF separado para cada contrato com o nome: `Contrato – Nome.pdf`
- 📦 Compacta automaticamente todos os contratos gerados em um único arquivo `.rar`
- 🖥️ Interface gráfica com Streamlit para selecionar os arquivos de entrada e saída

---

## 🛠 Tecnologias Utilizadas

- **Python** – Linguagem principal
- **Streamlit** – Interface gráfica
- **pandas** – Leitura e manipulação de dados `.csv`
- **python-docx** – Manipulação de documentos Word (.docx)
- **fpdf**, **reportlab** ou **docx2pdf** – Geração e conversão de PDFs
- **pyminizip** ou **patool** – Compressão de arquivos `.rar`
- **os**, **shutil** – Manipulação de arquivos e diretórios

---

## ▶️ Como Usar

1. Selecione o **modelo de contrato** (.docx)
2. Selecione o **arquivo de dados** (.csv)
3. Escolha onde salvar o **arquivo .rar** final
4. A automação fará o resto: gerar os PDFs personalizados e compactar tudo

-----------

