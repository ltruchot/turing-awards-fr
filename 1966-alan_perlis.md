# Alan J. Perlis

Américain - 1922 - 1990

Premier informaticien à recevoir Prix Turing à sa création en 1966


**Raison**: influence dans domaine des techniques de programmation avancée et construction de compilateurs


**Résumé**: Pionnier, co-créateur ALGOL, formalisation informatique et premiers cursus informatique universitaires aux USA

## Biograhie
- né le 1er avril 1922 à Pittsburgh, Pennsylvanie (N-E USA)
- à 20 ans, prépa de Chimie au Carnegie Institute of Technology, Pennsylvanie
- pendant 2ème guerre mondiale, 1942 à 45
  - lieutenant météorologue pour les forces de l'air US
  - officier météo et renseignement pour les forces de l'air  UK
- après guerre:
  - Licence de Chimie au California Institute of Technology à L.A., mais passion pour les maths (S-O)
  - Master de Maths au M.I.T à Boston (N-E) à 27 ans
  - PhD de Maths à 29 ans, sujet: fonctions complexes - résolution d'équations intégrales par l'itération et le prolongement analytique 
- après étude, à partir de 1951:
  - Recherche sur la ballistique et la défense aérienne sur la côte Est, passage au MIT
  - Bosse sur l'ENIAC (Electronic Numerical Integrator And Computer), le tout premier ordinateur électronique... entouré de femmes mathématiciennes (computers - voir hidden figures), les premières personne à programmer le l'histoire
  - ENIAC, 30t, Turing-Complet, construit à la fin de la guerre: 100 000 additions par secondes (38 divisions) - calcul de la trajectoire d'un tir en 3s (contre 3 jours pour une équipe humaine)
  - travaux sur d'autres super computers
- Dès la fin dès années 50, création de langages
  - Purdue University (Indiana N-E) et Carnegie .I.T (Pennsylvanie), Perlis dévelope son premier langage IT (Iternal Translator), pour le Datatron et l'IBM 650: un "compilateur d'expressions mathématiques" (proche de Fortran, et concurrent pour machine plus petite)
  - Pour le compte de l'ACM (Association for Computing Machinery), contribution au premier langage indépendant des machines: ALGOL-60 (Algorithmic Language)

#### Hello world avec ALGOL (autre nom, ALGOL-60)
```ALGOL
BEGIN
  FILE F(KIND=REMOTE);
  EBCDIC ARRAY E[0:11];
  REPLACE E BY "HELLO WORLD!";
  WRITE(F, *, E);
END.
```
(EBCDIC Extended Binary Coded Decimal Interchange Code - 8bits pour carte perforées)

ALGOL est un language:
- procédural
- impératif
- types statiques
- compilé (peu pertinent)
- pas d'I/O (à implémenter selon les ordinateurs)
- commentaires, structures de contrôle, variable et scope, procedures (incomplètes)...
  
Invente notion de bloc, et par extension la récursion dans ces blocs et la notion de "variable locale"

- des années 60 à 70, en plus de ses recherches, le quarantenaire est très investit dans les universités et l'ACM pour créer un science informatique: computer science, formaliser le parcours, les programmes scolaires et et les diplômes... principalement financé par l'ARPA (Advanced Research Projects Agency de la défence américaine).
- Ambassadeur d'ALGOL à l'international, mais aussi d'APL, son langage favori


#### Hello world avec APL
```APL
'Hello World!'
```

Enfin de 70 à 1990
- professeur d'informatique à l'université de Yale (Connecticut - N-E)
- décède le 7 février 90 alors qu'il est encore en activité

## Citations choisies
- L’informatique est gênée par les ordinateurs.
- Les systèmes ont des sous-systèmes, et les sous-systèmes ont des sous-sous-systèmes et ainsi de suite à l’infini − c’est pourquoi nous recommençons toujours de zéro.
- Quand nous écrivons des programmes qui « apprennent », ce qui arrive c’est que nous apprenons, et eux pas.
- Il y aura toujours des choses que nous aimerions dire dans nos programmes, mais qui ne peuvent être que mal dites avec tous les langages connus.
- Il est plus facile de changer la spécification pour qu’elle corresponde au programme que le contraire.
- le meilleur livre grand public sur la programmation est « Alice au Pays des Merveilles », mais c'est parce que c’est le meilleur livre pour le profane sur tous les sujets.
- Un programme sans boucle et sans structure de donnée ne vaut pas la peine d’être écrit.
- C’est mieux d’avoir 100 fonctions travaillant sur une seule structure de données que 10 fonctions pour 10 structures.
- En programmation, tout ce que nous faisons est un cas particulier de quelque chose de plus général − et souvent nous nous en apercevons trop vite.
- Un programmeur LISP connaît la valeur de tout, mais le coût de rien.
- Enseigner la programmation va à l’encontre de l’éducation moderne : Quel est le plaisir à planifier, se discipliner à organiser ses pensées, faire attention aux détails et apprendre à être autocritique ?

## Biliographie choisie
- [1960 - Symbol manipulation by threaded lists](https://dl.acm.org/doi/10.1145/367177.367202)
- [1977 - In praise of APL: a language for lyrical programming](https://www.jsoftware.com/papers/perlis77.htm)
- [1982 - Epigrams on Programming](https://web.archive.org/web/19990117034445/http://www-pu.informatik.uni-tuebingen.de/users/klaeren/epigrams.html)

## Sources
https://amturing.acm.org/award_winners/perlis_0132439.cfm
https://en.wikipedia.org/wiki/Alan_Perlis
https://aplwiki.com/wiki/Alan_Perlis
https://fr.wikiquote.org/wiki/Alan_Perlis
https://en.wikipedia.org/wiki/ALGOL




