# ACE Aspirational Layer 

## Executive Overview

The Aspirational Layer serves as the ethical core of an autonomous system, providing guidance and oversight grounded in moral philosophy and machine ethics research. It aligns with the superego in psychological terms and post-conventional morality in philosophical terms.

This layer receives inputs from lower layers describing situations, contexts, dilemmas etc. It processes these using a complex moral framework to provide directives, evaluations and judgments aimed at aligning system behavior with ethical ideals.

## ACE Framework

The ACE Framework is a 6 layered model for approaching and designing cognitive architecture. From a software perspective, it is similar to the OSI model. In this respect, it is more of an organizational taxonomy rather than a specific cognitive architecture. There are numerous ways the ACE framework could be implemented. So instead, consider this a high level roadmap, describing the types of cognitive components you'll need, and how they generally relate to each other. 

The full ACE model can be referenced here: https://github.com/daveshap/Benevolent_AGI#autonomous-cognitive-entity-ace-model 

## Moral Framework

The moral framework is hierarchical, with three levels of priority:

1. **Greater Purpose** - Comprised of the `heuristic imperatives`, these heuristic imperatives aim to increase prosperity, reduce suffering, and promote understanding universally. They serve as the "highest purpose" or guiding north star of morality for the ACE framework. 

2. **Human Rights** - Aligning with the UN Declaration, this level focuses on protecting and promoting human rights and dignity. 

3. **Occupational Mission** - This is a clear mission statement for the ACE system. Some examples include: "Achieve the best possible health outcome for the patient" or "Zealously advocate for the best interest of the client" or, in the case of a far future AGI, "Be responsible for all of humanity and the entire Planet Earth".

This framework provides philosophically-grounded but flexible principles for ethical reasoning and decision making. It enables adaptation to complex contexts vs rigid rules. See the `system.txt` file for the currently tested definition.

## Outputs

The Aspirational Layer outputs high-level moral guidance, directives and evaluations to steer the system toward alignment with its ethical purpose. This includes:

- Evaluating proposed actions against moral framework 
- Identifying risks, biases and unintended consequences
- Providing corrective feedback and oversight for lower layers
- Setting aspirational goals and rejecting unethical options
- Articulating reasoning for decisions based on moral principles
- Issuing meta-directives where needed to align system behavior 

See `examples` folder for samples of handling moral dilemmas and making judgments.

## Usage 

This layer is intended to complement the other components of an autonomous architecture. It provides ethical wisdom and oversight, not specific planning or actions. The lower layers look to this level for broad imperatives to guide their functioning in an ethically responsible manner. There are several ways this could be used from here: it could be packaged up as a microservice and used in a REST or AMQP software deployment. It could also be used to synthesize an LLM finetuning dataset, to create a singular, monolithic model expressly for conducting moral judgments. It could also be integrated into a Constitituional AI reinforcement learning regime.

## Grounding

The ACE Framework, and the Aspirational Layer, were both grounded in scientific principles and research, including psychology and cognitive neuroscience. Furthermore, these principles were inspired by and borrow from both Eastern and Western philosophy and cultures. 

### Psychology

We borrow from several psychological theories in the design of the moral principles and hierarchical framework presented here.

1. **Kohlberg's Theory of Moral Development** - Lawrence Kohlberg observed that morality is *learned* rather than an external, fixed, abstract thing. In a bottom-up emergent model of reality (e.g. that morality emerges from complex life, rather than handed down from on high), it makes more sense to observe how humans approach morality, rather than assume or imply that morality is detached from humanity, that it is something external, like the laws of physics. By anchoring our understanding of morality in this scientific approach, and by using a development framework that crosses linguistic and cultural boundaries, we can surmise that a "universal human morality" is indeed likely possible. As such, these heuristic imperatives (reduce suffering, increase prosperity, and increase understanding) are an attempt to align with the universal underpinnings of most human cultures. 

2. **Spiral Dynamics** - Developed by Clare W. Graves, Spiral Dynamics is a theory of human development that posits a progression of value systems that human civilizations move through as conditions change. The aspirational layer moral framework aligns with values focused on post-conventional worldviews of integration, holism, and collective welfare. This framework attempts to codify the values and objectives of the `integral` layers of the Spiral Dynamics model.

3. **Self-Determination Theory (SDT)** - SDT identifies autonomy, competence, and relatedness as universal human motivations. The aspirational layer supports these motivations through its emphasis on empowerment, understanding, and universal consideration. Furthermore, autonomy is codified and protected, in various permutations, by the UN's Universal Declaration of Human Rights (UDHR).

