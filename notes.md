Ao iniciar uma nova api podemos dar o comando de npm init -y. Esse comando inicia um projeto básico e elimina a necessidade de confirmações de configuração.

Outra possíbilidade é instalar alguns módulos com a flag -D, con isso ele cria dep^}encias de desinvolvimento do projeto,
mas quando for feito a build ou deploy esses modeulos não são usados. Um comando para iniciar seria:

npm i -D @types/node tsup tsx typescript

E por último, devemos inatalar o Fastify com o comnando npm i fastify (Em produção)

Ai instalar modulos em desenvolvimento podemos criar um arquivo npmrc com o comando save-exact=true com isso quando essa aplicação for ser usada em outro desenvolvimento
os pacotes serão os mesmos usados.

Dentro do arquivo package.json na parte de depnecnisas, temos um acento cincurflexo, ele indica que a versão a ser baixada é listada ou superior, mas o recomendando é remover para que seja baixado a versão exata.