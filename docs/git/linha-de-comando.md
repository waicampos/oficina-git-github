# Linha de comando

馃敆 Mais informa莽玫es sobre linha de comando [link](https://git-scm.com/book/pt-br/v2/Come%C3%A7ando-A-Linha-de-Comando)

O Git pode ser usado de duas formas:
   1. GUI - Graphical User Interface - Programas com interfaces gr谩ficas;
   2. CLI - Command Line Interface - Linha de comando.

  Nesta oficina ser谩 utilizado a linha de comando:
  - A linha de comando 茅 o 煤nico lugar onde se pode rodar todos os comandos do Git;
  - Usando a linha de comando pode facilmente rodar vers玫es GUI.


  ## Comandos b谩sicos no terminal git bash.

  馃敆 Mais informa莽玫es sobre comandos no [link.](https://guialinux.uniriotec.br/)

- cd (change directory) - usado para mudar o diret贸rio de trabalho:
   
   Para ir ao diret贸rio do usu谩rio do sistema:
  
      $ cd ~/
  
   
   Para ir em um diret贸rio filho: 
  
      $ cd nome-do-diret贸rio
    
   Para voltar ao diret贸rio pai: 

      $ cd ..


- ls (list) - lista o conte煤do de um diret贸rio:

   Lista o conte煤do do diret贸rio atual:
  
      $ ls

   Lista o conte煤do do diret贸rio especificado:
  
      $ ls nome-do-diretorio
  

- mkdir (make directory) - cria diret贸rios:
   
   Criar um diret贸rio dentro do diret贸rio atual
  
      $ mkdir nome-do-diretorio
  
   Criar um diret贸rio dentro de outro diret贸rio. A tag -p ou 鈭掆垝parents cria hierarquia de diret贸rios:
  
      $ mkdir -p nome-do-diretorio/subdiretorio
  
- rm (remove) - comando que remove arquivos. Para apagar um arquivo:  

  Para apagar um diret贸rio e todo o seu conte煤do. A flag -r apaga os arquivos e subdiret贸rios. A tag -f apaga sem pedir confirma莽茫o:
      
      $ rm -rf nome-do-diret贸rio
  

- clear (limpa) - Para limpar o conte煤do da tela do terminal:

      $ clear