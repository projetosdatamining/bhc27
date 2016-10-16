# bhc27

## Pacotes instalados
###OpenCV
é um pacote otimizado para procesamento de vídeos e imagen com centenas de funções variando de um simples reajustar tamanho ao reconhecimento de images, pasando até mesmo por detecção facial. Possui uma grande comunidade e desenvolvimento com status ativo além de ampla documentação.

#### install
    pip install opencv-python
#### testando
    import cv2 as cv


### Numpy
Numpy é um pacote para computação científica que manipula arrays de múltiplas dimensões de forma muito eficiente. Em muitas operaçoes com rasters podemos utilzar do poder do numpy + opencv para calcular dados de imagens.
#### install 
        pip install numpy
#### testando
    import numpy as np
    
    
#### GDAL	(Geospatial	Data	Abstraction	Library)

Possibilita manipular arquivos de formato vetorial geoespacial com OGR e drivers que podem ler, criar e manipular rasters com GDAL
#### install
        sudo	apt-get	install	python-gdal
        (observações, caso encotnre dificuldades em instalar em um ambiente virtual crie  um ambiente com base nos pacotes já existentes no sistema usando:  
        virtualenv --python=python2.7 --system-site-packages <nome_do_ambiente>)
        opcionalmente também pode ser instalado o pacote: libgdal1 --> sudo apt-get install libgdal1-dev
#### testando
        import gdal
