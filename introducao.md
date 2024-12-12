#   Razões para aprender 

Interface gráfica é disperdício de desempenho de processadores , memória ram.  Ubuntu é um sistema operacional debian porém com outras configurações.
O terminal de comandos a ser utilizado é o bash.

##  Comandos iniciais

*   Abra o terminal de comandos no debian. 

1.  Comando de manual, para ser mandado para página de manual desse ls -> man ls
2.  Outra maneira de acessar ajuda a -> ls --help
3.  Para tornar-se um superusuário, digitar o comando e colocar a senha do super usuário -> su
4.  Para voltar para o usuário comum -> exit
5.  Tornar-se um super usuário com su, e utilizar o parametro apt -> apt install sudo . Sendo que sudo é o nome do pacote a ser instalado.
6.  Comando que atualiza o repositório -> apt update
7.  Comando -> apt upgrade
8.  Com o sudo instalado -> usermod -aG sudo nome_usuario (Coloca o usuário num grupo chamado sudo) . E agora esse grupo contém usuários que rodam comandos como se fossem o superusuário