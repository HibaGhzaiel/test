# Utiliser une image Python comme base
FROM python:3.10

# Définir le répertoire de travail
WORKDIR /app

# Copier les fichiers du projet dans le conteneur
COPY . .

# Installer les dépendances
RUN pip install --no-cache-dir -r requirements.txt

# Exposer le port Flask
EXPOSE 5000

# Démarrer Flask
CMD ["flask", "run", "--host=0.0.0.0"]  est ce que il faut replacer par mes info ou bir copier coller