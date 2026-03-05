# 🧑‍💻 HOG-Based Face Detector

## 📝 Descrizione del Progetto
Sviluppo di un sistema di Computer Vision per il rilevamento dei volti all'interno delle immagini, utilizzando l'estrazione delle feature HOG (Histogram of Oriented Gradients) abbinata a un classificatore Support Vector Machine (SVM).

## 🎯 Obiettivi e Risultati
* **Estrazione Feature:** Utilizzo di HOG per estrarre le caratteristiche visive dai volti (dataset LFW - Labeled Faces in the Wild).
* **Classificazione:** Addestramento di un modello LinearSVC.
* **Sliding Window:** Implementazione di un rilevatore che analizza porzioni di un'immagine di test per identificare ed evidenziare i volti trovati (tramite bounding boxes rosse).

## 🛠️ Tecnologie e Librerie
* Python
* Scikit-Image (HOG, view_as_windows)
* Scikit-Learn (LinearSVC)
* Matplotlib (Patches)
