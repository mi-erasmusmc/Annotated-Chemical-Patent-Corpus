# Annotated-Chemical-Patent-Corpus

Exploring the chemical and biological space covered by patent applications is crucial in early-stage medicinal chemistry activities. Patent analysis can provide understanding of compound prior art, novelty checking, validation of biological assays, and identification of new starting points for chemical exploration. Extracting chemical and biological entities from patents through manual extraction by expert curators can take substantial amount of time and resources. Text mining methods can help to ease this process. To validate the performance of such methods, a manually annotated patent corpus is essential.

In this study we have produced a large gold standard chemical patent corpus. We developed annotation guidelines and selected 200 full patents from the World Intellectual Property Organization, United States Patent and Trademark Office, and European Patent Office. The patents were pre-annotated automatically and made available to four independent annotator groups each consisting of two to ten annotators. The annotators marked chemicals in different subclasses, diseases, targets, and modes of action. Spelling mistakes and spurious line break due to optical character recognition errors were also annotated. A subset of 47 patents was annotated by at least three annotator groups, from which harmonized annotations and
inter-annotator agreement scores were derived. One group annotated the full set. The patent corpus includes 400,125 annotations for the full set and 36,537 annotations for the harmonized set.

Availability
The Patent corpus is available in 3 different sets:
1-Harmonized_set: Consisting of 47 patents annotated by at least 3 annotation groups and later harmonized.
2-Full_set: Consisting of 198 patents annotated by 1 annotation group.
3-Training_set: Consisting of 2 patents annotated by 4 annotation groups and later harmonized.

The following labels are used for the different entity types within the corpus:

* "M" for IUPAC.
* "I" for SMILES.
* "Y" for InChi.
* "D" for Trademark.
* "B" for Abbreviation.
* "C" for CAS number.
* "F" for Formula.
* "R" for Registry Number.
* "G" for Generic.
* "T" for Target.
* "Disease" for Disease.
* "MOA" for MOA.
* "OCRERRORSPELL" for Spelling error.
* "OCRERRORLINE" for Spurious line break.

The annotation.conf file can be used along with the visual.conf file to visualize the data in a local Brat installation.

All patents and annotated entities are publicly available in brat format from the following link.

**Citing the Chemical Patent Corpus**

If you have used the corpus in your study, please cite:

_Akhondi SA, Klenner AG, Tyrchan C, Manchala AK, Boppana K, Lowe D, Zimmermann M, Jagarlapudi SARP, Sayle R, Kors JA, Muresan S. (2014) Annotated Chemical Patent Corpus: A Gold Standard for Text Mining. PLoS ONE 9(9): e107477. doi:10.1371/journal.pone.0107477_
