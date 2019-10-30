# overview

Keras 를 이용한 기본적인 Seq2seq 모델입니다.

`skopt.gp_minimize` 를 이용해서 hyperparameter search 를 수행 합니다. 

teacher forcing 을 하지 않으려면 `decoder_train_input_data` 부분 주석을 바꾸면 됩니다.

# requirements 

```
pip install scikit-optimize
```
