

# Desafio Front End Pessoas de Tech - desafio 3  
  
Então, a firma cresceu, e o patrão precisa de um **fullstack** para tocar um projeto. O processo tá tão acelerado que o **terrível designer** nem foi convocado para a tarefa. Logo, está nas suas mãos este desafio.

A situação tá tão calamitosa que só deu tempo para elaborar o Briefing. Ao menos a empresa entregou um manual da marca, para vocês adaptarem. Tá **[aqui para você visualizar a guia de estilo.](https://www.figma.com/file/NyON1l59HQrDwafFn9ePEW/Tech-People---Desafio-03)**

## Briefing deste terceiro projeto

*PS: Este é um briefing de mentirinha, nem sempre será assim que você receberá os seus projetos. Porém entre na fantasia e pense num chefe biruta que apenas organizou o briefing, e mandou aquele **se vira** para você. Parece tolo, mas o mercado tem muitos processos que são tocados assim mesmo. Estamos te preparando para o futuro.*

Este terceiro cliente tem um processo de organização de equipes internas para os projetos dele. Ele lidera uma empresa que toca inúmeros pequenos projetos, mas não gosta dos sistemas disponíveis do mercado, pois não atendem a necessidade dele. Ele listou o problema dele abaixo:

*Oi pessoal, meu nome é Astolfo Adalberto, lidero a **Pirataria Projetos Web**, uma empresa líder do segmento de projetos para web. Nós temos uma equipe de 50 pessoas, sendo designers, programadores front e back-end, e todo mês temos um excel gigantesco para gerenciar quem faz qual projeto da nossa firma. Temos tido dificuldade em organizar as equipes, e todo mundo aqui está sobrecarregado, por isto contratamos vocês para dar aquela ajuda.*

*A gente gostaria de gerenciar os funcionários e botar eles dentro de projetos, definindo a quantidade de horas técnicas e os valores de hora, que fazemos para cada cliente. Por enquanto só preciso do acesso do administrador para organizar os times, pois usamos o trello para as tarefas. O que me prejudica é que não sei quem tá tocando qual projeto, e nem qual cliente está sendo atendido, pois odeio o excel.*

Bem, é uma oportunidade para a nossa agência a pegar clientes maiores, com aqueles dinheiros graúdos. Ele até **deixou botar no seu github** de tão desesperado que ele está. Como eu não consigo botar o nosso **terrível designer** no projeto, pedi pro cliente, e ele me entregou a guia de estilo. Pelo que conversei na reunião com ele, ele pediu:

- Ele pediu uma tela para login, usando e-mail e senha.
- Ele quer uma tela para cadastro de funcionários, pedindo:
	- Nome
	- Email
	- Telefone
	- Cargo
		- Designer
		- Frontend
		- Backend
		- Gerente
		- QA
		- DevOps
	- Foto
	- Salário em reais
- Uma tela para cadastro de clientes, onde gerenciamos:
	- Nome do cliente
	- Telefone
	- Email
	- Site
	- CNPJ
	- Logo
- Uma tela de projetos, onde eles pedem para gerenciar:
	- Nome do projeto
	- Dono do Projeto (a ID do cliente)
	- Quantidade de horas técnicas
	- Data de entrega
	- Prioridade do Projeto
	- Descrição do projeto
	- Líder do projeto
		- Este líder do projeto pode ser qualquer funcionário, mas tende a ser o Gerente
	- Valor, em reais, da hora técnica. Geralmente ele cobra R$ 200,00 por hora técnica, mas tem cliente que ele pode dar desconto e outros que pode cobrar mais ou menos.
	- Equipe ativa no projeto
		- Nesta parte, ele quer poder adicionar livremente as pessoas, ao menos um designer e um programador, podendo ser ou um front ou um backend. Ele quer poder adicionar mais do que um.
- Ele pediu para que na tela geral de projetos vir calculado o valor que o cliente irá pagar pelo projeto.
  
## FAQ  
**1) Para quem é indicado este desafio?**  
Este é um desafio recomendado para fullstackers ou para ser feito em equipes.
  
