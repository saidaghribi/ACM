# Utiliser une image officielle Nginx basée sur Alpine
FROM nginx:alpine

# Supprimer les fichiers statiques par défaut de Nginx
RUN rm -rf /usr/share/nginx/html/*

# Copier le contenu du dossier dist dans le répertoire html de Nginx
COPY dist/ /usr/share/nginx/html/

# ➕ Copier la config Nginx personnalisée
COPY nginx.conf /etc/nginx/nginx.conf

# Exposer le port 80 pour l'accès extérieur
EXPOSE 80

# Lancer Nginx en mode premier plan (sans daemon)
CMD ["nginx", "-g", "daemon off;"]