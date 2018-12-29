<!-- TITLE: Eines Seguiment Errors -->
# Cirrus CI
Flutter utilitza Cirrus CI, ja que, permet fer el cicle de desenvolupament més ràpid, eficient i segur aprofitant la moderna tecnologia de *cloud computing*.
Cirrus CI escala amb l'equip i fa el desplegament del software ràpid i barat.

## Configuració de Flutter a Cirrus CI

Flutter configura CirrusCI per a que comprovi que totes les *pull requests* siguin vàlides, és a dir, que passin totes les proves correctament, abans d'acceptar-les. A més una vegada ha comprovat que les incorporacions noves de codi a la branca "master" són correctes, automàticament realitza una release a la secció de *releases* de github.
Tenir aquesta configuració facilita la **detecció d'errors**, de forma fàcil i eficient, en el cicle de desenvolupament. 
A continuació es mostra una captura de l'eina Cirrus CI amb les últimes compilacions de flutter

![Cirrus CI flutter](/uploads/captura.png "Cirrus CI flutter")
# Codi obert

El fet que el codi de Flutter sigui visible per a tot el món també facilita la **detecció d'errors**, ja que, com més persones inpeccionin el codi, més possiblitats hi ha de trobar *bugs*.

