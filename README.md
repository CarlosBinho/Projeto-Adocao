# Projeto Adoção

## Descrição do projeto:
Para modernizar o processo das ongs na adoção de animais, surge a ideia de criar uma solução multi clientes onde a partir de uma busca pelo mapa, o usuário pode encontrar a creche mais próxima dele para realizar uma visita.

1. As creches devem poder criar sua página, com suas informações .
2. Elas devem poder mostrar fotos dos animais disponíveis para adoção, junto com informações como idade, vacinas, nome e etc.
3. Os usuários podem agendar visitas com hora marcada para ver determinados animais
4. O usuário pode realizar doações para cada ong
5. Deve haver uma versão para creche e outra para o usuário

## Pré-requisitos:
Visual studio community 2022 <br>
.net 8 <br>
Basta fazer a instalação mais recente do visual studio e optar pelas opções: 
+ ASP.NET e desenvolvimento web
+ Desenvolvimento para azure
+ Desenvolvimento de .Net Multi-Plataform app Ui
+ Desenvolvimento para desktop com .net
+ Desenvolvimento com a plataforma universal do windows

## Git e Github
Para utilizar o github segue o vídeo tutorial de como criar repositorio e os comandos básicos do git e github: <https://www.youtube.com/watch?v=192HgwRgOYE&t=7490s>
<br>
Para clonar o repositorio basta dar um git clone https://github.com/CarlosBinho/Projeto-Adocao.git
<br>

### Workflow do projeto
Nosso fluxo de trabalho segue as etapas abaixo:

1. Branches Principais:

+ main: Contém a versão estável e pronta para produção do projeto.
+ develop: Branch de desenvolvimento onde novas funcionalidades são integradas. Ela deriva da main

2. Trabalhando em Funcionalidades:

+ Cada desenvolvedor cria uma Feature Branch a partir de develop para trabalhar em uma funcionalidade específica. Exemplo: feature/nome-da-funcionalidade.
+ As alterações são feitas nessa branch e commitadas frequentemente.

3. Integração das Funcionalidades:

+ Quando a funcionalidade estiver pronta, é aberto um Pull Request (PR) da Feature Branch para a branch develop.
+ O código é revisado e, se aprovado, a branch é mesclada em develop.
+ No nosso caso não vamos ter o PR revisado pois o time é pequeno (mas isso pode ser mudado)

4. Lançamento de Versão Estável:

+ Quando todas as funcionalidades necessárias estiverem integradas e testadas na develop, o código é mesclado na main, tornando-se a nova versão estável do projeto.
<br>
Esse fluxo garante que a branch main esteja sempre estável e pronta para produção, enquanto o desenvolvimento ativo acontece na develop.




