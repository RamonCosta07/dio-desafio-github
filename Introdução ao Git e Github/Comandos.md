#	Prompt de comando (Windows)

o	Dir: no prompt de comando ele serve para listar todas as pastas

o	Cd: permite que navegue entre as pastas

o	Cd .. : Para voltar um diretório

o	Cls: limpa a tela do terminal

o	TECLA TAB: serve para completar quando começa a digitar o nome de uma pasta

o	Mkdir nome da pasta: serve para criar uma pasta

o	Echo frase: Printa na tela uma frase digitada

o	Echo frase > arquivo.txt: Irá criar um arquivo com esse nome (caso não exista) e guardar a frase nele

o	Del “mais arquivo ou pasta”: Irá apagar todos os arquivos de uma pasta ou um arquivo específico. Porém, ele não apaga a pasta em si

o	Rmdir nome da pasta /S /Q: Apaga de fato todo o diretório (pasta)

#	Prompt do Git

o	Abrir o terminal do Git em qualquer pasta que esteja: Clicar com o botão direito do mouse na pasta e ir em “Git Bash Here”

o	Sha1: Conjunto de caracteres único de 40 caracteres para cada modificação de um arquivo

o	ls: listar as pastas daquele diretório

o	ctrl + l: limpar a janela

o	git init: Para que o git comece a versionar e gerenciar o código, criando um repositório do git

o	ls -a: Ver pastas ocultas, incluindo a própria pasta criada com o git init

o	git config –global user.email “meu email”: Configurar o e-mail para utilizar o git

o	git config –-global user.name MEU USER: Configurar nickname para utilizar o git

o	git add *: Preparar o arquivo modificado para receber um commit

o	git commit -m “um texto”: comitar o arquivo modificado, incluindo um texto (mensagem) daquela modificação

o	git status: Ver o status daquele arquivo, se já foi comitado ou se tem algo a ser comitado ainda

o	mv PASTA OU ARQUIVO ./NOME DO REPOSITÓRIO QUE QUER MOVER/: Irá mover arquivo de uma pasta para outra

o	git remote add origin LINK DO REPOSITÓRIO DO GITHUB: Linkar os comites já realizados com o repositório do github. Origin é apenas um apelido

o	git remote -v: Ver os repositórios que ele está apontado

o	git push origin main: Empurrar os comites para o github. Lembrando que origin é o apelido que demos ao criar o remote

o	git pull origin master: Vai puxar a versão mais recente que existe no github

* Pode haver um conflito, se um mesmo arquivo no github foi alterado por terceiros numa mesma linha, e você o alterou em sua máquina local também. O conflito surge justamente na hora do push

o	Git clone URL DO REPOSITÓRIO: clonar para a máquina pelo terminal um repositório do GitHub. Deve utilizar, na hora de copiar o link, a aba de SSH



o	git branch NOME DA BRANCH: Ramificação de trabalhar no master antes de alterar o original, caso alguém esteja mexendo ao mesmo tempo

o	git branch -l: Mostra a master principal e todas as branchs iguais ao repositório da Master

o	git checkout NOME DA BRANCH QUE IRÁ TRABALHAR: Seleciona a branch que irá trabalhar

o	git merge NOME DA BRANCH QUE IRÁ PARA MASTER: Após selecionar a master como brench, tudo que estará na outra branch irá para a master

o	git checkout -b NOME DA BRANCH QUE IRÁ CRIAR: Irá criar uma branch ao mesmo tempo que muda para ela

o	.gitignore: Ao criar um arquivo exatamente com esse nome, podemos setar bibliotecas que queremos ignorar para comitar. Ao escrever o nome dela dentro do arquivo .gitinore. Por exemplo: node_modules

o	git log: Histórico de todos os comites feitos

o	git stash: Salvar o que está fazendo em um repositório temporário sem perder as alterações



Obs. Redmi é como se fosse um arquivo que seria a página inicial do nosso repositório, incluindo nele anotações, links úteis, etc.
