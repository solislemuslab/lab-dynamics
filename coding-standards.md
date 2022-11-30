---
title: "Suggestions and Best Practices for Coding in Teams"
collection: posts
permalink: /blog/team_coding
---

Working in a team can be an incredibly effective way to develop a package or application. However, working in a team comes with its own challenges not faced when working alone. Below are lessons I've learned the hard way from working on team-based projects.

# Before Starting

1. Map out the general form of the project. Literally. Create a diagram explaining each of the main components of the project and how they fit together. Focus especially on processes that can be shared between components, so multiple members of the team aren't re-implementing the same things in different ways. This will also help you split up the workload in an equitable way. 

2. If methods being developed by different members of the team include variables holding the same "things", decide on standardized names for these variables. The goal here is that if someone not in the project was to look at the code written by Bob and the code written by Alice, it would be immediately clear to them when Bob and Alice are manipulating the same object. 

3. Decide on a consistent set of standards the whole team will follow. Things to consider include: 
    - Function and variable naming: different casing should be used for public vs private methods. Global variables should be cased differently from local variables. I also like to use a standard form for temporary variables vs variables that will be used throughout a method.
    - Documentation: each function should have a doc-string style documentation. Decide both what information needs to be in the docstring and the formatting.
    

# During the project

Once you get started you should meet regularly so that everyone is on the same page regarding the state of the project. At these meetings, you should discuss challenges you're struggling with. Also, you will inevitably need to make changes to the structure of the project. You should discuss these changes, and update the "map" you made before starting so that it's always up to date. You should also do regular code review: each member of the team should review the code written by another member, not necessarily for quality assurance or correctness (though you should do this when methods are finished), but so that you know what the other members are doing and to make sure two people aren't implementing the same thing, that variables are consistently named, etc. Inevitably, you will realize you need to refactor something into a shared method. 

# General tips

1. Keep variable names consistent. If variable `user_name` is passed from function `main(...)` to `sum_hits(...)` to `output(...)`, the variable should be called `user_name` in all three functions.

2. Along the same lines, keep the order of variables in function signatures consistent. This one is easy, if you just always add new variables to the end of the function signature.