## Básico do git
<img src="./images/git icon.png" width="60px">

Após instalar, é preciso configurar o usuário, o nome e o email e a Ide para desenvolvimento. A baixo esta a lista dos comandos e sua sintaxe:

`git config --global user.name"Seu nome" `

`git config --global user.email "email@email.com" `

No terminal, use:

`git init`

Isso irá adicionar o git ao seu projeto, talvez você não saiba, mas esse comando cria uma pasta oculta chamada ".git"

Após isso, você deverá adicionar algum arquivo ao projeto, usando o comando:

`git add .` OBS: o "." adicionará todos os arquivos da pasta onde você estiver, mas você pode colocar o nome do arquivo após o "."

Para que essas alterações sejam salvas é necessario enviar um commit, seguindo um dos dois modelos a baixo:
Mesmo após você fazer a adição dos arquivos usando o "git add .", para salvar-los, deve utilizar:
`git commit -a -m ""` o '-m "" ' é para você adicionar um nome ao commit, e o '-a "" ' é para você adicionar uma descrição ao commit (não é preciso usar o -a ou -m)

Também é possível ver o histórico dos commits, usando:

`git log` ou `git log --oneline`

Se você quiser saber se os commits estão sincronizados com os arquivos, apenas digite:

`git status`


Quando você ficar preso no console, na maioria dos terminais é só utilizar ctrl + c, que você fecha o sistema

Para criar uma branch, basta usar:

`git branch -M ""`

O -M "", diferentemente do commit, estará adicionando um nome a Branch

É possível comparar as diferenças de um arquivo no git e em outro lugar com o comando:
`git diff --nome`

Para retornar ao ultimo commit, basta usar:
`git checkout HEAD -- arquivo.tipo`
