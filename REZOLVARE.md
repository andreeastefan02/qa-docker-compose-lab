Rezolvare

1. Tabelul tests in Adminer

Tabelul tests a fost creat cu succes.

<img width="2070" height="1072" alt="image" src="https://github.com/user-attachments/assets/aaaff7a3-c6d5-473f-a08f-aae5b5321525" />



2. Importanța flag-ului -v

Folosirea flag-ului -v la comanda docker compose down -v este importanta într-un flux de lucru QA deoarece elimina si volumele asociate containerelor, inclusiv datele persistente ale db-ului. Practic resetam mediul si pornim pe curat, de ce avem nevoie sa pornim pe curat? Deoarece uneori cand baza de data este plina de teste, si ne dorim un test specific este mai ușor sa verificam pe curat, de exemplu corectitudinea datelor care ajung in baza de date.
