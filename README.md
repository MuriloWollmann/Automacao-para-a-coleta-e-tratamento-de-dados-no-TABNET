![image](https://github.com/user-attachments/assets/f11ea1f2-4fdc-474f-852a-a367e85b883b)# Automação para a coleta e tratamento de dados no TABNET

A automação desenvolvida tem a função de facilitar a coleta e o tratamento de dados epidemiológicos do sistema TABNET, utilizado pelo DATASUS. Ela automatiza o processo de busca, download, concatenação e correção de dados, eliminando a necessidade de etapas manuais demoradas e sujeitas a erros. Utilizando Python e bibliotecas como Selenium e Pandas, a aplicação navega pelo site do TABNET, realiza o download das tabelas em formato CSV, padroniza a formatação dos dados e corrige inconsistências, garantindo uma coleta de dados mais eficiente, precisa e atualizada para análise na área da saúde pública.

Tabelas baixadas:
•	Exames por Ano segundo Faixa Etária - Local de Atendimento (Somente mulheres) - Cruz Alta, Giruá, Ijuí, Panambi – (2019 – 2024);
•	Exames por Ano segundo Faixa Etária - Local de Residência (Somente mulheres) - Cruz Alta, Giruá, Ijuí, Panambi - (2019 – 2024);
•	Exames por BI-RADS segundo Faixa Etária - Local de Atendimento (Somente mulheres) - Giruá e Panambi - (2019 – 2024);
•	Exames por BI-RADS segundo Faixa Etária - Local de Residência (Somente mulheres) - Giruá e Panambi - (2019 – 2024);
•	Exames por BI-RADS segundo Tempo Exame - Local de Atendimento (Somente mulheres) - Giruá e Panambi - (2019 – 2024);
•	Exames por BI-RADS segundo Tempo Exame - Local de Residência (Somente mulheres) - Giruá e Panambi - (2019 – 2024).

Linguagens de programação no qual foi desenvolvido e está disponibilizado o programa:
•	Google Colab (1.0.0);
•	Python (3.10.12);
•	Selenium (1.0.14);
•	Pandas (2.1.4).

//PRINTS//

Dois blocos de códigos disponíveis.
![image](https://github.com/user-attachments/assets/2ef7e19a-24ce-4cdb-ad88-68da4fab8e5d)

Comentários sobre o funcionamento do código e instalação das bibliotecas.
![image](https://github.com/user-attachments/assets/6b7bb1c9-4a3d-4248-974c-98c6781df739)

Classe WebScraper com as funcionalidades que serão utilizadas.
![image](https://github.com/user-attachments/assets/2e84eb7e-8fb9-464e-9d3d-5dc905e325cd)

Funcionalidades restantes.
![image](https://github.com/user-attachments/assets/1c07a6db-3580-4e20-aa08-4f17ff9aebab)

WebScraper é inicializado e percorre o site do TABNET através dos XPaths. 
![image](https://github.com/user-attachments/assets/7d386213-12f2-4553-8fd3-5c4e986761a5)

WebScraper preenche os filtros necessários, gera as tabelas, faz o download e é finalizado. 
![image](https://github.com/user-attachments/assets/a9ad5224-0d18-4572-909a-b94266eab3bc)

WebScraper é inicializado e percorre o site do TABNET através dos XPaths. 
![image](https://github.com/user-attachments/assets/597be0fd-8812-4f67-ac8a-84864726cd99)

WebScraper preenche os filtros necessários, gera as tabelas, faz o download e é finalizado. 
![image](https://github.com/user-attachments/assets/5fd40574-58ac-4c49-a964-8670bc8b5351)

WebScraper é inicializado e percorre o site do TABNET através dos XPaths. 
![image](https://github.com/user-attachments/assets/9caebc81-ee5a-4c20-8197-87ef4e73a818)

WebScraper Seleciona os filtros necessários e gera as tabelas. 
![image](https://github.com/user-attachments/assets/4c77ab8e-a5c4-4420-a153-7a0d78fdb10a)

WebScraper faz o download das tabelas. 
![image](https://github.com/user-attachments/assets/3e551e8e-fb23-46e4-b6ef-112b2541f0b6)

WebScraper continua o download das tabelas e é finalizado. 
![image](https://github.com/user-attachments/assets/d1af2185-526a-4878-940b-3f5d8daeab58)

WebScraper é inicializado e percorre o site do TABNET através dos XPaths. 
![image](https://github.com/user-attachments/assets/8ccbec4d-adfb-4ba6-9234-0193398d99f0)

WebScraper Seleciona os filtros necessários e gera as tabelas. 
![image](https://github.com/user-attachments/assets/593d51ff-d234-48db-8c39-25131dd309dc)

WebScraper faz o download das tabelas. 
![image](https://github.com/user-attachments/assets/ecbf85a5-af6e-4bdd-a710-395933380197)

WebScraper continua o download das tabelas e é finalizado. 
![image](https://github.com/user-attachments/assets/e30aec29-1136-4356-93d8-3f8a2b1a5010)

WebScraper é inicializado e percorre o site do TABNET através dos XPaths.  
![image](https://github.com/user-attachments/assets/aa961af4-f05c-4b43-9384-57b82c2aa795)

WebScraper Seleciona os filtros necessários e gera as tabelas.  
![image](https://github.com/user-attachments/assets/02a8da68-16a3-4e38-a1bb-3eb9e580bcbb)

WebScraper faz o download das tabelas.  
![image](https://github.com/user-attachments/assets/14a0dd08-fc4a-404f-9d07-ea56e5651a46)

WebScraper continua o download das tabelas e é finalizado.  
![image](https://github.com/user-attachments/assets/1f5f8778-e09a-4bf5-97f9-b2881bd71c43)

WebScraper é inicializado e percorre o site do TABNET através dos XPaths.  
![image](https://github.com/user-attachments/assets/edc7ef6c-4b6f-4820-acbc-56ef15e50858)

WebScraper Seleciona os filtros necessários e gera as tabelas.  
![image](https://github.com/user-attachments/assets/ef7fc5be-1b11-4759-8294-60c152021ca2)

WebScraper faz o download das tabelas.  
![image](https://github.com/user-attachments/assets/60b768b6-0f40-47c8-adfb-044992ce3275)

WebScraper continua o download das tabelas e é finalizado.  
![image](https://github.com/user-attachments/assets/c30decef-28af-4ed7-8d99-749f79bef51b)

Função para limpar o diretório do Colab antes de rodar o código main. 
![image](https://github.com/user-attachments/assets/8fe5bcc3-d99e-4b41-9f7c-a4319aa7f806)

Função para nomear os arquivos baixados pelo WebScraper. 
![image](https://github.com/user-attachments/assets/13fce09d-9af3-4160-9998-2ce608244162)

Continuação da função para nomear os arquivos e função para corrigir inconsistências na formatação dos dados do TABNET. 
![image](https://github.com/user-attachments/assets/579e55f4-bb88-43d8-b1a8-b6c6b692db2d)

Adiciona algumas colunas às tabelas baixadas. 
![image](https://github.com/user-attachments/assets/3c374728-3a30-421f-9229-511b7f93d332)

Adiciona algumas colunas às tabelas baixadas. 
![image](https://github.com/user-attachments/assets/02d9348b-2b94-436b-8727-50a0f6fa17cc)

Concatena todas as tabelas baixadas. 
![image](https://github.com/user-attachments/assets/48ffc4bd-2f88-4d3d-aaac-0a8b5156730b)

Termina de concatenar todas as tabelas baixadas e envia as tabelas resultantes para o diretório do Colab. 
![image](https://github.com/user-attachments/assets/e081763c-f623-4fb6-ad6e-51e991747184)

Roda o processo main. 
![image](https://github.com/user-attachments/assets/844b7324-bd85-400e-9c50-9dcfe21654aa)

Importa as tabelas concatenadas do diretório para o drive da ClickPalm. 
![image](https://github.com/user-attachments/assets/4da0e830-3002-4a37-8d15-12f51f0a019e)
