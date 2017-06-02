## backup

<blockquote>
#!/bin/bash


#senha PGADMIN
export PGPASSWORD="123123"

#código
pg_dump -U postgres -h localhost -O -o -b -F c padawan > /home/yoda/Documentos/bercario.backup


#mensagem
echo echo "Realizado o backup está."
exit 
</blockquote>


## Restore

<blockquote>
#!/bin/bash

export PGPASSWORD="123123"

pg_restore -U postgres -h localhost -d padawan /home/yoda/Documentos/padawan_backup


echo echo "May the force be with you."
exit 

</blockquote>
