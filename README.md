# backup_mysql
Script para backup Mysql/MariaDB via Dump
Eventualmente pode ser necessário criar rotinas de backup para bancos mysql/mariadb, sendo assim disponibilizo abaixo um script que verifica todas as bases existentes numa instância mysql/mariadb e realiza o backup individual e compactado, facilitando assim a restauração individual de cada banco caso haja essa necessidade.

obs.: Para o script funcionar corretamente é necessário inserir o nome de usuario com permissão de administração dos bancos(o usuário admin da instância), senha, e localização dos backups, a váriavel VALIDADE_DIAS informa por quantos dias os arquivos serão mantidos, nosso caso abaixo é definido 5 dias.

** Também não é garantida a execução com sucesso em qualquer ambiente, esteja preparado para testar o script num ambiente de testes ou acrescentar possíveis ajustes.
