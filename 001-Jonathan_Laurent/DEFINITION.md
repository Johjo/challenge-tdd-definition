
# TDD par Jonathan LAURENT

Bonjour, je suis [Jonathan LAURENT](https://www.linkedin.com/in/jonathan-laurent/) et voici ma définition de TDD. 

## Ma description de la méthode

Le Test Driven Development consiste à travailler à l'aide d'hypothèse les plus petites et simples possibles et de les valider ou invalider le plus rapidement possible. Chaque fois que l'on valide ou invalide une hypothèse, on obtient un feedback qui nous permet de mieux comprendre le système.

TDD repose donc sur les concepts d'hypothèses, de feedback, de simplicité et de vitesse.

Le processus est très simple. Il y a 3 lois à suivre : 

1. Vous devez écrire un test qui échoue avant d’écrire tout code de production
2. Vous ne devez pas écrire plus d’un test suffisant pour échouer, ou qui échouera à la compilation
3. Vous ne devez pas écrire plus de code que nécessaire pour faire passer le test en cours

On lui associe aussi le cycle RED - GREEN - REFACTORING. 

L'étape RED sert à proposer une hypothèse sur quelque chose que le code ne fait pas.
L'étape GREEN sert à proposer une hypothèse pour résoudre le problème proposé en RED
L'étape REFACTORING sert à proposer une hypothèse d'un code plus adapté

![TDD - cycle red green refactoring](https://johjo.github.io/blog-collectif-ytreza/blog/posts/feedback_rules_the_world_part_2/tdd-red-green-refactoring.svg)

### Ma pratique

Ici, je vais parler de la pratique à l'état pur. Il y a bien entendu des exceptions qui viennent la modifier. Je reste disponible pour en discuter.

Je respecte littéralement les 3 lois de TDD.
- Je commence par écrire un test.
	- Cela signifie que j'utilise le code avant même de l'avoir écrit. Si j'ai besoin d'une fonction, je l'utilise avant qu'elle ne soit créée.
- Je m'arrête d'écrire le test, même s'il n'est pas terminé, dès qu'un échec du test est rencontré.
	- Si une fonction n'existe pas, c'est un échec
	- Si une classe n'existe pas, c'est un échec
	- Si une assertion échoue, c'est un échec
- Dès qu'un échec est rencontré, j'analyse sa signification et j'en déduis la prochaine tâche
- Je réalise cette tâche et uniquement cette tâche jusqu'à ce que le test arrête d'échouer et que les autres continuent de passer.
- Je supprime tout le code qui ne fait pas échouer au moins un test.
- J'améliore si besoin le code tant que cela ne fait pas échouer de test
- Je supprime à nouveau tout le code qui ne fait pas échouer au moins un test.
- Je continue l'écriture de mon test s'il n'est pas terminé ou j'en commence un autre

Pour donner un ordre d'idée, je lance les tests plusieurs fois par minute, toutes les 15 - 20 secondes. 

----
### Les avantages à cette pratique

Le principal avantage est le fait de réduire drastiquement la charge cognitive :
- On ne fait qu'une seule chose à la fois
- On le fait très très vite
- On sait quand ça commence, on sait quand ça se termine
- Les tests nous disent littéralement ce qu'il faut faire, à condition de savoir les interpréter

Si l'on s'en tient à cette définition, TDD est une pratique que l'on peut utiliser tout le temps. Je m'en sers comme d'un socle accueillant mes autres compétences (testing, refactoring, design du code, etc...). Celles-ci ont une excellente synergie et plus je progresse, plus je deviens fluidre.

Je suis l'une des rares personnes à considérer TDD comme une silver bullet parce que je n'attends qu'une chose de TDD, c'est de fractionner mon travail.

### Ce que n'est pas le Test Driven Development

- TDD ne vous permet pas de faire des choses que vous ne savez pas faire.
- TDD ne vous guide pas dans le design du code. Par contre, il vous récompense quand vous progressez dans cette pratique.
- TDD ne sert pas à tester. Ce n'est pas parce que vous faîtes du TDD que vous aurez de bons tests. Par contre, TDD vous récompense quand vous savez correctement tester
- TDD n'est pas compliqué à apprendre. Il suffit de savoir lire et suivre les 3 lois de TDD. Ce qui est compliqué, c'est d'apprendre le refactoring, le design du code, le testing, etc...

### Transparence

Afin d'être transparent, voici quelques éléments qui pourraient entraîner des biais : 
- Je suis pro-TDD et je l'utilise en permanence
- Je forme les gens à cette pratique, je cherche donc à ce qu'il y ait plus de personnes qui la pratiquent
- Je suis développeur professionnel depuis 2006
- Je pratique TDD depuis 2017
- Je me suis formé seul mais j'ai été inspiré par d'autres personnes qui pratiquent
