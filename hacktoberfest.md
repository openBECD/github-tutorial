## Tutorial Hacktoberfest

Salve família BECD e BCD (se você não é, tudo bem, todo mundo tem defeitos).
Vim aqui explicar pra vocês do que se trata a hacktoberfest, introduzir noções de git e de quebra te fazer ganhar uma camiseta pra usar quando todas as suas do caaso estiverem sujas
A Hacktoberfest é um evento organizado anualmente pela Digital Ocean para incentivar a cultura open source.
\- Ok, e de que forma eles incentivam?

Bem, no site da hacktoberfest são listadas algumas formas de contribuir:

> - Prepare and share your project for collaboration
- Contribute to the betterment of a project via pull requests
- Organize an event
- Mentor others
- Donate directly to open source projects

E eu to aqui para fazer o papel de "mentor" e mostrar pra vocês que o git não é um bicho de sete cabeças e você pode contribuir facilmente com projetos. À primeira vista parece ser muito difícil ter conhecimento suficiente pra contribuir, porém você pode ter um repositório com um amigo da turma onde vocês podem guardar os códigos de ICC, inferência ou até mesmo guardar poemas, feitiços ou simpatias pra trazer a pessoa amada em 3 dias.

\- Ok, já entendi. Como eu ganho a camiseta??????

Calma lá, jovem gafanhoto. Vamos com calma.
Primeiramente vamos conhecer alguns conceitos:

#### Git

O git nada mais é do que uma ferramenta para versionamento de códigos.
Imagina que você trabalha numa empresa e você está construindo uma programa juntamente com um colega de trabalho. Então você terminou de fazer uma alteração e ele precisa do código atualizado para trabalhar em cima dele. Como você faria pra ele ter sempre o código atualizado e saber exatamente o que você fez??
Bom, você pode salvar o arquivo num pen drive e passar pra ele, enviar via email/whatsapp ou até mesmo imprimir o código e entregar o papel pra que ele digite ou use o camScanner pra transformar em pdf e tentar copiar.
Obviamente essas são as maneiras mais espertas de fazer isso e muito usadas no mundo corporativo. Porém devemos nos preocupar mais com a natureza e evitar usar o papel. Assim, com esse objetivo o ministério do meio ambiente criou o amado **Git**.
Com o git você pode facilmente explicar a alteração que você fez, com uma mensagem  do tipo **"Essa alteração nao serve pra nada, só quero a camiseta"** ou outras mais explicativas como **"Agora vai"**, **"Bugfix"**, **"fhksjdfhskjdfh"** e outras variantes.
Você também consegue ver exatamente a linha que foi alterada e o que foi alterado. E caso queira, pode voltar exatamente ao ponto antes de uma determinada alteração. Além de poder  criar versões paralelas do código em diferentes *branchs* e muitas outras funcionalidades que eu nao faço ideia de como usa e tenho raiva de quem sabe pq é dificil de aprender. (ou eu sou burro, nao sei)
\- Ok, Caique. To entendendo. Mas e a camiseta????
Calma, calma. Como falei, o git foi uma maravilhosa invenção e salva muitas árvores até hoje. Poréém, o repositório git fica no seu computador, como o seu amigo de trabalho que não faz nada vai conseguir ver as alterações? Vocês precisam usar o repositório na famosa nuvem (pois ela traz chuva e ajuda a natureza)
E é ai que entram as plataformas de hospedagem de repositórios git. Existem diversas delas: github, gitlab, bitbucket entre outras (só conheço essas 3, rs)

#### Github

Certa vez eu vi um meme de uma pessoa no reddit perguntando a diferença entre git e github. Logo em seguida, um verdadeiro gênio da computação e candidato a prêmio nobel respondeu de forma genial que a diferença é a mesma que há entre *porn* e *pornhub*.
Aposto um pastel de óleo do podrão que depois dessa comparação vocês já sacaram tudo. É exatamente isso, o github hospeda repositórios git (e serve pra outras coisas tambem, como stalkear o que os outros tão fazendo).
\- É agora que eu ganho a camiseta??
Mais ou menos. O Github, assim como o gitlab, são as plataformas que estão sendo usadas esse ano pela hacktoberfest para validar suas contribuições em projetos. E é através dela que vou te explicar como você pode fazer isso.

#### Ganhando a camiseta

