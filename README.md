# Implementando um Classificador de Spam com Naive Bayes
## https://www.datascienceacademy.com.br/

O objetivo deste projeto é apresentar um classificador de Spam usando algoritmo de classificação Naive Bayes. 

O modelo de documento usado aqui é um modelo de saco de palavras (bag of words). Usamos dois tipos de modelo bag of words:

A. Com base na presença de palavra (se uma palavra aparece no documento ou não,o que tornará os atributos de entrada binários)
B. Com base na frequência de palavras (frequência de ocorrência de palavra no documento, o que tornará os atributos de entrada contínuos)

### Modelo Bag of Words

Um saco de palavras (bag of words) é uma representação de um texto como um agrupamento de palavras, sem qualquer consideração da sua estrutura gramatical ou da ordem das palavras. 

É simplesmente um histograma sobre as palavras da língua, e cada documento é representado como um vetor sobre estas palavras. As entradas neste vetor simplesmente correspondem à presença ou à ausência da palavra correspondente (quando se utiliza o tipo A acima ou a frequência da ocorrência da palavra quando se usa o caso B acima).


### Execução

Para executar o aplicativo é necessário ter o interpretador do Python 3 instalado (se você instalou Anaconda, você já possui o interpretador Python 3 instalado). 

A execução do aplicativo deve ser feito da seguinte forma:

1 - Abra um terminal ou prompt de comando

2 - Navegue até o diretório onde estão os arquivos que você baixou

3 - Execute o aplicativo para os dados de treino, a fim de treinar o modelo

4 - Execute o aplicativo com os dados de teste, para avaliar o modelo

5 - Atingindo  o  nível  de  acurácia  desejado,  seu  aplicativo  analítico  para classificação de Spam está pronto para receber novos conjuntos de dados e realizar a classificação do que é spam e do que não é


Para treinar o modelo digite: python spam.py train bayes train/ output/resultado.txt

onde: 
python –nome do interpretador
spam.py –nome do seu aplicativo Python(nome do script)
train –tipo de operação do aplicativo, que será executado em modo treinamento
bayes –nome do método de classificação, no caso Naive Bayes, mas você pode mais tarde implementar outros algoritmos
train/ -nome do diretório onde estão os dados de treinooutput/resultado.txt–arquivo onde será gravado o resultado do modelo de classificação treinado


Para testar o modelo digite: python spam.py test bayes test/ output/resultado.txt

Se você atingiu o nível de acurácia desejado, sua aplicação analítica está pronta e poderá receber novos dados a fim de classificá-los como spam ou não spam.
