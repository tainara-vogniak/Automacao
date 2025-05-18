📌 Projeto: Automação de Contratos – Reiters Productions (fictício)
Este projeto foi desenvolvido como uma solução automatizada para preenchimento, geração e organização de contratos de trabalho, com base em dados fornecidos por arquivo .csv. A interface gráfica foi construída com Streamlit, permitindo ao usuário executar todas as etapas de forma simples e intuitiva.

🚀 Funcionalidades:
📄 Preenche contratos em formato Word com os dados do .csv

🧾 Gera um PDF separado para cada contrato com o nome: Contrato – Nome.pdf

🗃️ Compacta automaticamente todos os contratos gerados em um único arquivo .rar

🖥️ Interface gráfica com Streamlit para selecionar os arquivos de entrada e saída

🛠 Tecnologias utilizadas:
Python – Linguagem principal

Streamlit – Para a interface gráfica

pandas – Leitura e manipulação de dados do .csv

python-docx – Manipulação de documentos Word (.docx)

fpdf / reportlab / docx2pdf – Geração e conversão de PDFs (dependendo da sua escolha)

pyminizip ou patool – Para compressão no formato .rar

os / shutil – Manipulação de arquivos e diretórios

🗂️ Como usar:
Selecione o modelo de contrato (.docx)

Selecione o arquivo de dados (.csv)

Escolha onde salvar o arquivo .rar final

A automação fará o resto: gerar os PDFs personalizados e compactar tudo
