# Cat-Classifier-Using-DNN

This classifier uses 4-layer DNN. And the maxmimum accuracy of test set is 80%.

It's just a simple classifier, which does NOT use regularization techniques. So it's only for the **beginners**, who want to build own deep neural network. The whole structure of jupyter notebook is complete, which is clear to see.

```
Main steps of building deep neural networks:
0x000 Initialization of network parameters, arguments (layer_dims), returns (parameters)
0x001 Forward propagation, arguments (X, parameters), returns (AL, caches)
0x010 Compute cost, arguments (AL, Y), returns (cost)
0x011 Backward propagation, arguments (AL, Y, caches), returns (grads)
0x100 Update parameters, arguments (parameters, grads, learning_rate), returns (parameters)
0x101 Prediction, arguments (X, y, parameters), returns (p)
```
