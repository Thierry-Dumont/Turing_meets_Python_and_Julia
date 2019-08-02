# Turing meets Python and Julia



### Théorème de l'Arrêt  (Turing Halting Theorem, 1936) en Python et en Julia.

(Apologize for using French; translation is easy, but I am lazzy).

##### Adapté de _The Unknowable_ de Gregory J. Chaitin.
(Springer, 1999, ISBN 981-4021-72-5).



Dans le livre cité ci-dessus G. Chaitin propose une démonstration en _Lisp_
du [théorème de l'Arrêt](https://fr.wikipedia.org/wiki/Probl%C3%A8me_de_l%27arr%C3%AAt) (ainsi que des démonstrations du théorème de Godel et de son théorème sur les _programmes élégants_, également en _Lisp_).

Il m'a paru plus accessible de donner des présentations en Python et en Julia, ces deux langages étant bien adaptés. Et puis c'est un exercice amusant !

#### Comment éxécuter ces programmes ?

Dans les deux cas, il s'agit de _notebooks jupyter_, ce qui permet d'obtenir une version discursive des programmes.

##### Installations préalables :


* Vous devez d'abord installer [jupyter](https://jupyter.org/), qui va nécessiter une installation basique de _python 3_.  
Le plus simple est d'utiliser _pip_ ou _conda_ selon vos préférences. Voir le [lien](https://jupyter.readthedocs.io/en/latest/install.html).

* Le notebook python a besoin du module _inspect_ (là aussi, pip ou conda sont vos amis).

* Pour le notebook Julia, vous devez d'abord installer... Julia. Le mieux est d'installer une version stable récente depuis le [site Julia](https://julialang.org/). Il faut ensuite installer [IJulia](https://github.com/JuliaLang/IJulia.jl), qui est le _noyau_ pour jupyter.

##### Exécution des notebooks:

Il suffit de lancer jupyter en ligne de commande  dans le répertoire où vous avez cloné ce _repository_:

```

>jupyter notebook
```
et voilà, la suite est évidente.

*Ne pas* tenter de visualiser les notebooks dans cette page github: ça ne foctionne pas (bug ?).
