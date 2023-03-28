# Sistema de Propagação de Vagas para Profissionais da Saúde
Este é um sistema baseado em microserviços desenvolvido utilizando Spring Boot 3 e Java 19. O objetivo é propagar vagas para profissionais da saúde, em especial cuidadores de idosos.

# Microserviços
O sistema é composto pelos seguintes microserviços:

# Controle de Usuário
Responsável pelo cadastro e gerenciamento dos usuários do sistema. Realiza todas as operações CRUD (Create, Read, Update, Delete) relacionadas aos usuários.

# Servidor de Autorização
Utiliza o Spring Security para criar tokens e cuidar da autenticação e autorização dos usuários do sistema. É responsável por garantir que apenas usuários autenticados e autorizados tenham acesso às funcionalidades do sistema.

# Envio de Email
Microserviço responsável pelo envio de emails, como notificações e alertas para os usuários do sistema.

# Posts
Responsável pela postagem de vagas para profissionais da saúde. Realiza todas as operações CRUD relacionadas às vagas, permitindo que os usuários possam visualizar, criar, atualizar e excluir vagas.

# Banco de Dados
O sistema utiliza o banco de dados PostgreSQL para armazenar e gerenciar as informações dos usuários e das vagas.

# Configurações do Ambiente
O sistema foi desenvolvido utilizando as seguintes ferramentas e tecnologias:

Spring Boot 3
Java 19
PostgreSQL
Spring Security
Para configurar o ambiente de desenvolvimento, você precisará ter o PostgreSQL instalado e configurado em sua máquina. Além disso, será necessário configurar as variáveis de ambiente e as dependências do projeto.

# Como Executar o Sistema
Para executar o sistema, siga as instruções abaixo:

Clone o repositório em sua máquina
Abra o terminal na pasta raiz do projeto e execute o comando ./mvnw clean install para instalar as dependências do projeto
Execute o comando ./mvnw spring-boot:run para iniciar o sistema
Considerações Finais
Este sistema é uma solução eficiente e escalável para a propagação de vagas para profissionais da saúde, oferecendo um ambiente seguro e fácil de usar para os usuários. O uso de microserviços e tecnologias modernas como Spring Boot e Java 19 garantem alta performance e confiabilidade ao sistema.
