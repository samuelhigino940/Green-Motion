# Green-Motion
# Apresentação do Aplicativo de Geração de Ordem de Serviço – GreenMotion
# Projeto Desenvolvido por Samuel Cerretti Higino

O aplicativo GreenMotion foi desenvolvido com foco em usabilidade, eficiência e modernização dos processos de cadastro e gerenciamento de ordens de serviço, com interface amigável e integração ao banco de dados MongoDB.

![image](https://github.com/user-attachments/assets/2fee14f4-5ded-440e-ae53-e35df3ada983)

![image](https://github.com/user-attachments/assets/2d52e5c2-b842-4879-aa14-dfd0ef6bc3d0)

![image](https://github.com/user-attachments/assets/37b2947d-4b78-4bae-aaf6-2706eb93a5b6)

# Estrutura e Funcionalidade
O sistema foi construído utilizando a tecnologia Electron, o que permite sua execução como uma aplicação de desktop multiplataforma com interface moderna baseada em HTML, CSS e JavaScript. A aplicação conta com as seguintes funcionalidades principais:

# 1. Cadastro e Gerenciamento de Clientes
Na interface de cliente (cliente.html), o usuário pode realizar:

Busca de clientes por nome ou CPF, com um campo de pesquisa e botão de busca.

Cadastro de novos clientes, preenchendo os campos como nome, CPF e e-mail.

Os dados são enviados ao backend por meio de eventos conectados ao preload.js, que utiliza IPC para comunicação segura entre o front-end e o processo principal.

# 2. Menu Principal
A tela inicial apresenta uma interface limpa com os botões principais de navegação, como:

Acesso ao cadastro de clientes.

Acesso ao cadastro de ordem de serviço (OS).

Exibição da data atual, proporcionando maior organização para os usuários.

Ícones visuais que facilitam a identificação das funcionalidades disponíveis.

# 3. Ordem de Serviço
A interface de OS (os.html) permite:

Criação de novas ordens de serviço com associação ao cliente selecionado.

Inclusão de dados como descrição do serviço, data, status e possíveis anexos.

As ordens são armazenadas de forma estruturada no banco de dados.

# 4. Design Responsivo
O sistema utiliza Bootstrap para garantir uma interface responsiva e agradável, com componentes visuais padronizados que facilitam a navegação.

# 5. Integração com o MongoDB
Todas as informações de clientes e ordens de serviço são armazenadas em um banco de dados MongoDB, garantindo persistência e escalabilidade das informações. Os dados são manipulados por meio de repositórios específicos no backend.

