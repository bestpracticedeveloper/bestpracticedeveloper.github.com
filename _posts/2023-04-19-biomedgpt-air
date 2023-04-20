---
layout: post
title: BioMedGPT, The Ultimate LLM in Biomedicine
date: 2023-04-19
published: true
---

In the field of biopharmaceutical research and development, a lightweight research version of a basic model called BioMedGPT-1.6B has just been open-sourced.

With 1.6 billion parameters, its biggest feature is the integration of cross-modal and knowledge fusion. The training data includes multi-scale cross-modal biopharmaceutical big data such as molecules, literature, patents, and knowledge bases, as well as the integration of knowledge from molecular structures, knowledge graphs, and literature texts, to enhance the model's generalization ability and interpretability.

Regarding its application tasks, BioMedGPT-1.6B demonstrates excellent performance in multiple tasks such as drug property prediction, natural language processing, and cross-modal processing.

The team behind the development of BioMedGPT-1.6B is from the Tsinghua Institute of Artificial Intelligence (AIR). The project leader, Professor Nie Zaiqing, is a chief researcher at AIR and a professor at Tsinghua University, with a research focus on cutting-edge innovations in big data and AI, as well as industrial applications in the health and medical field. Previously, he was well-known as a chief scientist of Tmall Genie and a top researcher at Alibaba Damo Academy.

The open-sourcing of BioMedGPT-1.6B is actually a lightweight version of BioMedGPT, which is a universal large-scale model for biopharmaceutical research and development that the team is currently working on. The purpose of releasing the 1.6B version is to test the waters and provide a tool for industry-related researchers.

<!-- more -->

Professor Nie Zaiqing explains the reasoning behind BioMedGPT and the team's progress so far. Despite the existence of many large-scale models for biopharmaceutical specialties in the industry, they have considered developing a universal large-scale model and how to approach it.

Let's take a look at what the BioMedGPT project is and at what stage it is currently at.

Professor Nie Zaiqing believes that just as ChatGPT has become the foundational large model in the field of natural language processing, BioMedGPT will also become the foundational large model in the field of biomedicine.

However, in this case, "like ChatGPT" does not just mean that BioMedGPT is a biomedical large model with conversational abilities, but rather that, like ChatGPT, there will be instances of intelligence emergence.

In this case, "intelligence" refers to the understanding of biomedical knowledge, the discovery of regularities, and the inspiration of ideas.

The foundation of this model can provide basic capabilities for drug discovery, molecular/protein design, and other applications, while also serving as a co-pilot for biomedical researchers to conduct research more efficiently.

So, what does BioMedGPT look like in terms of architecture to achieve this effect?

Overall, it is a model with multiple input encoders that first process different modalities of input, such as molecules, proteins, and literature, separately.

Then, these different modalities of input are processed into a unified representation so that the model can learn the associated knowledge between different modalities.

This gives the model the ability to "connect the dots" and read literature, patents, as well as molecular sequences, protein structures, and experimental data.

Moreover, BioMedGPT is the first project to introduce multi-modal knowledge into model building. It injects biomedical knowledge into the model through a knowledge graph to enhance the model's generalization and interpretability, while also being able to adapt to the rapid turnover of knowledge in the scientific research field, allowing the model to continue learning and becoming "smarter".

Based on this ability to connect the dots and enhance knowledge, BioMedGPT has shown overall improvement in multiple downstream tasks.

The team has already completed the experimental verification phase and demonstrated the feasibility of this approach using a relatively small end-to-end model.

So, what is the expected scale of a model that can exhibit intelligence emergence in biomedicine?

Professor Nie Zaiqing predicts that the model's parameter scale is expected to be around several hundred billion, and the amount of data required to train the model to achieve intelligence emergence is estimated to be several billion to tens of billions.

In fact, before ChatGPT appeared, more than a year ago, Professor Nie Zaiqing and his team were already preparing for this project. Currently, the size of the Tsinghua AIR life science-related team has reached about 50 people.

Regarding the future of BioMedGPT, Professor Nie Zaiqing is very confident:

"Within two years, this model should have a certain degree of influence in a small range. As for becoming a universal large model in the industry, achieving the same level of influence as ChatGPT may still require at least 3-5 years."

