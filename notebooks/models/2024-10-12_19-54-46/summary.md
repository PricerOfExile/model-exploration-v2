PoE model training of 12/10/2024 - 19:54'46''
========================

training set description
------------------------
learning rate: 0.025
number of epochs: 40
model configuration: 
  NNCOnfig(dropout_rate=None,
           with_batch_norm=True,
           with_residual=True,
           layers=[ NNLayerConfig(in_size=920,
                                  out_size=1840,
                                  activation=<class 'torch.nn.modules.activation.LeakyReLU'>),
                    NNLayerConfig(in_size=1840,
                                  out_size=920,
                                  activation=<class 'torch.nn.modules.activation.Tanh'>),
                    NNLayerConfig(in_size=920,
                                  out_size=460,
                                  activation=<class 'torch.nn.modules.activation.Tanh'>),
                    NNLayerConfig(in_size=460,
                                  out_size=230,
                                  activation=<class 'torch.nn.modules.activation.LeakyReLU'>),
                    NNLayerConfig(in_size=230,
                                  out_size=6,
                                  activation=<class 'torch.nn.modules.activation.ReLU'>)])

training results
----------------
best epoch: 13
best epoch validation loss: 196997606261.3799

### ecpoh resutls
Epoch 1/40, Validation Loss: 56042790767477.38
Epoch 2/40, Validation Loss: 1984114264591.6506
Epoch 3/40, Validation Loss: 2737649540440.3145
Epoch 4/40, Validation Loss: 14294666146024.523
Epoch 5/40, Validation Loss: 1909963825831.6855
Epoch 6/40, Validation Loss: 1542871000578.2358
Epoch 7/40, Validation Loss: 11683678461486.951
Epoch 8/40, Validation Loss: 8164890788054.638
Epoch 9/40, Validation Loss: 1897673267924.4019
Epoch 10/40, Validation Loss: 269709838649.0131
Epoch 11/40, Validation Loss: 660926022705.1877
Epoch 12/40, Validation Loss: 417419044640.4192
Epoch 13/40, Validation Loss: 196997606261.3799
Epoch 14/40, Validation Loss: 338362046329.8515
Epoch 15/40, Validation Loss: 248183361625.4323
Epoch 16/40, Validation Loss: 6161966836992599.0
Epoch 17/40, Validation Loss: 30344179976576.56
Epoch 18/40, Validation Loss: 14260534841540.752
Epoch 19/40, Validation Loss: 8632901607674.41
Epoch 20/40, Validation Loss: 21320005957175.895
Epoch 21/40, Validation Loss: 3152126575021.275
Epoch 22/40, Validation Loss: 2679323702410.62
Epoch 23/40, Validation Loss: 1636234424695.6157
Epoch 24/40, Validation Loss: 1003089588885.7991
Epoch 25/40, Validation Loss: 638939978237.7642
Epoch 26/40, Validation Loss: 564452096330.8995
Epoch 27/40, Validation Loss: 408852445729.5371
Epoch 28/40, Validation Loss: 352637513745.8865
Epoch 29/40, Validation Loss: 9069485883392.0
Epoch 30/40, Validation Loss: 6472006325780.122
Epoch 31/40, Validation Loss: 232013940226.2358
Epoch 32/40, Validation Loss: 4440682905385.362
Epoch 33/40, Validation Loss: 3174571169157.031
Epoch 34/40, Validation Loss: 2519182866476.7163
Epoch 35/40, Validation Loss: 9048290580560.488
Epoch 36/40, Validation Loss: 2550547807397.4497
Epoch 37/40, Validation Loss: 1460268106872.7336
Epoch 38/40, Validation Loss: 787390311178.0612
Epoch 39/40, Validation Loss: 551757021040.9083
Epoch 40/40, Validation Loss: 430908432849.04803