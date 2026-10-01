# Pioche — page d'invitation

Page statique servie par GitHub Pages : `https://maxougarry.github.io/pioche-invite/?t=<jeton>`.

Les messageries ne rendent pas cliquable le lien `tablee://invite?token=…` de l'app Pioche. L'app
partage donc ce lien web, qui ouvre Pioche (lien `intent` sur Android, `tablee://` ailleurs) et
explique quoi faire si l'app n'est pas installée. Aucune donnée n'est envoyée nulle part : la page
lit le jeton dans l'adresse et le passe à l'app.
