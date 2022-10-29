# Descomplicando a criação de pacotes em Python
Nesse exemplo é realizado a criação de um pacote para processamento de imagens

Description. 
The package "image_processing" is used to:

	Processing:
		Histogram matching;
		Structural similarity;
		Resize image;

	Utils:
		Read image;
		Save image;
		Plot image;
		Plot result;
		Plot Histogram;

## Installation

Instalação de setuptools e wheel

py -m pip install --upgrade pip
py -m pip install --user setuptools wheel twine


```bash
pip install image_processing
```

## Usage

```python
from image_processing import processing
```

## Author
Karina Kato

## License
[MIT](https://choosealicense.com/licenses/mit/)