# GIT – GITHUB
## Comandos básicos do UNIX / WINDOWS
- Limpar tela – clear / cls
- Apagar diretório e seus arquivos rm - rf “diretório” (r = recursive e f=force apaga subpastas e arquivos) / rmdir “diretório” /S /Q
- Caminho completo atual – pwd
- Exibir todos os arquivos incluso ocultos – ls - a
### Informações:
Utiliza o SHA1 como encriptação – 40 caracteres 
##Objetos básicos
- Blobs – Metadados do arquivo. Possui tipo, tamanho do arquivo \0  em seguida o conteúdo do arquivo
- Tree – Armazenam os blobs e outras árvores. Contém os metadados dos blobs.
- Commit – Combinação de blob e tree. 
## Chaves SSH e Token
- SSH – Conexão segura com computador remoto. Assinatura do computador de origem do acesso.
- Criar  chave ssh -  ssh- keygen - t ed25519 (tipo de chave) - C “e- mail da conta do git”
o	Crie um password
- Inserir no site do git a chave criada. Cat id_...pub
- Iniciar o agente – eval $(ssh- agent - s)
- Passar para o agente a chave privada -  Ssh- add id... (sem pub)
- Token são chaves de acesso temporárias 
## Comandos básicos GIT
- Git init – inicializar o git
- Git config - - global user.email “email” em seguida git config - - global user.name -  configurar primeira utilização do repositório de forma global
- Git add * – adiciona os todos os arquivos do diretório para área pronta para o commit
- Git commit -  Precisam de mensagem de texto
## Criando conexão git -  github
- Git remote - v – lista os repositórios remotos cadastrados
- Git remote add origin (origin é apenas um apelido para não utilizar depois o link do repositório remoto) “url do repositório”
- Git status – verifica os status de arquivos do projeto
- Git push “apelido” “branch” – enviar os dados para o repositório remoto
- Git pull origin master – tenta realizar a união dos arquivos do projeto


