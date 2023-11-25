<h2><a href= "https://www.mackenzie.br">Universidade Presbiteriana Mackenzie</a></h2>
<h3><a href= "https://www.mackenzie.br/graduacao/sao-paulo-higienopolis/sistemas-de-informacao">Sistemas de Informação</a></h3>


<font size="+12"><center>
#Projeto Pizza-Express
</center></font>

**Conteúdo**

- [Autores](#nome-alunos)
- [Descrição do projeto](#introdução-do-projeto)
- [Análise de requisitos funcionais e não-fucionais](#descrição-dos-requisitos)
- [Diagrama de casos de uso](#diagrama-de-comportamento-atores)
- [Descrição dos casos de uso](#descrição-das-funcões)
- [Diagrama de senquencia](#diagrama-de-ordem-interações)
- [Diagrama de classes](#diagrama-orientado-objetos)
- [Diagrama de componentes](#diagrama-estrutura-componente)
- [Decisões de arquitetura](#decisões-de-arquitetura)
- [Diagrama de implantação](#diagrama-de-hardware-software)
- [Referências](#referências)


# Autores

* Guilherme Augusto
* Leonardo Rodrigues
* Pedro Calvacante 


# Descrição do projeto

Uma pizzaria chamada pizza-Express é uma cadeia de 40 lojas. A empresa tem perdido recentemente 30% dos seus pedidos devido ao seu problema de entrega. Com o atraso da pizzaria a empresa Papa-leguas entrou no projeto para ajuda-la a reduzir o tempo de espera de seus clientes. O objetivo da empresa é receber o pedido, localizar a cozinha mais próxima e assim encaminhar o pedido pronto até a casa do cliente com o menor tempo de espera possível. Nesse projeto iremos criar uma solução para essa empresa.

# Análise de requisitos funcionais e não-funcionais
Autenticação e Pedido:<br>
01: O sistema deve permitir que o cliente inicie o aplicativo e se autentique (caso
necessário).<br>
02: O sistema deve permitir que o cliente faça um pedido de pizza selecionando os
ingredientes e/ou opções prontas do menu.<br>
Localização:<br>
03: Uma vez que o pedido é feito, o sistema deve obter automaticamente a localização do
cliente.<br>
04: O sistema deve determinar qual é a fábrica de pizza mais próxima do cliente com base
em sua localização.<br>
Notificações:<br>
05: A fábrica de pizza mais próxima deve ser notificada automaticamente sobre o novo
pedido.<br>
06: O cozinheiro na fábrica de pizza deve receber a ordem em uma tela de pedidos em
tempo real.<br>
07: O entregador deve ser notificado sobre um novo pedido pendente de entrega.<br>
08: Uma vez que o cozinheiro conclua a preparação da pizza, o entregador deve ser
notificado de que a pizza está pronta para ser coletada.<br>
Preparação e Entrega:<br>
09: O cozinheiro deve ser capaz de visualizar os detalhes do pedido e marcar a pizza como
"Em preparação" e posteriormente como "Pronta".<br>
10: O entregador deve usar a integração GPS do aplicativo para encontrar o endereço do
cliente e entregar a pizza.<br>
Inventário:<br>
11: O cozinheiro deve ser capaz de verificar os ingredientes disponíveis e atualizar o
inventário no sistema.<br>
12: Se um ingrediente estiver em falta ou em baixo estoque, o sistema deve enviar
notificações automáticas.<br>
13: O menu do aplicativo deve ser atualizado automaticamente com base na disponibilidade
de ingredientes.<br>
Relatórios:<br>
14: O sistema deve permitir que o gerente acesse e visualize relatórios de vendas.<br>
15: O gerente deve ser capaz de verificar a eficiência da entrega (tempo médio, atrasos,
etc.) através de relatórios.<br>
Feedback do Cliente:<br>
16: Após a entrega, o sistema deve permitir que o cliente forneça feedback sobre a
qualidade da pizza e a eficiência da entrega.<br>
Estes requisitos funcionais oferecem uma visão clara das operações e interações
esperadas entre os atores e o sistema. Eles servirão como base para o desenvolvimento e
implementação do sistema.<br>

# Diagrama de casos de uso
![WhatsApp Image 2023-10-04 at 4 52 38 PM](https://github.com/Leo-RH/UML-Classroom-FCI/assets/59239397/4044fd4e-f60d-402c-9bc7-9a9ef02f0711)

# Descrição dos casos de uso

Arquivo com a descrição de uso: 
[TABELAOFICIAL.xlsx](https://github.com/Leo-RH/UML-Classroom-FCI/files/12835440/TABELAOFICIAL.xlsx)


# Diagrama de sequencia

![Sequence Diagram Example_ Buy Tickets (2)](https://github.com/Leo-RH/UML-Classroom-FCI/assets/59239397/beafc4e3-973b-4460-8ca3-cc5c7f5b51be)


# Diagrama de classes

![DiagPizzaOfc](https://github.com/Leo-RH/UML-Classroom-FCI/assets/59239397/27a55aeb-f7d5-4174-95cf-eed5290d5a30)

# Diagrama de Componentes

![DiagramaDeComponenteEngenharia](https://github.com/Leo-RH/UML-Classroom-FCI/assets/59239397/1acebd00-4249-4ed3-8ae7-3eb7533c3934)

# Decisões de arquitetura

Sobre o servidor que nós iremos usar será em Linux e com a linguagem JAVA teremos o firewall para protege-los e backups online e off-line para garantir mais ainda a segurança. 
Teremos um servidor web para o aplicativo para os clientes efetuarem os pedidos e terem fácil acesso ao cardápio.
O sistema entrará em ação quando o cliente fizer seu pedido no aplicativo e assim o sistema calcula a rota e localiza a cozinha mais próxima do cliente para que o pedido seja mandado para lá, os cozinheiros recebem o pedido pelo monitor instalado dentro da cozinha e assim que o pedido ficar pronto é deixada ao entregador, que será informado do endereço, leve a pizza ao local, fazendo assim com que o cliente espere o menor tempo possível.
O sistema também terá um sistema de SQL de banco de dados que nele será armazenado alguns históricos dos pedidos recentes que os clientes fizerem e também a localização de todas as cozinhas para serem facilmente localizadas

# Diagrama de implantação

![DIagrama de Implantação](https://github.com/Leo-RH/UML-Classroom-FCI/assets/59239397/67e0c5a8-a4d3-4c6a-830c-d68bde3eac59)

# Referências

*&lt;Lista de referências&gt;*
