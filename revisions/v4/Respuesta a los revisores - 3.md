# Responses to the Reviewers' comments

We appreciate the editor and reviewers for the comments we have received. We have considered all the comments in the current revision. The improvements are indicated in the manuscript using track changes. Each change is labeled with a version tag (v2, v3, v4) and a different color to ease the review process.

The final version of the manuscript can be obtained by replacing the line:

> \usepackage[draft]{changes}

 in the "Article.tex" file with:

> \usepackage[final]{changes}

The manuscript is hosted on the following GitHub repository:

> https://github.com/rodrifonsi/ESE-Process

In some cases, the changes could not be highlighted in the document due to limitations of the *changes* package. However, these changes can be identified by performing a diff between the HEAD and HEAD~# versions of the .tex files using the following command:

> git diff  HEAD~# *.tex

Below, we detail the responses to the reviewers' comments and the changes made:

## Reviewer 1

**Comment 1.1** - GENERAL COMMENTS: (1) The present work seems to be a revised manuscript. The author smartly updated the manuscripts as per journal requirements to justify the proposed work with focused research.

*Response to Comment 1.1* - It is correct. The original version of this manuscript is available at https://arxiv.org/abs/2108.12800 and has undergone several improvements through the review process.

<br>

**Comment 1.2** - (a) The purpose of this work is to catalogue typical software engineering experimentation procedures or conventions. It was difficult to find multiple groups with the necessary experience, motivation, and predisposition for the research, so instead of doing it for brief periods of time in different research groups, the author conducted an ethnographic study within a specific and very representative software engineering research group for just over two years.

*Response to Comment 1.2* - We applied an ethnographic approach. Such a methodology reveals detailed information about the *real* experimental process but requires a long observation time. That is why we chose to focus on a single group.

<br>

**Comment 1.3** - (b) The manuscript is good and should be considered for publication.

*Response to Comment 1.3* - Thank you!

<br>

**Comment 1.4** - (2) The author smartly presented the problem statement with a contribution:

(a) Identifying activities that depart from or are not described in mainstream experimentation procedures.

(b) Characterising roles, i.e., groups of experimental activities performed by the same person, in Empirical Software Engineering (ESE) research.

(c) Evidence of the existence of tacit knowledge in ESE, which, in turn, leads to discrepancies between experimentation protocols and actual practice.

(d) Conceptual and process models that represent how experimentation is conducted in practice in an experimental research group.

*Response to Comment 1.4* - It is correct. These are the main  contributions of our research.

<br>

**Comment 1.5** - (3) A new section is recommended, if it can be done. But the present paper also fits well:

(a) There should be a nomenclature table (abbreviation used table) at the end of the manuscript.


*Response to Comment 1.5* - Such a table has been added after the references, at the end of the paper, as an appendix. It contains the following acronyms and abbreviations:
- EM: Experiment Manager
- EPM: Experimental Process Model
- EPW: Experimental Process Workflow
- ESE: Empirical Software Engineering
- RGUS: Research Group Under Study
- RM: Research Manager
- SE: Software Engineering
- SrEx: Senior Experimenter

<br>

**Comment 1.6** -  (a) The author smartly updated the manuscripts as per journal requirements to justify the proposed work with focused research.

*Response to Comment 1.6* - Thank you!

<br>

**Comment 1.7** -  (1) The author provides a method to investigate and determine how experimental researchers conduct experiments in practice. The author intends to find out how experimental researchers plan, execute, analyse, and report their investigations and what concepts, protocols, and processes they use using an ethnographic method within an experienced experimental research group. By observing the researchers in their lab for two years, conceptual and process models were created to represent the concepts they use and the activities they perform daily. These models fit the community’s procedures and terminology at a high level. Still, the models show particularities at lower levels:

(a) the number and diversity of activities;

(b) the existence of different roles;

(c) the granularity of the concepts used by the roles; and

(d) the viewpoints that different sub-areas or families of experiments have about the overall process.

*Response to Comment 1.7* - The existence of various levels of concepts has been one of the greatest surprises of our research. At a general level, experimenters communicate using general concepts, but when delving into their specific field of research, they begin to use particular concepts that are not necessarily comprehensible to experimenters from other fields. Likewise, each experimenter plays a specific role in the experimentation process, which involves performing particular tasks that other roles do not perform.

<br>

**Comment 1.8** -  (2) The author preferred the methods for:

(a) To verify the existence of terminological diversity, one of the first aspects that emerged in the research and is relatively easy to check. The authors have already started this work and surveyed SE experimenters from multiple research groups.

(b) In the survey, it is asked about the meaning and usage of experimentation-related terms. Preliminary results confirm the existence of terminological diversity.

*Response to Comment 1.8* - The survey has been completed, and the results are aligned with this manuscript's conclusion: Terminological diversity exists in Experimental Software Engineering. The new manuscript is not publicly available because it has not been translated into English yet. A Spanish version is available at this link: https://short.upm.es/5u2ih

<br>
  
**Comment 1.9** - (c) After completing the ethnographic research, a comparative study was initiated of the experimental process between SE and an established engineering discipline (specifically, biotechnology).

*Response to Comment 1.9* - The comparative study has been completed too. The comparison results are available in the same link as above: https://short.upm.es/5u2ih

<br>

**Comment 1.10** - (d) Preliminary results indicate the absence of terminological diversity and a greater formalisation of the experimental process within specific research areas but not at a general level. This could be the key to terminological diversity in SE: sub-areas of SE generally have not developed specific terminology and protocols, which could lead to the need for ad hoc concepts and processes.

