Meu primeiro README
Respostas das questões:

1- https://github.com/LucasCscBks/my_first_steps.git

2- entrei na pasta que eu criei e apertei com o botão direito do mouse e selecionei gitbash here, para abri o git bash já
dentro da pasta, depois digitei a linha de comando abaixo:
- git init
- git remote add origin https://github.com/LucasCscBks/my_first_steps.git

3- criei o arquivo usando o bloco de notas normal,depois digitei as linhas de comando abaixo:
- git add ola_mundo.txt
- git commit -m "Meu primeiro COMMIT"
- git push -u origin master

4- -touch .gitignore (para criar o arquivo gitignore)
depois criei o arquivo no bloco de notas normal serei_ignorado.txt
   -nano .gitgnore 
e escrevi dentro do gitignore "serei_ignorado.txt"
ctrl X pra sair, Y pra confirmar a alteração
pronto, quando procurei agora no git status não apareceu mais o serei_ignorado.txt
   -git add . (para adicionar o .gitignore para ser comitado)
   -git commit -m"Comitando meu git ignore"
   -git push (para enviar as modificações para o repositório remoto)
   
5- -touch Readme.md (primeiro comando pra criar o arquivo Readme)
Depois usei o notepad para editar o arquivo e inserir as respotas das questões.
   - git add Readme.md
   - git commit -m "Vai README"
   - git push
   