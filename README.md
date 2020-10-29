# p2-reservia


Partie cours: du 18/09 au 01/10. 


1-PARTIE HTML


01/10/20 Découpage maquette + démarrage HTML 

02/10/20 Commencement Body: Header= insertion logo + nav

03/10/20 Commencement Footer.

04/10/20 Établissement de plusieurs sections + ancres (Héb.+ Act.)
         Recherche et insertion icones Font Awesome  
         
05/10/20 Section 1: Recherche (Barre de recherche + Filtres) 

07/10/20 Section 2: Hébergements

       Article 1: Hébergements à Marseille
       
       Article 2: Les + populaires
       
10/10/20 Section 3: Activités à Marseille

22/10/20 Header: Partie nav refaite suite à des bug rencontrés aux Media Queries. J'ai retiré le .signup ("s'inscrire") de la nav afin de mieux le disposer et pour           plus de facilités pour les résolutions tablettes et mobiles. 



2- PARTIE CSS

11/10/20 Insertion police Raleway

       Header:
       Position logo + nav et mise en forme. 
       Mise en couleur. Marges. 
       Suppression des puces, des barres de soulignement et insertion des effets au survol (bordure + couleurs) (:hover)
       Quelques problèmes de décallage rencontrés au survol (le site developer.mozilla.org m'a beaucoup aidé)
             
12/10/20 Section 1: Recherche
       Mise en forme titre + barre de recherche (icone, couleur de fond, bordure)
          
13/10/20 Mise en forme filtres, bug rencontré au survol (corrigé), modification de la taille + bordure

14/10/20 Mise en forme info-bulle 

        Section 2: Hébergements= Couleur de fond, taille bordure
	
        Article 1: Hébergements à Marseille= choix de disposition en grille (Je suis retournée sur developer.mozilla.org pour l'apprendre)
                 Grille 3fr=3colonnes, 2fr=2lignes, taille vignettes, bordures, mise en couleurs étoiles + effets au survol 		 
		 
16/10/20 Article 2: Les + pop.= Titre + icone taille et disposition
                 Disposition en grille. Mise en couleur fond, bordures, tailles, marges
                Bug rencontré: L'article 1 et 2 se chevauchent... Suite à la session avec mon mentor et aux différents conseils qu'il me donne, j'arrive à le                         corriger.
                Commencement de la section 3: tailles et disposition des vignettes non adaptées: À revoir.		
		
17/10/20 Section 3: Activités à Marseille= Section entièrement refaite. Disposition des 6 vignettes nth-child, ombres, bordures, tailles width + height revues +                          marges.

19/10/20 Footer=  Suppression puces et barres de soulignement, space-between, couleur fond.



3- Partie Responsive

20/10/20 Commencement de la partie responsive. 
         Recherche de renseignements sur les différentes résolutions 
         (Desktop de 1024 à 1200px; Tablette de 768 à 900px (portait) et de 900 à 1024px (paysage); mobile de 480 à 720px)
         
   Réso Tab.
   
         J'ai voulu commencé par le Header, j'ai rencontré plusieurs difficultés (esais de grid et flex non concluants). Je me suis donc résignée à commencer par le            Footer puis la section 3, la section 2 avec les héb puis les "+ pop.", les filtres et barre de recherche puis enfin terminer par le header.
	 
21/10/20 Footer: Mise en page: 1 colonne + width et height.

         Section 3: Activités à Marseille= Taille titre + disposition en 1 colonne, grid (1 colonne, 6 lignes), tailles + marges générales + vignettes.
	 
         Section 2: Modif taille bloc
	 
                    Article1: Hébergements à Marseille= Taille titre + disposition en 1 colonne, 6 lignes (grid), tailes + bordures, ombres, marges entre vignettes et                      marges de "Afficher plus".
		    		    
22/10/20 Section 2: Article 2: Les + pop.= Taille titre + disposition en 1 colonne, 3 lignes (grid), tailles + marges # + colomn-reverse (Les + pop. avant Héb.)

         Section 1: Filtres: Disposition colonne + wrap (élements à la ligne quand il n'y a plus de place). 
		   Correction d'un bug au survol des filtres		   
		   
        // ÉDIT DU 28/10: Icone LOUPE à intégrer dans la searchbar //
	
	
        Suite à la session avec mentor, je cherche et essaie plusieurs solutions pour mon Header.
	
25/10/20 Header: Refonte de la partie html= suppression du .signup de la nav pour plus de facilité afin de le disposer au même niveau que le logo puis les nav en                      dessous. 

         Reessaie de grid, cette fois, ça fonctionne! Vue du header comme une grille (2 colonnes, 2 lignes)
         Quelques soucis de marges, corrigés ensuite. 
         Effets au survol + bordure nav bottom (grise puis bleue au survol).
	 
28/10/20 Commencement de la partie responsive mobile. 
	Insertion icone loupe dans barre de recherche.
	
29/10/20 Correction d'un bug lié à l'insertion de l'icone Loupe dans la barre de recherche. 
	Partie responsive mobile OK
	Refonte de la partie responsive tablette, changements marges.
	Validator W3C: Sur la partie HTML= 2 Warning. CSS OK.
	
        
        
        
        
         
         
         
         

        
                
                

                 
       
       


