# Dictionnaire de Données Basé sur le MCD

## Entités et Attributs

### Livre
| Nom de l'Attribut     | Type de Données | Description                                   |
|-----------------------|-----------------|-----------------------------------------------|
| ID_Livre              | Entier          | Identifiant unique du livre                   |
| Titre                 | Texte           | Titre du livre                                |
| Date_Publication      | Date            | Date de publication du livre                  |
| ISBN                  | Texte           | Numéro ISBN unique du livre                   |

---

### Emprunteur
| Nom de l'Attribut     | Type de Données | Description                                   |
|-----------------------|-----------------|-----------------------------------------------|
| ID_Emprunteur         | Entier          | Identifiant unique de l’emprunteur            |
| Nom                   | Texte           | Nom de l’emprunteur                           |
| Prénom                | Texte           | Prénom de l’emprunteur                        |
| Adresse               | Texte           | Adresse de l’emprunteur                       |
| Téléphone             | Texte           | Numéro de téléphone de l’emprunteur           |
| Email                 | Texte           | Adresse e-mail de l’emprunteur                |

---

### Emprunt
| Nom de l'Attribut     | Type de Données | Description                                   |
|-----------------------|-----------------|-----------------------------------------------|
| ID_Emprunt            | Entier          | Identifiant unique de l’emprunt               |
| Date_Emprunt          | Date            | Date à laquelle le livre a été emprunté       |
| Date_Retour           | Date            | Date de retour prévue du livre                |
| Date_Retour_Effectif  | Date            | Date de retour réel du livre                  |

---

### Auteur
| Nom de l'Attribut     | Type de Données | Description                                   |
|-----------------------|-----------------|-----------------------------------------------|
| ID_Auteur             | Entier          | Identifiant unique de l’auteur                |
| Nom                   | Texte           | Nom de l’auteur                               |
| Prénom                | Texte           | Prénom de l’auteur                            |

---

### Catégorie
| Nom de l'Attribut     | Type de Données | Description                                   |
|-----------------------|-----------------|-----------------------------------------------|
| ID_Categorie          | Entier          | Identifiant unique de la catégorie            |
| Nom_Categorie         | Texte           | Nom de la catégorie                           |

---



