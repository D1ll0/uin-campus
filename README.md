# UIN-Campus

Système de gestion académique de l'UIN (squelette du projet fil rouge, TP 2).

## Versions des outils relevées

| Outil | Version |
|-------|---------|
| g++ | 15.2.0 |
| clang++ | 21.1.8 |
| cmake | 4.2.3 |
| ninja | 1.13.2 |
| gdb | 17.1 |
| git | 2.53.0 |

Environnement : Ubuntu dans une machine virtuelle VMware.

## Commandes de construction

    cmake --preset debug
    cmake --build --preset debug
    ./build/debug/uin-campus

Résultat attendu :

    UIN-Campus — Système de gestion académique
    Version 0.1.0
