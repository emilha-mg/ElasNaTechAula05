# ElasNaTechAula05
Atividade da Aula 05: explorando GIT e GitHub


Configurações de usuários:

    - git config --global user.name <usuario>: define nome do usuário;
    - git config --global user.email <usuario>: define email do usuário;
    - git config --global -l: lista as últimas configurações no terminal.

Comandos:

    - git init: inicializa um novo repositório;
    - cd <local>: acessa a pasta raiz do projeto;
    - git clone <repo url>: clona um repositório existente;
    - git add .: adiciona todos os arquivos na stage;
    - git commit -m 'mensagem': cria um novo commit com uma mensagem descrevendo o trabalho que foi feito no commit;
    - git commit -am ‘mensagem’: adiciona na stage e realiza commit;
    - git status: acessa o status;
    - git log: acessa o histórico dos commits realizados;
    - git checkout <codigo do commit>: acessa a versão de determinado commit;
    - git checkot master: volta ao estado atual;
    - git push: envia os arquivos para o repositório remoto;
    - git pull: busca e baixa o conteúdo de um repositório remoto para o repositório local.

Possíveis status dos arquivos:

    - tracked: o Git está controlando o ciclo de vida deste arquivo;
    - untracked: o arquivo ainda não foi 'rastreado';
    - modified: é o estado onde o arquivo sofreu alterações, ou seja, ele está diferente do último commit;
    - unmodified: o arquivo não tem modificações, se comparado com o último commit;
    - staged: o arquivo  está na staging area, ou seja, já foi endereçado e aguarda ser transferido ao repositório.
