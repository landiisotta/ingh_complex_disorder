1) run create_ehr_cohorts.py --> cohort-ehr.csv, cohort-vocab.csv, cohort-person.csv.
2) run filter_collection_frequencies.py --> stop-words.csv, collection-frequencies.csv.
3) run preprocessing_ehr.py to remove the stop clinical terms (high/low occurrencees), 
   order the sequences w.r.t age in days,
   divide the sequences in subsequences of unique terms T (start with T=15) days long,
   shuffle the terms in the subsequences.
   
