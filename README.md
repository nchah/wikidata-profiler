# wikidata-profiler

This is a data profiling framework that parses the entire Wikidata data dumps to produce a series of granular descriptive statistics on the languages, properties, and items of Wikidata.

## How To

### Download Wikidata Data Dumps

- Documentation: https://www.wikidata.org/wiki/Wikidata:Database_download
- Data dumps: https://dumps.wikimedia.org/wikidatawiki/entities/

Download the JSON data dumps from the above link.

### Run Jupyter code

The code to run the profiler is in the Jupyter notebook `s1-wikidata-profiling-framework-GitHub.ipynb`

### Upload to Google Data Studio

The following output from the profiler should be uploaded to Google Drive, to be linked to Google Data Studio.

- wd-counts-entities-claims-props.tsv
- wd-counts-entities-label-desc-alias.tsv
- wd-counts-props-label-desc-alias.tsv
- wd-counts-P31-obj-sets-wlabel-wdesc-en.tsv

Clone the dashboard at https://datastudio.google.com/reporting/7f6f76eb-c24f-4a1d-b7a0-86fc4c2a55c4 and connect it to the uploaded TSVs.


## Paper

[Paper link](http://ceur-ws.org/Vol-2982/paper-13.pdf)

```

@inproceedings{chah_wikimetadata_2021,
	title = {WikiMetaData Studio: Dashboards From Data Profiling the Languages, Properties, and Items of Wikidata},
	author = {Chah, Niel and Andritsos, Periklis},
	year = {2021},
	booktitle = {Proceedings of the 2nd Wikidata Workshop (Wikidata 2021) co-located with the 20th International Semantic Web Conference (ISWC 2021)},
}
```




