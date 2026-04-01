# Simulare-de-trafic-rutier

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


 
