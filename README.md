# TP2

## Partie 1 — Publier dans Docker Hub
> Pourquoi une image locale ne suffit pas ?

1.Portabilité — Les serveurs cloud ne peuvent pas accéder au filesystem local. Ils ont besoin d'une URL publique pour puller l'image.

2.Reproductibilité — Sans registry, impossible de garantir que tous les environnements (dev, staging, prod) utilisent exactement la même image. 


