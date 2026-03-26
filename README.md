# Sistema Web para Realização de Pedidos – Gráfica

## Descrição do Projeto

Este projeto consiste no desenvolvimento de um sistema web completo para realização de pedidos em uma gráfica. A aplicação permite que usuários façam solicitações de serviços gráficos de forma online, enquanto o sistema gerencia o armazenamento, processamento e organização desses pedidos.

O sistema foi desenvolvido utilizando tecnologias de frontend, backend e banco de dados, integradas para oferecer uma solução funcional e estruturada.

---

## Tecnologias Utilizadas

* **Frontend:** HTML, CSS e JavaScript
* **Backend:** Python
* **Framework:** Flask
* **Banco de Dados:** SQL

---

## Funcionalidades

### Para o usuário:

* Realizar pedidos de serviços gráficos
* Inserir informações detalhadas do pedido
* Interagir com uma interface web simples e intuitiva

### Para o sistema:

* Receber e processar os pedidos enviados
* Armazenar os dados em banco de dados
* Organizar as informações para posterior consulta

---

## Funcionamento

O sistema segue a arquitetura cliente-servidor:

1. O usuário acessa a interface web (frontend)
2. Preenche os dados do pedido
3. As informações são enviadas para o backend (Flask)
4. O backend processa os dados
5. Os dados são armazenados em um banco SQL
6. O sistema pode recuperar e manipular essas informações conforme necessário

---

## Exemplo de Fluxo

1. Usuário acessa a página de pedidos
2. Preenche campos como tipo de serviço, quantidade e detalhes
3. Clica em “Enviar”
4. O sistema registra o pedido no banco de dados
5. Confirmação é exibida ao usuário

---

## Observações Importantes

* O sistema utiliza Flask para integração entre frontend e backend
* A comunicação entre as camadas ocorre via requisições HTTP
* O banco de dados armazena as informações dos pedidos de forma estruturada
* O projeto segue o modelo MVC simplificado
* A aplicação pode ser executada localmente

---

## Conceitos Praticados

* Desenvolvimento web full stack
* Integração entre frontend e backend
* Uso de framework (Flask)
* Manipulação de banco de dados SQL
* Estruturação de aplicações web
* Comunicação cliente-servidor
