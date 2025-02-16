# NLP-Applications-with-Hugging-Faces

Here I want to run some common Natural Language Processing (NLP) tasks using Hugging Face:
- **sentiment analysis**
- **text embedding** (i.e. transforming a piece of text into a numerical, n-dimensional vector, representation);
- **semantic search** (i.e. matching a query with the most appropriate result based on embeddings);

The dataset comes from "Rent the Runway" [link](https://cseweb.ucsd.edu//~jmcauley/datasets.html#clothing_fit)

It is comprised of user reviews on clothing items, their ratings on fit, and other metadata about the user (i.e. gender, height, size, age, reason for renting) and the item (i.e. category). 

  
| Column Name  | Non-Null Count | Data Type       | Description |
|-------------|---------------|----------------|-------------|
| user_id     | 1506          | int64          | Unique identifier for the user |
| item_id     | 1506          | int64          | Unique identifier for the item |
| rating      | 1506          | int64          | Rating given by the user |
| rented for  | 1506          | object         | Purpose or occasion for renting |
| review_text | 1506          | object         | Review provided by the user |
| category    | 1506          | object         | Category of the item |
| height      | 1503          | object         | Height of the user (if provided) |
| size        | 1506          | int64          | Size of the item rented |
| age         | 1500          | float64        | Age of the user (if provided) |
| review_date | 1506          | datetime64[ns] | Date when the review was posted |
