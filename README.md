# Flask + Jupyter Notebook: xml_to_dict_to_pandas_to_xlsx

Projeto de upload de arquivos em `.xml` para processamento de tags e conversão para um Pandas DataFframe via Jupyter Notebook e visualização em um navegador via Flask. Ao final do processo é possível realizar o download do arquivo conertido em formato `.xlsx`!

## Arquivos e Diretórios
- **Example.xml** - Arquivo de exemplo com as tags correspondentes ao código de exemplo;
- **xml_to_dicts_to_pandas.ipynb** - Arquivo em formato .ipynb com o código da aplicação;
- **templates** - Diretórico com o arquivo `index.html` com o código para a página de upload de arquivos pelo navegador. 

## Como usar
1. Abra o arquivo **Example.xml** e ajuste as tags às variáveis da função `process_xml` no arquivo `xml_to_dicts_to_pandas.ipynb` com os campos desejados;
2. Execute o código no Jupyter Notebook;
3. Acesse o URL [http://localhost:5000](http://localhost:5000) no seu navegador para realizar o o upload do arquivo em `.xml`.
4. Clique no botão `Enviar` e localize o documento em formato `.xlsx` exportado no diretório raiz do projeto.

Bons estudos! :snake: :books:
