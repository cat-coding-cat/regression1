# regression1

Considera el archivo data.csv

    default: Indica si un individuo ha incumplido o no. Valores:1,0
    student: Indica si un individuo es o no estidiante. Valores 1,0
    balance: Balance promedio de un individuo.
    income: Ingreso.
    
    1. Construye un modelo de regresión logística para predecir si un individuo es o no 'student'
    con base en las variables: ['default', 'balance', 'income']
    1.1 Entrena el modelo con el 30% de los datos.
    1.2 imprime la matriz de confusión y l  a acuracy del modelo obtenido utilizando el test set.
    1.3 utiliza en el random_state=7
    1.4 como argumento de train_test_split
    
    ------------------------------------------------------------------------------
    
    2. Considera el archivo winequality-white.csv
    
    Has una regresión Lineal para predecir la calidad del vino blanco en términos de las variables:
    ['fixed acidity','volatile acidity','citric acid','residual sugar','chlorides','free sulfur dioxide','total sulfur dioxide','density','pH','sulphates','alcohol']
    
    imprime:
    
    2.1 El score de la regresión lineal.
    2.2 La suma de errores al cuadrado.
