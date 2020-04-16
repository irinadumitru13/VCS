# VCS
Version Control System - Java

## Descriere generala
Acest proiect reprezinta o proprie implementare a unui sistem de versionare de fisiere tip
github, mai putin comanda de merge. Proiectul se bazeaza pe folosirea pattern-urilor
Singleton, Factory si Visitor.
Proiectul contine atat comenzi de fisiere, cat si comenzi specifice VCS.

## Comenzi de filesystem
Acestea fac parte din scheletul temei.

## Comenzi de VCS
Contine o clasa pentru fiecare operatie:
- BranchOperation
- CheckoutOperation
- CommitOperation
- InvalidVcsOperation
- LogOperation
- Status Operation
In plus, clasa Branch a fost creata pentru a se putea retine toate informatiile necesare unu branch,
iar clasei Vcs i-au fost adaugate diferite campuri si metode, aceasta fiind responsabila de buna
functionare a VCS-ului.
