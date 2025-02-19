# Gerador de PDFs

## ❓ O Que É Esta Solução?

Esta solução foi criada para **automatizar a geração de documentos personalizados** a partir de uma lista de dados. Imagine que você precisa criar vários documentos (como contratos, certificados ou relatórios) com informações diferentes para cada pessoa. Fazer isso manualmente pode ser demorado e sujeito a erros.

Com esta ferramenta, você só precisa:

1. **Uma planilha do Excel**: Onde estão armazenados os dados das pessoas (como nomes, CPFs, endereços, etc.).
2. **Um template do Word**: Um modelo de documento onde os dados serão inseridos automaticamente.

A solução faz o seguinte:
- Lê os dados da planilha.
- A partir de marcadores dentro do documento (ex: `{NOME}`, `{CPF}` que correspondem as colunas NOME e CPF na planilha) ele preenche o template do Word com as informações de cada pessoa.
- Gera um arquivo PDF para cada pessoa, pronto para ser impresso ou enviado.

---

## 🚀 Como Usar

Siga os passos abaixo para utilizar a solução:

### 1. Pré-requisitos

Antes de começar, certifique-se de que você tem os seguintes itens instalados:

- **Microsoft Word**: O script utiliza o Word para gerar os PDFs.
- **Planilha do Excel**: Uma planilha com os dados que serão usados para preencher o template. 
- **Template do Word**: Um documento do Word com marcadores para os dados.
- Os templates necessários são disponibilizados também neste documento caso você já não os tenha.

### 2. Baixar o Script 

1. Acesse a aba **"Releases"** do projeto no GitHub: (https://github.com/pjuliusl/createpdf/releases/tag/v1.0).
2. Selecione **"create_pdf.exe"**.
3. Um download será iniciado, certifique-se de manter o download caso seu navegador impeça o procedimento, para que não ocorram problemas.
4. Caso necessário, faça também o download dos templates `Planilha_Base.xlsx` e `Termo_Bolsa.docx`. 

### 3. Preparar os Arquivos

- Coloque a planilha do Excel (`Planilha_Base.xlsx`) e o template do Word (`Termo_Bolsa.docx`) na mesma pasta onde está o script.
- Certifique-se de que os nomes dos arquivos correspondem exatamente aos nomes `Planilha_Base` e `Termo_Bolsa` que são esperados pelo script .
- Caso queira, pode criar uma pasta no seu dispositivo para organizar os arquivos, é de suma importância para o funcionamento correto da solução que eles estejam na mesma pasta.

### 4. Executar o Script

## 🖥️ Versão Executável

Para facilitar o uso, disponibilizamos uma versão executável do projeto. Siga os passos abaixo:

1. Procure pela pasta que contém os arquivos `create_pdf.exe`, `Planilha_Base.xlsx`, `Termo_Bolsa.docx`.
2. Faça alterações na planilha e no template conforme sua demanda.
3. Execute o arquivo `create_pdf.exe`.
4. Os PDF's serão gerados numa pasta chamada `PASTA` no mesmo diretório onde os itens se encontram.

## 🤝 Contato

Se você tiver dúvidas ou precisar de ajuda, entre em contato:

pedro.santos@irede.org.br

Teams: Pedro Julius
