# Meu Caderno de Estudos - Piscina 42


# Comandos do terminal Linux (Navegação e arquivos)

pwd   = Print Working Directory - mostra a pasta atual, o caminho completo da pasta a qual eu estou agora.
ls    = serve para me mostrar o nome e arquivos da pasta atual, se estou em uma pasta atual e quero ver todos os nomes do arquivos e pastas que estão dentro da pasta atual eu uso ls
ls -a = serve para mostrar todos os arquivos e itens da pasta atual, mas neste caso, inclusive  os ocultos. Ocultos são aqueles que começam com um . exemplo: .ssh
cd    = change directory - me leva para para dentro de uma pasta existente, exemplo cd nomedapasta.
mkdir = cria se uma nova pasta que antes não esxistia, ex: mkdir piscina_42, make directory = criar novo diretorio/pasta vazia no lugar onde eu estou, então devo sempre observar onde estou, qual pasta quero criar com comando mkdir.
touch = Tocar - Cria um arquivo novo vazio (ou atualiza a data/hora de um arquivo existente).
echo ...>  = Ecoar - imprime um texto e, com o simbolo > reireciona esse texto para dentro de um arquivo (criando ou substituindo o conteúdo).
Cat   = abre um arquivo de texto e imprime o conteúdo dele na tela do terminal
nano  = é um editor de texto simples para fazer anotações fora a parte (crtl+o para gravar as informações e crtl+x para sair)


# Comando so Git (controle de versão e nuvem)

git init = inicializar - Transforma a pasta atual em um repositório monitorado pelo git.
git  status = situação - Mostra quais arquivos foram criados ou modificados desde o ultimo registro salvo.
git add = adicionar - Prepara os arquivos escolhidos para entrarem na procima fotografia commit.
git commit = resgitrar - salva uma fotografia permanente das alterações no histórico local com uma mensagem descritiva.
git push = empurrar - envia os registros salvos no computador para o repositorio remoto na nuvem (github) usando suas chaves SSH (secure shell - concha segura)

