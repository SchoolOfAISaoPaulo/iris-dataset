## The School of AI - São Paulo

Esse repositório tem o objetivo de estudar e fazer análises de dados no repositório de [Iris da UC Irvine Machine](https://archive.ics.uci.edu/ml/datasets/iris).

### Setup

Você precisará do docker antes de começar a fazer seus notebooks.

1. [Mac](https://docs.docker.com/docker-for-mac/install/)
2. Linux
    * [Ubuntu](https://docs.docker.com/install/linux/docker-ce/ubuntu/)
    * [Debian](https://docs.docker.com/install/linux/docker-ce/debian/)
    * [Fedora](https://docs.docker.com/install/linux/docker-ce/fedora/)
3. [Win](https://docs.docker.com/docker-for-windows/install/)

Depois do docker instalado basta seguir os passos abaixo:

```sh
$ git clone git@github.com:SchoolOfAISaoPaulo/iris-dataset.git
$ cd iris-dataset
$ make up
```

Para parar o serviço:
> CRTL+C

ou
```sh
$ cd iris-dataset
$ make down
```

Abra seu browser em http://localhost:8888



Essa imagem possui as seguintes libs:
* Pillow 
* h5py
* ipykernel
* jupyter
* jupyterlab
* keras_applications
* keras_preprocessing
* matplotlib
* numpy
* pandas
* scipy
* sklearn
* tensorflow
* nltk
* opencv-python
* keras
* ipywidgets
* scikit-learn
* ipywidgets
* seaborn
* spacy
* folium


Fiquem a vontade para submeter pull-requests nesse repositório :)

