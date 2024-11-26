Ce code implémente une gestion simple de la heap en Rust dans un environnement #![no_std].
La structure Heap représente le tas mémoire avec deux pointeurs, heap_debut (début du tas) et heap_fin (fin actuelle).
La méthode creation initialise le tas en effectuant un appel système brk pour obtenir et étendre sa limite actuelle, 
tandis que extension permet d'ajouter 0x3000 octets au tas existant.
