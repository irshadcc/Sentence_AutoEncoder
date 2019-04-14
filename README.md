# Sentence_AutoEncoder
Sentence AutoEncoder using Keras

## Preprocessing Dataset

The text preprocessing filters can be edited in the function 

```python
class TextProcessor:
    def get_word_list(self,sent):

        < 
            

        return < list of word >

```


Dataset can be easily loaded from 

1. List of Files

    ```python
    tokenizer = Tokenizer()
    data = tokenizer.process_text(file_names= <list of filenames> )

    ```
2. From a large text

    ```python
    tokenizer = Tokenizer()
    data = tokenizer.process_text(text=<str of the text>)
    ```

3. Using a custom Function

    You can make your function to use Tokenizer object


### Make sure to reshape the data into shape (batch_size,seq_length)
##### You can also save the tokenizer as pickle 


