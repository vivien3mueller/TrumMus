In diesem Ordner befinden sich die Daten, aus denen die beiden Korpora
(Trump: tta_final_clean.json) und (Musk: all_musk_posts.csv)
bestehen.

- Files mit Monatsangaben in TTA: 2021-2024: wurden einzeln mit je 2.000 Posts von https://www.thetrumparchive.com heruntergeladen
(allerdings waren es fehlerhafte json-Dateien, die extra angepasst werden mussten)
- factbase_posts_clean.json: 2024-2025: ca. 5.000 Posts von https://rollcall.com/factbase-twitter/?platform=all&sort=date&sort_order=desc&page=1 gescrapt
- tweets_01-08-2021.json: 2009-2021: von https://www.thetrumparchive.com heruntergeladen
- tta_full.json: 2009-2024: Kombination aus den Monatsfiles und tweets_01-08-2021.json; shape = 80358, 9
- tta_final_clean.json: finale Datei ohne html-Schnipsel, mit korrigiertem Datum und korrigierten IDs; shape = 85548, 14
- trump_copy.zip: indexiertes Korpus TRUMP

- all_musk_posts.csv: 2010-2025: shape = 54461, 24
- a_musk_quote_tweets.csv: 2010-2025: shape = 7147, 21
