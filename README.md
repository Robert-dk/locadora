# Locadora de Veículos

Este projeto implementa um banco de dados SQL para gerenciar uma locadora de veículos. O script SQL cria as tabelas e define os relacionamentos necessários para armazenar informações sobre clientes, veículos, locações e outros dados relevantes para a operação da locadora.

## Funcionalidades

* Cadastro de clientes com nome, endereço, telefone e outros dados.
* Cadastro de veículos com placa, modelo, marca, ano e outras informações.
* Registro de locações com data de início, data de término, cliente e veículo.
* Cálculo automático do valor da locação com base na diária do veículo e número de dias.
* Geração de relatórios de locações por período, cliente ou veículo.

## Tabelas

* **cliente:** Armazena informações sobre os clientes da locadora.
* **veiculos:** Contém dados dos veículos disponíveis para locação.
* **locacao:** Registra as locações realizadas, incluindo cliente, veículo e datas.
* **marca:** Armazena as marcas dos veículos.
* **categoria:** Define as categorias dos veículos (ex: esportivo, SUV, van).

## Como Executar

1. Certifique-se de ter o MySQL instalado e configurado em sua máquina.
2. Crie um novo banco de dados no MySQL.
3. Execute o script `locadora.sql` para criar as tabelas e definir os relacionamentos.
4. Utilize um cliente SQL (ex: MySQL Workbench, Dbeaver) para interagir com o banco de dados e inserir dados.

## Observações

* O script SQL foi desenvolvido para o MySQL, mas pode ser adaptado para outros bancos de dados.
* É recomendável utilizar um ambiente virtual para evitar conflitos de dependências.
* Em caso de dúvidas, consulte a documentação do MySQL ou procure ajuda na comunidade.

## Autor

ROBERT EMANUEL
