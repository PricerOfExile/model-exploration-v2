PoE model training of 12/10/2024 - 21:48'16''
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
best epoch: 16
best epoch validation loss: 99815476.90829694

### ecpoh resutls
Epoch 1/20, Validation Loss: 1337094685172.821
Epoch 2/20, Validation Loss: 7837397783.475983
Epoch 3/20, Validation Loss: 8501092272.069869
Epoch 4/20, Validation Loss: 5405228104.663755
Epoch 5/20, Validation Loss: 7448076150345.781
Epoch 6/20, Validation Loss: 4606034389.51965
Epoch 7/20, Validation Loss: 1190613487.930131
Epoch 8/20, Validation Loss: 771304618.0611354
Epoch 9/20, Validation Loss: 625611091.5633187
Epoch 10/20, Validation Loss: 811859135.441048
Epoch 11/20, Validation Loss: 4981632197.310043
Epoch 12/20, Validation Loss: 1711695418.9694324
Epoch 13/20, Validation Loss: 1047393424.4890829
Epoch 14/20, Validation Loss: 4801965908.401747
Epoch 15/20, Validation Loss: 868235651.7030568
Epoch 16/20, Validation Loss: 99815476.90829694
Epoch 17/20, Validation Loss: 9182653824.558952
Epoch 18/20, Validation Loss: 200385110.7423581
Epoch 19/20, Validation Loss: 235034452.8558952
Epoch 20/20, Validation Loss: 1918146581.6593885