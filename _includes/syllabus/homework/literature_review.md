## Finding teammates and selecting papers for review & literature survey

To prepare for the review and literature surveys, you must find 4 teammates, select a topic for your literature survey, and select 4 papers that are related. Write a short justification for why you chose this topic, and why you chose each paper. Also describe each of the teammates' expertise.

Using the Google or Canvas form, give short explanations:

- What is the topic of your literature survey? Choose broadly,
- Write 4-5 sentences of introduction for this topic, including motivation (why it's important as a subject of study).
- For each paper, write 2-3 sentence description of its relevance to the topic.
- For each team member, write a 2-3 sentence background of the expertise and interest of each teammate with respect to the topic of study.

We will randomly assign each team member a paper from the list.

## Paper review

The review should consist of (adapted from the [ARR reviewing guide](https://aclrollingreview.org/reviewertutorial#how-to-write-a-good-review)):

- *A short summary* of the paper (5-7 sentences), written as a neutral, dispassionate summary of the research question and findings/contributions. Make sure you acknowledge **all** the contributions that you believe the paper is making: experimental evidence, replication, framing of a new question, artifacts that can be used in future work (models, resources, code), literature review, establishing new cross-disciplinary connections, conceptual developments, theoretical arguments. A paper may make several contributions, and not all of them need to be equally strong. You should state in your own words what you see as contributions of the paper, rather than copy/paste it from the abstract. 
- *Strengths of the paper*: even if you fundamentally disagree with a paper, it is important to accurately state all the best aspects of it. Once again, the strengths may come in many different forms: an engineering solution, framing an important issue, a literature review, a useful artifact (a model or a resource), a conceptual development, a reproduction. Performance improvements or complex math are by themselves neither necessary nor sufficient. It should be clear in what way the study advances the field: what did we learn from it that we did not know before? What can we do that we could not do before?
- *Weaknesses of the paper*: here, list the aspects of the paper that could be improved, of which there could be many. There may be claims that are not actually supported by the evidence or by the arguments, but that are presented as conclusions rather than as hypotheses/discussion. The framing may be misleading. There may be obvious methodological flaws (e.g., only the best run results are reported), errors in the proofs, in the implementation, or in the analysis. There may be insufficient detail to understand what was done or how to reproduce the method and the results. There may be a lack of clarity about what the research question is (even if it is “Does system A work better than system B”?), what was done, why, and what was the conclusion. The paper should also make it clear in what way the findings and/or the released artifacts advance the field.
  A common reviewer mistake is confusing "must-haves" (weaknesses) with "nice-to-haves" (often, possible follow up or alternative experiments). Any project has limited time and pages, and it is always possible to think of more follow-up experiments. As long as enough work was done to prove the claims that the authors are making, any extra experiments are in the “nice-to-have” category, and not a weakness as such.
- *Future directions and remaining open questions*: to get you started thinking about your capstone, we want you to think about remaining open questions with respect to the broader goal of the paper, as well as any future directions you can think of. These could include methodological changes or improvements to the method, adaptations to new domains, follow up experiments to run, etc. Make sure to mention follow up experiments that would shed important light onto the paper's main research goals and why the follow up directions would be required,(e.g., avoid simply saying "they should try it on another dataset", make sure to motivate why the paper's main research question would benefit from another dataset).

You must turn in your review using LaTex with Bibtex, using the ARR style format ([LaTeX templates](https://acl-org.github.io/ACLPUB/formatting.html), also available as an [Overleaf template](https://www.overleaf.com/latex/templates/association-for-computational-linguistics-acl-conference/jvxskxpnznfj)).

## Practice literature review

The goal of this assignment is to develop your skills in reviewing and synthesizing academic literature in the your subfield of data science. You will select a task and topic area, choose 4 related recently published research papers, and summarize and compare their methodologies, findings, and contributions. Additionally, you will identify and discuss any gaps or open questions that remain in the research. The review should be comprehensive yet concise, spanning 2 to 3 pages.

1. **Read and Analyze Your Chosen Papers:**
   - Thoroughly read each paper, taking notes on key points such as:
     - Research objectives and questions.
     - Methodologies and techniques used.
     - Key findings and results.
     - Contributions to the field.
     - Limitations and future research directions.
2. **Summarize the Papers:**
   - Write a brief summary for each of the four papers. Each summary should include:
     - A concise overview of the research problem and objectives.
     - Description of the methods and techniques employed.
     - Summary of the main findings and conclusions.
     - Discussion of the paper's contributions to the field.
3. **Compare and Contrast the Papers Along Various Dimensions:**
   - Analyze the similarities and differences among the papers in terms of the following dimensions:
     - Research questions and objectives.
     - Methodological approaches.
     - Dataset, domain, scope.
     - Key findings and results.
     - Contributions and impact on the field.
   - Identify common themes, patterns, and trends that emerge from the comparison.
4. **Discuss Open Questions and Future Directions:**
   - Highlight any gaps or open questions that the papers leave unanswered.
   - Discuss potential areas for future research based on the identified gaps.
   - Reflect on how addressing these questions could advance your subfield.
5. **Write the Structured Review:**
   - Organize your review into a coherent and logical structure, according to this structure:
     - **Introduction:** Introduce the topic area and the importance of the selected task within data science. Provide a brief overview of the four papers you will review.
     - **Summaries:** Provide individual summaries of the four papers, focusing on highlighting the details of each paper's approach that you will focus on in the comparison part. Suggestion: avoid writing more than a 1/4 page (1/2 column) for each summary), and use the `\paragraph` command for each new paper.
     - **Comparison:** Compare and contrast the methodologies, findings, domains, and contributions of the papers. Suggestion: have one subsection for each of the dimensions.
     - **Open Questions:** Discuss the gaps and open questions that remain.
     - **Conclusion:** Summarize the main points of your review and suggest directions for future research.
6. **Format and Submission:**
   - The review should be between 2 to 3 pages in length, not including references.
   - Use LaTex with Bibtex, using the ARR style format ([LaTeX templates](https://acl-org.github.io/ACLPUB/formatting.html), also available as an [Overleaf template](https://www.overleaf.com/latex/templates/association-for-computational-linguistics-acl-conference/jvxskxpnznfj)). 
   - Proofread your review to ensure clarity, coherence, and correctness.
   - Submit your assignment by the specified deadline.

Some notes:

- You can and are encouraged to cite more than just the required papers, especially in the introduction (e.g., to motivate the existence of the research area) and future directions sections (e.g., to give ideas of how to address open gaps).
- You can include at most one figure and one table in your write-up. They must bring in useful information that isn't better written in text.
- Example published literature reviews (which are useful to learn how to frame reviews, we do not expect as much work as these published reviews):
  - Human-centered/NLP: https://aclanthology.org/P19-1159.pdf
  - Analytics/NLP: https://aclanthology.org/2020.coling-main.247.pdf
  - Systems: https://ietresearch.onlinelibrary.wiley.com/doi/full/10.1049/cdt2.12016
  - Data science/ML: https://arxiv.org/abs/2402.16827
  - LLMs/Systems: https://arxiv.org/abs/2312.03863

Rubric:

- *2 points* - Formatting & turning in assignment: did the student turn in the assignment on time? Is it using Latex & fits within the page limit?
- *3 points* - Coherent choice of papers: are the papers related to the same overall topic?
- *5 points* - Introduction
  - Does the review introduce the topic area well (with examples)? Does it motivate why the task is meaningful or important? Does it give an overview of the literature review?

- *12 points* - Summaries
  - For each paper: Does the review summarize the papers' main task and overall topic? Does it summarize papers' methodology, approach? Does it summarize the papers' main results, findings, and takeaways?

- *20 points* - Comparison. For each dimension: 
  - Does the review appropriately compare the similarities the papers of the papers? Does the review contrast the papers appropriately? If some dimensions are not applicable, does the review mention it? Does the review go beyond simply restating what papers did, but instead tie the papers together thematically and relationally?
  - Dimensions: Research questions and objectives; Methodological approaches; Dataset, domain, scope; Key findings and results.

- *10 pts* - Open Questions. Does the review appropriately outline open questions that are remaining? Does the review mention future directions for next research projects towards tackling the broader task? Does the review provide possible methods for tackling these future directions? Does the review mention more than 2 open remaining questions?
- *3 pts* - Conclusion - Does the review appropriately summarize the task at hand, and papers examined? Does it briefly mention open questions or future work? Is the conclusion an appropriate length (~1/4-1/2 column)?

Total: 55 points

## Literature review

The goal of this assignment is to further finetune your skills in reviewing and synthesizing academic literature in the your subfield of data science. You will build on top of the existing practice literature review, adding 4 more papers, and incorporating the comments from TAs. The final review should 5-6 pages.

You should find 4 related papers, preferably ones that are cited in your other 4 papers, or that cite one/some of the 4 papers. 

Rubric:

- *2 points* - Formatting & turning in assignment: did the student turn in the assignment on time? Is it using Latex & fits within the page limit?
- *3 points* - Coherent choice of papers: are the papers related to the same overall topic?
- *5 points* - Introduction
  - Does the review introduce the topic area well (with examples)? Does it motivate why the task is meaningful or important? Does it give an overview of the literature review?
- *24 points* - Summaries
  - For each paper: Does the review summarize the papers' main task and overall topic? Does it summarize papers' methodology, approach? Does it summarize the papers' main results, findings, and takeaways?
- *40 points* - Comparison. For each dimension: 
  - Does the review appropriately compare the similarities the papers of the papers? Does the review contrast the papers appropriately? If some dimensions are not applicable, does the review mention it? Does the review go beyond simply restating what papers did, but instead tie the papers together thematically and relationally?
  - Dimensions: Research questions and objectives; Methodological approaches; Dataset, domain, scope; Key findings and results.
- *20 pts* - Open Questions. Does the review appropriately outline open questions that are remaining? Does the review mention future directions for next research projects towards tackling the broader task? Does the review provide possible methods for tackling these future directions? Does the review mention more than 2 open remaining questions?
- *6 pts* - Conclusion - Does the review appropriately summarize the task at hand, and papers examined? Does it briefly mention open questions or future work? Is the conclusion an appropriate length (~1/4-1/2 column)?

Total: 100 points