# Desafio Seazone para vaga Analista de Dados Júnior

##  Dependências

### Instalar ambiente virtual:
 python -m pip install virtualenv

### Criar ambiente virtual e usá-lo:
virtualenv ENV
.\ENV\Scripts\activate


### Instalar pacotes requeridos:
python -m pip -r .\requeriments.txt

### abrir jupyter:
jupyter-notebook


## Observação
1 - Caso não utilize o ambiente virtual e o arquivo requeriments.txt para instalar o pacote verifique se a versão do scikit-lear ígual à 1.0.2, caso seja diferente e de erro ao importar MissForest do pacote missingpy retire da celula de carregamento de pacotes o seguinte trecho:

" import sys
import sklearn.neighbors._base
sys.modules['sklearn.neighbors.base'] = sklearn.neighbors._base "

Para não ocorrer erros sugiro que instale os pacotes de acordo com o Readme

2 - Foi encontrado uma grande quantidade de valores faltantes em algumas colunas, para esse caso ocorreu a imputação. Se a proposta da empresa não é a imputação de valores faltantes, ignore essas duas celulas.
