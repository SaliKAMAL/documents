# Documents — Proxy cache HTTP/HTTPS pour Kameleon

Dépôt des documents du projet de stage INFO4
Polytech Grenoble — Laboratoire IMAG, UGA — 2024-2025

## Contenu

- `Rapport_projet_https_proxy.pdf` — Rapport technique complet
- `Rapport_gestion_projet.pdf` — Rapport de gestion de projet

## Projet

**Titre** : Intégration d'un proxy cache HTTP/HTTPS dans Kameleon

**Outil** : Kameleon 2.11.1 — remplacement de Polipo par mitmproxy 11.x

**Client** : Laboratoire IMAG, Université Grenoble Alpes

**Code** : https://gricad-gitlab.univ-grenoble-alpes.fr/kamals/https-proxy

**Période** : Janvier — Mars 2025

## Résultats clés

- Cache HTTP et HTTPS via mitmproxy (MITM)
- Replay complet sans réseau depuis archive .tar.gz
- Validé avec iptables DROP — Exit 0, 1 seconde
