## PhD candidate

- Name: Mr. Tianyi Li
- LinkedIn profile: [https://www.linkedin.com/in/tianyikillua](https://www.linkedin.com/in/tianyikillua)

## PhD work

- Title: Gradient-damage modeling of dynamic brittle fracture: variational principles and numerical simulations
- Keywords: dynamic brittle fracture, gradient damage models, phase-field, theoretical analyses, variational methods, parallel implementation, numerical simulations, FEniCS, EuroPlexus

## Related documents

- Github repository where you can also LaTeX source files of the manuscript: [https://github.com/tianyikillua/thesis-manuscript](https://github.com/tianyikillua/thesis-manuscript)
- Presentation PDF file: [here](https://drive.google.com/file/d/1FRWKTQaRgNCm5vlq-bt_kZCwO43oshyK/view?usp=sharing): for videos, open the file with Adobe Reader and make sure that Flash Player is installed. Verified under Windows and Mac.

## Public defense

- Date: Thursday, October 6, 2016, at 14:00 CEST (or at 08:00 EDT in New York; at 21:00 JST in Japan)
- Place: [ENSTA ParisTech](https://www.ensta-paristech.fr), Amphitheater R111 on the ground floor

In the main building of the ENSTA ParisTech, arrows and posters will then indicate the PhD defense room.

**Please make sure that you fill in [this form](https://goo.gl/forms/acUx5EucMcr12YZx2). Your name will then be transferred to the ENSTA ParisTech for your access to the main building that day.**

### Jury composition

Name             | Title              | Affiliation  | Role
---------------- | ------------------ | ------------ | ----------
M. Alain COMBESCURE | Professeur émérite | INSA de Lyon | Rapporteur
M. Corrado MAURINI  | Professeur | Université Pierre et Marie Curie | Rapporteur
M. Gilles  FRANCFORT | Professeur | Université Paris-Nord | Examinateur
Mme Laura DE LORENZIS | Professeur | TU Braunschweig | Examinateur
M. Jean-Jacques MARIGO | Professeur | Ecole Polytechnique | Examinateur
M. Gilles DAMAMME | Directeur de recherche | CEA/DAM | Examinateur
M. Serguei POTAPOV | Ingénieur de recherche | EDF Lab Paris-Saclay | Examinateur
M. Daniel GUILBAUD | Ingénieur de recherche | CEA Saclay | Invité

### Access information

The location of the ENSTA ParisTech with respect to the Paris region and two airports

![](https://raw.githubusercontent.com/tianyikillua/phd-thesis/gh-pages/images/paris.jpg)

Zoom of the ENSTA ParisTech location

![](https://raw.githubusercontent.com/tianyikillua/phd-thesis/gh-pages/images/zoom.jpg)

[Google Maps location](https://goo.gl/maps/wMibfypBCy12) for the ENSTA ParisTech

![](https://raw.githubusercontent.com/tianyikillua/phd-thesis/gh-pages/images/ensta.jpg)

#### From downtown Paris or the Charles-de-Gaulle airport

Detailed access information can be found [here](https://www.ensta-paristech.fr/en/getting-ensta-paristech) from the website of the ENSTA ParisTech.

Using public transportation, you could

- Take the RER line B, direction `Massy-Palaiseau` or `St-Rémy-lès-Chevreuses` or `Orsay`, and descend at the train station `Massy-Palaiseau`
- Then take the 91-06B/C or 91-10 buses and descend at the stop `ENSTA - Les Joncherette` (approximately 10 minutes). **Please kindly confirm with the driver that the bus will stop at the ENSTA**.  For your convenience, you can find [here](http://www.albatrans.net/wp-content/uploads/2012/01/Albatrans-91.06-C-D.pdf) the time table for 91-06C and [here](http://www.albatrans.net/wp-content/uploads/2012/01/Albatrans-91.06-A-B-91.10.pdf) for 91-06B and 91-10
- Count about 1 hour from downtown Paris and 2 hours from the CDG airport

To transfer from RER B to the bus at the train station `Massy-Palaiseau`, please refer to the following diagram.

![](https://raw.githubusercontent.com/tianyikillua/phd-thesis/gh-pages/images/massy.png)

#### From the Orly airport

- Either take the Orlyval metro line to `Antony` and then take the RER B line to `Massy-Palaiseau` and then follow the steps described above
- Either take a taxi

#### From the EDF Lab Paris-Saclay

You can take any 91-06B/C or 91-10 buses (direction Massy) at the stop `Palaiseau Campus` just in front of the EDF building. Descend at the stop `ENSTA - Les Joncherette` (4 stops from EDF, approximately 5 minutes). For your convenience, you can find [here](http://www.albatrans.net/wp-content/uploads/2012/01/Albatrans-91.06-C-D.pdf) the time table for 91-06C and [here](http://www.albatrans.net/wp-content/uploads/2012/01/Albatrans-91.06-A-B-91.10.pdf) for 91-06B and 91-10. Maybe the best option is to take the 91-06C at 13:19.

#### From the CEA Saclay

You can find [here](https://goo.gl/maps/S1habJYs1dE2) the driving directions given by Google (approximately 11 minutes)

## Abstract of the PhD work

### Version française

Une bonne tenue mécanique des structures du génie civil en béton armé sous chargements dynamiques sévères est primordiale pour la sécurité et nécessite une évaluation précise de leur comportement en présence de propagation dynamique de fissures. Dans ce travail, on se focalise sur la modélisation constitutive du béton assimilé à un matériau élastique-fragile endommageable. La localisation des déformations sera régie par un modèle d'endommagement à gradient où un champ scalaire réalise une description régularisée des phénomènes de rupture dynamique. La contribution de cette étude est à la fois théorique et numérique. On propose une formulation variationnelle des modèles d'endommagement à gradient en dynamique. Une définition rigoureuse de plusieurs taux de restitution d'énergie dans le modèle d'endommagement est donnée et on démontre que la propagation dynamique de fissures est régie par un critère de Griffith généralisé. On décrit ensuite une implémentation numérique efficace basée sur une discrétisation par éléments finis standards en espace et la méthode de Newmark en temps dans un cadre de calcul parallèle. Les résultats de simulation de plusieurs problèmes modèles sont discutés d'un point de vue numérique et physique. Les lois constitutives d'endommagement et les formulations d'asymétrie en traction et compression sont comparées par rapport à leur aptitude à modéliser la rupture fragile. Les propriétés spécifiques du modèle d'endommagement à gradient en dynamique sont analysées pour différentes phases de l'évolution de fissures : nucléation, initiation, propagation, arrêt, branchement et bifurcation. Des comparaisons avec les résultats expérimentaux sont aussi réalisées afin de valider le modèle et proposer des axes d'amélioration.

### English version

In civil engineering, mechanical integrity of the reinforced concrete structures under severe transient dynamic loading conditions is of paramount importance for safety and calls for an accurate assessment of structural behaviors in presence of dynamic crack propagation. In this work, we focus on the constitutive modeling of concrete regarded as an elastic-damage brittle material. The strain localization evolution is governed by a gradient-damage approach where a scalar field achieves a smeared description of dynamic fracture phenomena. The contribution of the present work is both theoretical and numerical. We propose a variationally consistent formulation of dynamic gradient damage models. A formal definition of several energy release rate concepts in the gradient damage model is given and we show that the dynamic crack tip equation of motion is governed by a generalized Griffith criterion. We then give an efficient numerical implementation of the model based on a standard finite-element spatial discretization and the Newmark time-stepping methods in a parallel computing framework. Simulation results of several problems are discussed both from a computational and physical point of view. Different damage constitutive laws and tension-compression asymmetry formulations are compared with respect to their aptitude to approximate brittle fracture. Specific properties of the dynamic gradient damage model are investigated for different phases of the crack evolution: nucleation, initiation, propagation, arrest, kinking and branching. Comparisons with experimental results are also performed in order to validate the model and indicate its further improvement.
