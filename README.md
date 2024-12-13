# Progetti di modelli della percezione
## Convolutional Neural Network per il riconoscimento di numeri scritti a mano e cartelli stradali
I due progetti utilizzano entrambi le CNN (Convolutional Neural Network) per riconoscere i numeri scritti a mano e per riconoscere i cartelli stradali. <br>
Il dataset per i numeri scritti a mano è il dataset [MNIST](https://www.kaggle.com/datasets/hojjatk/mnist-dataset) <br>
Il dataset per i cartelli stradali è il [German Traffic Singn Recognition Benchmark](https://www.kaggle.com/datasets/meowmeowmeowmeowmeow/gtsrb-german-traffic-sign) <br>
**N.B** I due dataset sono già all'interno delle due cartelle del progetto, quindi non è necessario scaricarli dai link in sovraimpressione.

## Istruzioni per l'uso
1. Scarica una versione di python uguale o successiva alla 3.10
2. Scarica Jupyter per poter visualizzare i notebook
3. Installa le seguenti librerie con il comando **pip install numpy pandas tensorflow keras matplotlib tqdm**
4. Clona il repository con il comando **git clone <https://github.com/godfredboateng02/MDP>**
   
### Riconoscimento dei numeri scritti a mano
Per fare il training della Rete Artificiale Neurale e per utilizzare il pad basterà:
1. Eseguire tutti i codici nel notebook **numeri.ipynb**
2. Eseguire tutti i codici nel notebook **padPerNumeri.ipynb**

### Riconoscimento dei cartelli stradali
Per fare il training della Rete Artificiale Neurale per il riconoscimento dei cartelli stradali basterà:
1. Eseguire tutti i codici nel notebook **notebook.ipynb**
