# Sentimental Analysis onNews headlines using BiLSTM model

A sentiment analysis implementation on the News headlines dataset.

<a href="https://www.kaggle.com/mohamedaldofani/glove-bilstm-sentimental-analysis-on-newsheadlines">Notebook link</a>

Created👀 by Mohamed aldoufani

Email📪: mohamed.al.dofany@gmail.com

**> Overview**

a Bidirectional LSTM classifier  built to predict sentiments in news headlines by using transfer learning with<a href="https://www.kaggle.com/robertyoung/glove-twitter-pickles-27b-25d-50d-100d-200d">glove 100d</a> word embedding(without using embedding layer)

**> Most used words in the train data** :

<div class="row">
  <div class="column">
      <div class="column">
    <img src="https://user-images.githubusercontent.com/34875234/156903416-bae1c19c-8931-4f42-af73-b9d3040db8ad.PNG" alt="Forest" style="width:30%">
  </div>
    <img src="https://user-images.githubusercontent.com/34875234/156903405-7c842720-87f0-452d-bca1-72a9f5c78312.PNG" alt="Snow" style="width:30%">
  </div>
  <div class="column">
    <img src="https://user-images.githubusercontent.com/34875234/156903420-09fcb45f-f025-4ee1-9798-1a98d8a569af.PNG" alt="Mountains" style="width:30%">
  </div>
</div>

**>Model Result**
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

**>Confusion matrix**

![Capture](https://user-images.githubusercontent.com/34875234/156904281-31fd8794-1a5f-4996-9723-02dd2bb654ee.PNG)


**>Accuracy graph**:

![06 03 2022_06 13 42_REC](https://user-images.githubusercontent.com/34875234/156901631-1fe8411f-ea58-4076-aa39-f8d7eb870e4d.png)



**>Loss graph**:

![06 03 2022_06 14 10_REC](https://user-images.githubusercontent.com/34875234/156901614-1b12d1c5-be08-4dfd-94c7-9fe33367ffe4.png)

**>Test dataset prediction**:
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

