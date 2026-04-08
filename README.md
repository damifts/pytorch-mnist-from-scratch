# PyTorch MNIST from Scratch 🧠

Questo repository contiene un'implementazione "low-level" di una rete neurale (**Multi-Layer Perceptron**) per la classificazione delle cifre scritte a mano del dataset **MNIST**.

### 🎯 Obiettivo del Progetto
A differenza delle implementazioni standard che usano `torch.nn` o `torch.optim`, questo notebook si focalizza sulla comprensione profonda del Deep Learning implementando manualmente:
- **Inizializzazione dei pesi** (Xavier/He initialization manuale).
- **Funzioni di attivazione** (ReLU e Softmax realizzate da zero).
- **Loss Function** (Cross Entropy calcolata sui tensori).
- **Backpropagation** (sfruttando `autograd` per l'aggiornamento manuale dei gradienti).
- **Training Loop** con gestione dei mini-batch e rimescolamento dei dati.

### 🚀 Tecnologie Utilizzate
- **Python**
- **PyTorch** (Tensori e Autograd)
- **Torchvision** (per il caricamento del dataset)
- **Google Colab** (ambiente di sviluppo con accelerazione GPU T4)

### 📊 Risultati
Il modello raggiunge un'accuratezza superiore al **93%** sul test set in poche epoche, dimostrando l'efficacia della logica implementata.

### 📖 Come utilizzare questo repository
Puoi visualizzare il notebook direttamente qui su GitHub oppure eseguirlo interattivamente su Google Colab cliccando sul badge presente all'interno del file `.ipynb`.

---
*Progetto creato per approfondire le basi matematiche e computazionali delle reti neurali.*