## "A Rational and Bold Choice"
In the fields of biology and chemistry, the essence of life can be viewed as a precise coding language, particularly in the microcosmic world of molecular sequence data in life sciences. Professor Nie Zaiqing believes that natural language is also a very precise sequence, where a small deviation or omission can lead to a different meaning. Therefore, the two have similar features. Based on this, the underlying principles of large models may be applicable to the processing of microcosmic data in life sciences. If achieved, it would be possible to leverage professional knowledge in the biomedical field to assist in research tasks.

Before the project officially began, the team compressed microcosmic data (genes, molecules, proteins, and cells) and literature knowledge into an end-to-end model, and validated the feasibility of this approach through experimentation. They achieved state-of-the-art (SOTA) results in some downstream tasks critical to drug development.

Thus, the development of a fundamental large model applicable to the biomedical industry began. Previously, teams had created large models specifically for molecules, proteins, or biomedical literature, but no one had developed a multi-modal version applicable to the entire industry. The current open-source version, BioMedGPT-1.6B, is not yet close to AGI or even comparable to the abilities of ChatGPT.

"Since everyone's expectations are quite high, we still need to lower them," explained Professor Nie Zaiqing, who was gracious in stating that the current model's capabilities have not yet reached an ideal state. "In reality, our main goal is to serve researchers who are conducting relevant studies."

However, Professor Nie Zaiqing described this attempt as a rational and bold choice. It is rational because it was confirmed through experiments that encoder-processed human knowledge can be helpful, and it is bold because, on one hand, the commercial value of this work has not yet been fully proven, and on the other hand, the work is still in its preliminary stages, and the model's size and modality need to be expanded.

Nonetheless, despite this optimistic estimate, the work has progressed and a lightweight version has been quickly produced. The optimism is not baseless, as Professor Nie Zaiqing stated that there are no concerns with data, computation power, or costs for BioMedGPT at this time. In terms of data quality, the quality of biomedical literature and patents is "still quite high," so there is no need to worry excessively about low-quality training corpus situations. Additionally, the team gathered students with biomedical backgrounds to design and annotate the dataset professionally and meticulously.

Of course, some private data is required for certain tasks, and BioMedGPT hopes to supplement this through future two-way dry-wet cycles.

## The Illusion of LLM
Finally, we also posed the soul-searching question to Professor Nie Zaiqing - in the realm of biopharmaceutical research and development, where there is no room for error, how do we constrain the illusion of large-scale models?

Professor Nie Zaiqing offered a tongue-twisting response:

"Of course, we hope that the large-scale model knows _what it knows_ and _what it doesn't know._ However, it is currently possible for the model to _not know what it doesn't know._"

When the large-scale model "doesn't know what it doesn't know," it is what we commonly refer to as the illusion of the model - it thinks it knows, but in reality, it does not.

To address this issue in the field of biopharmaceuticals, the solution is to use two closed loops to "correct" the model.

The first loop involves wet-lab experiments to verify the model's accuracy and to bring it closer to the physical reality of the world. The second loop involves expert-guided design to align the model's cognition with that of human experts.

In other words, the use of "experimental verification" and "expert guidance" loops can reduce the illusion of AI models.

The next step for Nie Zaiqing and his team is to use these two loops to expand the range of "what the large-scale model knows it can do" as much as possible, thus further reducing the proportion of the large-scale model that "doesn't know what it doesn't know."

Regarding this open-source release, Zhang Yaqin, a member of the Chinese Academy of Engineering, Tsinghua University Professor and President of the Institute of Artificial Intelligence and Robotics, commented:

"The application of the large-scale model paradigm to the life sciences is a rational and bold exploration.
The research team at AIR has set the goal of constructing large-scale AI models in the field of biopharmaceuticals and has developed several AI models in various biopharmaceutical domains, achieving good results in protein structure prediction, antibody design, and other areas.
The open-source release of the BioMedGPT-1.6B lightweight research version of the basic model is a significant advancement in the field of life sciences.
In the future, the research team will continue to use BioMedGPT to further integrate heterogeneous data sources in the field, incorporate knowledge into model construction, and achieve unified representation learning of biological text and knowledge, bringing about _intelligent emergence_ in the biopharmaceutical field."
