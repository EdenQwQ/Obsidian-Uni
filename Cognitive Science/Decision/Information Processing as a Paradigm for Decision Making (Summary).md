#psychology/cognitive-science/decision #summary 

# Introduction

The field of judgment and decision-making (JDM) has long been dominated by an economic perspective. This approach suggest that humans are rational animals whose decisions serve to optimize utility. Yet, psychologists have been finding empirical results that cannot be easily explained by such a framework. Information processing models have started to emerge as reasonable alternatives in psychology. This article aims to provide evidence proposing that the field of JDM is going through a paradigm shift, and describe the promising future directions during this transition period.

## The Evolution of Scientific Paradigms

Paradigm: set of practices that defines a scientific discipline at any particular period 

A paradigm provides:

- What **phenomena** to study
- What kinds of **questions** meaningfully probe for answers
- How these questions should be **structured**
- How an **experiment** is to be conducted
- How the results of the investigations should be **interpreted**

Anomalies may accumulate to the point that normal science becomes difficult owing to weakness in the accepted paradigm. Revolutionary science may begin if efforts by normal science to explain anomalies(异常) within a paradigm fail. The field returns to the process of normal science when a new paradigm has been established.

Kuhn: Paradigm shifts will not take place until a new paradigm is established.

This article identifies several current models of DM that suggests the field is currently undergoing a paradigmatic transition.

# History of DM Paradigms

Traditional aim of decision theory: To understand how agents pursue goals in the face of opinions.

- Blaise Pascal & Pierre de Fermat **Expected Value Theory**
	- Agents should maximize expected value(EV)
		- $EV = \sum{p_{i} \cdot x_{i}}$. $p_{i}$: probability of receiving a given outcome; $x_{i}$: the amount of the outcome
	- St. Petersburg paradox(悖论)
		- $EV = +\infty$
		- Rational people won't pay much for the gamble.
- Daniel Bernoulli 
	- Modified EVT to account for these kinds of anomalies.
	- The value of an outcome should be judged not by monetary value but rather a concave function(凸函数) of the value.
- Von Neumann & Morgenstern **Classic Expected Utility Theory**
	- Axioms(公设)
		- Completeness: ! prefer A and B
		- Independence: prefer A to B -> ! prefer B to A
		- Transitivity: prefer A to B, prefer B to C -> ! prefer C to A
		- Continuity: gamble != sure gain
- Leonard Savage 
	- Further modification of EUT
	- $EV = \sum{u(x_{i}) \cdot P(x_{i})}$
	- Observations of bias in people's perceptions of probability 
- Kahnemen & Tversky **Prospect Theory**
	- Logically identical decisions led to different behaviors when they were described as losses rather than as gains.
	- Suggests a function that was concave for gains and convex for losses, with steeper slope for losses than for gains. 
	- Refines the nature of subjective probability. People overweight unlikely events and underweight highly likely events.
	- People overweight unlikely events independently of their relative outcomes.
- Quiggin **Rank-dependent EUT**
	- People overweight only unlikely extreme outcomes rather than all unlikely events.
- Tversky & Kahneman **Cumulative Prospect Theory**
	- Cumulative probability functions rather than probability themselves are transformed.
- Thaler **Mental Accounting**
	- People tend to be more willing to make risky gambles with house money than with house money.
	- Decision makers have separate mental accounts for various areas of spending or sources of wealth, each with its own utility curve.

Researchers spend half a century to expand DM models that can be considered modifications of EUT. 

The general mold: presenting empirical deviations from the expectations of prior utility-based models and proposing modifications, extra parameters, or other forms of additional complexity to utility theory to account for the anomalies.

# A Paradigm Shift

Look for domain-specific, DM algorithms known as heuristics(试探法). Address the problem of DM from an information processing approach: consider the specific information available to the decision maker and how that information could be used to achieve desired outcomes in a boundedly rational world.

