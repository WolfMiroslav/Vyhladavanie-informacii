
Script parsuje id, mena v inych jazykoch, pohlavie, vysku, datum
narodenia,miesto narodenia, príbuznych, rodicov a profesiu entity 
Person pomocou Hadoop a Pig z databazy Freebasu. Vystup je ulozeny 
v usporiadanom súbore, v ktorom su jednotlive informacie oddelene 
tabulatormi.


Spustenie: Script sa spusta v Grunte prikazom:

exec -param input=cesta_ku_vstupu/nazov_suboru	-param
output=cesta_kde_bude_vystup/nazov_priecinka	cesta_ku_scriptu/parser


teda najskor sa zadaju parametre a potom cesta ku scriptu ktory spustame.
