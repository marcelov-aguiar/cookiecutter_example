# {{cookiecutter.project_name}}

{{cookiecutter.description}}

## Used packages

The packages used in the interpreter {{cookiecutter.python_interpreter}}+ were:

* Pandas

## Directory structure

```
├── 1_dados_raw                         <- All raw data needed for modeling.
├── 2_modelagem                         <- All analysis and modeling of delivered products.
│   ├── 0_utilidades                    <- Files containing classes and methods that are generic and useful for all products.
│   ├── 1_preprocessamento              <- Responsible for transforming the raw data of different formats into formatted raw data.
│   │   └── out                         <- Formatted raw data. Can be used differently for each product.
│   └── {{cookiecutter.model_name}}     <- All product related files.
│       ├── 0_utilidades                <- Files containing classes and methods that are generic and useful for all products.
│       ├── 1_preprocessamento          <- Responsible for transforming the raw data of different formats into formatted raw data.
│       │   └── out                     <- File formatted for the product.
│       ├── 2_exploracao                <- Files related to product-related analyses, investigations and studies
│       └── 3_deploy                    <- Product deployment related files
|
└── requirements.txt                    <- The requirements file for reproducing the analysis environment, e.g.

```

## Products related to {{cookiecutter.model_name}}

### Project Stakeholders

* {{cookiecutter.author_name}}

