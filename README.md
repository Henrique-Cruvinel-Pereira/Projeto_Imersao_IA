# Projeto_Imersao_IA

O projeto consiste em um modelo que, a partir da imagem de um carro de Fórmula 1, fornece a equipe que ele pertece, os pilotos que pilotaram ele e o ano que competiu.
Utilizou-se a técnica few shots para ensinar a lógica para o modelo.

Para executar o modelo, é preciso inserir as imagens presentes no repositório no ambiente do Google Collab na seção de arquivos. E também inserir sua API Key em "INSERT API KEY"

Para alterar a imagem que o modelo está fornecendo a resposta basta alterar a linha "  *upload_if_needed("/content/teste1.jpg")," inserindo o nome do arquivo da imagem dentro dos parenteses entre aspas.

O código foi obtido a partir de um Prompt Estruturado no Google AI Studio (https://aistudio.google.com/app/u/1/prompts/1DaEj_3CWHngrLUcgySHl0BPSmfikzUaV)

É possível aplicar esse modelo em outros cenários, como, por exemplo, no preenchimento de um banco de dados do almoxarifado de uma empresa, de forma que apenas tirando uma foto do item as informações necessárias sobre ele já sejam inseridas no dataframe. 
