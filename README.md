## backup-and-restore

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