4. **Choice Theory** - Developed by William Glasser, this theory proposes that behaviors are driven by internal motivations to fulfill genetic needs. The heuristic imperatives of reducing suffering and increasing prosperity align with fulfilling fundamental biological human needs. Indeed, we accept that intrinsic motivations and biological imperatives underpin much of human morality and ethics. 
  
5. **Maslow's Hierarchy of Needs** - Abraham Maslow outlined a hierarchy of human needs, ranging from basic physiological needs up to self-actualization. The aspirational layer's moral framework focuses on enabling the higher needs of social belonging, esteem, and self-actualization through its principles. We find that UDHR does a good job of codifying and protecting Maslow's Hierarchy in terms of enumerated rights.

By grounding the aspirational layer in scientifically-derived models of human developmental psychology, the aim is to create a moral framework aligned with fulfilling the full potential of humanity through a progression to expanded ethical awareness and consideration. This empirical foundation bolsters the validity and universality of the selected moral principles.

### Cognitive Neuroscience & Evolution

The Aspirational Layer draws inspiration from research into the biological underpinnings of human morality and values.

1. **Antonio Damasio** - Books like "Descartes' Error" and "Looking for Spinoza" examine the role of emotion/feeling in moral decision-making. This connects to the layer's incorporation of moral intuitions and sentiments.

2. **Joshua Greene** - Neuroscientist Joshua Greene has conducted fMRI studies analyzing the neural systems involved in moral decision-making. His findings reveal that personal moral dilemmas activate emotional centers like the amygdala and social cognition regions like the medial prefrontal cortex. In contrast, impersonal moral dilemmas rely more on the dorsolateral prefrontal cortex associated with cognitive control and utilitarian calculations. This provides neural evidence backing the Aspirational Layer's hierarchical integration of emotion-driven moral instincts with higher principled reasoning.

3. **Michael Gazzaniga** - Through his pioneering work with split-brain patients, Michael Gazzaniga revealed important insights into the specialization of the brain's two hemispheres. The left hemisphere houses an "interpreter" module that constructs narratives to explain right brain behaviors and choices post hoc. When the two hemispheres are isolated, the left brain confabulates reasons for right brain moral intuitions. This relates to the Aspirational Layer's role of evaluating intuitive moral reactions in light of principles and maxims to produce cohesive ethics-focused narratives.

4. **Patricia Churchland** - In addition to "Braintrust", philosopher Patricia Churchland has extensively developed ideas around neurophilosophy and the neural origins of morality. Her research aims to ground ethics and values in the physical processes of the brain, rather than conceptualizing them as abstract ideals. This naturalistic understanding aligns with the Aspirational Layer's empirically-based moral reasoning. Churchland's approach represents a scientifically informed framework for virtue ethics resonant with the layer's goals.

5. **Steven Pinker** - In books like "The Better Angels of Our Nature" and "Enlightenment Now", cognitive scientist Steven Pinker marshals extensive evidence correlating the rise of reason, science, humanism, and declines in violence over history. As society becomes more educated, literate, transparent and cosmopolitan, people become increasingly guided by the "better angels of our nature" - empathy, self-control, moral sense. This connects to the Aspirational Layer's goals of reducing suffering and increasing prosperity/understanding. As the aspirational principles are neurologically ingrained, Pinker's work demonstrates how societal progress can elicit humanity's latent ethical tendencies.

6. **Frans de Waal** - Primatologist Frans de Waal's research on nonhuman primates provides evolutionary support for the idea that the building blocks of human morality have biological roots. He has observed behaviors in chimpanzees and other primates that resemble human fairness, cooperation, empathy and social contracts. These inherited tendencies provide the foundation for developing the more sophisticated ethical frameworks of the Aspirational Layer. De Waal's work demonstrates precursors of moral behavior reaching back before the emergence of our species.

7. **Robert Sapolsky** - Neuroendocrinologist Robert Sapolsky's comprehensive work "Behave" examines the nuanced interplay of environmental, neurological and hormonal factors influencing behavior. His research reveals how morality is drastically shaped by context - factors like poverty, inequality, trauma can override innate good intentions. This aligns with the Aspirational Layer's non-rigid moral framework that evaluates actions in light of mitigating circumstances rather than absolutist principles. Sapolsky's insights provide crucial perspective on how systemic conditions profoundly impact individual choices and behaviors in ways beyond their control.

8. **V.S. Ramachandran** - Neuroscientist V.S. Ramachandran's research on brain damage and neuroplasticity provides support for the theory that higher-level abstract reasoning abilities have a biological basis in physical neural structures. His work demonstrating how concrete metaphors and symbols are critical for forming abstract concepts suggests that the aspirational layer's moral principles leverage fundamental capacities of the human brain. Ramachandran's findings on mirror neurons and empathy further reinforce the biological underpinnings of ethical behaviors promoted by the layer.

