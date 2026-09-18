# Guide utilisateur
## Gestion des comptes utilisateur : 

### Connexion modérateur **compte de test** : 
email : sophie.martin@example.com
mot de passe : modo123

### Connexion administrateur **compte de test** : 
email : jean.dupont@example.com
mot de passe : admin123

### Connexion livreur **compte de test** : 
email : lucas.bernard@example.com
mot de passe : deliver123

### Connexion utilisateur **compte de test** : 
email : thomas.moreau@example.com
mot de passe : customer456

### Inscription :
1. Aller sur inscription 
2. Rentrer les informations d'identification 

> [!NOTE]
> Pour l'instant seul des comptes client sont créées.
---

## Fonctionnalités clés :   
### créer une commande
1. Se connecter avec le compte client de **test** suivant ou créer un nouveau compte utilisateur: 
email : camille.petit@example.com
mot de passe : customer123

2. Choisir un restaurant 

3. Aller sur voir la carte 

4. Choisir des plats et valider la commande 

5. Se déconnecter du compte utilisateur 

### s'assigner une livraison
6. Se connecter avec le compte livreur de **test** suivant : 
email : lucas.bernard@example.com
mot de passe : deliver123

7. Cliquer sur la commande créer précédement et se l'assigner
 1. Scénario alternatif (pour simuler une vérification utilisateur de sa commande au moment où la commande est en cours de traitement): 
 2. Se déconnecter 
 3. Se connecter avec le compte de l'utilisateur test camille.petit@example.com  
 4. Aller sur "mes commande"
 5. Voir la commande, et là on peut voir "lucas bernard" comme livreur. 

### Clôturé la livraison
8. Clique sur la commande créer précédement et la valider 

9. Se déconnecter 

10. Se connecter avec le compte de l'utilisateur test camille.petit@example.com  

11. Aller sur "mes commandes"

12. La commande est en état livré et si l'utilisateur la valide elle passe en état terminé.  

---
## Gestion des problème fréquent 
Actuellement rien n'est modifiable sur le site donc en cas d'oubli de mot de passer, d'erreur au moment de passer commande ou autre ses élément ne sont pas pris en compte. 