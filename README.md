# 📩 Détection de Spam avec un Modèle IA

Ce projet permet de classifier un message en **spam** ou **non-spam** grâce à un modèle entraîné en **Python** avec `scikit-learn`.  

## 📂 Organisation du projet  
- **SMSSpamCollection** : Dataset des messages utilisés pour entraîner le modèle. 
Source: https://archive.ics.uci.edu/dataset/228/sms+spam+collection 
- **spam_detector.ipynb** : fichier notebook

## 🚀 Installation et Exécution  

### 1️⃣ Prérequis  
Utilisation d'un notebook en local (ex: JupyterLab) ou à distance (ex:Google Colab)
Assurez-vous d'avoir **Python 3.x** 
- Créeer un environnement virtuel (à l'intérieur de votre projet)

!python -m venv env 
// ou préciser la version de python. ex: !python3.12 -m venv env

- Activer l'environnement
. Sous mac, linux:
    !source env/bin/activate
    ou,
    !env/bin/python -c "import sys; print(sys.executable)"
. Sous windows:
    !env/Scripts/activate.bat
     //Avec CMD
   !env/Scripts/Activate.ps1
    //Avec Powershel

- Installé les bibliothèques nécessaires :  

    !pip install pandas numpy matplotlib scikit-learn

- Vérifier la liste des packages installés:

    !pip list

(voir le fichier final spam_detector.ipynb)

NB: Toutes ces commandes sont executées dans le notebook.

## 📜 Licence
Ce projet est sous licence MIT – vous pouvez l'utiliser librement. Voir le fichier **LICENSE** pour plus d’informations.
