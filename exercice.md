EXERCICE 1 : **La famille**
 1. mkdir cli_tmp
 2. touch cli_tmp/ je_suis_dans_cli_tmp.txt
 3. cd cli_tmp/
  
        touch in_cli_tmp.txt
4. mkdir in_cli_tmp
5. rm je_suis_dans_cli_tmp.txt
6. cd ..
       rm -r cli_tmp/
 7. mkdir grand_parent parent grand_frere  grande_soeur ami connaissancecd grand_frere
 8. cd grand_frere
 9. touch bachir
 10. mv bachir ../ami
11. cd ..

        cp -r ami parent
 12. rm parent/ami/bachir
 13. pwd
 14. cd ~
 15. rm -r cli_tmp

 EXERCICE 2: **Mon Conteneur**
1. pwd
2. ls
3. mkdir conteneur
4. mkdir conteneur/voitures conteneur/ustensiles conteneur/electronique
5. touch conteneur/voitures/mes_voitures.txt
6. echo "benz toyota honda" >> conteneur/voitures/mes_voitures.txt
7. cd conteneur/ustensiles
8. echo "couteau tasse cuilleur" >> conteneur/ustensiles/cuisines.txt
9.  cd ..
10. ls -alt


EXERCICE 3: **Le journal**
1. pwd 
2. ls
3. mkdir -p actualites/politiques 
4. mkdir actualites/politiques/elections
5. echo "tanja issoufou kader" >> actualites/politiques/elections/candidats.txt 
6. mkdir  actualites/buzz


 EXERCICE 4 **Le Dessin**
1. pwd
2. touch .configuration_caché
3. LS
4. mkdir -p creation/crayons
5. touch creations/crayons/couleurs.txt
6. cp creations/crayons/couleurs.txt creations/crayon/colors.txt
7. touch creation/gomme.txt
8. mv creation/gomme.txt  creations/crayons/
9. cd ~
10. cd creation/

 EXERCICE 5 **Ma classe**
1. mkdir ma_classe
2. echo "eve moctar esaie rachide" >> mes_camarades.txt
3. cat mes_camarades.txt 
4. touch .surveillant_cahé
5. ls -a
6. mr .surveillant_cahé 
7. rm -r ma_classe/

 EXERCICE 6 **L'aquarium**
1. brew install asciiquarium
2. asciiquarium

 EXERCICE 7 **Le Train**
1. brew install sl 
2. sl 

 EXERCICE 8 **Le matrix**
1. brew install cmatrix
2. cmatrix
