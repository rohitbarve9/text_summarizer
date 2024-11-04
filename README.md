# Text Summarizer for Amazon reviews with Bi-LSTM and GPT-2 models

This project focuses on developing a text summarizer that efficiently condenses information into clear, concise summaries. We started with a baseline sequence-to-sequence model and enhanced it by fine-tuning a pre-trained GPT-2 model using Amazon food reviews data. This approach allows our system to generate accurate summaries that capture the essential points of the original text.

## Built With
<table>
  <tr>
    <td align="center">
      <a href="https://www.python.org">
        <img src="./images/python.jpg" width="80" height="100" alt="Python" />
      </a>
      <br>Python
    </td>
    <td align="center">
      <a href="https://www.tensorflow.org/">
        <img src="./images/tensorflow.png" width="110" height="100" alt="Tensorflow" />
      </a>
      <br>Tensorflow
    </td>
    <td align="center">
      <a href="https://huggingface.co/openai-community/gpt2">
        <img src="./images/gpt2.png" width="160" height="100" alt="GPT-2" />
      </a>
      <br>GPT-2
    </td>
  </tr>
</table>



## Installation and Usage

1. Import necessary libraries/packages by running the following command in the terminal.

``` bash
pip install -r requirements.txt
```

2. Get the data folder from Google drive [link](https://drive.google.com/drive/folders/1JYr0-QlBhZjSSXEexnvn8oNfGmqFg7Qk?usp=sharing).
The data folder must be present in the user's Google drive in the `text_summarizer/` folder.




