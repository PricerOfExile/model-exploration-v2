PoE model training of 12/10/2024 - 10:22'30''
========================

training set description
------------------------
learning rate: 0.05
number of epochs: 20
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
best epoch: 10
best epoch validation loss: 1264986.9950873363

### ecpoh resutls
Epoch 1/20, Validation Loss: 572074345.1528385
Epoch 2/20, Validation Loss: 56085185.44104803
Epoch 3/20, Validation Loss: 15597213.58951965
Epoch 4/20, Validation Loss: 67393614.43668123
Epoch 5/20, Validation Loss: 4812189.786026201
Epoch 6/20, Validation Loss: 6723804.903930131
Epoch 7/20, Validation Loss: 12049893.518558951
Epoch 8/20, Validation Loss: 20424884.041484717
Epoch 9/20, Validation Loss: 2187179.256004367
Epoch 10/20, Validation Loss: 1264986.9950873363
Epoch 11/20, Validation Loss: 127335210.40174672
Epoch 12/20, Validation Loss: 1.7174876397725485e+19
Epoch 13/20, Validation Loss: 5.426125631644056e+16
Epoch 14/20, Validation Loss: 1.936660704664162e+16
Epoch 15/20, Validation Loss: 9463533922101596.0
Epoch 16/20, Validation Loss: 5071094426331127.0
Epoch 17/20, Validation Loss: 3046721484117810.5
Epoch 18/20, Validation Loss: 2045551495110119.5
Epoch 19/20, Validation Loss: 1420503112218382.5
Epoch 20/20, Validation Loss: 1029788579006133.1