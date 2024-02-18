



# Responses to the Reviewers' comments

We appreciate the editor and reviewers for the comments we have received. We have considered all the comments in the current revision. The improvements are indicated in the manuscript using track changes.

The final version of the manuscript can be obtained by replacing the line:

> \usepackage[draft]{changes}

 in the "Article.tex" file with:

> \usepackage[final]{changes}

The manuscript is hosted on the following GitHub repository:

> https://github.com/rodrifonsi/ESE-Process

In some cases, the changes could not be highlighted in the document due to limitations of the *changes* package. However, these changes can be identified by performing a diff between the HEAD and HEAD~1 versions of the .tex files using the following command:

> git diff 

Below, we detail the responses to the reviewers' comments and the changes made:

**Comment 1** - Please add recent references.

*Response to Comment 1* - We have included the following recent references:

> Shepperd, M., Ajienka, N., Counsell, S.: ‘The role and value of replication in empirical software engineering results’, Information and Software Technology, 2018, 99, pp. 120–132

> Cockburn, A., Dragicevic, P., Besançon, L., Gutwin, C.: ‘Threats of a replication crisis in empirical computer science’, Communications of the ACM, 2020, 63, (8), pp. 70–79

> The International Organization for Standardization: ‘ISO/IEC 20000-1:2018 Information Technology - Service Management - Part 1: Service Management System Requirements’. 2018. https://www.iso.org/standard/70636.html

>European Commission. ‘Researchcomp: The european competence framework for researchers’. 2022. Accessed: 2024-02-18. https://research-and-innovation.ec.europa.eu/document/download/7da29338-37bf-4d51-b5eb-a1571b84c7ad_en?filename=ec_rtd_research-competence-presentation.pdf

**Comment 2** - Add some future scope conclusion section.

*Response to Comment 2* - Thank you for your suggestion. We have created a Section titled *Implications for practice* containing the following information:

> Our findings suggest specific improvements that could be applied to SE experimentation. The first and most evident is transitioning from an experimental process primarily based on the application of experimental designs and the conduct of statistical analyses to a more professional approach based on explicit processes, activities, and roles, as is customary in many areas, e.g., Information Technology \cite{iso20000}.
>
>It could be argued that current SE experimentation already has a well-defined process and activities, as can be seen, e.g., in the works of Juristo \& Moreno \cite{Juristo-2001-SE-experimentation} or Wohlin \textit{et al.} \cite{Wohlin-2000-Experimentation-SE}. However, as we have argued before, such a process and activities represent only an idealization of the activities performed in practice. We refer to more detailed processes and activities (such as the process models we provide in this work).
>
>Detailed processes and activities only make sense within specific research areas or even families of experiments. For example, Arcuri \& Briand \cite{Arcuri-2014-randomized} have published recommendations for the statistical analysis of randomized algorithms. Arcuri \& Briand do not claim that their recommendations have general applicability. Other areas of SE, such as programming or testing, will need specific recommendations. Although this may seem strange or unusual, a cursory examination of experimental literature in other sciences demonstrates the opposite. For example, in Psychology, there are recommendations on how to measure motivation \cite{toure2014measure} or consider experience \cite{hoffman1998can}. In Medicine, there are models of pain \cite{petersen2002pain}. Other examples could be cited, but all of them agree on highlighting the specificities of a research area instead of hiding details in abstractions that ultimately prove inoperative.
>
>Finally, we must add specific competencies to processes, activities, and roles, such as negotiation skills, asset curation, or human resource management. Again, SE is lagging behind established trends in other areas. To cite a very relevant example, the European Union \cite{ResearchComp} has defined a framework containing seven competency areas, 38 competencies, and 389 learning outcomes for researchers. Other institutions have undertaken similar efforts.

We have also separated in specific sections the research *limitations* and the *future work*.

# Other issues

We have updated the *Acknowledgement* section to comply with the requirements imposed by our funding agency. The text of this section now reads:

> This work was supported by the grant PID2022-137846NB-I00 funded by MCIN/AEI/10.13039/501100011033, and by ''ERDF A way of making Europe'', and the Universidad de las Fuerzas Armadas - ESPE's Grupo de Investigación en Modelos de Producción de Software e Industria Inteligente (GrIMPSoftII). 
