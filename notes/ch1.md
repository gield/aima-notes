# Chapter 1 - Introduction




## 1.1 What is AI?

Definitions of AI can be grouped into 4 groups:

| **Thinking Humanly** | **Thinking Rationally** |
|:--------------------:|:-----------------------:|
| **Acting Humanly**   | **Acting Rationally**   |

Top: thought processes and reasoning  
Bottom: behavior  
Left: human performance measure  
Right: ideal (**rational**) performance measure



### 1.1.1 Acting humanly: The Turing Test approach

Alan Turing designed the Turing Test (1950) to provide a satisfactory operational definition of intelligence

**Turing Test** = computer passes the test if a human interrogator, after posing some questions, cannot tell whether the responses come from a person or from a computer  
Not simple, a computer would need:

* natural language processing
* knowledge representation
* automated reasoning
* machine learning

Physical simulation of a person is unnecessary for intelligence

But the **Total Turing Test** includes a video signal and physical "grabbing" abilities  
A computer would then need:

* computer vision
* robotics

These 6 disciplines compose most of AI

Little effort has been made to pass the Turing Test: better to study underlying principles of intelligence  
Analogous: we build planes, not machines flying like pigeons



### 1.1.2 Thinking humanly: The cognitive modeling approach

We need to determine how humans think:

* through introspection
* through pshychological experiments
* through brain imaging

Once we have a theory of the mind, we can express that as a computer program  
Preferably using the same reasoning steps

The field of **cognitive science** brings together AI models and experimental psychology techniques to construct precise and testable theories of human mind



### 1.1.3 Thinking rationally: The "laws of thought approach"

Aristotle attempted to codify "right thinking" (= irrefutable reasoning processes)  
His **syllogisms** provided patterns for argument structures that always yield correct conclusions when given correct premises  
This initiated the field of **logic**

By 1965, we could solve any solvable problem described in logical notation  
The **logicist** tradition tries to build on this to create intelligent systems

Two main obstacles:

* difficult to state informal knowledge as format terms
* difference between solving a problem in theory and in practice



### 1.1.4 Acting rationally: The rational agent approach

**Agent** = something that acts (incl. operate autonomously, perceive the environment, adapt to change, create and pursue goals)  
**Rational agent** = acts to achieve the best (expected) outcome

Sometimes, there is no provably correct thing to do, but something must be done (quickly)

Two advantages over the other approaches:

* more general because correct inference is 1 of many possible mechanisms for achieving rationality
* more amenable to scientific development (i.e. mathematically well-defined and completely general, human behavior is well adapted for 1 environment)

Achieving perfect rationality is not always feasible, especially computationally  
**Limited rationality** = acting appropriately when there is not enough time to do all computations
