# Simulare-de-trafic-rutier
# Simulare Trafic Rutier - Proiect POO C++

Acest proiect reprezintă o simulare de vehicule care se deplasează pe o rețea de străzi, implementată în C++ utilizând principiile Programării Orientate pe Obiecte.

##  Cuprins
- [Descriere](#descriere)
- [Funcționalități](#funcționalități)
- [Structura Claselor](#structura-claselor)
- [Cerințe de Sistem](#cerințe-de-sistem)
- [Instalare și Compilare](#instalare-și-compilare)
- [Utilizare](#utilizare)
- [Autori](#autori)


#  Descriere
Aplicația simulează interacțiunea dintre diverse tipuri de vehicule (Mașini, Motociclete, Camioane) într-o rețea rutieră formată din străzi și intersecții. Accentul este pus pe gestionarea polimorfică a vehiculelor și logarea evenimentelor (intrări/ieșiri din intersecții, coliziuni).

#  Funcționalități
- **Ierarhie de Clase:** Utilizarea moștenirii pentru definirea comportamentelor specifice fiecărui tip de vehicul.
- **Sistem de Logging:** Toate evenimentele din trafic sunt salvate într-un fișier extern/consolă.
- **Gestiune Resurse:** Utilizarea STL (`std::vector`, `std::list`) pentru managementul obiectelor din rețea.
- **Validare:** Teste unitare simple pentru verificarea logicii de deplasare.

#  Structura Claselor (UML Simplificat)
- `Vehicul` (Clasă Abstractă)
  - `Masina`, `Motocicleta`, `Camion` (Clase Derivate)
- `ReteaRutiera` (Gestionar principal - Compoziție)
- `Strada` și `Intersectie` (Elemente de infrastructură)

#  Cerințe de Sistem
- Sistem de operare: Linux (sau WSL pe Windows)
- Compilator: `g++` (suport C++11 sau mai nou)
- Build Tool: `Make` sau `CMake`

#  Instalare și Compilare

1. Clonează repository-ul:
   ```bash
   git clone [https://github.com/utilizator/proiect-trafic.git](https://github.com/utilizator/proiect-trafic.git)
   cd proiect-trafic
