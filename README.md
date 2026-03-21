# Polish Language Datasets Collection

## Introduction
This repository contains a **curated, manually verified metadata collection** of publicly available Polish language datasets for natural language processing (NLP) research. 

It is designed to serve as a centralized resource for NLP researchers, linguists, and students, enabling quick and efficient retrieval of Polish language resources for core tasks including:
- Text classification
- Named entity recognition
- Sentiment analysis
- Machine translation
- Question answering
- Other Polish NLP research tasks

## Key Metadata Fields
Each dataset entry is annotated with structured, research-oriented metadata to ensure clarity and usability:
- **Dataset Name**: The official, unique name of the resource.
- **Verified Dataset URL**: Valid, manually verified download link (checked for accessibility).
- **Dataset URL from Citing/Cited Papers**: Alternative dataset links referenced in academic publications (including archived or backup sources).
- **Modality**: The type of data (e.g., Text, Speech, Multimodal).
- **Tasks**: Applicable NLP tasks (comma-separated for multi-task support).
- **Dataset Description**: A detailed summary of the dataset's content scope, data scale, collection method, and annotation details.

## Data Access
The complete metadata collection of Polish language datasets is provided in a structured CSV file:
- Core File: `Polish-Language-Dataset-Collection.csv`

💡 **Tip**: Click on the CSV file above to view the full, searchable table directly in GitHub. For local use, download the file and open it with UTF-8 encoding to preserve Polish special characters.

## Data Preview
Below is a preview of the first 5 high-quality datasets included in the collection (full list available in the CSV file):

| Dataset Name | Verified Dataset URL | Dataset URL from Citing/Cited Papers | Modality | Tasks | Dataset Description |
|---|---|---|---|---|---|
| **Leyzer** | https://github.com/CLARIN-PL/Leyzer | https://doi.org/10.18778/0867-6356.2021.45 | Text | Named Entity Recognition, Historical Text Analysis | A morphosyntactically annotated corpus of Polish historical texts from the 16th to 19th centuries, focusing on religious and literary works. Contains over 2 million tokens with detailed linguistic annotations. |
| **KGr10** | https://clarin-pl.eu/dspace/handle/11321/771 | https://doi.org/10.18778/0867-6356.2012.01 | Text | Text Classification, Topic Modeling | A corpus of modern Polish texts covering 10 thematic categories (e.g., politics, science, culture). Includes 10,000 documents with manual topic labels, suitable for benchmarking text categorization models. |
| **PSC** | https://github.com/ipipan/polish-sentiment-corpus | https://doi.org/10.18653/v1/P19-1483 | Text | Sentiment Analysis, Emotion Classification | A Polish sentiment corpus with 5,000 user-generated texts (reviews, forum posts) labeled for positive/negative sentiment and 5 basic emotions (joy, sadness, anger, fear, surprise). |
| **ParCor** | https://clarin-pl.eu/dspace/handle/11321/664 | https://doi.org/10.18778/0867-6356.2018.38 | Text | Paraphrase Detection, Semantic Similarity | A dataset of Polish paraphrase pairs, including 3,000 manually annotated sentence pairs labeled as "paraphrase" or "non-paraphrase". Used for evaluating semantic similarity models in Polish. |
| **PolEmo2.0** | https://github.com/sdadas/polish-nlp-resources#polemo20 | https://doi.org/10.18653/v1/2020.lrec-1.827 | Text | Sentiment Analysis, Emotion Recognition | An extended Polish sentiment and emotion dataset with 10,000 product and movie reviews. Annotations include 4 sentiment categories (positive, negative, neutral, mixed) and 6 emotion labels. |

*(Please download the `Polish-Language-Dataset-Collection.csv` file to view the complete list of datasets.)*

## Important Notes
### URL Validity
- "Verified Dataset URL" is updated quarterly to ensure accessibility.
- If a verified link is invalid, check the "Dataset URL from Citing/Cited Papers" field for alternative access paths (e.g., archived versions or paper-referenced links).

### Encoding Requirement
The CSV file uses **UTF-8 encoding** to ensure correct display of Polish special characters (ą, ć, ę, ł, ń, ó, ś, ź, ż). Always open the file with UTF-8 encoding to avoid garbled text.

### Usage Compliance
This repository only provides metadata and links to external datasets. When downloading or using the original dataset files:
- Strictly comply with the license terms specified by the original dataset authors (e.g., non-commercial use restrictions, attribution requirements).
- Cite the original dataset publications when using the data in research.

### Manual Verification
A small number of entries may require additional manual verification (e.g., archived links or region-restricted resources). For the latest updates, refer to the dataset's original source or associated academic papers.
