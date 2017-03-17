# Formularios XML
__Autor__: Guillermo Cirer  
Proyecto de formulario con autocorrección mediante _html, css y JavaScript_.

# Modificaciones respecto al proyecto anterior (Repostiorio FormulariosXML):
1) Modifica l'accés a l'objecte xmlDoc (corresponent al document xml llegit) per obtenir les opcions de tipus select, select multiple, checkbox i radio. L'accés s'ha de fer mitjançant Xpath. Modifica les funcions posarDadesHtml per llegir els nodes que surten de la cerca amb Xpath. (Nivell: fàcil)
(fins a 3 punts)

2) Crea questions.xsl i modifica el fitxer (o fes una còpia) questions.xml per posar l'enllaç a questions.xsl de tal forma que si obris directament el fitxer questions.xml el navegador fa una transformació simple per presentar les preguntes, totes les opcions i les respostes a una taula. (Nivell: fàcil)
(fins a 3 punts)

3) Inclou codi per forçar a l'usuari a respondre totes les preguntes. (Veure aplicació d'exemple) (Nivell: mitjà)
(fins a 2 punts)

4) Modifica el codi per que l'aplicació faci la correcció personalitzada modificant l'objecte xmlDoc i mostrant-ho amb una XSLT al client. Js farà només el càlcul de la nota final i ho mostrará després dels resultats. (Nivell: difícil)
(fins a 2 punts)

5) Aprofita per millorar la presentació, especialment per donar estil a la taula resultant de la XSLT.
(fins a 2 punts)