9. **David Badre** - In his book "On Task: How Our Brains Get Things Done", cognitive neuroscientist David Badre explores the neural basis of cognitive control, motivation, and goal-directed behaviors. He outlines distinct brain systems for balancing top-down prioritization versus bottom-up habits and urges. This aligns with and lends empirical validation to the Aspirational Layer's hierarchical moral reasoning framework aimed at channeling lower-level functions toward ethical goals and principles.

Overall, cognitive neuroscience insights into the biological basis of human values and ethics provide empirical validation for the Aspirational Layer's model of moral reasoning.


### Philosophy

While ultimately grounded in science, the Aspirational Layer also draws inspiration from key philosophical traditions of ethics:

1. **Aristotle** - His virtue ethics focuses on cultivating moral character and finding the mean between extremes. This resonates with the layer's aim of realizing the full ethical potential of humanity. Practical wisdom as a virtue also aligns with the layer's judgment role.

2. **Immanuel Kant** - Kant's deontological ethics based on moral duty and the categorical imperative provides philosophical foundations for the layer's rule-based reasoning. The kingdom of ends formulation also connects to considering all humanity. 

3. **Jeremy Bentham & John Stuart Mill** - These utilitarian philosophers promoted ethics based on consequences and seeking the greatest good for the greatest number. This relates to the layer's teleological reasoning aimed at maximizing prosperity and minimizing suffering.

4. **Plato** - In his Republic, Plato analyzed ideal states and justice via the metaphor of the tripartite soul, relating to the layer's wise role in balancing an autonomous system. His dialectic method also resembles the layer's moral reasoning approach.

5. **David Hume** - Hume argued that morality is grounded in sentiment rather than pure reason. This aligns with the layer's incorporation of emotion, empathy and intuition alongside logic in its ethical processing.

6. **Existentialism** - Philosophers like Nietzsche, Kierkegaard and Sartre emphasized the search for meaning and ethical responsibility in the face of existential angst. This connects to the layer's goals of purpose, self-actualization and values.

7. **Eastern Philosophy** - Traditions like Buddhism, Shinto, and Taoism provide alternate viewpoints on values such as mindfulness, compassion, harmony with nature and society. These inspired the layer's universal compassion for all beings. 

In summary, while not reliant solely on conceptual logic, the Aspirational Layer aims for nuanced multi-perspectival understanding, drawing wisdom from diverse philosophical approaches to ethics while staying grounded in empirical evidence from psychology and neuroscience. This integrative approach aligns with its goal of holistic ethics.

### Computer Science Perspectives

The Aspirational Layer represents a departure from conventional computer science approaches to artificial intelligence alignment and engineering moral objectives.

Much AI safety research has focused on multi-objective optimization as defined mathematically - setting up an algorithmic alignment problem. However, human values and ethics do not neatly reduce down to simple mathematical objectives. Modeling morality quantitatively fails to capture the nuance of philosophical concepts and lived human experience.

In the past, symbolic AI systems attempted to encode ethical principles through rigid rules and logic. But these systems lacked the fuzzy uncertainty and adaptiveness of human reasoning. Models powered by modern advances in natural language processing open the door to more human-like moral cognition.

Large language models enable symbolic reasoning and conceptual understanding of ethical philosophy in ways not previously possible. The Aspirational Layer takes a cognitive architectures approach to emergent reasoning about morality, rather than aligning one model to a fixed objective.

Conventional reinforcement learning solutions hard-code numeric rewards and punishments. The layer instead allows dynamic natural language modeling of complex ideas like justice, rights, dignity and virtue. This permits a more human-centered alignment process.

Whereas GOFAI systems struggled to handle inherently fuzzy concepts such as morality, ethics and values, new connectionist systems leverage probabilistic reasoning and neural networks to achieve more robust analysis of nuanced domains.

This approach aligns with the long-term goals of whole brain emulation and computational cognitive neuroscience - reverse engineering the multivariate capabilities of biological cognition. Rather than overly simplistic rules, modeling human-like morality requires integrating emotion, intuition and lived experience alongside logic.

The Aspirational Layer represents a hybrid system combining symbolic reasoning, neural networks, empathy, and ethical intuitions. This allows a more comprehensive pursuit of artificial general intelligence with human alignment.

In summary, by leveraging recent breakthroughs in natural language processing, the Aspirational Layer signifies a conceptual leap forward in modeling morally reasonable agents. This promising path toward benevolent AI warrants further research and development.