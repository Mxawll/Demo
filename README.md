# Demo
- Learning GitHub

# Working directory
- todos os nossos arquivos
- pode ser chamado de "Working tree"

# Stage area
- preparação de nossos arquivos, para serem comitados
- index
- Stage tree

# Repository (local)
- banco de dados dos nossos arquivos
- onde ficaram os pontos na história
- histórico

# Comandos no git bash
- (toch) 
  criar arquivos

- (add .) 
  adicionar todos os arquivos modificados

- (-m "") 
  mensagem no ponto na história 

- (add *. mais a extenção do arquivo) 
  adiciona todos os arquivos com a extenção especificada

- (diff) 
  para ver o que foi modificado nos arquivos rastreados

- (diff --staged) 
  para pegar o que esta no staged area

- (diff --color-words) 
  para ver quais palavras foram modificadas

- (mv) 
  renomear arquivos
  (EX: git mv README.md MELEIA.md)

- (git commit --amend) 
  para corrigir/mudar algo no ultimo commit, e apenas no ultimo
  (recomendado apenas para corrigir ou mudar algo sem importancia)

- (checkout + 7 primeiros caracteres do shaHEAD + -- + nome do arquivo)
  para recuperar arquivos

- (clean -n) 
  para ver quais arquivos vão ser removidos

- (clean -f) 
  para remover de fato
  (REMOÇÃO PERMANENTE)

- (revert HEAD~posição do arquivo ou revert + 7 primeiros caracteres do shaHEAD) 
  para reverter um commit/voltar no ponto da historia
  (a posição do aquivo conta de cima para baixo sendo o segundo commit -1 o terceiro -2 e assim por diante)

- (git log --oneline)
  resumo dos arquivos do repositorio

- (git commit -am"")
  para comitar algum arquivo, sem precisar passar pelo comando "add."
  (se for um arquivo novo, não funcionará)

- (git show + shaHEAD do arquivo)
  para mostrar as alterações que o commit sofeu