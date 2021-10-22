Here is a list of transformers on [HuggingFace](https://huggingface.co/transformers/index.html) for easy reference.

## Glossary
* Model Name: The name of the model and a link to its HuggingFace page
* Published: The venue where the paper releasing the model was published and a link to the paper
* Variant: The size of the model (typically base, large, etc.)
* Params: Number of _learnable_ elements in the transformer
* `vocab_size`: Number of tokens in the vocabulary
* `embedding_size`: Size of vocabulary embeddings
* `hidden_size`: Size of the encoder layers and pooler layer
* `num_hidden_layers`: Number of hidden layers in the encoder
* `num_hidden_groups`: Number of groups for the hidden layers, parameters in the same group are shared
* `num_attention_heads`: Number of attention heads for each attention layer in the encoder
* `intermediate_size`: Size of the “intermediate” (often named feed-forward) layer in the encoder

## List of Transformers

Model Name | Published | Variant | Params | `vocab_size` | `embedding_size` | `hidden_size` | `num_hidden_layers` | `num_hidden_groups` | `num_attention_heads` | `intermediate_size`
| :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [ALBERT](https://huggingface.co/transformers/model_doc/albert.html) | [ICLR 2020](https://iclr.cc/virtual_2020/poster_H1eA7AEtvS.html)
| [BART](https://huggingface.co/transformers/model_doc/bart.html) | [ACL 2020](https://aclanthology.org/2020.acl-main.703.pdf)
