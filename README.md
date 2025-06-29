# Simple processor

The goal of this project is to build a simple 8 bit processor using logisim-evolution in order to understand how one works.

The recomended outline for this project is described in the `Memento_Processeur_8bits_Logisim.pdf` file

![8 bit full adder](https://raw.githubusercontent.com/themarcman314/logisim_processor/refs/heads/master/images/full_adder.png)


Actuellement les blocs suivants du processeur ont été réalisés :

## Unité Arithmétique et Logique (UAL) 
- [ ] Une UAL capable de réaliser les opérations suivantes : 
  - [x] Addition 
  - [x] Soustraction 
  - [x] ET logique (AND) 
  - [x] OU logique (OR) 
  - [x] Décalage à gauche (SHL) 
  - [x] Décalage à droite (SHR) 
## Registres 
- [x] Deux registres principaux (A et B) de 8 bits chacun. 
- [x] Un registre de sortie (OUT) de 8 bits. 
## Unité de Contrôle 
- [ ] Une unité de contrôle avec un décodeur pour interpréter les instructions. 
- [ ] Un ensemble d’instructions de base (chargement, stockage, addition, soustraction, etc.). 
## Mémoire 
- [x] Une mémoire de 256 octets (8 bits par case mémoire). 
## Bus de Données 
- [ ] Un bus de données de 8 bits reliant les différentes unités. 