*Response to Comment 1.10* - This is the main message we want to convey to the community of experimenters in Software Engineering. For some time, there have been various attempts to standardize experimental activities without success. Our proposal is not to try to standardize all fields under a single scheme but to work within specific fields and carry out standardization therein. Proceeding as such can improve the replication and synthesis of experiments.

<br>

**Comment 1.11** - (3) Directions for Researchers:

(a) The researcher will get insights and research direction towards looking at ways to better optimise the objects under study and the methodologies used since ethnography is very demanding. A possibility for studying the impact of specialisation in the sciences is to analyse experimental repositories.

*Response to Comment 1.11* - This is a rather exciting research direction. There are numerous isolated experimental data files, as well as data repositories and ontologies with various degrees of formality. These data items are structured based on the conceptualization that researchers have of their study fields. Reviewing experimental data and ontologies would allow, at least a priori, for obtaining information about this conceptualization more efficiently than conducting surveys or ethnographies.

<br>

**Comment 1.12** - (b) This represents an indirect but efficient approach in terms of time and effort. Another alternative is conducting qualitative studies using focus groups composed of SE experimental researchers.

*Response to Comment 1.12* - Another alternative, indeed, is to use research methods such as interviews or focus groups. These strategies are also very efficient, but they have the problem of not adequately addressing the experimenters' tacit knowledge. Precisely for this reason we chose an ethnographic methodology in the initial research.

## Reviewer 2

**Comment 2.1** - The work aligns with the scope of the journal. I have no comments on the content of the paper; it is evident that the authors have already addressed previous reviewers' comments. However, I would like to emphasize that relatively old references have been utilized. Out of 59 references, 34 are 10 years old or older. Could more recent literature have been incorporated?

*Response to Comment 2.1* - You are completely right. We added the following recent references:

- Mahmood, Z., Bowes, D., Hall, T., Lane, P.C., Petric ́, J.: ‘Reproducibility and replicability of software defect prediction studies’, Information and Software Technology, 2018, 99, pp. 148–163
- dos Santos, D.A., de Almeida, E.S., Ahmed, I.: ‘Investigating replication chal- lenges through multiple replications of an experiment’, Information and Software Technology, 2022, 147, pp. 106870
- Zhang, H., Huang, X., Zhou, X., Huang, H., Babar, M.A. ‘Ethnographic research in software engineering: a critical review and checklist’. In: 2019 joint meeting on European software engineering conference and symposium on the foundations of software engineering (ESEC-FSE). Tallinn, Estonia: ACM, 2019. pp. 659–670
- Wang, Z., Liu, B., Zhan, Z., Zhang, H., Li, G. ‘An ethnographic study on the ci of a large scale project’. In: 2024 International Conference on Software Engineering: Software Engineering in Practice (SEIP). Lisboa, Portugal: ACM, 2024. pp. 287– 297
- de Souza.Santos, R.E., Ralph, P. ‘Practices to improve teamwork in soft- ware development during the covid-19 pandemic: An ethnographic study’. In: 2022 International Conference on Cooperative and Human Aspects of Software Engineering (CHASE). Pittsburgh, Pennsylvania, United States: ACM, 2022. pp. 81–85
- Modi, B.A., Cain, A., Wood.Bradley, G., Renzella, J. ‘Using focus to personalise learning and feedback in software engineering education’. In: 2023 International Conference on Software Engineering: Software Engineering Education and Training (SEET). Melbourne, Australia: IEEE, 2023. pp. 296–301
- Runeson, P., Olsson, T. ‘Challenges and opportunities in open data collaboration – a focus group study’. In: 2020 Euromicro Conference on Software Engineering and Advanced Applications (SEAA). online: IEEE, 2020. pp. 205–212
- Sowden, P.T., Pringle, A., Peacock, M. ‘Verbal protocol analysis as a tool to understand the creative process’. In: Handbook of Research Methods on Creativity. Cheltenham, UK: Edward Elgar Publishing, 2020. pp. 314–328
- Collins, H. ‘Collective and distributed knowledge: Studies of expertise and experience’. In: The Routledge Handbook of Philosophy and Implicit Cognition. London, UK: Routledge, 2022. pp. 202–214

<br>

**Comment 2.2** - While the primary focus of the review should not be on formatting, it is crucial to correct typos and formatting errors before the paper's publication. This is particularly noticeable in the reference list, where references 6, 10, 16, 17, 23, 24, 32, 33, 34, 37, 39, 31, 43, 50, 52, 53, 56, and 58 contain errors.

*Response to Comment 2.2* - Thank you for noticing this problem. The formatting problems were due to missing attributes in our bibtex file, and also due to inconsistencies in the publisher .bst file (which defines how the references are formatted). We have fixed the issues and reviewed all references in the bibliography. The references should be displayed consistently now.

<br> 

**Comment 2.3** - Additionally, there is inconsistency in in-text citations. For example, there is inconsistency in the order of listing multiple references (in multiple instances, e.g., [37] [35]) and in the format used, such as "p." for [18, p. 71–73], and "pp." for [15, pp. 55-56], as well as the format "pp." or "p." in the reference list.

*Response to Comment 2.3* - Thank you very much for pointing this out:
- We have fixed the LaTex *\cite{}* commands to maintain the right order in multiple citations. Previously, we were citing papers using multiple *\cite{}* commands. Right now, we are using a single command with multiple references inside.
- We have fixed the *page(s)*'s acronym, using "pp." to refer to multiple pages, and "p." to refer to a single page. We are using the same convention as the EIT Software .bst file.
