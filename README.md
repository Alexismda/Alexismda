```mermaid
graph TD
    A[Achats - Anne-Sophie<br>1300/mois<br>≈60/jour] -->|60/jour| B[Tests Entrée Benoit Matin<br>60/jour<br>= 2 cartons]
    B -->|60/jour × 5 jours = 300/semaine| C[Réparations<br>250-300/semaine<br>Testés, nettoyés]
    C -->|60/jour| D[Tests Sortie Benoit Après Midi<br>60/jour<br>50 validés + 20% retours]
    D -->|60/jour| E[Mise en Stock<br>60/jour<br>RAS]
    E -->|Jusqu'à 60/jour| F[Expédition<br>60/jour<br>+2 réassorts/semaine]
    F -->|Retours| G[SAV<br>Traitement sous 3 jours<br>Courriers + partenaires]
    G -->|Retours à tester| B
    style A fill:#FF6B6B,stroke:#2C3E50,stroke-width:2px
    style B fill:#4ECDC4,stroke:#2C3E50,stroke-width:2px
    style C fill:#45B7D1,stroke:#2C3E50,stroke-width:2px
    style D fill:#96CEB4,stroke:#2C3E50,stroke-width:2px
    style E fill:#FFEEAD,stroke:#2C3E50,stroke-width:2px
    style F fill:#D4A5A5,stroke:#2C3E50,stroke-width:2px
    style G fill:#9B59B6,stroke:#2C3E50,stroke-width:2px
