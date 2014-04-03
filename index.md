# Git++ : Le recap

---

## Un historique propre !

* Mise en contexte
* Perte de mémoire
* Retour de congés
* Arrivée d'un nouveau
* Revue de code

---

## Un formalisme commun

```
feat(login): reset password on demand

send an email with unique reset url
display a form to define a new password

Closes #1234
```

---

## Répondre aux questions importantes

* Quoi ?
* **Où** sont les changements ?
* Pourquoi ce changement ?
* Comment ?
* Références ?

---

## Générer un changelog

![generated changelog](./img/generated-changelog.jpg)

---

## Soigner l'historique<br>=<br>modifier des commits

/!\ Ne jamais le faire sur master

---

### Rebase plutôt que merge

TODO Rappels sur le rebase

```
git rebase master
```

---

### Rebase interactif

```
git rebase -i master
git rebase -i HEAD~3
git rebase -i 74dec23

# editer la todo list

# faire les actions

git rebase --continue

# (résoudre les conflits)
```

---

### Renommer un commit

`reword/r`

---

### Modifier un comit

`edit/e`

---

### Réordonner un commit

changer l'ordre des lignes

---

### Fusionner un commit

`squash/s` : fusionner les messages<br>
ou `fixup/f` : garder le message le plus ancien

---

### Supprimer un commit

supprimer une ligne

---

## Merci ;-)

---

## Q/A ??