Bem, agora chegou a parte importante.
Para ganhar a camiseta, você precisa fazer 4 *pull requests* (PR) válidos em repositórios.
\- Mas o que seria o PR válido?
Bem, primeiro você precisa saber o que é um pull request.
Vamos lá. Suponha que o Dollynho, o seu amiguinho, tem um repositório em que ele guarda códigos do complexo programa que ele ta fazendo pra escrever a frase "Hello World" na tela do computador.
Porém, você percebeu que ele é burro e escreveu "Helo Word" e você quer corrigir. Mas você não consegue simplesmente editar o programa dele, imagina a bagunça que seria caso isso fosse possível...
Sendo assim, você precisa seguir alguns passos para ajudar o Dollynho:

Primeiro você vai "copiar" o repositório dele para a sua conta, que é o que chamamos de *fork*. Eu sempre imaginei fork como um garfo, mas eu acabei de descobrir que também pode ser bifurcação
Agora que você já tem uma cópia do repositório dele só pra você, você pode alterar o que quiser, até mesmo escrever *Hello World* em russo, que eu não faço ideia de como é.
Depois de feita a alteração, você pode avisar ao seu amigo que você alterou uma parte do código dele e fazer um pedido pra ele adotar a sua alteração para o código original.
Então a tradução do termo *Pull Request* seria algo como "Cara, eu mudei isso aqui no seu código e agora ta bem melhor. Aceita ai minha alteração".
Caso ele aceite, essa "bifurcação" vai juntar, que é o que chamamos de *merge*
\- Aah, to entendendo. Então eu preciso fazer isso pra descolar minha peita?
Exatamente!! Porém temos ainda a palavra "válido" depois de "*pull request*".
Segundo a hacktober fest:
> Your pull requests will count toward your participation if they are in a repository with the 'hacktoberfest' topic and once they have been merged, approved by a maintainer or labeled as **hacktoberfest-accepted**. 
Additionally, any pull request with the **hacktoberfest-accepted** label, submitted to any public GitHub/GitLab repository, with or without the hacktoberfest topic, will be considered valid for Hacktoberfest.

O Dollynho, dono do repositório, consegue colocar algumas flags tanto no repositorio quanto no seu PR.
Caso o repositório dele tenha a flag "hacktoberfest", então qualquer PR que você fizer e for aceito vai contar.
Além disso, qualquer PR com a flag "hacktoberfest-accepted" conta também, ele estando em um  repositório participante ou não.
Ok, agora vamos colocar a mão na massa.

#### Contribuindo

Primeiramente você precisa ter instalado o git no seu computador. Caso você use linux, existe grande chance de ele já estar instalado e você nem sabe disso. Tenta digitar *git* no terminal.
Caso esteja no windows, você provavelmente não tem, mas na dúvida, tenta digitar *git* no cmd e ver o que acontece.

Caso você não tenha, pode baixar no seguinte link:
https://git-scm.com/downloads
(Ou instalar via terminal pra vc que é nerd)

Feito isso, você precisa escolher em qual repositório você deseja contribuir. (pode ser um repositório seu, inclusive).
Vou pegar como exemplo um repositório meu, o CabeçaBOT, que foi um bot que fiz pro telegram cerca de 5 anos atrás. Ele consistia em enviar a sua mensagem pro robô Ed (alguns vão lembrar), pegar a resposta e enviar de volta pro telegram.

