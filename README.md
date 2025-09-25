# Grunge-Dataset
This project extracts, cleans, and analyzes song data from four grunge bands: Alice in Chains, Nirvana, Pearl Jam, and Soundgarden. Data extraction was done based on multiple sources (**Spotify**, **Wikipedia**, **AllMusic**, **Discogs**, **Billboard**).
<br><br>
Using a combination of static and dynamic web scraping in Python with Jupyter Notebooks, a unified dataset (grunge.csv) was created containing 707 songs, each described by 97 variables.
<br><br>
The analysis applies exploratory methods and multiple machine learning models to uncover trends about success of grunge song on Billboard Charts.
<br><br>
# Web Scraping
**Folders** – Alice in Chains, Nirvana*, Pearl Jam, Soundgarden <br>
These folders contain the code used for web scraping, organized by band.<br><br>
*During the creation of the data collection scripts, the process was first carried out for the band Nirvana. In that folder, there are multiple separate scripts, each used to collect data from a different website. For the other bands, the script was written as a single file for the sake of simplicity.
<br>
Each folder contains data extraction Jupyter Notebooks: 
1. Nirvana<br>
      * ```Combining datasets.ipynb```<br>
      * ```AllMusic Data Extraction.ipynb```<br>
      * ```Billboard Data Extraction.ipynb```<br>
      * ```Discogs Data Extraction.ipynb```<br>
      * ```Spotipy Data Extraction (By Album).ipynb```<br>
      * ```Spotipy Data Extraction (By Playlist).ipynb```<br>
      * ```Wikipedia Data Extraction.ipynb```<br>
2. Alice In Chains
    * ```Data Extraction (Alice In Chains).ipynb```
3. Soundgarden
     * ```Data Extraction (Soundgarden).ipynb```
4. Pearl Jam
    * ```Data Extraction (Pearl Jam).ipynb```
<br><br>
# Data Analysis

* File 0: Exploratory data analysis<br>
* Files 1, 2, and 3: Machine learning models (three different ones)<br>
* File 4: Comparison of the results of the three models<br>
<br><br>

```
|   Notes for Grunge Dataset.docx              # Notes, manual corrections etc.
|
+---Alice in Chains                            # Data Extraction
|   |   alice_allmusic.csv
|   |   alice_spotify.csv
|   |   alice_v1.csv
|   |   alice_v2.csv
|   |   alice_v3.csv
|   |   alice_wiki.csv
|   |   billboard.csv
|   |   Data Extraction (Alice In Chains).ipynb
|   |
|
+---All Bands                                   # All Datasets Combined
|   |   Grunge Bands Dataset .ipynb
|   |   grunge.csv
|
+---Analysis                                    # Data Analysis
|       0. exploratory-analysis.ipynb
|       1. logistic-regression.ipynb
|       2. classification-model-comparison.ipynb
|       3. k-nearest-neighbors-classification.ipynb
|       4. classification-model-comparison.ipynb
|
+---Nirvana                                     # Data Extraction
|   |   AllMusic Data Extraction.ipynb
|   |   Billboard Data Extraction.ipynb
|   |   billboard.csv
|   |   Combining datasets.ipynb
|   |   Discogs Data Extraction.ipynb
|   |   nirvana_additional_info.txt
|   |   nirvana_allmusic.csv
|   |   nirvana_spotify.csv
|   |   nirvana_v1.csv
|   |   nirvana_v2.csv
|   |   nirvana_v3.csv
|   |   nirvana_v4.csv
|   |   nirvana_v5.csv
|   |   nirvana_wiki.csv
|   |   Spotipy Data Extraction (By Album).ipynb
|   |   Spotipy Data Extraction (By Playlist).ipynb
|   |   Wikipedia Data Extraction.ipynb
|
|
+---Pearl Jam                                # Data Extraction
|   |   Data Extraction (Pearl Jam).ipynb
|   |   pearl_allmusic.csv
|   |   pearl_billboard.csv
|   |   pearl_spotify.csv
|   |   pearl_v1.csv
|   |   pearl_v2.csv
|   |   pearl_v3.csv
|   |   pearl_wiki.csv
|
\---Soundgarden                            # Data Extraction
    |   check.csv
    |   Data Extraction (Soundgarden).ipynb
    |   soundgarden_allmusic.csv
    |   soundgarden_billboard.csv
    |   soundgarden_spotify.csv
    |   soundgarden_v1.csv
    |   soundgarden_v2.csv
    |   soundgarden_v3.csv
    |   soundgarden_wiki.csv
```
