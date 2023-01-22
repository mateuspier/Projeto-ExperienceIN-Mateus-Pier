# Projeto Experiencein 💻

Objetivo: A origem do projeto, desenvolvido por estudantes do curso de Tecnologia em Sistemas para Internet do Instituto Federal de Brasília - Campus Brasília, proposta pela disciplina de Programação para Internet II, subdividida em módulos, lecionada pelo Mestre Fábio Henrique tem como ponto de partida a criação de uma rede social para simulação de algumas funcionalidades básicas encontradas neste tipo de produto, como a capacidade de criar uma conta para cadastro de usuário, visualizar uma página de perfil, enviar e aceitar convites enviados para/por outros usuários e visualizar a página de perfil desses usuários. Além disso, o projeto do back-end fora hospedado em um ambiente de hospedagem na nuvem, o PythonAnywhere, que permite aos desenvolvedores executar código Python em um servidor remoto e fornece uma plataforma fácil de usar para desenvolvimento e implantação de aplicativos Python, incluindo projetos Django. Outra vantagem do PythonAnywhere, é sua capacidade de tornar possível implantar um aplicativo em um ambiente de produção seguro e escalável, oferecendo recursos robustos como gerenciamento de banco de dados, gerenciamento de arquivos e suporte para vários frameworks e bibliotecas Python populares.

-----------------------------------------------------------------------------------

## Funcionalidades 🚀

• Criar conta para cadastro de usuário com autenticação
• Exibir perfil
• Convidar outro usuário cadastrado
• Visualizar lista de usuários convidados
• Receber convite
• Aprovar ou recusar convite

-----------------------------------------------------------------------------------

## Tecnologias 🚀

• Python 3.7.9
• Django 2.2
• PIP3
• Visual Studio Code 1.69
• PythonAnywhere (Back-end)


-----------------------------------------------------------------------------------

## Como configurar o back-end do projeto 🔨

1. Abra o terminal gitbash e clone o repositório para sua máquina local:

		git clone https://github.com/Prof-Fabio-Henrique/projeto-final-2022-2-g4-rm.git

2. Navegue até a raiz do diretório do projeto:

		cd experiencein/

3. Crie um ambiente virtual e ative-o:

		python -m venv venv
		source venv/bin/activate


4. Instale os pacotes necessários:

		pip3 install -r requirements.txt


5. Configure as variáveis de ambiente, se necessário.

6. Faça as migrações no banco de dados:

		python manage.py makemigrations
		python manage.py migrate

## Como configurar o ambiente de produção do back-end no PythonAnywhere 🔨

1. Crie uma nova Web App: Vá para a seção Web do PythonAnywhere e crie uma nova Web App. Selecione o Python 3.7.9 como a versão do Python.

2. Utilize o banco de dados SQLite3: Django vem com o banco de dados SQLite3 como opção padrão, não é necessário criar um banco de dados MySQL ou PostgreSQL.

3. Através do console Bash, crie um novo ambiente virtual usando o comando:

		virtualenv 

4. Ative o ambiente virtual com o seguinte comando:
		
		"source nome_do_ambiente_virtual/bin/activate"

5. Instale o Django: Dentro do ambiente virtual, instale o Django usando o comando pip:

		"pip install django==2.2"

6. Crie um novo projeto Django: Dentro do ambiente virtual, crie um novo projeto Django usando o comando:

		"django-admin startproject nome_do_projeto"

7. Edite o arquivo settings.py: Edite o arquivo settings.py do seu projeto e adicione as configurações do banco de dados que você criou anteriormente.

8. Rode as migrações: Dentro do ambiente virtual, vá para a pasta do projeto e rode o comando:

		python manage.py makemigrations
		python manage.py migrate

9. Configure o PythonAnywhere: Vá para a seção Web do PythonAnywhere e configure a Web App para usar o seu ambiente virtual e o diretório do projeto.

10. Rode o servidor de desenvolvimento: Dentro do ambiente virtual, vá para a pasta do projeto e rode o comando abaixo para iniciar o servidor de desenvolvimento:

		"python manage.py runserver" 