Other researchers attempt to unify the heuristics into an integrated theory.

# Information Processing Theories

Instead of starting from the assumption that people accurately gauge utility for various options, and thus that modeling people's choice will give insight into their utility functions, information processing models argue that researches on DM should start from basic cognitive building blocks. DM recruits basic processing from memory, attention and perception, to name a few, and thus decision systems are best understood by developing models of how decision-relevant information is sampled, retrieved, and integrated.

## Query Theory 查询理论

- Johnson
- People's preferences are subject to the processes and dynamics associated with memory encoding and retrieval.
- Basic assumption: When agents are faced with a decision, they naturally decompose the overall question into a series of component queries. ==The order of the queries is shaped by one's implicit(隐含的) goals in the situation==, such as one's valuation of the status quo(现状) as a buyer or a seller. Various aspects of the situation are recruited from memory in a serial manner due to the queries. Based on retrieval-induced forgetting, QT posits that ==retrieval is less successful for later queries than for earlier ones====. Earlier queries result in a richer, more heavily weighted set of information compared with later ones as the initial retrievals interfere the subsequent.
- Decision makers undergo serial evidence sampling toward an ad hoc(特设) goal to make decisions rather than calculate some abstract utility or value.
- Endowment Effect 禀赋效应/捐赠效应
	- People tend to value an item more when they own the item.
	- Johnson conducted the mug experiment:
		- Participants are shown a mug and then were randomly grouped as sellers and choosers.
		- Those endowed with the mug considered more aspects that increase the value of the mug and vice versa. 
		- Sellers generate positive statements earlier. 
		- Changing the query order eliminated the effect.
		- Sellers had more accurate recall for positive features, which is consistent with the idea that first query causes interference and reduced accessibility for the second query.
- Ting & Wallsten: ==Individuals generate more reasons for pursuing the invested option== than for an alternative, and generate those reasons earlier. These effects increases as individuals make progress toward attaining the reward yielded by the invested option.
- Krajbich: QT may not be limited to memory retrieval. Visual attention is highlighted in **Drift Diffusion Model**. Fixation patterns influence binary and ternary choice.

## Decision Field Theory (DFT)

- Busemeyer & Townsend
- DFT is based on the notion that preferences change during **deliberation**(深思熟虑) and that the amount of time spent making a decision influences the final choice.
- The deliberation process involves an accumulation of information about the consequences of a decision through repeated sampling of decision-relevant information. This process is manifested by indecisiveness(优柔寡断), vacillation(动摇) and inconsistency.
- Amount of attention allocated to the various consequences change over the course of deliberation time, similar to random walk.
- Evidence slowly accumulates as various features of the decision set are brought to mind, but action is not taken until the preference for one action reaches a **motivation threshold**.
- Basic neural and cognitive processes lead to emergent choices.
- Probabilistic rather than deterministic; Dynamic rather than static.
- EUT suggest that the same choice will be made regardless of deliberation time, while DFT capitalizes on deliberation time as a main strength.
- Multiattribute DFT(MDFT): Attention is initially focused on the most important attribute, and during this time the drift rate drives the preference toward one opinion. ==Action threshold is set to lower magnitude(幅度，量级) under shorter time pressure==, allowing time only for the most important attributes to be processed. Under longer or no time pressure, the second attribute is processed, the drift rate drives the preference toward the alternative option.
- Preference could be effected by newly presented options.
	- Similarity effect 
	- Attraction effect 
	- Compromise effect 
