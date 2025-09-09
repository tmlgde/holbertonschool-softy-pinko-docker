# 🚀 Introduction à Docker

## 📋 Pré-requis avant de commencer

- Installer **Docker Desktop** sur ton ordinateur local (⚠️ pas dans un sandbox).  
  👉 [Télécharger Docker](https://www.docker.com/)  

- Instructions détaillées d’installation :  
  - [Windows](https://docs.docker.com/desktop/install/windows/)  
  - [Mac](https://docs.docker.com/desktop/install/mac/)  
  - [Linux](https://docs.docker.com/desktop/install/linux/)  
  - **Chromebook** – Remarque : ceci installe uniquement le moteur Docker, et non Docker Desktop.  
    ⚠️ Le fonctionnement sur Chromebook n’est pas garanti. Il est recommandé d’utiliser **Windows, Mac ou Linux** (ou une machine sur le campus).  

---

## 📖 Découvrir les bases de Docker

Avant de plonger dans la pratique, il est conseillé de te **familiariser avec Docker** :  
- [Tutoriel officiel Docker](https://docs.docker.com/get-started/)  

---

## 🛠 Ressources utiles

- [Cheatsheet Docker](https://dockerlabs.collabnix.com/docker/cheatsheet/)  
- Proxy vs Reverse Proxy (exemples concrets) :  
  - [Qu’est-ce qu’un Reverse Proxy ? (vs. Forward Proxy)](https://www.youtube.com/watch?v=1KjDglvU9Hg) → ⏱ Stop à **06:25**  

---

## ✅ Premiers pas avec Docker

1. Vérifie que Docker Desktop est installé et lancé.  
2. Exécute ton premier conteneur :  

```bash
docker run hello-world
