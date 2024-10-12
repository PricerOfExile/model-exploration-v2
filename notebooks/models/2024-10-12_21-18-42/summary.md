PoE model training of 12/10/2024 - 21:18'42''
========================

training set description
------------------------
learning rate: 0.01
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
best epoch validation loss: 6394757718.078603

### ecpoh resutls
Epoch 1/20, Validation Loss: 1043851432234060.0
Epoch 2/20, Validation Loss: 388442559178170.7
Epoch 3/20, Validation Loss: 253130401318.00873
Epoch 4/20, Validation Loss: 110597265291.73799
Epoch 5/20, Validation Loss: 90711987535.37119
Epoch 6/20, Validation Loss: 30375954785.25764
Epoch 7/20, Validation Loss: 48701544376.45415
Epoch 8/20, Validation Loss: 11184964885.240175
Epoch 9/20, Validation Loss: 7054368504.174672
Epoch 10/20, Validation Loss: 6394757718.078603
Epoch 11/20, Validation Loss: 112775742352.20961
Epoch 12/20, Validation Loss: 1991803466103.6157
Epoch 13/20, Validation Loss: 200738204139.87772
Epoch 14/20, Validation Loss: 79589914990.67249
Epoch 15/20, Validation Loss: 40886107623.40611
Epoch 16/20, Validation Loss: 26182975018.48035
Epoch 17/20, Validation Loss: 16103985518.67249
Epoch 18/20, Validation Loss: 336271561723.5284
Epoch 19/20, Validation Loss: 86574996144.62881
Epoch 20/20, Validation Loss: 14883231600.908297