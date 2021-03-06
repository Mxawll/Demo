# Demo
- Learning GitHub

# Working directory
- Todos os nossos arquivos
- Pode ser chamado de "Working tree"

# Stage area
- Preparação de nossos arquivos, para serem comitados
- Index
- Stage tree

# Repository (local)
- Banco de dados dos nossos arquivos
- Onde ficaram os pontos na história
- Histórico

# Comandos no git bash
- (toch + nome do arquivo) 
  Criar um arquivo

- (add .) 
  Adicionar todos os arquivos da stage area

- (-m "") 
  A mensagem do commit

- (add *. mais a extenção do arquivo) 
  Adiciona todos os arquivos com a extenção especificada

- (diff) 
  Para ver o que foi modificado nos arquivos rastreados

- (diff --staged) 
  Para pegar o que esta no staged area

- (diff --color-words) 
  Para ver quais palavras foram modificadas

- (mv) 
  Renomear arquivos
  (EX: git mv README.md MELEIA.md)

- (git commit --amend) 
  Para corrigir/mudar algo no ultimo commit, e apenas no ultimo
  (recomendado apenas para corrigir ou mudar algo sem importancia)

- (checkout + 7 primeiros caracteres do shaHEAD + -- + nome do arquivo)
  Para recuperar arquivos

- (clean -n) 
  Para ver quais arquivos vão ser removidos

- (clean -f) 
  Para remover de fato
  (REMOÇÃO PERMANENTE)

- (revert HEAD~posição do arquivo ou revert + 7 primeiros caracteres do shaHEAD) 
  Para reverter um commit/voltar no ponto da historia
  (a posição do aquivo conta de cima para baixo sendo o segundo commit -1 o terceiro -2 e assim por diante)

- (git log --oneline)
  Resumo dos arquivos do repositorio

- (git commit -am"")
  Para comitar algum arquivo, sem precisar passar pelo comando "add."
  (se for um arquivo novo, não funcionará)

- (git show + shaHEAD do arquivo)
  Para mostrar as alterações que o commit sofeu
  
- (git push)
  Faz o upload das mudanças do git para o github
  
- (git pull)
  Faz o download das mudanças do github para o git
