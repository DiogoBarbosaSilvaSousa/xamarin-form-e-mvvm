# Livro - Xamarin Forms e MVVM Persistência local com Entity Framework Core

Desenvolver aplicativos multiplataformas se tornou uma tarefa muito mais simples com Xamarin e com Xamarin Forms, frameworks para desenvolvimento de aplicações mobile. São ferramentas com boa estabilidade e consistência, com uma curva de aprendizado muito tênue. O desenvolvimento de páginas para os dispositivos pode ser feito em arquivos XAML e/ou por meio de classes C#, com diversos recursos, como layout e gerenciadores de conteúdo, entre outros que você conhecerá aqui.

Neste livro, Everton Coimbra demonstra na prática como criar uma aplicação para iOS e Android com Xamarin e Xamarin Forms, utilizando a linguagem C#. Você vai desenvolver um projeto de exemplo que lidará com cadastro, imagens e base de dados, aplicando o modelo MVVM (Model, View, ViewModel). Para o acesso à base de dados, será feito uso do Entity Framework Core, API da Microsoft para persistência de objetos em um paradigma relacional. O autor ainda complementa o material com a implementação de serviços REST em um servidor Web, para serem consumidos em sua aplicação Xamarin. Tudo isso em uma arquitetura bem elaborada e flexível, que você poderá comprovar.

Edição atualizada em 08/2021: Atualização para a versão 4.5.0.495 do Xamarin Forms.

## 1 Dispositivos móveis, desenvolvimento cross-platform e o Xamarin
1.1 Os dispositivos móveis na atualidade
1.2 O desenvolvimento móvel cross-platform
1.3 O Xamarin
1.4 O foco prático deste livro com o MVVM e o Entity Framework Core
1.5 Conclusão

##2 Xamarin — Instalação e testes
2.1 Download e instalação
2.2 Teste da instalação realizada
2.3 Visualização das páginas diretamente no Visual Studio
2.4 Conclusão

## 3 Tipos de páginas, layouts e alguns controles para interação com o usuário
3.1 ContentPage e o Stacklayout
3.2 TabbedPage e o Grid como layout
3.3 Navegação entre páginas, ListView e ContentView
3.4 Master Detail Pages e Hamburger Menu
3.5 Conclusão

## 4 O padrão Model-View-ViewModel e o Messaging Center do Xamarin
4.1 A página de serviços oferecidos
4.2 Alteração de um serviço
4.3 Inserção de um novo serviço
4.4 Remoção de um serviço da coleção
4.5 Conclusão

## 5 Execução no dispositivo físico, SQLite e Entity Framework Core
5.1 Publicação da aplicação para um dispositivo iOS
5.2 Publicação da aplicação para um dispositivo Android
5.3 Persistência de dados de maneira física com SQLite
5.4 Dependency Service para utilizar a base de dados
5.5 A classe de modelo
5.6 A classe de contexto
5.7 A classe de manipulação de dados
5.8 A visão que lista todos os clientes
5.9 Implementação do Hamburger Menu
5.10 A página responsável pela inserção e alteração de um cliente
5.11 Remoção de cliente já cadastrado
5.12 Interação e manutenção dos dados de Serviço
5.13 Atualização da base de dados EF Core com Migrations
5.14 Manipulação da base de dados do SQLite
5.15 Conclusão

## 6 Associações, Pesquisa, DatePicker, TimePicker e ActionSheet
6.1 Classe de modelo e de acesso a dados
6.2 A listagem de atendimentos
6.3 Pesquisa por clientes para atendimento
6.4 Veículo, datas e horas de entrada, previsão e entrega
6.5 Botão e Command para realizar a gravação do atendimento
6.6 Operações com atendimentos registrados
6.7 Implementações para a consulta e alteração de um atendimento
6.8 Destaque de um atendimento finalizado pelo uso de Converters
6.9 O método para recuperar um único objeto
6.10 Conclusão

## 7 Associações com coleções
7.1 Classe de modelo e de acesso a dados
7.2 Acesso às visões para itens de serviço e fotos do veículo
7.3 A listagem e remoção de serviços registrados para o atendimento
7.4 A pesquisa de serviços para o atendimento
7.5 Registro dos serviços a serem realizados
7.6 Conclusão

## 8 Uso de câmera e álbum
8.1 Registro das fotos do veículo
8.2 Visão para registro das fotos
8.3 O acesso à câmera
8.4 Tirando foto com o Android
8.5 Problemas no caminho para a imagem gravada
8.6 O acesso ao álbum de fotos
8.7 Gravação do caminho da foto na base de dados
8.8 Remoção de objetos de associações
8.9 Conclusão

## 9 Listagem de fotos e manipulação de gestos
9.1 Listagem das fotos inseridas
9.2 O uso de gestos para definir funcionalidades
9.3 Operação de zoom na imagem selecionada
9.4 Remoção de uma foto da listagem
9.5 Remoção de objetos de associações
9.6 Conclusão

## 10 Custom renderers, login de acesso e consumo de serviços REST
10.1 A visão de Login
10.2 Renderizadores personalizados (Custom Renderers)
10.3 O login com o serviço REST
10.4 Xamarin Essentials
10.5 Conclusão

## 11 O CRUD de peças com o consumo de serviços REST
11.1 A classe Peca, com arquivo de imagem, suas visões e DAL para o REST
11.2 Envio de um objeto com uma imagem para o serviço REST
11.3 Recebendo as peças registradas no servidor
11.4 Remoção de uma peça no servidor
11.5 Recuperação de uma peça específica no servidor
11.6 Envio de uma peça sem imagem para o servidor
11.7 Um serviço REST que retorna uma imagem
11.8 Inserção e alteração para a nova estratégia
11.9 Peças que não forem sincronizadas automaticamente
11.10 Conclusão

## 12 Os estudos não param por aqui

## 13 Apêndice - Criação de serviços REST
13.1 Preparação do ambiente para o desenvolvimento REST
13.2 Criação do projeto Web no STS
13.3 Teste e deploy da aplicação para o Heroku
13.4 O serviço REST que receberá o objeto e imagem para persistência
13.5 Envio de um objeto com uma imagem para o serviço REST
13.6 Obtenção de dados remotos por meio de um serviço REST
13.7 Remoção de uma peça no servidor
13.8 Recuperação de uma peça específica no servidor
13.9 Envio de uma peça sem imagem para o servidor
13.10 Um serviço REST que retorna uma imagem
13.11 Conclusão
