# AIOC-linux-applications
Les possibilités infinies d'un BaoFeng couplé à un PC avec l'adaptateur AIOC.

Je suis un super-fan du BaoFeng UV5R qui est un bon petit bi-bande V/U doté d'une sensibilité correcte. Du coup, vu son prix très bas, il est le bienvenu pour implémenter beaucoup de systèmes et des prototypes en tout genre. Le point principal est bien sure d'arriver à le connecter à une machine pour faire un peu plus que des appels.*
Bonne nouvelle, il y a le superbe travail (en opensource) de Simon Küppers (https://github.com/skuep/AIOC) qui nous mets à dispo. un périphérique qui permet de connecter un UV5 ou tout autre compatible doté d'une entrée/sortie audio K9.

Ce périphérique installe une liaison USB entre un PC et le pocket. Le branchement de ce périphérique fait apparaitre sur le PC une nouvelle carte son (qui transporte le son en E/S vers le talki) et une liaison RS232 qui permet de faire la programmation (avec chirp) et de passer le talki en émission.

Dans ce repo, je vous présente tout les usages que j'ai pu mettre au point sous linux pour transformer un UV5 en super système de communication.

