---
title: "Are Multi-language Design Smells Fault-prone? An Empirical Study"
collection: publications
permalink: /publications/TOSEM2021
date: 2021-02-10
paperurl: "/files/tosem-2021.pdf"
citation: 'Mouna Abidi, <b>Md Saidur Rahman</b>, Moses Openja and Foutse Khomh &quot;Are Multi-language Design Smells Fault-prone? An Empirical Study&quot; <i>ACM Transactions on Software Engineering and Methodology (<b>TOSEM</b>)</i>. Volume 30 (3), Article 29, pages 56, 2021.'
---
<br>

## Abstract
Nowadays, modern applications are developed using components written in different programming languages
and technologies. The cost benefits of reuse and the advantages of each programming language are two main
incentives behind the proliferation of such systems. However, as the number of languages increases, so does
the challenges related to the development and maintenance of these systems. In such situations, developers
may introduce design smells (i.e., anti-patterns and code smells) which are symptoms of poor design and
implementation choices. Design smells are defined as poor design and coding choices that can negatively
impact the quality of a software program despite satisfying functional requirements. Studies on mono-language
systems suggest that the presence of design smells may indicate a higher risk of future bugs and affects code
comprehension, thus making systems harder to maintain. However, the impact of multi-language design
smells on software quality such as fault-proneness is yet to be investigated.
In this paper, we present an approach to detect multi-language design smells in the context of JNI systems.
We then investigate the prevalence of those design smells and their impacts on fault-proneness. Specifically, we
detect 15 design smells in 98 releases of nine open source JNI projects. Our results show that the design smells
are prevalent in the selected projects and persist throughout the releases of the systems.We observe that in the
analyzed systems, 33.95% of the files involving communications between Java and C/C++ contain occurrences
of multi-language design smells. Some kinds of smells are more prevalent than others, e.g., Unused Parameters,
Too Much Scattering, Unused Method Declaration. Our results suggest that files with multi-language design
smells can often be more associated with bugs than files without these smells, and that specific smells are more
correlated to fault-proneness than others. From analyzing fault-inducing commit messages, we also extracted
activities that are more likely to introduce bugs in smelly files. We believe that our findings are important for
practitioners as it can help them prioritize design smells during the maintenance of multi-language systems.