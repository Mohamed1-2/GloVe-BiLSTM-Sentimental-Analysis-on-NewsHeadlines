# Sentimental Analysis onNews headlines using BiLSTM model

A sentiment analysis implementation on the News headlines dataset.



**Overview**

a Bidirectional LSTM classifier  built to predict sentiments in news headlines by using transfer learning with<a href="https://www.kaggle.com/robertyoung/glove-twitter-pickles-27b-25d-50d-100d-200d">glove 100d</a> word embedding(without using embedding layer)


* Model Result
<table>
  <tr>
    <th>accuracy</th>
    <th>f1 score</th>
    <th>precision</th>
    <th>Recall</th>

  </tr>
  <tr>
    <td>0.62</td>
    <td>0.61</td>
    <td>0.64</td>
    <td>0.61</td>

  </tr>

</table>



* Accuracy graph:

![06 03 2022_06 13 42_REC](https://user-images.githubusercontent.com/34875234/156901631-1fe8411f-ea58-4076-aa39-f8d7eb870e4d.png)



* Loss graph:

![06 03 2022_06 14 10_REC](https://user-images.githubusercontent.com/34875234/156901614-1b12d1c5-be08-4dfd-94c7-9fe33367ffe4.png)

* Test dataset prediction:
<table>
  <tr>
    <th>sentiment</th> 
    <th>emojis</th>
  </tr>
  <tr>
    <td>Negative</td>
    <td>🙁</td>
  </tr>
    <tr>
    <td>Neutral</td>
    <td>😐</td>
    </tr>
    <tr>
    <td>Positive</td>
    <td>😀</td>
    </tr>
</table>

![pred](https://user-images.githubusercontent.com/34875234/156903098-39822a4e-013d-4e6a-a0e1-6c4701dc19ca.PNG)

