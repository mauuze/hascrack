# hascrack
### A company stored a secret message on a server which got breached due to the admin using weakly hashed passwords. Can you gain access to the secret stored within the server?
Primero nos conectamos al servidor con el comando:
#### nc verbal-sleep.picoctf.net 50889
y nos sale lo siguiente:
#### N: 13868150610650392749719546306335318637724413151463364711719004413065525986789747088127629477487250011069125104573992075830924340408147286907089418653253842
#### e: 65537
#### cyphertext: 6500131210518921458930623065969211068631135690173411061552635583505865328808742923865718532151632302263929167908399002066016296281489390955704741528333909
Con la ayuda de dcoder identificamos que esta en cifrado RSA y con la misma herramienta desciframos la flag. \

<img width="860" height="485" alt="Captura de pantalla 2026-05-31 203808" src="https://github.com/user-attachments/assets/7eeb89a1-8586-447b-b550-553110209393" />

Y obtenemos la siguiente flag:
### picoCTF{tw0_1$_pr!m375129bb1}
Subimos la flag a picoctf y listo.
<img width="814" height="86" alt="Captura de pantalla 2026-05-31 184815" src="https://github.com/user-attachments/assets/da29e303-a7f0-45ac-99f6-c203f0226201" />


