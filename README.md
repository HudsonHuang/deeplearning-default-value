# deeplearning-default-value

## Functions

| Object names in Chainer | Parameter names in Chainer | Chainer     | PyTorch     | TensorFlow     |
|:----------------------- |:---------------------------|:-----------:|:-----------:|:--------------:|
| dropout | ratio | [0.5](https://docs.chainer.org/en/stable/reference/generated/chainer.functions.dropout.html)| [0.5](https://pytorch.org/docs/stable/nn.html?highlight=dropou#torch.nn.functional.dropout)| [None](https://www.tensorflow.org/api_docs/python/tf/nn/dropout)|

## Links

| Object names in Chainer | Parameter names in Chainer | Chainer     | PyTorch     | TensorFlow     |
|:----------------------- |:---------------------------|:-----------:|:-----------:|:--------------:|
|Link  | initilizer | [LecunNormal](https://docs.chainer.org/en/stable/reference/initializers.html#weight-initializers)| Each link has <br> a different <br> initializer.| [GlorotUniform](https://www.tensorflow.org/api_docs/python/tf/get_variable)|

## Initializers
- PyTorch initializers are difined in each layer implementation, so skip it.

| Object names in Chainer | Parameter names in Chainer | Chainer     | TensorFlow     | 
|:----------------------- |:---------------------------|:-----------:|:--------------:|
| LecunNormal | scale | [1.0](https://docs.chainer.org/en/stable/reference/generated/chainer.initializers.LeCunNormal.html#chainer.initializers.LeCunNormal)| No args[(1.0)](https://www.tensorflow.org/api_docs/python/tf/keras/initializers/lecun_normal)|
| Normal | scale | [0.05]((https://docs.chainer.org/en/stable/reference/generated/chainer.initializers.LeCunNormal.html#chainer.initializers.Normal)|             1.0|
| Uniform | scale | [0.05](https://docs.chainer.org/en/stable/reference/generated/chainer.initializers.LeCunNormal.html#chainer.initializers.Uniform)| No args|

### Symbol Meanings
- x: No implementations
