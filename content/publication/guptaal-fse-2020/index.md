---
title: "Machine Translation Testing via Pathological Invariance"
date: 2020-08-01
publishDate: 2020-04-06T05:47:36.453048Z
authors: ["Shahij Gupta", "Pinjia He", "Clara Meister", "Zhendong Su"]
publication_types: ["1"]
abstract: "Machine translation software has become heavily integrated into our daily lives due to the recent improvement in the performance of deep neural networks. However, machine translation software has been shown to regularly return erroneous translations, which can lead to harmful consequences such as economic loss and political conflicts. Additionally, due to the complexity of the underlying neural models, testing machine translation systems presents new challenges. To address this problem, we introduce a novel methodology called PatInv.  The main intuition behind PatInv is that sentences with different meanings should not have the same translation. Under this general idea, we provide two realizations of PatInv that given an arbitrary sentence, generate syntactically similar but semantically different sentences by: (1) replacing one word in the sentence using a masked language model or (2) removing one word or phrase from the sentence based on its constituency structure. We then test whether the returned translations are the same for the original and modified sentences. We have applied PatInv to test Google Translate and Bing Microsoft Translator using 200 English sentences. Two language settings are considered: English to Hindi (En-Hi) and  English to Chinese (En-Zh). The results show that PatInv can accurately find 308 erroneous translations in Google Translate and 223 erroneous translations in Bing Microsoft Translator, most of which cannot be found by the state-of-the-art approaches."
featured: false
publication: "*Proceedings of the 28th ACM Joint European Software Engineering Conference and Symposium on the Foundations of Software Engineering*"
publication_short: "FSE"
links:
url_pdf: https://dl.acm.org/doi/10.1145/3368089.3409756
---

