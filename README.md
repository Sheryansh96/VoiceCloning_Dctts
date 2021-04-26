# A TensorFlow Implementation of DC-TTS

This project is to implement the text-to-speech model, dc-tts, introduced in introduced in [Efficiently Trainable Text-to-Speech System Based on Deep Convolutional Networks with Guided Attention](https://arxiv.org/abs/1710.08969).

## Requirements
  * NumPy >= 1.11.1
  * TensorFlow >= 1.3 (Note that the API of `tf.contrib.layers.layer_norm` has changed since 1.3)
  * librosa
  * tqdm
  * matplotlib
  * scipy

This is how I sound like :-
https://soundcloud.com/shreyansh-upadhyay-809471998/normalvoice/s-esYDSQhe08t

Below are the samples generated by the model which was trained using my voice:-
1) It needs to be trained more. - https://soundcloud.com/shreyansh-upadhyay-809471998/sample1/s-ERZ8lmajEz3
2) The boy was trying till he got what he wanted. - https://soundcloud.com/shreyansh-upadhyay-809471998/sample2/s-VsnGBS8aRLA
3) Give your best. Believe that you can achieve everything you want to. - https://soundcloud.com/shreyansh-upadhyay-809471998/sample3/s-mslgJxI0xqy


