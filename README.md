# Welcome to Sasha Friese's tfcb_2025 Homework 1 repository
## On this repository, you will find:
- Data 
  --
  - https://github.com/safriese/tfcb-homework01/blob/main/data/survey_data.xlsx
- Images
  -
  Rhytidoponera Metallica
![Getting Started](images/casent0172345_rhytidoponera_metallica.jpg)
Camponotus Darwinii
![Getting Started](images/casent0191696_camponotus_darwinii.jpg)
Acanthomyrmex Ferox
![Getting Started](images/casent0901788_p1high_acanthomyrmex_ferox.jpg)
Cataglyphis Fortis
![Getting Started](images/casent0906296_p1high_cataglyphis_fortis.jpg)

- Source Code
  -
  
    | Description| Code File Name |
    | -------- | -------- |
    |  Functions for downloading and handeling the datasets.  | get_dataset.py |
    | Script to create a csv file with the species that are imaged the most. As of now, the list is not entirely correct, as some specimens have extra images, like close-ups and these also count as images. |  get_species_list.py |
    | This is were it all happens. This file initializes the model and trains the model, after which training is evaluated and the model is tested. | main.py  |
    | Load a model with trained weights and predict an image or a test set. | predict_image.py |

- A template for the PDF that will be submitted to Canvas for this assigment
  - 
  - https://github.com/safriese/tfcb-homework01/blob/main/tfcb_2025_homework1_readme_edits_canvas_submission.md