# ML-IRIS-classification

Nama : Farah Dhia Fadhila </br>
NRP : 5025211030 </br>
Kelas : Pembelajaran Mesin C

Classification Iris flower dataset into 3 classes (Iris Setosa, Iris virginica, and Iris versicolor) using classification method and artificial neural network. There are 2 scenarios, with normalization using MinMax scalling and without normalization.

1. Decision Tree
   - Criterion gini
   - Criterion entropy
2. KNN
   - k=3
   - k=5
   - k=7
3. Naive Bayes
4. SVM
   - kernel linear
   - kernel polynomial
   - kernel rbf
   - kernel sigmoid
5. ANN
   - 2 hidden layers (6 neurons for each layer, activation function ReLU)
   - 1 output layers (3 neuron, activation function softmax)
   - Compiling (optimizer="adam", loss="categorical_crossentropy", metrics=['accuracy']), fitting (batch_size=32, epochs=100)
