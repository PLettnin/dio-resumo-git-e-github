# Patrick Resumo Git GIThub     


 GIT  ( https://git-scm.com/ )
        - é uma sistema de controle de versão distribuido;
        gratuito e open source;
        leve rapido; 
        raminficaçôes e fusões eficientes; 

        - git clone = clona um repositório Git existente para uma novo arquivo (pasta) local
        - git commit = grava as laterações no repositório;
        - git pull = "puxa" as alteraç~eos do repositório remoto para o local (busca e mescla);
        - git push = envia as alteraç~eos do repositório local para o remoto;
        - git init = cria pastas
        - rm -rf . xxx= para remover pasta
        - git status = ver status, se for modificado volta msgm, 
        - git restore =recupera ultino vez que foi salvo (git restore XXXX.xx)
        - git commit --amend -m"adiciona mensagem gitignore e diretorios aulas e resumo" ou 
        - git commit --amend + enter, vai abrir o editor, + tcl inserir + alterar o que precisa , para sair tcla ESC dois PTOS W para escrever e Q para sair;
        - Git add  . 
        - Git commit -m"mensgema do novo commit
        - Git reset ( caso não queira refazer msgm do commit, e sim desfazer,) opções ( soft/mixed/hard) + codigo do commit
        soft :
        mixed : altera para area de trabalho e aguarda preparação
        hard :
        - git reflog - detalhes dos commit
        - git add = apos criar os arquivos aula-01 e aula-02, se der um status vai ficar vermelho, falta inserir na preparação, dar comando ( GIT ADD .) posteriormente git status;
        - PARA REMOVER ARQUIVOS
           git reset XXXX.xx nome do arquivo  
           ou comando git restore --staged resumo/aula-01.md 
        
        
       

Site (https://github.com/PLettnin/hello-world)

##📖 documentos
- [Documentos Git] (https://git-scm.com/docs)
- [Documentos GitHub] ( https://docs.github.com/pt )


## 👩‍💻Comando
Lista de comandos no Git... ( https://git-scm.com/docs/git#_git_commands )
- git status  = lista o status do arquivo
- git commit -m" commit inicial "= cria commit com mensangem que aparece entre aspas, preparando para salvar
- git log = mostra que foi criado e por quem 
- mkdir xxxxx = cria uma nova pasta xxxx nome da pasta a ser criada (OBS se der um git status, não vai aparecer nada, vazio, isso pq ele não reconhe arquivos/pasta vazio; para corrigir precisa criar uma arquivo)
- exemplo para criar arquivo; touch resumos/resumo-aula1.md
- gitignore = para ocultar pastas arquivos 
- gitkeep = comando que faz reconhecer algum diretorio vazio, e seja mostrado no git status;
- 
## Enviando e Baixando com o Repositario remoto - 

 - git remote add origin https:xxxxxxxxxxxxxxx ( completar com o link, para comentar o local com o github)
 - git push -u origin main // responsavel por enviar os comando repositario local para o remoto, atualiza pagina vai atualizar o github com os arquivos local.
 - outra forma de editar os arquivos no repositório, no guihut, utilizando a tecla PONTO "." do teclado; 
      -  precisa estar logado
      - clicar no PONTO
      - vai abrir um visual code online; 
      - editar os arquivo desejado;
      - opção de visualizar alterações, clicando botão direito no arquivo, ABRIR VISUALIZAÇÕES;
      - 
   - git pull // no repositorio local, para baixar as atualizações realizadas no repositorio remoto (GIT HUB/ Visual code);

## Branches (Ramo)
 - ramificações;
   - para adicionar um projeto novo ao projeto em execução, sem interferir no principal;

 - exemplo;

    - um projeto em execução, tenha duas ou mais pessoas trabalhando/acessando, poderia confitar, se cada um tiver uma branches, cada uma trabalha na sua, e pode testar o seu recurso;

                              
    - commit0 < commit1 < commit 2
                           teste
   
   - comandos
      - git branch -v  //para as branch
      -echo "#commit -XXX-brach-YYYY" > commit-brach-YYYY.txt // criar uma branch 
      - checkin XXXX // para entrar numa branch XXXX
      - checkout main // para voltar para main
      - git merge XXXX // mescla a branch XXXX com as branches aparece pasta
      - git branch // para lista as branche, * branch que estamos
      - git branch -d XXXX  // DELETAR a brach XXXX






## 🖨💻 Resumo da aula

| aulas | Resumo|
|-------| ------|
|tokens | configurações (lado direito)/configurações de desenvolvedor(lado direito)/fichas classico para gera e ver quandon expira o token; |
|-------| ------|
| Gravando alterações no REPO |resumo  ()|


...

git init

