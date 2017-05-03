# Contributing to CORE @ Mozilla Global Sprint 2017

Thank you for your interest! 

Currently CORE aggregates 70 million research outputs and 7 million full text, we need your help to unleash the power of Open Access :)

We are looking for developers, data scientists, text miners, designers and testers to exploit as much as they can our APIs and dataset to increase the use and visibility of Open Access in the world.
We have a list of ideas in the [issues](../../issues) section to get you started. Feel free to add more ideas to the issue tracker if you want.
In the following weeks we will be adding more content and ideas in the issues section.

## Participation guidelines

This project adheres to a [code of conduct](CODE_OF_CONDUCT.md). By participating, you are expected to uphold this code. Please report unacceptable behavior to [mailto:matteo.cancellieri@open.ac.uk].

## How to contribute?
We have plenty of ideas to work on, some of them are just a sentence or two and some of them are more detailed. If you head to [issues](../../issues) section you will see some of them. 
There are many ways to contribute:

- if you are a developer in any language please help us build clients for our APIs. 
- if you are a machine learning specialist please use our dataset to train and test your models.
- if you are a data scientist you can get helpful insights on how the research world works. [This](https://blog.core.ac.uk/2016/10/21/analysing-orcid-coverage-across-repositories-through-core/) is for example our analysis of the uptake of ORCID identifiers in the world.
- if you find any bugs, please help us collect them and improve our data and access to it.

We always welcome new ideas, feel free to add your own ideas directly to the [issues](../../issues) section.
If the APIs and the dataset are not enough please contact us and we will try our best to offer you all the data we have available.

## Where to start
We have two ways to access all the CORE content. The CORE APIs give you access to all our content in a fresh way. If you want to analyse our data in bulk please use the CORE dataset.
### CORE API
Please register [here](https://core.ac.uk/api-keys/register) to receive an API key and start testing the [live examples](https://core.ac.uk/docs/).
A good starting point to start coding with our API is to follow this [iPython notebook](/oacore/or2016-api-demo).
In collaboration with [rOpenSci](https://ropensci.org/) you can also find [here](/ropenscilabs/cored) an R client for the CORE API.

### CORE Dataset
You can get the latest CORE dataset from [here](https://core.ac.uk/dataset/getdatadump). 
There are two different section in our dataset the metadata and the fulltext part.
The following is an example of how the metadata is structured in the dataset.
```json
{
    "identifier": 13291,
    "ep:Repository": 1,
    "dc:type": [
        "Report"
    ],
    "bibo:shortTitle": "Evaluating stillbirths : improving stillbirth data could help make stillbirths a visible public health priority",
    "bibo:AuthorList": [
        "IMMPACT",
        "Population Reference Bureau"
    ],
    "dc:date": "2007-02",
    "bibo:cites": [
        {
            "rawReferenceText": "Cynthia Stanton. Stillbirth Rates: Delivering Estimates",
            "authors": [

            ],
            "bibo:shortTitle": "Stillbirth Rates: Delivering Estimates",
            "doi": "10.1016/S0140-6736(06)68586-3"
        }
    ],
    "bibo:citedBy": [

    ],
    "similarities": [
        {
            "identifier": 29886,
            "sim:weight": 0.333121,
            "sim:AssociationMethod": "similarity_cosine"
        },
        {
            "identifier": 33044,
            "sim:weight": 0.325861,
            "sim:AssociationMethod": "similarity_cosine"
        },
        ...,
        {
            "identifier": 43755,
            "sim:weight": 0.173635,
            "sim:AssociationMethod": "similarity_cosine"
        }
    ]
}
```
This one is how the fulltext looks like:
```json
{
  "identifier":612,
  "fullTextSource":"Here goes the fulltext ..."
}
```

## How to submit changes

1. **Add/Comment to the issue you're working on.** If you have a new idea you're working on please add it as an [issue](../../issues) so we can keep track of it.
2. **Link** the Github repository of your code.
3. **[Contact us](mailto:matteo.cancellieri@open.ac.uk)** for any questions or if you need help using our APIs and dataset.

> First time contributing to open source? Check out this *free* series, [How to Contribute to an Open Source Project on GitHub](https://egghead.io/series/how-to-contribute-to-an-open-source-project-on-github).

## How to report bugs
We are well aware that aggregating 70 million research papers raises a lot of inconsistencies and possible conflicts. If you spot any bugs, please report them to our [issue tracker](../../issues). We will try to address the issues as soon as possible.

## Communication channels
We have a gitter chat ready for this sprint. 
[![Join the chat at https://gitter.im/oacore-mozsprint17/Lobby](https://badges.gitter.im/oacore-mozsprint17/Lobby.svg)](https://gitter.im/oacore-mozsprint17/Lobby?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)
You can also [contact us](mailto:matteo.cancellieri@open.ac.uk) if you prefer using emails.

