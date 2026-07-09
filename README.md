# LMs Learn Universal Representations of Numbers 

This repo contains a minimal, transferrable implementation of the new param-sin probe and experiments from our paper *[Language Models Learn Universal Representations of Numbers and Why You Should Care](https://arxiv.org/pdf/2510.26285)*.


## How to set up 

The project uses `uv` for managing the Python virtual environment. 

```shell
git clone ...
cd ...
uv sync
```

## How to use

**See [notebooks/reference.ipynb](notebooks/reference.ipynb) with the implementation and end-to-end example of how to use the new param-sin probe.**

Other notebooks and scripts were used to produce the experiments in the paper.


## Citation

```bibtex
@inproceedings{stefanik-etal-2026-language,
    title = "Language Models Learn Universal Representations of Numbers and Here{'}s Why You Should Care",
    author = "{\v{S}}tef{\'a}nik, Michal  and
      Mickus, Timothee  and
      Kadl{\v{c}}{\'i}k, Marek  and
      H{\o}jer, Bertram  and
      Spiegel, Michal  and
      V{\'a}zquez, Ra{\'u}l  and
      Sinha, Aman  and
      Kucha{\v{r}}, Josef  and
      Mondorf, Philipp  and
      Stenetorp, Pontus",
    editor = "Liakata, Maria  and
      Moreira, Viviane P.  and
      Zhang, Jiajun  and
      Jurgens, David",
    booktitle = "Proceedings of the 64th Annual Meeting of the {A}ssociation for {C}omputational {L}inguistics (Volume 1: Long Papers)",
    month = jul,
    year = "2026",
    address = "San Diego, California, United States",
    publisher = "Association for Computational Linguistics",
    url = "https://aclanthology.org/2026.acl-long.1415/",
    doi = "10.18653/v1/2026.acl-long.1415",
    pages = "30663--30681",
    ISBN = "979-8-89176-390-6"
}
```
