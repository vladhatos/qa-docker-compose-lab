Importanta folosirii -v in docker compose down:
docker compose down -v : Oprește și șterge containerele ȘI volumele asociate. Este utilă pentru a garanta un mediu complet curat (o bază de date goală) la începutul fiecărei runde de teste.
-v : folosit pentru a si sterge volumele