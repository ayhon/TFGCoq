Overview:
 1. Introduction
 
 3. State of the art
 Motivation for the project.  Talk about the optimizations we'd like to use the octagonal inequalities for. Talk about FORVES2 (Use the linked papers for inspiration) and compiler optimizations. Also talk about the need for the verifier and for the verifier itself to be verified. Finally give a small introduction to what a theorem prover is and talk about Coq.
 Mention the used papers and previous work on octogonal restrictions.
 
 4. Description of the project
 Design a plan for the project with a set of goals. Go over the past emails, notes and commits to get an idea of the progress of the project. 
 Things which could be mentioned at this point:
 - Learning Coq (introduction to Coq)
 - Original definition of imp_checker (and relevant definitions)
  -- Literals and variables
  -- Models
  -- Inequalities
  -- What does satisfiability mean
  -- What does implication mean
 - How it changed to include hypothesis disjunctive normal form
 - How we first thought about doing things with graphs
 - How we realized it wasn't possible with that approach alone
 - The algorithms stated in the papers and how they gave us confidence in trying out the new approach.
 - The new approach
 
 5. Conclusions and future work
 In future work we could talk about the implementation of the original algorithm, proving the completeness of the procedure and abstracting away the container being used into a module type, and proving that a matrix would satisfy such a module type.
 As a conclussion we coul


 When talking about Coq and verification of programs we can use the example of the scala program I derifed to more easily see what the algorithm was doing and how I found bugs in my original program thanks to the verified one.
 Also talk about the benefits of using functional programming as defined in Coq's standard library in order to have access to the theorems proved in the standard library.