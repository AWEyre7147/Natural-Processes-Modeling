# Natural Processes Modeling Project

# Abstract

This project is an effort to generate a repository of agent-based models (ABMs) covering the dynamics of various natural processes.  Exploration of these models by an individual can facilitate an intuitive understanding of how certain resources change over time and how these changes can result in various natural phenomena, including unintended consequences by human intervention.

# Introduction

The current dilemma of environmental sustainability seems to derive from the large number of components of ecosystems needing to be understood and their interconnectedness, which poses significant challenges for modern reductionist thinking.  The kind of understanding needed to make well informed decisions within an ecosystem with minimal unintended consequences resembles that of a naturalist rather than a scientist.  These individuals spend several years observing and interacting with ecosystems as a whole to identify the important factors that strongly influence the dynamics of the environment, whether that be rainfall, vegetation types, wildfires, biodiversity, and more.  The type of understanding that is most vital and difficult to communicate/demonstrate usually involves the interplay of one or more of these factors that sustain the ecosystem.  The capacity to generate this understanding is very limited in the context of science or reductionist thinking in general, as it seeks to understand phenomena by investigating its parts in isolation.  

This project is an attempt to build a bridge between the naturalist and scientist by constructing a collection of simplified visualizalizations of natural processes and giving the user the ability to vary the parameters involved with the usage of agent-based models (ABMs).  These models begin by giving the various components of a natural process simple and intuitive rules, building an environment with incorporated randomness, then allowing the agents and environment to play out over time.  A well formed model can allow the user to explore the natural process and ask questions about what happens under various conditions that would otherwise be left to speculation.

The project will begin with brainstorming which natural processes are going to be modeled and investigation into which ABMs already exist.  The NetLogo programming environment will be used for this project, and it already contains a plethora of informative ABMs that efficiently demonstrate various phenomena, such as climate change, erosion, prey/predator patterns, wild fires, and more.  Further brainstorming will uncover the fundamental rules that the agents, etc. in the model will follow and models will then be written, explored for consistency, and experimented with.  The grand goal of this project is to develop a repository of ABMs that cover a plethora of natural processes in an attempt to generate and facilitate more interdisciplinary talk in the sciences and more.  The hope is that with such intuitive visual aids grouped into one environment, that individuals who mainly adhere to modern reductionism can begin to uncover the more complex and dynamic processes that sustain whole ecosystems.

# Agent-based Modeling

Agent-based models (ABMs) are unique from many models currently employed in that their grand function is to explore the phenomenon of interest rather than to prove a pattern exists or to make a prediction.  This is possible by allowing the user to adjust the variables within the model and then observe the outcome in a visual manner, similar to simulation.  Experimentation is possible upon completion of the model, allowing the user to generate a large volume of data over many values of the variables.  This data can be explored readily to identify over what conditions unique phenomena arise.  More can be learned about agent-based modeling below:

https://en.wikipedia.org/wiki/Agent-based_model

https://www.youtube.com/watch?v=FVmQbfsOkGc

For this project, the NetLogo environment will be used to generate the models.  This is a simple piece of software that allows the user to quickly add variables, give the agents roles, then allow the phenomena to play out.  A web-based version of NetLogo is now available to explore this type of modeling:  

https://ccl.northwestern.edu/netlogo/

http://www.netlogoweb.org/launch#http://www.netlogoweb.org/assets/modelslib/Sample%20Models/Earth%20Science/Climate%20Change.nlogo

The type of understanding necessary to make informed decisions about ecosystems is generally only available to those individuals that spend a significant amount of time observing and interacting with the ecosystems firsthand.  This type of modeling is being used for this project as it allows the user to explore the landscape of possibility that may contribute to particular natural phenomena.  It may give an individual experience with the various natural processes that need observed within an ecosystem in order to understand it and make informed decisions.  It also provides an avenue for interdisciplinary talk among individuals with specialized knowledge by visually demonstrating what factors are important for a particular ecosystem and how they interact.

I suggest taking this course to get background in ABMs and NetLogo:

https://www.complexityexplorer.org/courses/96-introduction-to-agent-based-modeling

# The Repository

The repository will be formatted with each folder containing a particular model of a natural process.  Two readme documents will be made available within each branch: the first will document any brainstorming/information that has been compiled (not yet strucutred), and the second will be the formatted contents of the NetLogo 'Info' tab for the particular model.  Codes for the models will be made publically available.

Experimentation will also be performed and individual experiments will be placed within their own folder within the model's contents.  These will contain a readme with a brief outline of experiment, particularly if there's any phenomenon that's being searched for, and the settings in NetLogo's 'BehaviorSpace' application.  R will be preferred to do analyses and these scripts will be uploaded in addition to results.
