# Tensor_PyTorch
Deep Learning para Aplicações de IA com PyTorch e Lightning - Ambiente com GPU Local

### Arquitetura do Modelo
Resnet 18

#Precisão
A entrada de matrix de pixels de ser avaliado e escolhida qual a maior quantidade escolhida.

#Otimização 
O erro do modelo será usado para um calculo de derivada matemática com a decida Estocastica do gradiente
_toch.optm_

_Obs.:_ Se por acaso o modelo tem 100% de performance em treino e cai demais a performance em teste, sinal de _Overfiting_

### Função de Ativação
 As funções de ativação são usadas em redes neurais para introduzir não linearidade em suas camadas. 
   - ReLU (Unidade Linear Retificada
   - Sigmoíde
   - Tangente Hiperbólica (Tanh)

Suponha que uma camada tenha a seguinte equação de transformação
   y = Wx + b

   onde W é a matrix de pesos, x é o input e b matrix bias ou vies.
Se a função de ativação f é aplicada a essa camada, a saída da camada será f(x). Isso entroduz não linearidade na camada, quando a função f for não linear.
