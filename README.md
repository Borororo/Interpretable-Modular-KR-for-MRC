## Install

Code is based on hugging face transformer v2.3.0, to install all dependencies, including external libraries, or a link to such resources, following commands will help you to install easily.

```
pip install . 
pip install allennlp==0.9.0
pip install -r requirements.txt 
```

If you have problems about installing above package, especially the first line. The best way is go to [Huggingface](https://github.com/huggingface/transformers), find the version 2.3.0 then download it. 

After that , replace all the files in the **examples** and **src/transformers/data/** with this repositories.  Then continue installation. 

Be careful with **Pytorch** version, make sure it is compatible with both allennlp and transformers. (suggest v1.5.1)

## Data & Model

We provide official data, auxiliary labeled data and 5-fold cross-validation data in [here](https://drive.google.com/file/d/1zBQw3rlYuV8ZdHO_wzXN7Rd4jo3peaTF/view?usp=sharing).