11. Configure o endereço IP e a porta: Configure o endereço IP e a porta no PythonAnywhere para que o servidor possa ser acessado através da internet.

12. Acesse o seguinte link:

    		mateuscopier.pythonanywhere.com

-----------------------------------------------------------------------------------

## Licença 🔑

Este projeto possui limita sua licença a uso pessoal, somente, e é proibida a comercialização ou uso indiscriminado do mesmo para fins de lucro ou infração de qualquer natureza nestes termos. 

-----------------------------------------------------------------------------------

## Autoria 👨 

O projeto contou com a produção e realização do estudante Mateus Santos, aluno do 5º semestre do curso de tecnologia em Sistemas para Internet do Instituto Federal de Brasília (IFB) – Campus Brasília. O desenvolvimento ocorreu durante o semestre letivo em curso da disciplina de Programação para Internet II, ministrada pelo professor Fábio Henrique.

-----------------------------------------------------------------------------------

## Problemas conhecidos 🚩

• Problemas de compatibilidade entre as versões do Django e do Python, especialmente se o projeto usa bibliotecas ou pacotes que não são compatíveis com essas versões específicas.

• Problemas de performance ao lidar com grandes volumes de dados ou de usuários simultâneos.

• Problemas de segurança ao lidar com autenticação e autorização, especialmente se o projeto usa bibliotecas ou pacotes não atualizados.
	
-----------------------------------------------------------------------------------

## Colabore ✋

• Abra Pull Requests com atualizações
• Discuta ideias em Issues
• Compartilhe o repositório com a sua comunidade
• Envie feedbacks por e-mail para mateus.santos5@estudante.ifb.edu.br ou richard.ornelas@estudante.ifb.edu.br 

-----------------------------------------------------------------------------------

## Futuras atualizações e contribuições 🔮

   Para aprimorar o desenvolvimento do projeto, pretende-se em breve, configurar o front-end e hospedar a versão no deploy para explorar versões incrementais das seguintes funcionalidades, oferecendo um app com uma experiência completa e recursos e funcionalidades mais avançados:

• Acessibilidade: Tornar a aplicação reconhecida em ferramentas de tradução para pessoas portadoras de necessidades visuais e/ou auditivas.

• Busca e filtragem: Adicionar recursos de busca e filtragem ao seu projeto, permitindo que os usuários pesquisem e filtrem os dados disponíveis.

• Paginação: Adicionar recursos de paginação ao seu projeto, permitindo que os usuários naveguem facilmente por grandes conjuntos de dados.

• Notificações: Adicionar recursos de notificação ao seu projeto, permitindo que os usuários recebam notificações sobre atualizações ou eventos importantes.

• Integração com redes sociais: Adicionar recursos de integração com redes sociais ao seu projeto, permitindo que os usuários se conectem com suas contas de redes sociais e compartilhem conteúdo.

• Integração com outros serviços: Adicionar recursos de integração com outros serviços, como por exemplo envio de email, pagamentos online, entre outros.

• Geração de relatórios: Adicionar recursos de geração de relatórios, permitindo que os usuários visualizem e exportem dados do projeto.

• Multi-idiomas: Adicionar recursos de suporte a múltiplos idiomas, permitindo que os usuários naveguem e interajam com o projeto em sua própria língua.

• Suporte a dispositivos móveis: Adicionar recursos de suporte a dispositivos móveis, permitindo que os usuários acessem o projeto a partir de dispositivos móveis.

• Dashboard: Adicionar um dashboard para o administrador, para que ele possa gerenciar o projeto, visualizar estatísticas e dados.

• Backup automático: Adicionar recursos de backup automático, para garantir que os dados do projeto estejam sempre seguros.

• Integração com inteligência artificial: Adicionar recursos de inteligência artificial, para melhorar a experiência do usuário e tornar o projeto mais inteligente e personalizado.

• Integração com Chatbot: Adicionar recursos de chatbot, permitindo que os usuários interajam com o projeto através de conversas naturais, e ajudando-os a encontrar informações ou realizar tarefas de forma rápida e eficiente.
