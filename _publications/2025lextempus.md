---
title: "LexTempus: Enhancing Temporal Generalizability of Legal Language Models Through Dynamic Mixture of Experts"
collection: publications
category: conferences
permalink: /publication/2025lextempus
excerpt: 'We pioneer LexTempus, a dynamic mixture of experts model that explicitly models the temporal evolution of legal language in a parameter-efficient online learning framework. We validate the effectiveness of LexTempus on ECHR and EU case law datasets, demonstrating its superiority in both perplexity and open-ended text generation quality metrics.'
date: 2025-07-01
venue: 'Proceedings of the 63rd Annual Meeting of the Association for Computational Linguistics (Volume 1: Long Papers)'
paperurl: 'https://aclanthology.org/2025.acl-long.329/'
citation: 'Santosh T.y.s.s and <strong>Tuan-Quang Vuong</strong>. 2025. LexTempus: Enhancing Temporal Generalizability of Legal Language Models Through Dynamic Mixture of Experts. In Proceedings of the 63rd Annual Meeting of the Association for Computational Linguistics (Volume 1: Long Papers), pages 6608–6624, Vienna, Austria. Association for Computational Linguistics.'
---
The rapid evolution of legal concepts over time necessitates that legal language models adapt swiftly accounting for the temporal dynamics. However, prior works have largely neglected this crucial dimension, treating legal adaptation as a static problem rather than a continuous process. To address this gap, we pioneer LexTempus, a dynamic mixture of experts model that explicitly models the temporal evolution of legal language in a parameter-efficient online learning framework. LexTempus starts with a single lightweight adapter expert and dynamically expands by adding new experts as significant deviations in the data distribution are detected. This self-expansion strategy allows LexTempus to adapt to new information without forgetting past knowledge, thereby improving temporal generalization. We use a a non-parametric similarity-based router to merge relevant experts into a unified expert for each test instance, ensuring efficient inference without additional overhead. We validate the effectiveness of LexTempus on ECHR and EU case law datasets, demonstrating its superiority in both perplexity and open-ended text generation quality metrics.
