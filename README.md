# Datathon_image_similarity
 using the CLIP model to differentiate pairs of artworks

## Data Overview

artworks: contains information about individual artworks, including their name, URL, image URL, artist ID, rating, summary, year, medium, and location. Artworks can be linked to each other based on the Recommendation table.

generated: contains the URL of images generated using Text-To-Speech technology.

artists: contains information about individual artists, including their name, URL, image URL, summary, birth- and deathplace, birth- and deathdate, and cause of death. Artists can also be linked to each other through apprenticeships.

movements: gives a unique ID to certain art movements and contains the movement name, ID, and description.

specializations: gives a unique ID to specializations of artists and contains the specialization name, ID, and description.

artistmovements: gives a relationship between artist ID and movement ID

artistspecializations: gives a relationship between artist ID and specialization ID
