# Objectifs

On fait l’étude sur la modélisation de la croissance en diamètre (en cm) d’un arbre au sein d’une forêt. Xk (k correspond à une année) est le diamètre (en cm) à l’instant k, la suite X0, X1, · · · , Xk (encore notée (Xk)k≥0) est un processus (de Markov) qui modélise l’évolution annuelle du diamètre d’un arbre. Le diamètre à l’instant k dépend de celui des instants k − 1 et k − 2, ainsi, la loi de transition vers Xk, ∀ k ≥ 2 est inspirée d’un modèle de croissance celui de Gompertz [Gom25] et peut s’ ́ecrire comme suit :

Xk = D^(1-exp^(-r)) x ( (X[k-1] + X[Xk-2]) / 2 )^(exp^(-r)) x εk-1 pour k≥2

où r et D représentent respectivement le taux de croissance et le diamètre maximal d’un arbre. Dans la suite, prendre r = 0.3 et D = 150 cm. εk est le bruit du modèle et on suppose qu’il peut être modélisé par la loi exponentielle (de paramètre θ) de densité :


f(x) = 0 si x<0 ou θexp−θx si si 0 ≤ x.

On suppose que X0 et X1 sont choisit de telle sorte que le vecteur (X0,X1) suit une loi multi- normale N (μ, Q) car les arbres sont généralement inventoriés à partir de 10 cm. Pour simuler une réalisation de cette loi.

