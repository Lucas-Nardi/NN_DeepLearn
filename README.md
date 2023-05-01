# NN_DeepLearn
Projeto sobre a matéria redes neurais e deep learn com foco em modelo de classificação.
Esse projeto tem o proposito de classifacar 4 tipos de animais: gato, cachorro, macaco e coruja.
São 235 imagens de treinamento, 95 imagens de teste e 9 de vaidação.
Dos 235 imagens de treinamento, 63 imagens foram de gato, 50 de cachorro, 70 de macaco e 52 de corujas.

Esse dataset foi criado na plataforma chamado roboflow.
### Nome do aluno

|**Tipo de Projeto**|**Modelo Selecionado**|**Linguagem**|
|--|--|--|
|Classificação de Imagens|YOLOv5|Python|

## Performance

O modelo treinado possui performance de **54,7%**.

### Output do bloco de treinamento

<details>
  <summary>Click to expand!</summary>
  
  ```
   Epoch   GPU_mem  train_loss   test_loss    top1_acc    top5_acc
     1/350     8.75G        1.56        1.38       0.379           1: 100% 8/8 [00:06<00:00,  1.17it/s]
     2/350       11G        1.38        1.34       0.379           1: 100% 8/8 [00:06<00:00,  1.14it/s]
     3/350       11G        1.32        1.35       0.389           1: 100% 8/8 [00:06<00:00,  1.16it/s]
     4/350       11G        1.31        1.38       0.358           1: 100% 8/8 [00:07<00:00,  1.13it/s]
     5/350       11G        1.31        1.39       0.316           1: 100% 8/8 [00:06<00:00,  1.18it/s]
     6/350       11G        1.31        1.45       0.316           1: 100% 8/8 [00:07<00:00,  1.12it/s]
     7/350       11G        1.31        1.44       0.295           1: 100% 8/8 [00:06<00:00,  1.21it/s]
     8/350       11G        1.27        1.46       0.316           1: 100% 8/8 [00:07<00:00,  1.09it/s]
     9/350       11G        1.29        3.59       0.389           1: 100% 8/8 [00:06<00:00,  1.22it/s]
    10/350       11G        1.33        1.37       0.347           1: 100% 8/8 [00:07<00:00,  1.10it/s]
    11/350       11G        1.36        1.39       0.326           1: 100% 8/8 [00:06<00:00,  1.26it/s]
    12/350       11G        1.36        1.41       0.253           1: 100% 8/8 [00:07<00:00,  1.05it/s]
    13/350       11G         1.3        1.35       0.358           1: 100% 8/8 [00:06<00:00,  1.26it/s]
    14/350       11G         1.3        1.34       0.358           1: 100% 8/8 [00:07<00:00,  1.12it/s]
    15/350       11G        1.27        1.76       0.326           1: 100% 8/8 [00:06<00:00,  1.26it/s]
    16/350       11G        1.25        1.93       0.379           1: 100% 8/8 [00:07<00:00,  1.03it/s]
    17/350       11G        1.24        1.43       0.316           1: 100% 8/8 [00:06<00:00,  1.25it/s]
    18/350       11G        1.23        1.45       0.316           1: 100% 8/8 [00:07<00:00,  1.06it/s]
    19/350       11G        1.27        1.46       0.253           1: 100% 8/8 [00:06<00:00,  1.26it/s]
    20/350       11G        1.28        1.35       0.337           1: 100% 8/8 [00:07<00:00,  1.03it/s]
    21/350       11G        1.25        1.35       0.326           1: 100% 8/8 [00:06<00:00,  1.28it/s]
    22/350       11G        1.24        1.33       0.347           1: 100% 8/8 [00:07<00:00,  1.04it/s]
    23/350       11G        1.26        1.24         0.4           1: 100% 8/8 [00:06<00:00,  1.28it/s]
    24/350       11G        1.24        1.26       0.411           1: 100% 8/8 [00:07<00:00,  1.07it/s]
    25/350       11G        1.24        1.31       0.347           1: 100% 8/8 [00:06<00:00,  1.28it/s]
    26/350       11G        1.23        1.41       0.379           1: 100% 8/8 [00:07<00:00,  1.04it/s]
    27/350       11G        1.21        1.39       0.411           1: 100% 8/8 [00:06<00:00,  1.24it/s]
    28/350       11G        1.24        1.45       0.484           1: 100% 8/8 [00:07<00:00,  1.08it/s]
    29/350       11G        1.28        1.53       0.411           1: 100% 8/8 [00:06<00:00,  1.23it/s]
    30/350       11G        1.24        1.39       0.411           1: 100% 8/8 [00:07<00:00,  1.08it/s]
    31/350       11G        1.21         1.4       0.316           1: 100% 8/8 [00:06<00:00,  1.19it/s]
    32/350       11G        1.26        1.39       0.389           1: 100% 8/8 [00:07<00:00,  1.11it/s]
    33/350       11G        1.22        1.38       0.411           1: 100% 8/8 [00:07<00:00,  1.11it/s]
    34/350       11G        1.22         1.3       0.463           1: 100% 8/8 [00:06<00:00,  1.15it/s]
    35/350       11G         1.2        1.26       0.484           1: 100% 8/8 [00:07<00:00,  1.12it/s]
    36/350       11G        1.17        1.25       0.537           1: 100% 8/8 [00:06<00:00,  1.24it/s]
    37/350       11G        1.21        1.31       0.463           1: 100% 8/8 [00:07<00:00,  1.11it/s]
    38/350       11G        1.13        1.38         0.4           1: 100% 8/8 [00:06<00:00,  1.20it/s]
    39/350       11G        1.23        1.45       0.368           1: 100% 8/8 [00:07<00:00,  1.10it/s]
    40/350       11G        1.21        1.73       0.389           1: 100% 8/8 [00:06<00:00,  1.20it/s]
    41/350       11G        1.21        3.53       0.453           1: 100% 8/8 [00:07<00:00,  1.05it/s]
    42/350       11G        1.18        2.49       0.463           1: 100% 8/8 [00:06<00:00,  1.23it/s]
    43/350       11G        1.19        1.31         0.4           1: 100% 8/8 [00:07<00:00,  1.04it/s]
    44/350       11G        1.17        1.35       0.368           1: 100% 8/8 [00:06<00:00,  1.27it/s]
    45/350       11G        1.16        1.45       0.453           1: 100% 8/8 [00:07<00:00,  1.06it/s]
    46/350       11G        1.13        1.32         0.4           1: 100% 8/8 [00:05<00:00,  1.39it/s]
    47/350       11G        1.21         1.6       0.326           1: 100% 8/8 [00:07<00:00,  1.05it/s]
    48/350       11G        1.12        1.54       0.442           1: 100% 8/8 [00:06<00:00,  1.27it/s]
    49/350       11G        1.13        1.29       0.432           1: 100% 8/8 [00:07<00:00,  1.04it/s]
    50/350       11G         1.2        1.26       0.411           1: 100% 8/8 [00:06<00:00,  1.24it/s]
    51/350       11G        1.15        1.21       0.495           1: 100% 8/8 [00:07<00:00,  1.05it/s]
    52/350       11G        1.13        1.18       0.505           1: 100% 8/8 [00:06<00:00,  1.26it/s]
    53/350       11G        1.09        1.45       0.558           1: 100% 8/8 [00:07<00:00,  1.03it/s]
    54/350       11G        1.17        1.47       0.505           1: 100% 8/8 [00:06<00:00,  1.28it/s]
    55/350       11G        1.19        1.31       0.484           1: 100% 8/8 [00:07<00:00,  1.02it/s]
    56/350       11G        1.19        1.23       0.411           1: 100% 8/8 [00:06<00:00,  1.25it/s]
    57/350       11G        1.14         1.2       0.537           1: 100% 8/8 [00:07<00:00,  1.04it/s]
    58/350       11G        1.15        1.17       0.537           1: 100% 8/8 [00:06<00:00,  1.19it/s]
    59/350       11G        1.11        1.23       0.568           1: 100% 8/8 [00:07<00:00,  1.06it/s]
    60/350       11G        1.11        1.29       0.495           1: 100% 8/8 [00:06<00:00,  1.17it/s]
    61/350       11G        1.15        1.24       0.463           1: 100% 8/8 [00:07<00:00,  1.10it/s]
    62/350       11G        1.21        1.28       0.484           1: 100% 8/8 [00:06<00:00,  1.15it/s]
    63/350       11G        1.24        2.09       0.211           1: 100% 8/8 [00:07<00:00,  1.11it/s]
    64/350       11G         1.2        6.23       0.137           1: 100% 8/8 [00:06<00:00,  1.17it/s]
    65/350       11G        1.19        3.61       0.137           1: 100% 8/8 [00:07<00:00,  1.12it/s]
    66/350       11G        1.16         1.6       0.442           1: 100% 8/8 [00:07<00:00,  1.13it/s]
    67/350       11G        1.14        1.46       0.432           1: 100% 8/8 [00:07<00:00,  1.13it/s]
    68/350       11G         1.1        1.61       0.358           1: 100% 8/8 [00:07<00:00,  1.09it/s]
    69/350       11G        1.16        1.69       0.337           1: 100% 8/8 [00:06<00:00,  1.20it/s]
    70/350       11G        1.15        1.39       0.326           1: 100% 8/8 [00:07<00:00,  1.07it/s]
    71/350       11G        1.15        1.44       0.505           1: 100% 8/8 [00:06<00:00,  1.20it/s]
    72/350       11G        1.13        1.51       0.495           1: 100% 8/8 [00:07<00:00,  1.05it/s]
    73/350       11G        1.16        1.26       0.526           1: 100% 8/8 [00:06<00:00,  1.25it/s]
    74/350       11G        1.14        1.33       0.558           1: 100% 8/8 [00:07<00:00,  1.02it/s]
    75/350       11G        1.14        1.23       0.558           1: 100% 8/8 [00:06<00:00,  1.24it/s]
    76/350       11G        1.11        1.29       0.453           1: 100% 8/8 [00:07<00:00,  1.02it/s]
    77/350       11G        1.09        1.16       0.611           1: 100% 8/8 [00:06<00:00,  1.21it/s]
    78/350       11G        1.16        1.37       0.568           1: 100% 8/8 [00:07<00:00,  1.02it/s]
    79/350       11G        1.17        2.35       0.421           1: 100% 8/8 [00:06<00:00,  1.24it/s]
    80/350       11G        1.12        1.58       0.474           1: 100% 8/8 [00:07<00:00,  1.02it/s]
    81/350       11G        1.13        1.36       0.495           1: 100% 8/8 [00:06<00:00,  1.25it/s]
    82/350       11G         1.1        1.43       0.453           1: 100% 8/8 [00:07<00:00,  1.13it/s]
    83/350       11G        1.18        1.25       0.495           1: 100% 8/8 [00:06<00:00,  1.24it/s]
    84/350       11G        1.08        1.12       0.547           1: 100% 8/8 [00:07<00:00,  1.03it/s]
    85/350       11G        1.13        1.26       0.453           1: 100% 8/8 [00:06<00:00,  1.16it/s]
    86/350       11G        1.17        1.16       0.579           1: 100% 8/8 [00:07<00:00,  1.10it/s]
    87/350       11G        1.08        1.22       0.568           1: 100% 8/8 [00:07<00:00,  1.13it/s]
    88/350       11G        1.13        1.22       0.568           1: 100% 8/8 [00:07<00:00,  1.14it/s]
    89/350       11G        1.07         1.2       0.579           1: 100% 8/8 [00:07<00:00,  1.07it/s]
    90/350       11G        1.07        1.19       0.526           1: 100% 8/8 [00:06<00:00,  1.17it/s]
    91/350       11G        1.04        1.22       0.568           1: 100% 8/8 [00:07<00:00,  1.04it/s]
    92/350       11G        1.13        1.37       0.463           1: 100% 8/8 [00:06<00:00,  1.21it/s]
    93/350       11G        1.12        1.25       0.484           1: 100% 8/8 [00:07<00:00,  1.03it/s]
    94/350       11G        1.11        1.21       0.558           1: 100% 8/8 [00:06<00:00,  1.24it/s]
    95/350       11G        1.06        1.21       0.579           1: 100% 8/8 [00:07<00:00,  1.03it/s]
    96/350       11G        1.13        1.25       0.474           1: 100% 8/8 [00:06<00:00,  1.24it/s]
    97/350       11G        1.06        1.16       0.611           1: 100% 8/8 [00:07<00:00,  1.03it/s]
    98/350       11G        1.09        1.19       0.547           1: 100% 8/8 [00:06<00:00,  1.25it/s]
    99/350       11G        1.04        1.29       0.558           1: 100% 8/8 [00:07<00:00,  1.03it/s]
   100/350       11G        1.12        1.24       0.526           1: 100% 8/8 [00:06<00:00,  1.25it/s]
   101/350       11G        1.07        1.32       0.558           1: 100% 8/8 [00:07<00:00,  1.05it/s]
   102/350       11G         1.1         1.2       0.568           1: 100% 8/8 [00:06<00:00,  1.25it/s]
   103/350       11G         1.1        1.32       0.516           1: 100% 8/8 [00:07<00:00,  1.04it/s]
   104/350       11G        1.04        1.83       0.484           1: 100% 8/8 [00:06<00:00,  1.20it/s]
   105/350       11G        1.03        1.72       0.505           1: 100% 8/8 [00:07<00:00,  1.07it/s]
   106/350       11G           1        1.45       0.558           1: 100% 8/8 [00:06<00:00,  1.15it/s]
   107/350       11G        1.02        1.29       0.463           1: 100% 8/8 [00:07<00:00,  1.09it/s]
   108/350       11G        1.05        1.38       0.537           1: 100% 8/8 [00:07<00:00,  1.14it/s]
   109/350       11G        1.09        1.16       0.621           1: 100% 8/8 [00:07<00:00,  1.13it/s]
   110/350       11G        1.04        1.21       0.632           1: 100% 8/8 [00:07<00:00,  1.11it/s]
   111/350       11G        1.09        1.21       0.547           1: 100% 8/8 [00:06<00:00,  1.22it/s]
   112/350       11G        1.03         1.2       0.547           1: 100% 8/8 [00:07<00:00,  1.06it/s]
   113/350       11G        1.08        1.26       0.537           1: 100% 8/8 [00:06<00:00,  1.23it/s]
   114/350       11G        1.03        1.22       0.537           1: 100% 8/8 [00:07<00:00,  1.04it/s]
   115/350       11G        1.07        1.36       0.484           1: 100% 8/8 [00:06<00:00,  1.25it/s]
   116/350       11G        1.06        1.27       0.463           1: 100% 8/8 [00:07<00:00,  1.04it/s]
   117/350       11G        1.05        1.28       0.484           1: 100% 8/8 [00:06<00:00,  1.21it/s]
   118/350       11G        1.01        1.14       0.611           1: 100% 8/8 [00:07<00:00,  1.05it/s]
   119/350       11G        1.02        1.13       0.663           1: 100% 8/8 [00:06<00:00,  1.23it/s]
   120/350       11G        1.03        1.23       0.579           1: 100% 8/8 [00:07<00:00,  1.04it/s]
   121/350       11G        1.03        1.23       0.568           1: 100% 8/8 [00:06<00:00,  1.25it/s]
   122/350       11G           1        1.29       0.568           1: 100% 8/8 [00:07<00:00,  1.01it/s]
   123/350       11G        1.08        1.32       0.621           1: 100% 8/8 [00:06<00:00,  1.21it/s]
   124/350       11G        1.07        1.47       0.516           1: 100% 8/8 [00:07<00:00,  1.03it/s]
   125/350       11G        1.08        1.17       0.547           1: 100% 8/8 [00:06<00:00,  1.15it/s]
   126/350       11G        1.06        1.21       0.484           1: 100% 8/8 [00:07<00:00,  1.06it/s]
   127/350       11G        1.06        1.15       0.558           1: 100% 8/8 [00:07<00:00,  1.12it/s]
   128/350       11G        1.07        1.24       0.558           1: 100% 8/8 [00:07<00:00,  1.12it/s]
   129/350       11G       0.998         2.1       0.453           1: 100% 8/8 [00:07<00:00,  1.11it/s]
   130/350       11G        1.01        1.19       0.579           1: 100% 8/8 [00:06<00:00,  1.18it/s]
   131/350       11G        1.12        1.12       0.579           1: 100% 8/8 [00:07<00:00,  1.05it/s]
   132/350       11G        1.01         1.1       0.653           1: 100% 8/8 [00:06<00:00,  1.22it/s]
   133/350       11G        1.07        1.11       0.547           1: 100% 8/8 [00:07<00:00,  1.03it/s]
   134/350       11G        1.03        1.33       0.579           1: 100% 8/8 [00:06<00:00,  1.28it/s]
   135/350       11G        1.11        1.11       0.611           1: 100% 8/8 [00:07<00:00,  1.02it/s]
   136/350       11G        1.01        1.16       0.579           1: 100% 8/8 [00:06<00:00,  1.25it/s]
   137/350       11G        1.02        1.32       0.537           1: 100% 8/8 [00:07<00:00,  1.03it/s]
   138/350       11G        1.06        1.83       0.379           1: 100% 8/8 [00:06<00:00,  1.24it/s]
   139/350       11G        1.03         1.5       0.453           1: 100% 8/8 [00:07<00:00,  1.03it/s]
   140/350       11G        1.06        1.31       0.568           1: 100% 8/8 [00:06<00:00,  1.23it/s]
   141/350       11G           1        1.11         0.6           1: 100% 8/8 [00:07<00:00,  1.06it/s]
   142/350       11G        1.01        1.09       0.558           1: 100% 8/8 [00:06<00:00,  1.29it/s]
   143/350       11G        1.03        1.18       0.537           1: 100% 8/8 [00:07<00:00,  1.04it/s]
   144/350       11G        1.05        1.18       0.579           1: 100% 8/8 [00:06<00:00,  1.23it/s]
   145/350       11G       0.913        1.25       0.589           1: 100% 8/8 [00:07<00:00,  1.05it/s]
   146/350       11G       0.944        1.18       0.621           1: 100% 8/8 [00:06<00:00,  1.21it/s]
   147/350       11G       0.981        1.29       0.505           1: 100% 8/8 [00:07<00:00,  1.05it/s]
   148/350       11G       0.931        1.22       0.558           1: 100% 8/8 [00:06<00:00,  1.15it/s]
   149/350       11G        1.05        1.25       0.547           1: 100% 8/8 [00:07<00:00,  1.12it/s]
   150/350       11G       0.963        1.35       0.516           1: 100% 8/8 [00:06<00:00,  1.15it/s]
   151/350       11G       0.981        1.36       0.505           1: 100% 8/8 [00:06<00:00,  1.17it/s]
   152/350       11G       0.936        1.27       0.474           1: 100% 8/8 [00:07<00:00,  1.12it/s]
   153/350       11G        1.07        1.16       0.579           1: 100% 8/8 [00:06<00:00,  1.18it/s]
   154/350       11G       0.999        1.33       0.463           1: 100% 8/8 [00:07<00:00,  1.09it/s]
   155/350       11G       0.947         1.3       0.495           1: 100% 8/8 [00:06<00:00,  1.20it/s]
   156/350       11G       0.988        1.14       0.611           1: 100% 8/8 [00:07<00:00,  1.08it/s]
   157/350       11G       0.981        1.45       0.516           1: 100% 8/8 [00:06<00:00,  1.21it/s]
   158/350       11G        1.03        1.27       0.547           1: 100% 8/8 [00:07<00:00,  1.06it/s]
   159/350       11G       0.955         1.2       0.568           1: 100% 8/8 [00:06<00:00,  1.24it/s]
   160/350       11G        1.03        1.18       0.589           1: 100% 8/8 [00:07<00:00,  1.05it/s]
   161/350       11G        1.03         1.2       0.568           1: 100% 8/8 [00:06<00:00,  1.26it/s]
   162/350       11G        0.96        1.26       0.611           1: 100% 8/8 [00:07<00:00,  1.04it/s]
   163/350       11G       0.956        1.28         0.6           1: 100% 8/8 [00:06<00:00,  1.27it/s]
   164/350       11G        1.02        1.27       0.568           1: 100% 8/8 [00:07<00:00,  1.05it/s]
   165/350       11G        1.01        1.13         0.6           1: 100% 8/8 [00:06<00:00,  1.25it/s]
   166/350       11G       0.981         1.1       0.579           1: 100% 8/8 [00:07<00:00,  1.03it/s]
   167/350       11G        1.04        1.43       0.558           1: 100% 8/8 [00:06<00:00,  1.27it/s]
   168/350       11G        1.01        1.18       0.621           1: 100% 8/8 [00:07<00:00,  1.04it/s]
   169/350       11G       0.937        1.44       0.526           1: 100% 8/8 [00:06<00:00,  1.24it/s]
   170/350       11G       0.946        1.61       0.547           1: 100% 8/8 [00:10<00:00,  1.32s/it]
   171/350       11G        1.01        1.96       0.484           1: 100% 8/8 [00:07<00:00,  1.02it/s]
   172/350       11G        0.97        1.14         0.6           1: 100% 8/8 [00:06<00:00,  1.18it/s]
   173/350       11G        1.01        1.22       0.547           1: 100% 8/8 [00:07<00:00,  1.05it/s]
   174/350       11G       0.936        1.24       0.589           1: 100% 8/8 [00:06<00:00,  1.23it/s]
   175/350       11G       0.987        1.21       0.663           1: 100% 8/8 [00:07<00:00,  1.03it/s]
   176/350       11G        1.03        1.26       0.568           1: 100% 8/8 [00:06<00:00,  1.28it/s]
   177/350       11G       0.958        1.44       0.526           1: 100% 8/8 [00:07<00:00,  1.04it/s]
   178/350       11G        1.05        1.37       0.495           1: 100% 8/8 [00:06<00:00,  1.27it/s]
   179/350       11G       0.936        1.47       0.547           1: 100% 8/8 [00:07<00:00,  1.01it/s]
   180/350       11G       0.939        2.11       0.421           1: 100% 8/8 [00:06<00:00,  1.24it/s]
   181/350       11G        1.01        1.94       0.516           1: 100% 8/8 [00:07<00:00,  1.01it/s]
   182/350       11G       0.957        1.17       0.674           1: 100% 8/8 [00:06<00:00,  1.24it/s]
   183/350       11G        1.01         1.1       0.589           1: 100% 8/8 [00:07<00:00,  1.07it/s]
   184/350       11G           1        1.32       0.495           1: 100% 8/8 [00:06<00:00,  1.19it/s]
   185/350       11G       0.962        1.07       0.674           1: 100% 8/8 [00:07<00:00,  1.11it/s]
   186/350       11G        1.01        1.04       0.663           1: 100% 8/8 [00:07<00:00,  1.12it/s]
   187/350       11G        1.01        1.06       0.632           1: 100% 8/8 [00:06<00:00,  1.26it/s]
   188/350       11G       0.995        1.17         0.6           1: 100% 8/8 [00:07<00:00,  1.06it/s]
   189/350       11G       0.936        1.39       0.547           1: 100% 8/8 [00:06<00:00,  1.19it/s]
   190/350       11G           1        1.14       0.642           1: 100% 8/8 [00:07<00:00,  1.06it/s]
   191/350       11G           1        1.27       0.579           1: 100% 8/8 [00:06<00:00,  1.23it/s]
   192/350       11G       0.922        1.41       0.526           1: 100% 8/8 [00:07<00:00,  1.05it/s]
   193/350       11G       0.916        1.44       0.505           1: 100% 8/8 [00:06<00:00,  1.25it/s]
   194/350       11G       0.977        1.33       0.558           1: 100% 8/8 [00:07<00:00,  1.02it/s]
   195/350       11G       0.968        1.18       0.642           1: 100% 8/8 [00:06<00:00,  1.25it/s]
   196/350       11G       0.942        1.52       0.558           1: 100% 8/8 [00:07<00:00,  1.04it/s]
   197/350       11G       0.909        1.46       0.589           1: 100% 8/8 [00:06<00:00,  1.25it/s]
   198/350       11G       0.965        1.26       0.579           1: 100% 8/8 [00:07<00:00,  1.02it/s]
   199/350       11G       0.923        1.45       0.579           1: 100% 8/8 [00:06<00:00,  1.27it/s]
   200/350       11G       0.918        1.09       0.621           1: 100% 8/8 [00:07<00:00,  1.04it/s]
   201/350       11G       0.876        1.29       0.568           1: 100% 8/8 [00:06<00:00,  1.25it/s]
   202/350       11G        1.04        1.76       0.516           1: 100% 8/8 [00:07<00:00,  1.02it/s]
   203/350       11G        1.01        1.31       0.537           1: 100% 8/8 [00:06<00:00,  1.20it/s]
   204/350       11G       0.928        1.19       0.547           1: 100% 8/8 [00:07<00:00,  1.06it/s]
   205/350       11G       0.952        1.46       0.547           1: 100% 8/8 [00:07<00:00,  1.13it/s]
   206/350       11G       0.947         1.2       0.621           1: 100% 8/8 [00:07<00:00,  1.10it/s]
   207/350       11G       0.912        1.46       0.516           1: 100% 8/8 [00:07<00:00,  1.13it/s]
   208/350       11G       0.971        1.24       0.568           1: 100% 8/8 [00:07<00:00,  1.14it/s]
   209/350       11G       0.982         1.1       0.642           1: 100% 8/8 [00:07<00:00,  1.08it/s]
   210/350       11G        0.97        1.67       0.579           1: 100% 8/8 [00:06<00:00,  1.18it/s]
   211/350       11G       0.961        1.38       0.568           1: 100% 8/8 [00:07<00:00,  1.07it/s]
   212/350       11G       0.927        1.56       0.526           1: 100% 8/8 [00:06<00:00,  1.18it/s]
   213/350       11G       0.901        1.32       0.495           1: 100% 8/8 [00:07<00:00,  1.02it/s]
   214/350       11G       0.989        1.54       0.432           1: 100% 8/8 [00:06<00:00,  1.23it/s]
   215/350       11G       0.883        1.04       0.653           1: 100% 8/8 [00:07<00:00,  1.03it/s]
   216/350       11G       0.925        1.29       0.589           1: 100% 8/8 [00:06<00:00,  1.21it/s]
   217/350       11G       0.954        1.11       0.684           1: 100% 8/8 [00:07<00:00,  1.03it/s]
   218/350       11G       0.918        1.22       0.589           1: 100% 8/8 [00:06<00:00,  1.26it/s]
   219/350       11G       0.922        1.12       0.621           1: 100% 8/8 [00:07<00:00,  1.04it/s]
   220/350       11G       0.982        1.09       0.642           1: 100% 8/8 [00:06<00:00,  1.29it/s]
   221/350       11G       0.888        1.03       0.653           1: 100% 8/8 [00:07<00:00,  1.04it/s]
   222/350       11G       0.958        1.04       0.642           1: 100% 8/8 [00:06<00:00,  1.23it/s]
   223/350       11G       0.923        1.24       0.589           1: 100% 8/8 [00:07<00:00,  1.02it/s]
   224/350       11G       0.944        1.19       0.632           1: 100% 8/8 [00:06<00:00,  1.25it/s]
   225/350       11G       0.939        1.13       0.642           1: 100% 8/8 [00:07<00:00,  1.05it/s]
   226/350       11G        0.94        1.17       0.621           1: 100% 8/8 [00:06<00:00,  1.18it/s]
   227/350       11G       0.993        1.06       0.716           1: 100% 8/8 [00:07<00:00,  1.08it/s]
   228/350       11G       0.895        1.37       0.568           1: 100% 8/8 [00:06<00:00,  1.16it/s]
   229/350       11G       0.935        1.37       0.611           1: 100% 8/8 [00:07<00:00,  1.12it/s]
   230/350       11G       0.917        1.29       0.505           1: 100% 8/8 [00:07<00:00,  1.13it/s]
   231/350       11G       0.953        1.14         0.6           1: 100% 8/8 [00:06<00:00,  1.16it/s]
   232/350       11G       0.892        1.03       0.642           1: 100% 8/8 [00:07<00:00,  1.09it/s]
   233/350       11G       0.971        1.09       0.621           1: 100% 8/8 [00:06<00:00,  1.18it/s]
   234/350       11G       0.937        1.54       0.547           1: 100% 8/8 [00:07<00:00,  1.07it/s]
   235/350       11G       0.855        1.11       0.695           1: 100% 8/8 [00:06<00:00,  1.20it/s]
   236/350       11G       0.886        1.67       0.547           1: 100% 8/8 [00:07<00:00,  1.04it/s]
   237/350       11G       0.867        1.71       0.537           1: 100% 8/8 [00:06<00:00,  1.24it/s]
   238/350       11G       0.916        1.58       0.537           1: 100% 8/8 [00:07<00:00,  1.03it/s]
   239/350       11G       0.897        1.04       0.684           1: 100% 8/8 [00:06<00:00,  1.26it/s]
   240/350       11G       0.866        1.06       0.653           1: 100% 8/8 [00:07<00:00,  1.02it/s]
   241/350       11G       0.879        1.17       0.611           1: 100% 8/8 [00:06<00:00,  1.27it/s]
   242/350       11G       0.904        1.21       0.589           1: 100% 8/8 [00:07<00:00,  1.02it/s]
   243/350       11G       0.912        1.17       0.642           1: 100% 8/8 [00:06<00:00,  1.26it/s]
   244/350       11G       0.893        1.15         0.6           1: 100% 8/8 [00:08<00:00,  1.01s/it]
   245/350       11G       0.886        1.32       0.558           1: 100% 8/8 [00:06<00:00,  1.24it/s]
   246/350       11G       0.951        1.47       0.495           1: 100% 8/8 [00:07<00:00,  1.02it/s]
   247/350       11G       0.873        1.24       0.674           1: 100% 8/8 [00:06<00:00,  1.24it/s]
   248/350       11G       0.893        1.08       0.632           1: 100% 8/8 [00:07<00:00,  1.04it/s]
   249/350       11G       0.872        1.08       0.632           1: 100% 8/8 [00:06<00:00,  1.21it/s]
   250/350       11G       0.863        1.07       0.674           1: 100% 8/8 [00:07<00:00,  1.06it/s]
   251/350       11G       0.976        1.19       0.589           1: 100% 8/8 [00:06<00:00,  1.16it/s]
   252/350       11G       0.861         1.1         0.6           1: 100% 8/8 [00:07<00:00,  1.11it/s]
   253/350       11G       0.824        1.07       0.642           1: 100% 8/8 [00:06<00:00,  1.15it/s]
   254/350       11G       0.882        1.09       0.663           1: 100% 8/8 [00:07<00:00,  1.13it/s]
   255/350       11G       0.897        1.19       0.653           1: 100% 8/8 [00:06<00:00,  1.15it/s]
   256/350       11G       0.824        1.06       0.695           1: 100% 8/8 [00:07<00:00,  1.12it/s]
   257/350       11G       0.841           1       0.705           1: 100% 8/8 [00:06<00:00,  1.14it/s]
   258/350       11G       0.937        1.13       0.684           1: 100% 8/8 [00:06<00:00,  1.23it/s]
   259/350       11G       0.845        1.12       0.632           1: 100% 8/8 [00:07<00:00,  1.03it/s]
   260/350       11G        0.83        1.25       0.589           1: 100% 8/8 [00:06<00:00,  1.24it/s]
   261/350       11G       0.852        1.16       0.663           1: 100% 8/8 [00:07<00:00,  1.02it/s]
   262/350       11G       0.922        1.11       0.653           1: 100% 8/8 [00:06<00:00,  1.24it/s]
   263/350       11G       0.865        1.18       0.663           1: 100% 8/8 [00:07<00:00,  1.01it/s]
   264/350       11G       0.859        1.22       0.568           1: 100% 8/8 [00:06<00:00,  1.26it/s]
   265/350       11G       0.838        1.13       0.621           1: 100% 8/8 [00:07<00:00,  1.01it/s]
   266/350       11G       0.809         1.3       0.589           1: 100% 8/8 [00:06<00:00,  1.23it/s]
   267/350       11G       0.933        1.14       0.695           1: 100% 8/8 [00:07<00:00,  1.03it/s]
   268/350       11G       0.779        1.08       0.695           1: 100% 8/8 [00:06<00:00,  1.23it/s]
   269/350       11G       0.827        1.09       0.695           1: 100% 8/8 [00:07<00:00,  1.03it/s]
   270/350       11G       0.813         1.1       0.716           1: 100% 8/8 [00:06<00:00,  1.19it/s]
   271/350       11G       0.878        1.25       0.632           1: 100% 8/8 [00:07<00:00,  1.08it/s]
   272/350       11G       0.871        1.05       0.653           1: 100% 8/8 [00:06<00:00,  1.19it/s]
   273/350       11G       0.832        1.29       0.632           1: 100% 8/8 [00:07<00:00,  1.06it/s]
   274/350       11G       0.913        1.14       0.642           1: 100% 8/8 [00:07<00:00,  1.11it/s]
   275/350       11G       0.793        1.09       0.642           1: 100% 8/8 [00:07<00:00,  1.13it/s]
   276/350       11G       0.866        1.05       0.642           1: 100% 8/8 [00:07<00:00,  1.07it/s]
   277/350       11G       0.885           1       0.653           1: 100% 8/8 [00:06<00:00,  1.17it/s]
   278/350       11G        0.95        1.02       0.674           1: 100% 8/8 [00:07<00:00,  1.07it/s]
   279/350       11G       0.844         1.1       0.589           1: 100% 8/8 [00:06<00:00,  1.20it/s]
   280/350       11G       0.874        1.16       0.621           1: 100% 8/8 [00:07<00:00,  1.04it/s]
   281/350       11G       0.761        1.04       0.674           1: 100% 8/8 [00:06<00:00,  1.22it/s]
   282/350       11G       0.898         1.2         0.6           1: 100% 8/8 [00:07<00:00,  1.03it/s]
   283/350       11G       0.822        1.04       0.674           1: 100% 8/8 [00:06<00:00,  1.26it/s]
   284/350       11G       0.818       0.946       0.653           1: 100% 8/8 [00:07<00:00,  1.03it/s]
   285/350       11G       0.848       0.986       0.621           1: 100% 8/8 [00:06<00:00,  1.27it/s]
   286/350       11G       0.748        1.11       0.642           1: 100% 8/8 [00:07<00:00,  1.01it/s]
   287/350       11G       0.764        1.05       0.653           1: 100% 8/8 [00:06<00:00,  1.25it/s]
   288/350       11G       0.838        1.04       0.684           1: 100% 8/8 [00:07<00:00,  1.05it/s]
   289/350       11G       0.839        1.08       0.684           1: 100% 8/8 [00:06<00:00,  1.25it/s]
   290/350       11G        0.86        1.06       0.653           1: 100% 8/8 [00:07<00:00,  1.01it/s]
   291/350       11G       0.785        1.03       0.663           1: 100% 8/8 [00:06<00:00,  1.18it/s]
   292/350       11G       0.847        1.13       0.674           1: 100% 8/8 [00:07<00:00,  1.02it/s]
   293/350       11G       0.761        1.04       0.663           1: 100% 8/8 [00:06<00:00,  1.23it/s]
   294/350       11G       0.796        1.13       0.653           1: 100% 8/8 [00:07<00:00,  1.03it/s]
   295/350       11G       0.824        1.05       0.674           1: 100% 8/8 [00:06<00:00,  1.19it/s]
   296/350       11G        0.82        1.05       0.705           1: 100% 8/8 [00:07<00:00,  1.08it/s]
   297/350       11G       0.858        1.09       0.653           1: 100% 8/8 [00:07<00:00,  1.10it/s]
   298/350       11G       0.824        1.03       0.621           1: 100% 8/8 [00:06<00:00,  1.15it/s]
   299/350       11G       0.801        1.06       0.663           1: 100% 8/8 [00:07<00:00,  1.08it/s]
   300/350       11G       0.805        1.01       0.674           1: 100% 8/8 [00:06<00:00,  1.22it/s]
   301/350       11G       0.782        1.01       0.716           1: 100% 8/8 [00:07<00:00,  1.07it/s]
   302/350       11G       0.791        1.06       0.695           1: 100% 8/8 [00:06<00:00,  1.18it/s]
   303/350       11G       0.847        1.01       0.695           1: 100% 8/8 [00:07<00:00,  1.05it/s]
   304/350       11G        0.77         1.1       0.621           1: 100% 8/8 [00:06<00:00,  1.20it/s]
   305/350       11G       0.806        1.04       0.663           1: 100% 8/8 [00:07<00:00,  1.03it/s]
   306/350       11G       0.783        0.92       0.737           1: 100% 8/8 [00:06<00:00,  1.25it/s]
   307/350       11G       0.776       0.993       0.716           1: 100% 8/8 [00:07<00:00,  1.05it/s]
   308/350       11G       0.773       0.961       0.695           1: 100% 8/8 [00:06<00:00,  1.26it/s]
   309/350       11G       0.783        1.05       0.737           1: 100% 8/8 [00:07<00:00,  1.04it/s]
   310/350       11G        0.88        1.02       0.716           1: 100% 8/8 [00:06<00:00,  1.29it/s]
   311/350       11G       0.766        1.04       0.695           1: 100% 8/8 [00:07<00:00,  1.03it/s]
   312/350       11G        0.77        1.04       0.705           1: 100% 8/8 [00:06<00:00,  1.25it/s]
   313/350       11G       0.769        1.01       0.716           1: 100% 8/8 [00:07<00:00,  1.04it/s]
   314/350       11G       0.766       0.963       0.705           1: 100% 8/8 [00:06<00:00,  1.20it/s]
   315/350       11G       0.818        1.02       0.684           1: 100% 8/8 [00:07<00:00,  1.00it/s]
   316/350       11G       0.834        1.08       0.632           1: 100% 8/8 [00:06<00:00,  1.19it/s]
   317/350       11G       0.802        1.11       0.695           1: 100% 8/8 [00:07<00:00,  1.05it/s]
   318/350       11G       0.746        1.04       0.705           1: 100% 8/8 [00:07<00:00,  1.12it/s]
   319/350       11G       0.885        1.02       0.705           1: 100% 8/8 [00:07<00:00,  1.11it/s]
   320/350       11G       0.741       0.992       0.705           1: 100% 8/8 [00:07<00:00,  1.11it/s]
   321/350       11G       0.812        0.96       0.705           1: 100% 8/8 [00:06<00:00,  1.17it/s]
   322/350       11G       0.782        1.05       0.663           1: 100% 8/8 [00:07<00:00,  1.10it/s]
   323/350       11G       0.714       0.977       0.663           1: 100% 8/8 [00:06<00:00,  1.16it/s]
   324/350       11G       0.802        1.05       0.684           1: 100% 8/8 [00:07<00:00,  1.03it/s]
   325/350       11G       0.703        1.06       0.684           1: 100% 8/8 [00:06<00:00,  1.20it/s]
   326/350       11G       0.756        1.06       0.684           1: 100% 8/8 [00:07<00:00,  1.09it/s]
   327/350       11G       0.764           1       0.684           1: 100% 8/8 [00:06<00:00,  1.24it/s]
   328/350       11G       0.773       0.967       0.705           1: 100% 8/8 [00:07<00:00,  1.03it/s]
   329/350       11G       0.802       0.958       0.695           1: 100% 8/8 [00:06<00:00,  1.24it/s]
   330/350       11G       0.771       0.975       0.695           1: 100% 8/8 [00:07<00:00,  1.01it/s]
   331/350       11G       0.761       0.964       0.726           1: 100% 8/8 [00:06<00:00,  1.24it/s]
   332/350       11G       0.713        1.05       0.705           1: 100% 8/8 [00:07<00:00,  1.02it/s]
   333/350       11G        0.76       0.975       0.674           1: 100% 8/8 [00:06<00:00,  1.27it/s]
   334/350       11G       0.804        1.05       0.663           1: 100% 8/8 [00:07<00:00,  1.02it/s]
   335/350       11G       0.705        1.05       0.642           1: 100% 8/8 [00:06<00:00,  1.24it/s]
   336/350       11G       0.729        1.04       0.684           1: 100% 8/8 [00:07<00:00,  1.03it/s]
   337/350       11G       0.784        1.03       0.663           1: 100% 8/8 [00:06<00:00,  1.19it/s]
   338/350       11G       0.767        1.02       0.674           1: 100% 8/8 [00:07<00:00,  1.07it/s]
   339/350       11G       0.789        1.04       0.684           1: 100% 8/8 [00:06<00:00,  1.15it/s]
   340/350       11G       0.727        1.04       0.674           1: 100% 8/8 [00:07<00:00,  1.10it/s]
   341/350       11G       0.721       0.951       0.695           1: 100% 8/8 [00:07<00:00,  1.08it/s]
   342/350       11G       0.752        1.01       0.684           1: 100% 8/8 [00:06<00:00,  1.15it/s]
   343/350       11G       0.697       0.945       0.695           1: 100% 8/8 [00:07<00:00,  1.03it/s]
   344/350       11G       0.811        1.09       0.695           1: 100% 8/8 [00:06<00:00,  1.20it/s]
   345/350       11G       0.797        1.01       0.695           1: 100% 8/8 [00:07<00:00,  1.02it/s]
   346/350       11G        0.78       0.986       0.716           1: 100% 8/8 [00:06<00:00,  1.24it/s]
   347/350       11G       0.692       0.967       0.705           1: 100% 8/8 [00:07<00:00,  1.03it/s]
   348/350       11G       0.758       0.967       0.695           1: 100% 8/8 [00:06<00:00,  1.25it/s]
   349/350       11G       0.719           1       0.684           1: 100% 8/8 [00:07<00:00,  1.02it/s]
   350/350       11G       0.766       0.975       0.695           1: 100% 8/8 [00:06<00:00,  1.25it/s]

  ```
</details>

### Evidências do treinamento

<img src="https://github.com/Lucas-Nardi/NN_DeepLearn/blob/main/assets/train_loss.png"  alt="Grafico train loss" title="Grafico train loss" align="center" />

<img src="https://github.com/Lucas-Nardi/NN_DeepLearn/blob/main/assets/predicao da imagem de coruja.png"  alt="Predição da imagem de coruja" title="Predição da imagem de coruja" align="center" />

## Roboflow

https://app.roboflow.com/lucas-nardi-baroni-w0bvx/animal-dataset-ehsm2/browse?queryText=&pageSize=50&startingIndex=0&browseQuery=true

## Hagging Face

https://huggingface.co/Lucas-Nardi/AnimalsPredict/tree/main

## wandb.ai

https://wandb.ai/lucas-nardi-baroni/YOLOv5-Classify?workspace=user-lucas-nardi-baroni
