# Réponses — chasse au trésor

<!-- Format imposé, une réponse par ligne :
Q01: <réponse>
commande: <commande(s) utilisée(s)>
-->

Q01: 32
commande: git rev-list --count depart

Q02: Sarah Benali
commande: git blame src/format.js

Q03: c95def0
commande: git log -S "seuil" --oneline src/stock.js

Q04: sk_live_01de6ba0c9f4d846
commande: git show 9fa1b7d:.env

Q05: 11544ab
commande: git log --oneline --full-history -- .env

Q06: 17
commande: git rev-list --count v0.2.0..v1.0.0

Q07: essai-perf
commande: git tag -l --format='%(refname:short) %(objecttype)'

Q08: experiment/cache-redis
commande: git branch -a --no-merged main

Q09: src/utils.js
commande: git log --follow --oneline --name-status src/outils.js

Q10: Nathan Robin
commande: git shortlog -sn depart

Q11: 2026-03-24
commande: git log -1 --format="%cd" --date=short v1.0.0

Q12: feat(cli): bannière de démarrage
commande: git log --grep="Revert" --oneline

Q13: de5637a
commande: git log --oneline --grep="fix/valeur-totale"

Q14: 16
commande: git diff --numstat v0.1.0 v1.0.0 -- src/stock.js

Q15: 6d6b920
commande: git log -S "TODO: gérer les quantités négatives" --oneline
