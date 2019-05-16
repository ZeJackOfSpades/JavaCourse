# Contrôle de connaissance 1

### 1. Quels sont les principaux objectifs du langage JAVA ?
> 1. Simple, orienté objet et familier
> 2. Robuste et sûr
> 3. Indépendant de la machine employée pour l'exécution
> 4. Très performant
> 5. Compilé, multi-tâches et dynamique

### 2. Donnez la définition d’un LOO
> Langage Orienté Objet (LOO) : Langage informatique où l’on
peut définir des objets, c’est-à-dire des instances de classes,
manipulables dans un programme informatique ;
Pour qu’un langage soit considéré comme pure LOO il doit respecter les
règles suivantes :


### 3. Que doit respecter un langage pour être considéré comme pur LOO (6 points en tout) ?

> 1. L’encapsulation / « Data hiding »
> 2. L’héritage
> 3. L’abstraction
> 4. Tous les types prédéfinis sont des Objets
> 5. Tous les types définis par l’utilisateur sont objets
> 6. Toutes les opérations effectuées sur des Objets doivent être
réalisées uniquement via les méthodes visibles des Objets en question.


### 4. Est-ce que Java est un LOO pur ? Expliquez pourquoi
> Tout est-il vraiment instance de classe ?
> * Il existe des types primitifs,
> * et aussi des méthodes et membres de classes statiques.
> Java n'est donc pas un LOO Pur.

### 5. Expliquez le concept du « write once, run everywhere » :
#####	a. A quoi sert le compilateur Java ?
#####	b. A quoi sert l’interpréteur ?
> * Le langage Java est un langage semi interprété.
> Les sources sont compilés en byte code
> => javac présent dans le JDK

> * Le byte code est interprété et executé par la JVM.
> => Java Virtual Machine présent à la fois dans
> le JRE et le JDK

### 6. Donnez la définition d’une classe
> Une Classe en langage Java, est donc la définition d'un type
d'objet. Cette définition se fait au travers de la création d'un fichier
« .java » compilé en « .class ».
Des classes peuvent être considérées comme des types
personnalisés.

### 7. Donnez la définition d’instanciation
> L'instanciation est l'action d'instancier, de créer un objet à
partir d'un modèle (=la classe). Elle est réalisée par la
composition de deux opérations : l'allocation et
l'initialisation.

### 8. Donnez la définition du mot clef « this »
> * « this » : désigne, dans une classe, l'instance
courante de la classe elle-même.

### 9. Ecrivez votre propre application qui affichera le texte suivant : « Hello World ! (Votre Nom) ».

```java
public class HelloWorld{
	public static void main ( String[] args ) { 
		System.out.println("Hello World ! Jacques");
	}
}
```

### 10. Indiquez les lignes de commandes pour exécuter cette application. (On considère ici que nous n’avons pas d’environnement de programmation intégré).

> 1. Compilation du fichier source HelloWorld.java : `javac HelloWorld.java`
> 2. Execution du programme HelloWorld : `java HelloWorld`