1. Como eu tinha dito, o primeiro passo é fazer o garfo, digo, o *fork*
![](https://i.imgur.com/7lkoI8d.png)

Caso o repositório seja de outra pessoa, você pode clicar em Fork. Caso seja seu, pode passar para o proximo passo e criaremos uma *branch* localmente

2. Feito isso, queremos baixar o repositório pro nosso computador para que possamos fazer alterações.
Basta clicar no botão "Code" e copiar o link que aparecerá
![](https://i.imgur.com/bUazqnd.png)

3. Com o link copiado, basta ir no seu cmd ou terminal e digitar:
`git clone <link>`
No meu caso ficaria
`git clone https://github.com/caiqueff/CabecaBot.git`

Pronto!! O repositório já está no seu computador. Basta navegar até a pasta recém criada e fazer alguma alteração. Você pode adicionar um código novo da ultima aula, alterar algo que já existe, apagar algo ou colocar la uma selfie sua, pelo menos lá ninguém vai ver.
No meu caso, irei criar um arquivo novo chamado hacktober.py e colocar nessa pasta

3. Criemos então uma nova branch, que também não sei a tradução. Mas é uma das "pernas" da bifurcação.
Naveguemos até a pasta do nosso projeto com
` cd ./pasta`
No meu caso ficaria
`cd ./CabecaBOT`
Feito isso, podemos criar a nossa branch com
`git branch <nomeDaSuaBranch>`
eu usei
`git branch hacktoberfest`
Em seguida, digitando apenas `git branch` você pode ver as branchs existentes
![](https://i.imgur.com/KyvJq5B.png)
Perceba que apesar de exister a branch hacktoberfest, nós ainda estamos na master.
Vamos trocar com `git checkout hacktoberfest`, obviamente trocando pelo nome que você escolheu.
![](https://i.imgur.com/2AENTcO.png)
Pronto, agora estamos onde queremos!!

4. Depois disso, vejamos as alterações feitas digitando
`git status`
Você provavelmente vai ver algo como
![](https://i.imgur.com/EgWJEdZ.png)

Isso significa que a sua belíssima selfie (ou código, whatever) está untracked. Ou seja, o git ta cagando e andando pra alteração que você fez. Então você precisa falar pra ele que todas as vidas importam, e todos os arquivos também.
Você pode fazer isso com:
`git add *`
Ou substituindo o asterisco pelo seu arquivo. E assim o tabu foi quebrado com sucesso
![](https://i.imgur.com/cXqeJQI.png)
5. Agora chegou a hora de *commitar* a alteracao que você fez.
\- Mas Caique, o que significa commit?
Não sei, e to com preguiça de abrir o google tradutor. Mas basicamente, o commit serve pra você salvar a alteração feita e adicionar uma mensagem pra identificar. Após isso você terá um histórico de todas as alterações feitas a cada *commit*, podendo acessar qualquer ponto desse histórico
Digitemos então:
`git commit -m "Fazendo alteração importante"`
ou então algo como
`git commit -m "kjashdkashdkahdl"`
Funciona da mesma forma.

6. É isso!!
Já criamos o repositório, clonamos pro nosso computador, criamos uma nova *branch*, fizemos alteração na pasta e commitamos a alteração. Agora falta subir isso pro GitHub e fazer o nosso tao esperado *pull request*.
Façamos então
`git push origin <nomeDaSuaBranch>`
![](https://i.imgur.com/iKBYBQ8.png)

Nesse passo, se for a sua primeira vez, você provavelmente precisará fazer login com a sua conta do github.

7. Voltando ao GitHub nos deparamos com a seguinte mensagem
![](https://i.imgur.com/MOOa2B6.png)
Bem, existe um quadrado amarelo gigante com um botão verde falando pra voce comparar e fazer um pull request. Acredito que eu não preciso dizer o que você precisa fazer agora...
Com o pull request criado, basta você ir em labels e adicionar a flag **hacktoberfest-accepted**
![](https://i.imgur.com/VY048sw.png)

E pronto. Após isso o seu PR está valido. Basta fazer isso mais 3 vezes para ganhar uma belíssima camiseta de graça (até pq ser de graça é o conceito de ganhar).
Após tudo isso (ou antes, tanto faz), basta ir no site da hacktoberfest (https://hacktoberfest.digitalocean.com/) e logar com a sua conta do github

No início desse tutorial a minha intenção era mostrar pra vocês como é fácil contribuir com um projeto alheio. Porém, agora q terminei eu percebi que expliquei apenas como fazer em um repositório de autoria própria, rssss.
Mas o processo para fazer PR em um repositório de outra pessoa é bem parecido. Caso tenha dificuldades pode me contatar no telegram (@caiqueff)

Apesar de parecer apenas uma forma fácil de ganhar uma camiseta, essa iniciativa do digital ocean serve justamente pra fazer com que pessoas ousem tentar fazer uma contribuição e acabem aprendendo sem querer.
Foi assim comigo em 2016, eu ja programava algumas coisas mas tinha muito medo do git, pois pra mim parecia difícil (inclusive deixei passar a hacktober 2015). O incentivo de ganhar uma camiseta me fez tentar, e quando eu percebi já tinha aprendido o básico.

Vale lembrar também que o git faz muuuito mais coisas do que ta descrito aqui. Vale a pena aprender, existem diversos cursos pela internet afora. E se você pretende trabalhar com ciência de dados ou qualquer outra coisa relacionada à programação, você com certeza precisará usar git, e saber usar essa ferramenta já é um grande diferencial para um estágio, por exemplo.

Por fim, segue a minha linda coleção sem motivo nenhum pq sim:
![](https://i.imgur.com/FQvJrx9.png)