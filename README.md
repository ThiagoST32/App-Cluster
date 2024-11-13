# App-Cluster
Criação de um cluster na nuvem usando os serviços da GPC com as ferramentas da GKE para subir os serviços e usando Kubernetes para a orquestração dos Containers, Services e NodesPorts.

A aplicação consiste em subir 3 pods de PHP (backend) para o save dos dados inseridos pelo usuario no frontend da aplicação, tendo comunicação com outro pod que fica responsavél por gerenciar o banco de dados MySQL.