- Models with similar assumptions (based on evidence accumulation)
	- Trueblood **Multiattribute Linear Ballistic Accumulation Model** (MLBA) 线性弹道蓄能器模型
		- Has an analytical solution
		- Linear and deterministic 
	- Bhatia **Associative Accumulation Model** (AAM) 关联积累模型
		- The model can be instantiated(实例化) in a three-layer neural network corresponding to task representation, potentially relevant attribute listing and preference states.
		- Associations between an attribute and an available alternative affect the attribute's **accessibility**.
		- AAM can be seem as a hybrid of QT and DFT: the model relies on repeated stochastic sampling of attributes, but the current states and goals of the agent exert effects on the likelihood that ==certain attributes will be sampled over others==.
		- Can explain major context effects as well as alignability effects (i.e. putting more weight on attributes of a choice that are easy to compare, even if they are less important) and less-is-more effects (i.e. improved decision making when the decision maker has less information upon which to base their choice).

## Leaky, Competing Accumulator Model (LCA)

- Modeling DM as an error-prone(i.e. leaky)(易错的，易遗漏的) buildup of information over the deliberation process.
- Relies on stochastic alternation of attention and collection of information during the input-processing stage.
- Imperfections and decay of memory during the deliberation process. Evidence degrades over time.
- When two options in a choice set are similar along a particular attribute, activation of one of the options inhibits activation of the other.
- LCA allows context effect to emerge naturally as predictions of the theory rather than anomalies.
- LCA differs from MDFT as in LCA the strength of the lateral inhibition interactions is independent of the psychological distance between options; LCA does not make use of negative activation, instead loss aversion is assumed.

## Decision by Sampling DbS

- Explicitly reject the notion of utility.
- People are better at comparing than estimating an absolute magnitude.
- Decision maker do not mentally represent utility at all. Instead, DMers are presumed to make binary, ordinal comparisons between the present option and alternatives drawn from memory and the current environment, and to track frequencies of how often a particular option wins.
- Supporting evidence: Short-term exposure to lower or higher supermarket prices changes the environment of sampling for dollar values.
- DbS argues that utility is meaningless outside of a particular context and that people do not process utility, instead having access only to ordinal comparisons of magnitudes. However, DbS subsumes(包含) what EUT can explain and anomalies that confounded EUT.
- DbS does not sample attributes or features of a decision but focuses on sampling of the universe of possible options and determining an ordinal rank for present options. 
- One must compare the attributes of the options in order to compare the options themselves. One potentially fruitful avenue for future work in the information processing paradigm would be to juxtapose these two approaches.

## Voting Agent Model of Preferences (VAMP)

- Many of the observed anomalies can be explained as a by-product(副产品) of aggregation(聚合) of differential preferences of neural systems within an individual.
- Certain neurons and neural systems are sensitized to different features.
- Within a single individual, different neural systems might have different preferences. The preference of the individual as a whole is a result of the aggregation of the preferences of the neural system.
- Anomalies of EUT emerge naturally from VAMP as evidence rather than problems.
- DM is a separate and insulated system. VAMP assumes that it is based on cognitive building blocks similar to the rest of cognition.

## Constraint Satisfaction 约束满足

- Posits an associative network between each item in the choice set and the attributes upon which they vary. Related concepts have similar levels of activation. The links are presumed to be bidirectional(双向的): not only do the attributes influence preferences for various options, but also these preferences influence perceptions of the attributes. Activation spreads through the network in multiple iterations(迭代) until the network stabilizes.

## Other Notable Models

- Soltani **Range Normalization Model**
	- Fits into the physiological limits of the basic units of cognition--neurons.
	- The rate of neural firing is central to the brain's representation of values and options and that there is an upper and lower boundary to these values.
	- In order for the neural system to represent many distinct kinds of values, the neural system dynamically adjusts itself to distinguishably represent the required information while maintaining the relative magnitudes of that information.
- Hagmayer & Sloman **Causal Reasoning**
	- People's choices are driven to a large extent by the underlying causal structure of the decision options.
- Busemeyer **Quantum Dynamic Model**
	- Underlying mathematical structures derived from quantum theory provide a much better account of human thinking than traditional models do.
	- Choice and preference probability states are assumed to exist in a **dynamic superposition**(叠加态), and only when a preference is revealed does the state collapse into a particular partial order. 