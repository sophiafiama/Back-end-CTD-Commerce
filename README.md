# Back-end-CTD-Commerce
Back-end: Java, Spring Framework - modelo MVC distribuido pelo AWS ElasticBeanStalk, Banco de dados H2 no AWS RDS.
Requisitos Back-end:
Back-end de nosso e-commerce em Java com o Framework Spring no modelo MVC.
O banco de dados deverá ser o H2. 
Modelo de dados: O banco de dados terá duas entidades principais, products e categories. Onde cada produto tem apenas uma categoria e cada categoria pode ter vários ou nenhum produto.  Segue o modelo para o banco de dados:
![image](https://user-images.githubusercontent.com/85448082/149217223-a14fa4b0-0a1c-40b8-887d-228dee6a8907.png)

API - O projeto deverá disponibilizar uma API com quatro end-points:

Método GET - 'https://front-end-ctd-commerce.vercel.app/products/filter/all': este end-point deverá disponibilizar os dados de todos os produtos cadastrados em um JSON com o formato que segue:

![image](https://user-images.githubusercontent.com/85448082/149217440-df86f4aa-faa3-44b7-80ea-45d88913a2ce.png)

Método GET - 'https://front-end-ctd-commerce.vercel.app/products/product/1': este end-point deverá disponibilizar os dados de um produto específico em um JSON  com o formato que segue:

![image](https://user-images.githubusercontent.com/85448082/149217506-998af2c2-bf4d-48b9-8820-2a99c654949d.png)

Método GET - https://front-end-ctd-commerce.vercel.app/products/filter/categories: este end-point deverá disponibilizar uma lista de categorias cadastradas em um JSON  com o formato que segue:

![image](https://user-images.githubusercontent.com/85448082/149217552-d69f7a7f-4864-4fe4-b9fb-c05e4b74e8b6.png)

Método GET - 'https://front-end-ctd-commerce.vercel.app/products/product/33': este end-point deverá disponibilizar os produtos de uma determinada categoria, em um JSON  com o formato a seguir:

![image](https://user-images.githubusercontent.com/85448082/149217615-c76c2f8f-b4c2-42f3-ba17-e3681cc28319.png)


