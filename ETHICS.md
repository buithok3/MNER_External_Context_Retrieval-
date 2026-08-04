# Legal and Ethical Documentation

## 1. Data Collection and Usage
**- Data Source:**

**NewsMNER:**
We collected Vietnamese online news articles published
between 2016 and 2024 from five news websites: tienphong.vn, dantri.com.vn, anninhthudo.vn, nhandan.vn, and tuoitre.vn. They covered the news, law, business, and sports domains. For each article, we select the title or caption of the image that best reflects the content to use as the input sentence. Each article has multiple images, and we choose the image that best fits the chosen sentence.

**VLSP:**
Textual modality — derived from three established Vietnamese NER corpora: VLSP-NER 2016, 2018. These consist of articles collected from Vietnamese electronic news websites (e.g., VnExpress, BaoMoi, ZingNews) covering diverse domains such as education, sports, science, and law.
Visual modality — obtained by retrieving relevant images through the Google Lens API, using nouns, verbs, and adjectives extracted from the original texts. Because these images come from third-party web sources rather than VLSP, their provenance may correspond to external websites, and we do not claim ownership of them.

**Twitter2015 and Twitter2017:**
Twitter2015 and Twitter2017 are existing multimodal NER benchmarks that are publicly available online. We use them as released, without modifying their content, for benchmarking and comparison.

All data (text and images) is collected strictly for academic research and educational purposes in the field of Multimodal Named Entity Recognition (MNER).

**- Compliance:**
Our use of the VLSP corpora is limited to research purposes, consistent with the conditions under which these resources are released via the VLSP website (vlsp.org.vn/resources)
We follow standard web-scraping guidelines, respectful crawling frequencies, and the applicable terms of service of the data sources.
Retrieved images are intended for research purposes only, with no commercial intent and no AI-based content modification.
Every text–image pair underwent a rigorous human validation process with three annotators, who assessed semantic correlation and replaced irrelevant images with blank images. For each retrieved image, we record available retrieval metadata (e.g., retrieval query and source information) to improve transparency regarding image provenance.
Our use of the Twitter2015 and Twitter2017 datasets follows the terms of their original public sources, and we use them for research purposes only.
## 2. Privacy and Anonymity
**- Personal Information:**
eb-retrieved images may contain people, public figures, private places, sensitive content, or copyrighted material. During human validation, annotators were instructed to remove images that were irrelevant, sensitive, offensive, private, or likely to raise privacy or licensing concerns. Any such image is replaced with a blank image in the released version of the dataset. This filtering also helps separate reliable visual evidence from images whose use may be legally or ethically problematic, and reduces the risk of including Personally Identifiable Information (PII).

**- Non-Malicious Intent:**
The dataset and models are intended solely for advancing natural language processing and multimodal machine learning research. No malicious or harmful profiling of individuals is conducted.

## 3. Dataset License

The textual modality of our datasets is derived from three established corpora: VLSP-NER 2016, VLSP-NER 2018, and VLSP-NER 2021. These original text datasets do not operate under a standard open-source license; instead, they are made publicly available for research purposes via the official portal of the Association for Vietnamese Language and Speech Processing (VLSP) (vlsp.org.vn/resources). Our study uses the text corpora only for research, consistent with this condition.

Regarding the visual modality, the associated images were retrieved using Google Lens. We explicitly acknowledge the potential copyright risks involved in using images collected from Google's search engine. However, we emphasize that these images were collected and utilized strictly for research purposes only, and no AI-based tools were employed for image content modification. Images with unclear provenance, unavailable licenses, or restricted redistribution rights are replaced with blank images in the released dataset, and we provide a takedown procedure allowing copyright holders or depicted individuals to request removal of any specific image or its associated metadata; we will review such requests, replace the corresponding image with a blank image, and document the changes in the updated dataset release. Users must use the VLSP text corpora for research purposes only and must comply with the licenses or terms of use of the original third-party image sources. The released dataset accordingly includes the VLSP-derived text sequences, image metadata or retrieval references where applicable, and blank-image replacements for images that cannot be safely redistributed.

In line with the aforementioned research-use conditions, the newly constructed multimodal datasets (MNER 2016, MNER 2018, and MNER 2021), along with the source code for our proposed model, are made publicly available to the research community for non-commercial research purposes only.
