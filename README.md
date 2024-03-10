Polish ASR speech datasets survey and catalog.


Important - before getting familiar with the Polish ASR speech data survey and catalog, please consider completing the short feedback [form](https://forms.gle/FL1obRfYMvgHVoEu5).<br>
Your feedback will help to assess the state of Polish ASR datasets from the community perspective and improve the design of the [Polish ASR speech datasets catalog.](https://docs.google.com/spreadsheets/d/181EDfwZNtHgHFOMaKNtgKssrYDX4tXTJ9POMzBsCRlI/edit?usp=sharing) <br>
Each response is awarded by donation of 50 PLN to the chosen charity organization. Thank you!
[Feedback form link](https://forms.gle/FL1obRfYMvgHVoEu5)

# Polish ASR speech data survey goals
- Organization of publicly available information about Polish ASR speech datasets into the catalog.
- Providing the ASR community with a collectively maintained, up-to-date source of information about available datasets.
- Identification of ASR speech datasets for Polish, which are freely available for research and commercial purposes.
<br>

# Survey results:
- **Fifty-three datasets (53)** intended for Polish ASR development were identified based on the information available in the public domain.
- **Fourty-four (44)** out of 53 identified datasets are accessible. 
- The **total** **size** of **documented Polish ASR speech data** amounts to approx. **26860** **hours** of **audio** and **5744** **hours** of **transcribed** speech.
-  **For thousand five hundred and seventy (4570)** hours of speech is validated as accessible (79.5% of identified and cataloged speech material)
- **One thousand and four hundred (1400)** hours of transcribed speech data is **available in a public domain**.
-  **Three thousand one hundred seventy-one (3171) hours** of transcribed speech is **available through commercial providers**.
  
- Each dataset in the catalog is described with up to 61 attributes. See the [Catalog attributes](https://github.com/goodmike31/pl-asr-speech-data-survey#attributes) for details.
* Detailed analysis results will be available in the article soon.
* Resulting Polish ASR speech datasets catalog is available in 2 formats:
  * [Google Sheets](https://docs.google.com/spreadsheets/d/181EDfwZNtHgHFOMaKNtgKssrYDX4tXTJ9POMzBsCRlI/edit?usp=sharing)
  * [TSV](https://github.com/goodmike31/pl-asr-speech-data-survey/blob/main/snapshots/pl-asr-speech-datasets-catalog-latest.tsv)

# How to contribute to the Polish ASR speech datasets catalog 
## 1. To report a bug in the catalog:
* Open an [issue](https://github.com/goodmike31/pl-asr-speech-data-survey/issues), describe it, and label it as a "bug".
* (alternatively) Leave a comment in the Google Sheet.

## 2. To propose adding or modifying catalog attributes:
* Open an [issue](https://github.com/goodmike31/pl-asr-speech-data-survey/issues), describe your proposal (attribute name, meaning, and motivation), and label it as "enhancement".
* (alternatively) Leave a comment in the Google Sheet and describe your proposal.

# How to identify public domain PL ASR speech datasets
1. Open the [catalog](https://docs.google.com/spreadsheets/d/181EDfwZNtHgHFOMaKNtgKssrYDX4tXTJ9POMzBsCRlI/edit?usp=sharing)
2. Set filter on **Usage cost** column to **free**

# How to cite this resource?
@misc{junczyk-2023-pl-asr-speech-data-catalog, <br>
title = {Polish ASR Speech Datasets Catalog},<br>
author = {Michał Junczyk},<br>
year = {2023},<br>
publisher = {Github},<br>
url = {https://github.com/goodmike31/pl-asr-speech-data-survey} }
<br>
# Addendum - Survey design  

## Dataset characteristics analysis process
- Publicly available information sources were analyzed, annotated, and standardized with 60 attributes.
- Additionally, the content of publicly available datasets was analyzed automatically.
 
## Information sources
* Language Data Repositoriesadc.upenn.edu/)
  * [ELRA Catalog](http://catalogue.elra.info/en-us/)
  * [META-SHARE repository](http://www.meta-share.org/)
  * [CLARIN ERIC - Virtual Language Observatory](https://vlo.clarin.eu/)
  * [CLARIN-PL - D-space](https://clarin-pl.eu/dspace/)
  * [Open Science Resource Atlas 2.0 (AZON)](https://zasobynauki.pl/)
  * [PELCRA](http://pelcra.pl/new/tools_and_resources)
  * [Hamburger Zentrum fur Sprach Corpora HZSK](https://corpora.uni-hamburg.de/hzsk/)
* Other
  * [PolEval 2019 competition](http://2019.poleval.pl/)
  * [Google dataset search](https://datasetsearch.research.google.com/)
  * [Kaggle](https://www.kaggle.com/)
  * [Hugging face](https://huggingface.co/)
  * [Google Scholar Search](https://scholar.google.com/) (keywords: Polish, ASR, speech corpus, dataset, etc.)
  * [Google Web Search](https://www.google.com/) (keywords: Polish, ASR, speech corpus, dataset, etc.)

## Attributes
- Each dataset is described with up to 60 attributes covering:
  - authorship, creation date, funding, etc.
  - availability, licensing, pricing, etc.
  - content e.g. audio format, number of speakers recorded, meta-data distributions, etc.
- Values of attributes not reported by dataset authors, publishers, or researchers are recreated, when feasible (e.g. number of recordings)
- Full list of attributes, their purpose, and allowed values are available as:
  - [Google sheet](https://docs.google.com/spreadsheets/d/181EDfwZNtHgHFOMaKNtgKssrYDX4tXTJ9POMzBsCRlI/edit?usp=sharing)
  - [TSV](https://github.com/goodmike31/pl-asr-speech-data-survey/blob/main/snapshots/pl-asr-speech-datasets-taxonomy-latest.tsv)

## Limitations
The metadata collected for the catalog is primarily based on information available online in language repositories and scientific articles. When feasible, it was further verified through manual inspection of dataset content and discussion with dataset authors. Despite our best efforts, some essential metadata values may be missing. Naturally, if the metadata source contained errors, the resulting values in the catalog, metrics, and derived observations may be biased or inaccurate. Additionally, despite our best efforts to manually validate all collected data before publication, the catalog may contain inaccuracies resulting from curation-related errors. 
We hope that making the catalog publicly available to the community will enable collective curation of the catalog and taxonomy, particularly by ad- dressing any errors in the catalog metadata that have a practical impact on the community. Engaging in discussions is also crucial for filling in missing values, establishing the availability of datasets with unknown status, and determining licensing and re-usage of existing datasets for Polish ASR benchmarking purposes. Lastly, all datasets available online are subject to automatic analysis to draw new insights from the data and verify values reported by the authors in the documentation. This process, however, may introduce additional limitations in terms of the accuracy and reliability of the resulting insights.

## Changelog 

| Version | Date | Scope |
| --- | ---------| ------------- |
| 0.8 | 19 December 2023| Updated SpokeBiz corpus metadata (hours, speakers, recordings) based on http://docs.pelcra.pl/doku.php?id=spokesbiz |
| 0.7 | 23 July 2023 | Added form for collecting feedback and assessment of catalog usability from the community perspective | 
| 0.6 | 22 July 2023 | Added FLEURS and SpokesBiz corpora to the catalog. Updated survey summary statistics. Added "speakers education" attribute. |
| 0.5 | 6 July 2023 | Changed "Creator or publisher" attribute to "UL" (University of Łódź) for corpora created by the PELCRA group.
| 0.4 | 21 March 2023  | Fixed taxonomy link |
| 0.3 | 12 March 2023 | Added github.io page
| 0.2 | 22 February 2023 | Added datasets from Shaip company catalog | 
| 0.1 | 15 January 2023 | Initial release |

