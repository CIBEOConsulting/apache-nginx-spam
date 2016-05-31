# Apache & Nginx Spam Blacklist

Fichier de configuration pour Apache et Nginx pour bloquer les requêtes HTTP depuis des spams referer

# Nginx : spam-referer.conf

Pour utiliser cette méthode votre serveur doit disposer de Nginx.
Copier le contenu du fichier spam-referer.conf dans /etc/nginx/site-available/votre-site.conf

# Apache: .htaccess

Pour utiliser cette méthode votre serveur doit disposer de Apache et du module mod_rewrite.c

# Google Analytics: Créer un segment

Copier le contenu du fichier google-analytics-segment.txt dans Nouveau segment > Conditions > Exclure > Source > correspond à l'expression régulière
