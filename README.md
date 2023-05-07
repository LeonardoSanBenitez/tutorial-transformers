# tutorial-transformers
Introduction to NLP, Transformers architecture, Transformers library and HuggingFace

[Slides](https://docs.google.com/presentation/d/1re4sFg7Dpch40jPvmRgKnK4VLcbu5uP6mc0apJ374f4/edit?usp=sharing)

## Running locally

TODO

## Running on Colab

TODO

## Customizing the container

If you just want to learn about transformers, this is useless

but you will deploy transformers-based software to production and you wanna have full control over it, this is probably the type of thing that you'll need to do

just go to the folder `customized-container` and execute:

```
docker-compose up
```

and go to the address `http://127.0.0.1:8888?token=c61a728d-f4e6-45f0-9bb6-65646801f994`

and you should be able to run the same notebooks as in the last part

**Cautionary note:** the file `customized-container/.env` stores the token above. Usually this file is used to store secrets/keys/credentials, and thus it's ignored in the git repo (using the `.gitignore` file). For learning purposes, <u>I'm explicitly committing this file to the repository</u>. If you want to store real secrets using this repository as base, please take this into consideration.

## Using the hugging face cloud

TODO: instructions about how to create the account
