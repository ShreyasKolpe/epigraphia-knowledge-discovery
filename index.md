# Epigraphia Carnatica Knowledge Discovery

This is a project to make the collection of inscriptions known as Epigraphia Carnatica rich with annotations and entities to make knowledge discovery possible through knowledge graphs.

The project is in-progress and has the following sub-projects:

## Data Cleaning

The data being used is in the form of PDFs available at [Internet Archive](www.archive.org) which has been made possible through various digitization efforts.


In the absence of physical copies of the books, these PDFs provide the data. The copied text needs to be corrected both due to the errors caused by the OCR and to make the texts use a modern encoding scheme for Indian languages.


Checkout this project [here](https://github.com/ShreyasKolpe/epigraphia-data-cleaning)

## REST APIs

The cleaned data of the inscriptions is to be made available through a database to programs and people.


This is achieved through a web app that exposes API endpoints for registering and fetching data, as well as a UI for seeing the data. In addition, a contributor's portal allows users to enter the data through forms.


Checkout this project [here](https://github.com/ShreyasKolpe/epigraphia-rest-apis)

A version of the site is active at [http://epigraphiacarnatica.pythonanywhere.com/](http://epigraphiacarnatica.pythonanywhere.com/), populated with data as it comes in. This website will provide a persistent link to an inscription and its translation and transliteration in Roman characters.

### Indic Character Input

The forms in the above web app needed a virtual keyboard to enter non-standard Unicode cgaracters representing different sounds from Indic alphabets. This project achieves it in hacky way, though the aim is to make it a web component.


Checkout this project [here](https://github.com/ShreyasKolpe/indic-character-input)

## Contributing

Contributors
- Shreyas Kolpe, [find me here](https://www.shreyaskolpe.com)

If you would wish to contribute, please email me!
