# Document  de collaboration pour la traduction en Francais
Si vous souhaitez aider à traduire, vous pouvez: 
- choisir un document pas encore traduit/en cours de traduction en vous ajoutant dans ce fichier (faites une PR directement).
- seconde traduction: relire une traduction qui n'a pas eu de relecture et aider à fermer les [points ouverts](Pointsouverts)  
- vers la fin: faire des check de qualité et d'affichages (la traduction en francais aura plus de mots que la version anglaise)

|   | Traduit | Relecture  | Check qualité final |
|---|---------|---|----|
| index.html head  | [X] @cyrilou242  |   | |
| index.html  footers | [X] @e-guenat |   | |
| index.html sidebars  |    |   | |
| /pics  |     |   | |
| sharing/thumbnail.png  |     |   | |
| sharing/thumbnail.png  |     |   | |
| [words/words.md](words/words.md)  |  [voir ci-dessous](words/words.md)   |   | |

## words/words.md
La traduction de words.md est séparée en partie. Vous pouvez prendre plusieurs parties à la fois.
Ne pas changer le nombre de lignes en traduisant. (ie ne pas rajouter/supprimer de retour à la ligne).  

|   |Lignes | Traduit | Relu  |Check qualité |
|---|---|------|---|----|
| Misc |[L1-L23](https://github.com/cyrilou242/covid-19/blame/master/words/words.md#L1-L23) |[X] @cyrilou242  |   | |
| Intro |[L25-L41](https://github.com/cyrilou242/covid-19/blame/master/words/words.md#L25-L41) | [X] @cyrilou242  | [X] @donok1  | |
| LastMonths: Curves | [L43-L153](https://github.com/cyrilou242/covid-19/blame/master/words/words.md#L43-L153) | [X] @cyrilou242   | [X] @e-guenat  | |
| LastMonths: R | [L155-L237](https://github.com/cyrilou242/covid-19/blame/master/words/words.md#L155-L237)| [X] @e-guenat | [X] @cyrilou242  | |
| NextMonths: Scénario 0-3  | [L239-L359](https://github.com/cyrilou242/covid-19/blame/master/words/words.md#L239-L359) |  [X] @e-guenat | [X] @maximebedoin  | |
| NextMonths: Scénario 4  | [L361-L471](https://github.com/cyrilou242/covid-19/blame/master/words/words.md#L361-L471) | [X] @kephas |   | |
| NextMonths: Scénario 4+  | [L473-L573](https://github.com/cyrilou242/covid-19/blame/master/words/words.md#L473-L573) | [X] @cyrilou242 | [X] @donok1  | |
| NextYears  | [L575-L682](https://github.com/cyrilou242/covid-19/blame/master/words/words.md#L575-L682) | [X] @e-guenat | [X] @cyrilou242  | |
| The Now  | [L684-L711](https://github.com/cyrilou242/covid-19/blame/master/words/words.md#L684-L711) | [X] @e-guenat | [X] @cyrilou242  | |

Dans vos MR, ne pas s'occuper de la génération de words.html et du copy/paste dans index.html. 
Je le ferai de manière régulière, cela permettra de s'assurer que le markdown to html est toujours réalisé par le même programme.

## Points ouverts
*Si vous avez des doutes pendant votre traduction ou faites des choix qui 
nécessitent quelques explication, ajoutez les ici. Cela facilitera la relecture.*
La relecture doit fermer tous les points ouverts d'une partie. 


### Intro |L25-L41
- L25: maybe cite - _Franklin D. Roosevelt_
- L27: had to take some liberty to translate the toilet paper example making the 
link to roosevelt sentence meaning understandable   
- L27-L29 reduced canalised and fear - canaliser et peur usage, sounds very repetitive in french. rewrite again.
- L32 - fix contact tracing -> suivi de contacts
- L35 - precise published in english and add link 
- L35  - faire peur to keep IMO
- L35 - plan b ou plan de secours. Plan B sounds like nicky IMO
- L39 convaincus for confiant may be discussed
- L39 Epidemiologie 101 will not be understood sound French --> initiation à l'épidémiologie
- L96 Just remember that in reality, some are dead --> "Mais garde en tête que la réalité est bien plus dure." sounds more respectful in French imo, et prends en compte à la fois mort et lésions irréversibles. To discuss
- L96 let's pretend --> "supposons" 

### LastMonths: Curves

### LastMonths: R
- L213: choisi le système français pour l'analogie avec les notes d'école.

### Scénario 4+
- L477 overshoot --> "débordement" ? Utilisé dans les parties précédentes pas encore traduites. "  

### Next years and Now
l.107: reduced the use of *month* to ease the readability in french
l.134 : choose to translate *builder* by *fabricants*. Best word so far to match the following higher-order repetition of *build* emphasizing the whole paragraph and its impact.

## Choix de traductions
Ajoutez des choix de traduction de mots/expressions spécifiques qui doivent rester les mêmes dans toutes la traduction ici.
Cela devrait être fait dès que possible en repérant les expressions spécifiques.

- Infectious people: les individus Infectieux 
- Suspectible people: les individus Susceptibles (de contracter la maladie) 
- Start (for simulations images): Lancer. Utiliser *réaliser* ou *lancer* en fonction.  
- technical caveats: limites techniques
- Epidémiologie 101 : Initiation à l'épidémiologie
- <icon i></icon> Infectious people --> les individus Infectieux <icon i></icon> . Noter l'inversion de l'ordre pour l'image.
- contact tracing  : traçage des contacts
- ICU : [unité(s) de] soins intensifs
- ventilators : respirateurs
- privacy-protecting [as an ADJ] : respectueuse de votre vie privée (à la place de *respectueuse de vos données personnelles*) 
- Exponential decay: décroissance exponentielle 

- What happens next ? : Et ensuite ?
- COVID-19 : COVID-19
- Test, Trace, Isolate : Tester, Tracer, Isoler
- 2 tiers : deux tiers
- virgule comme séparateurs décimal
- interval de confiance: IC
- Guillemets à la française à travers tout le document: "" : «∙Ceci est une citation∙», avec un espace insecable entre la citation et les guillemets 

- contextual notes: If title of an article or quote, I leave it in English and added a translation as the end of the note, as follows:
[^keyword]: «∙quote EN∙» [from REF](URL) Traduction: «∙quote FR∙»

## Get last update from nicky
TODO On May 4th: get last updates from nickys project and stop at this version.

## Traduire /pics
- retrouver les polices utilisées dans les images (contacter nicky si besoin)
- rédiger les traductions dans le fichier [pics/PICS_TRANSLATION.md](pics/PICS_TRANSLATION.md), et les valider, avant de les appliquer dans les images 

|   |  Traduit | Relu  | Appliqué à l'image |
|---|---|------|---|
| dp3t.png |  |  | [X] DP-3T github project |
| exponential.png | |   |   |
| graphs_q.png | aucun texte |  | [X] |
| masks.png | |  |   |
| mitigation_vs_suppression.png  |  |  |   |
| plan.png  |  |  |   |
| r.png  | aucun texte |  | [X] |
| r2.png  |  |  |    |
| r3.png  |  |  |    |
| r4.png |  |  |    |
| seir.png |  |  |    |
| seirs.png |  |  |    |
| sir.png |  |  |    |
| spread.png |  |  |    |
| susceptibles.png |  |  |    |
| timeline1.png |  |  |    |
| timeline2.png |  |  |    |
| timeline3.png |  |  |    |
