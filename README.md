# TrumMus
Analyse der Social-Media-Kommunikationsstrategien von Trump und Musk mittels CADS und FlexiConc

Inhalt des Repositorys:
- BA_[Vivien_Müller]_CL.pdf: die Bachelorarbeit
- Data: die Daten, auf denen die beiden Korpora TRUMP und MUSK basieren
- Testkorpus: alle Dateien, mit getesteten Taggervarianten, um dann den besten Tagger
auszuwählen
- requirements: _pytorch.txt für Notebook 01, 02, 03; _flexiconc.txt für Notebook 04; _cwb.txt für Notebook 05 und 06
- Die nummerierten Notebooks, die die einzelnen Arbeitsschritte des Projekts behandeln:
* 01 Datenbeschaffung+Vorverarbeitung_Trump.ipynb: Scraping und Herunterladen von Trumps Tweets & Vorverarbeitung der Posts
* 02 Tagging_Testkorpus.ipynb: Tests verschiedener Tagger anhand eines Testdatensatzes
* 03 Vorverarbeitung_Musk+Tagger.ipynb: Vorverarbeitung von Musks Tweets und Tagging beider Korpora
* 04 CWB_cwb-ccc.ipynb: Indexieren beider Korpora in CWB und Analyse mit cwb-ccc
* 05 FlexiConc_Analyse.ipynb: Analyse mit FlexiConc
* 06 Kommunikationsstrategien.ipynb: Analyse der Kommunikationsstrategien
* 07 Semmap_Statistik.ipynb: Darstellung der Keywords beider Korpora mit Semmap
