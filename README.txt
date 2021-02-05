I due dataframe utilizzati nei files sono: "kddcup99.data.corrected" e "kddcup99.data_10_percent.corrected"

I diversi files jupyter sono:

- kddcup99_10percent.ipynb: dove si effettua lo studio sul dataframe "kddcup99_10_percent.data_10_percent.corrected" per alberi
			    che utilizzano entropy e gini.

- kddcup99_bool.ipynb: dove si implementa il classificatore per riportare in modo booleano se la connessione considerata è un 
		       attacco o è normale.

- kddcup99.ipynb: dove si effettua lo stesso processo per kddcup99_10percent.ipynb ma su quello totale.

- kddcup99_IG.ipynb: dove si studiano i miglioramenti dell'albero usando il concetto di Information Gain per ottimizzare i tempi di addestramento e preprocessing.
