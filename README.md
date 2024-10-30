# **Mini Project 2**
*Ella Stasko*

*10.30.2024*


---

**Introduction**

The second Mini Project aims to use machine learning (ML) to build novel binding proteins to EGFR and evaluate the probable efficacy of each potential sequency using multiple metrics. The motivation behind this project is rooted in the importance of protein design and the possibilities emerging due to advancements in ML.

**Protein Design**

RF Diffusion, a protein design method available for public use, was used to determine possible binding sequences for EGFR. The results of this are seen in the RFDiffusion.ipynb This uses multiple different metrics to determine which sequence is the most promising.


**Binder Comparison**


Each student in the class was required to create a potential binding protein sequence for EGFR. Thus, with access to many different potential binders, a comparison using an open source notebook was completed. This uses the metric of Masked Language Model loss where the lower the value obtained, the more likely that the proteins would bind and can be seen in the "Protein_Protein_interactions.ipynb" file.

**Conclusions**


All of the discovered proteins faired similarly, with MLM losses within 5 units. At this point in time, these algorithms only produce viable proteins a few out of a hundred times and so it is not surprising, though maybe a bit disappointing, that none of the proteins perform spectacularly.
