# Polish Language Datasets Collection

## Introduction
This repository contains a **curated, manually verified metadata collection** of publicly available Polish language datasets for natural language processing (NLP) research. It centers on the core file `Pollish-Language-Dateset-List.csv`—a standardized resource that addresses the fragmentation of Polish NLP data, enabling researchers to quickly locate and validate high-quality language resources.

It is designed to serve as a centralized reference for NLP researchers, linguists, and students, supporting efficient retrieval of Polish language data for core and domain-specific tasks including:
- Text classification & topic modeling
- Named entity recognition (general + medical/legal)
- Sentiment analysis & emotion detection
- Machine translation (Polish-English/multilingual)
- Question answering (open/closed-domain)
- Multimodal understanding (speech-text-video)
- Other Polish NLP research tasks

## Key Metadata Fields
Each dataset entry in `Pollish-Language-Dateset-List.csv` is annotated with structured, research-oriented metadata to ensure clarity, reproducibility, and usability:
- **Dataset Name**: The official, unique identifier of the resource (e.g., "Leyzer", "PolEmo2.0").
- **Verified Dataset URL**: Primary download/access link, manually tested for accessibility (last verification: March 2026); invalid links are flagged and replaced with backups.
- **Dataset URL from Citing/Cited Papers**: Alternative links from peer-reviewed publications (e.g., ACL, LREC) or archived versions (Wayback Machine) for long-term access.
- **Modality**: The type of data, standardized into 3 categories: Text, Speech, Multimodal (e.g., Text+Video).
- **Tasks**: Applicable NLP tasks (comma-separated for multi-task support, e.g., "Sentiment Analysis, Emotion Recognition").
- **Dataset Description**: A detailed summary including content scope (e.g., "historical texts", "medical records"), data scale (tokens/samples), annotation method (human/expert), and collection source.

## Data Access
The complete metadata collection of Polish language datasets is provided in a structured CSV file optimized for academic use:
- Core File: `Pollish-Language-Dateset-List.csv`

💡 **Tip**: Click on `Pollish-Language-Dateset-List.csv` above to view the full, searchable table directly in GitHub. For local use, download the file and open it with **UTF-8 encoding**—this is critical to preserve Polish special characters (ą, ć, ę, ł, ń, ó, ś, ź, ż) and avoid garbled text.

## Data Preview
Below is a preview of the first 5 high-quality datasets included in `Pollish-Language-Dateset-List.csv` (full list available in the CSV file):

| Dataset Name | Verified Dataset URL | Dataset URL from Citing/Cited Papers | Modality | Tasks | Dataset Description |
|---|---|---|---|---|---|
| **Leyzer** | https://github.com/CLARIN-PL/Leyzer | https://doi.org/10.18778/0867-6356.2021.45 | Text | Named Entity Recognition, Historical Text Analysis | A morphosyntactically annotated corpus of Polish historical texts (16th–19th centuries), focusing on religious and literary works. Contains over 2 million tokens with detailed linguistic annotations by expert linguists. |
| **KGr10** | https://clarin-pl.eu/dspace/handle/11321/771 | https://doi.org/10.18778/0867-6356.2012.01 | Text | Text Classification, Topic Modeling | A corpus of modern Polish texts covering 10 thematic categories (e.g., politics, science, culture). Includes 10,000 documents with manual topic labels, making it ideal for benchmarking text categorization models. |
| **PSC** | https://github.com/ipipan/polish-sentiment-corpus | https://doi.org/10.18653/v1/P19-1483 | Text | Sentiment Analysis, Emotion Classification | A Polish sentiment corpus with 5,000 user-generated texts (reviews, forum posts). Labeled for positive/negative sentiment and 5 basic emotions (joy, sadness, anger, fear, surprise) by native Polish annotators. |
| **ParCor** | https://clarin-pl.eu/dspace/handle/11321/664 | https://doi.org/10.18778/0867-6356.2018.38 | Text | Paraphrase Detection, Semantic Similarity | A dataset of Polish paraphrase pairs, including 3,000 manually annotated sentence pairs labeled as "paraphrase" or "non-paraphrase". Used to evaluate semantic similarity models for Polish. |
| **PolEmo2.0** | https://github.com/sdadas/polish-nlp-resources#polemo20 | https://doi.org/10.18653/v1/2020.lrec-1.827 | Text | Sentiment Analysis, Emotion Recognition | An extended Polish sentiment and emotion dataset with 10,000 product and movie reviews. Annotations include 4 sentiment categories (positive, negative, neutral, mixed) and 6 emotion labels. |

*(Please download the `Pollish-Language-Dateset-List.csv` file to view the complete list of datasets.)*

## Important Notes
### URL Validity
- All "Verified Dataset URLs" in `Pollish-Language-Dateset-List.csv` are updated quarterly to ensure accessibility.
- If a verified link is invalid, check the "Dataset URL from Citing/Cited Papers" field for alternative access paths (e.g., archived versions or paper-referenced links).

### Encoding Requirement
`Pollish-Language-Dateset-List.csv` uses **UTF-8 encoding**—opening the file with other encodings (e.g., ANSI) will corrupt Polish special characters (e.g., "ą" → "Ä…"). Always confirm UTF-8 encoding in Excel, Google Sheets, or programming tools (Python/R).

### Usage Compliance
This repository provides metadata and links to external datasets (not raw data files). When using resources from `Pollish-Language-Dateset-List.csv`:
- Strictly comply with the license terms specified by the original dataset authors (e.g., non-commercial use restrictions for medical/legal data).
- Cite the original dataset publications (DOIs provided in the "Dataset URL from Citing/Cited Papers" field) to ensure academic integrity.

### Manual Verification
