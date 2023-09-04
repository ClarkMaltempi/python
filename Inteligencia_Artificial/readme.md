# Perceptron: algoritmo de aprendizado

<p>Obs: Para que o programa possa ser executado, crie um ambiente para utilizar a linguagem python, e importe a biblioteca :
<a href srr="https://github.com/joelgrus/data-science-from-scratch">linear_algebra.py</a></p>


<p>Nesse teste de nível baixo, simulo a aprendizagem de máquina, 
estimulando as entradas da rede por meio de padrões de entrada e observar a saída calculada pela mesma, 
comparando com a saída desejada. Como a resposta da rede é a função dos valores atuais do seu conjunto de pesos (números de conexões),
estes são ajustados de forma a aproximar a saída da rede para a saída desejada.</p></br>

<p>
<p>w(n) = vetor de pesos no instante n;</p>
<p>• ∆w(n) = valor do incremento a ser aplicado ao vetor de pesos no instante n;</p>
<p>•  = constante que é a medida da rapidez com que o vetor de pesos será atualizado;</p>
<p>• x = vetor de entrada;</p>
<p>• Y = saída atual;</p>
<p>• Yd = saída desejada;</p>
<p>• e = Yd – Y → erro. </p></br>

> Sequência do Algoritmo
</br>
<p>1. Inicializar o valor de ;</p>
<p>2. Inicializar o vetor de pesos w com valores aleatórios;</p>
<p>3. Aplicar a regra de atualização dos pesos w(n + 1) = w(n) +  e x(n) para todos os p pares
(xi , Ydi ) do conjunto de treinamento;</p>
<p>4. Repetir o passo 3 até que e = 0 para todos os p elementos do treinamento</p>
