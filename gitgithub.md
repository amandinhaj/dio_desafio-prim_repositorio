# Introdução ao Git e ao GitHub

> Anotações sobre o que curso de Introdução ao Git e ao GitHub da DIO.

**Git** = sistema de versionamento de código distribuido.
- ajuda a criar e a monitorar diferentes versões do nosso código.
- **CLI (Command Line Interface)** = interagimos com ele por meio de comandos.


#### Alguns comandos ####
*(obs: alguns comandos são diferentes quando trabalhamos com o Windows ou o Linux. Por isso, a ordem de aparição será primeiro do comando do Windows e depois do Linux com uma **/** de separação)*
- dir/ls = mostra todas as pastas que há.
- cd =possibilita navegar entre as pastas que há.
  - ex: cd *nome da pasta* e depois dar dir/ls.
  - cd .. = voltar uma pasta.
- cls/clear = limpar o terminal. Deixa o ambiente de trabalho mais limpo.
- mkdir = cria uma pasta.
- git status = mostra se o arquivo é Unmodified, Modified ou Stoged.
> **Windows**
> - del *nome da pasta* = deleta apenas os arquivos, não a pasta.
> - rmdir *nome da pasta* = deleta a pasta e todos os arquivos dentro.
> 
> **Linux**
> - rm -rf *nome da pasta* = deleta a pasta e todos os arquivos.

> Se apertar TAB, ele alto completa o nome da pasta.
> EX: se escrever **cd w**, e apertar TAB, ele irá complementar para **cd windows** *(se tiver uma pasta com tal nome)*.



**SHA** = Algoritmo de Hash Seguro.
  - conjunto de funções hash criptográficas projetadas pela NSA.
    - Blods = contém os metadados do GIT + Sha 1.
    - Tree = armazena os blods e guarda o nome do arquivo + Sha 1.
    - Commit = tree + parente (último commit realizado) + autor + mensagem.
  - O SHA1 desse commit é o hash de toda essa informação.
  
  
  > Chave SSH = estabelece uma relação segura e criptografada entre o Git e o GitHub.
  > 
  > Token = relação segura.
  > 
  > Morkdown = arquivo que escreve de uma forma mais "humana" um arquivo HTML.
  > 
  > Git Init = cria repositorio o git.



#### Ambiente de Desenvolvimento ####
-> Work Directory.
-> Staging Area.
-> Local Reposity.
