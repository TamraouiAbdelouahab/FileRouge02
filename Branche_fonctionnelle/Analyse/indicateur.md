# Problème : 
    Le problème est que le responsable de la formation a du mal à vérifier et à enregistrer rapidement les reçus d’absence tout en restant équitable envers tout le monde
    Calculer sanctions

# Carte d'empathie
mindmap
  root((Responsable des Stagiaires))
    Entend
      Excuses comme des raisons de santé.
      Préoccupations sur la confidentialité.
    Dit
      Demande des justificatifs détaillés.
      Explique qu'il les saisit sur papier.
    Fait
      Vérification des justificatifs avant saisie.
      Enregistrement des absences dans le dossier étudiant.
    Voit
      Justificatifs remis par les stagiaires.

# Diagramme de cas d'utilisation générale : 
    
```Puml
    @startuml
    left to right direction

    actor Responsable

    rectangle Pkg_Gestion_absence {
    usecase "Gérer les justifications" as UC1
    usecase "Consulter les statistiques" as UC2
    }

    Responsable -- UC1
    Responsable -- UC2



    @enduml
```