# Model Types

The first two days of NMA are all about the process of modeling and what models are. It’s important to learn about these meta-modeling aspects before diving into different kinds of modeling tools during the remainder of NMA. So today will be about the diversity of models and what different models can do for us. Typically everyone has an intuition about how different analysis tools can extract different kinds of information from experimental data; you choose a different analysis depending on your question. However, this is less appreciated for models. But it’s the same for them; you want to build a different kind of model to answer different kinds of questions. It all depends on your goals. So today, we will examine three kinds of models that we can classify as (according to Dayan and Abbott, 2001): what, how, and why models.

Each tutorial will guide you through one of those models to describe the exact same data: the time interval between neuronal action potentials, aka inter-spike interval (ISI). In tutorial 1, we will ask what function best describes the shape of the ISI distribution (it’s an exponential distribution). Such a “what” model can compactly describe the ISI distribution and allows, for example, to quantify ISI properties across datasets, task conditions, brain areas etc. In tutorial 2, we ask which mechanism could generate the observed ISI distribution. Such a “how” model proposes a specific way that a system produces the observed behavior. Here, you will see that it’s a balance between excitation and inhibition that generates exponentially distributed ISIs. Finally we will ask “why” the exponential distribution is the most optimal way to code information in neurons. “Why” models thus ask about the underlying principles of a phenomenon.

In any research, we typically start with descriptive (“what”) models; you will see examples of those during the model fitting, GLM, dimensionality reduction, and deep learning days. Next, we often ask about the mechanisms and build “how” models to generate or test hypotheses of underlying mechanisms; examples of those will be in linear systems, real neurons, dynamic networks, and decision making days. Ultimately, we are usually interested in the underlying reason of why the phenomenon exists in the first place; examples of those are in Bayes, optimal Control, and reinforcement learning days. “Why” models are often the hardest to achieve; “what” models are usually the easiest. But more importantly, they allow answering different questions, provide different insights and have different utilities. Thinking about the question I want to answer, why I want to answer this question (i.e. my goal) and the hypotheses I want to evaluate determines my own modeling choices every day. The resulting diversity in models is great because all models address different facets of a problem (like in today's 3 tutorials) and are thus complementary in our quest for knowledge. Today’s materials will hopefully allow you to better appreciate the opportunities and limitations offered by all the modeling tools you will learn during NMA.