**2) Tem prazo para entregar este desafio?**  
Este será um projeto de longa duração, com prazo de encerramento em 1 de julho de 2022. Logo, você tem 6 meses para me entregar.
  
**3) Quem vai avaliar o meu projeto?**  
Eu, Mateus Ávila Isidoro. Devo chamar mais algumas pessoas para avaliar, e quem foi bem demais no primeiro desafio.
  
**4) Posso botar no github como projeto "pinado" para avaliadores olharem meus códigos?**  
Este é um projeto original, pode e deve ser colocado no github. Tanto que não vamos nem entregar o design. 
  
**5) Posso usar algum framework tipo Boostrap, Sass, Stylus, React, Vue, Svelte, Wordpress, Tailwind, Astro, entre muitos outros?**  
Sim, você(s) são livres. Desde que as escolhas sejam discutidas pela equipe.

**6) Eu preciso subir este site numa URL pública?**  
Sim. Como é um sistema que terá acesso de login e senha, ao publicar o desafio na issue deste repositório, peço que envie um e-mail para **mateus@mateusavila.com.br** com acesso de login e senha da conta de administrador. Prometo cuidar da senha com carinho.

**7) Eu preciso subir num repositório público?**  
Sim. Mas os dados de ambiente precisam estar protegidos. A responsabilidade destes dados é de vocês.

**8) Preciso ter branches além da master (main)?**  
Não é necessário. Mas se criar branches, avise no seu README.md.

**9) Pode fazer com algum colega, pra estudarmos juntos?**  
Sim. Recomendamos que este projeto seja feito em equipe.

## O que vamos avaliar?

Para facilitar o seu trabalho, vamos listar o que vamos avaliar neste projeto, de coisas que consideramos necessárias e opcionais que irão agregar valor. Lembre-se, quanto mais coisas o projeto tiver, mais atento iremos avaliar o seu projeto. Temos descritores obrigatórios e descritores opcionais, se eles serão ou não atendidos pelo código:

1. **Qualidade Geral do código**: se o código possui clareza na leitura, utiliza nomenclaturas consistentes e é conciso.
2. **Se é fiel a proposta estabelecida**: se o projeto atende as regras do briefing proposto acima.
3. **Se é rápido o suficiente**: se o site consegue responder em até 4 segundos a requisição inicial.
4. **Links aplicados da maneira correta**: Se as rotas criadas fazem sentido e estão funcionando.
5. **Se o sistema é seguro**: o cliente não gostaria de que qualquer pessoa acessasse o sistema.

Abaixo listamos os descritores opcionais, que agregarão valor ao projeto. Aqui é a parte que pode começar a impressionar o patrão:

1. **Se é fácil e intuitivo de adicionar muitos projetos com facilidade** - se o administrador do sistema consegue adicionar rapidamente muitos projetos. Sim, ele tem muitos projetos que ele precisa adicionar na lista.
2. **Se há paginação de resultados**
3. **Se há busca interna**
4. **Se há ordenação de resultados**
5. **Se a exclusão é feita de maneira soft, isto é, apenas alterando o estado do registro, sem remover ele do banco.** O cliente gosta de ter logs de tudo.
6. **Se o upload das imagens for por drag'n'drop**

## Realmente impressionar o patrão (#vemBonus!)

Se você quer deixar o patrão feliz, faça algo a mais. Dicas de como impressionar o cara que assina o teu cheque:

1. **O README do seu projeto ser bem escrito**
2. **Utilizou variáveis ou mixins de CSS ou de algum pré-processador**
3. **Fez boa componentização do projeto**
4. **Fez bom uso do git, como criando branches, commitando com mensagens que descrevem bem a tarefa que subiu**
5. **Se a API tem documentação, podendo ser um site a parte, swagger, Postman ou Postwoman**
6. **Se as requisições seguras usam técnicas como JWT, Laravel Passport ou outra que aumente a segurança do dado.**
7. **Se há uma página de Dashboard que lista alguns dados para o cliente olhar rapidinho, como quantidade de funcionários, quanto que vai arrecadar no mês, entre outros.**

Bem, aqui é só para quem quer motivação para estudar um pouco mais. 
