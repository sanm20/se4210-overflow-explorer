# Reflection — Learning Sprint 2, Problem 1

Building this visualization helped us understand integer overflow in a 
way that writing about it alone did not. When we worked through Sprint 
1, we knew the math behind the Ariane 5 example and could explain why 
2,147,485 keys caused the store program to overflow. But building 
something interactive where you can drag a slider and watch the bits 
flip in real time made the concept click differently.

The part that surprised us most was implementing the signed vs unsigned 
toggle. We knew conceptually that a signed 16-bit integer tops out at 
32,767 while an unsigned one goes to 65,535, but writing the logic to 
handle the two's complement wrap-around and watching the sign bit flip 
at the exact moment the value crosses zero from the negative side made 
it feel much more concrete. That leftmost bit does a lot of work and 
seeing it visually helped connect the theory from class to what is 
actually happening in memory.

The workflow was mostly AI-assisted. We described what we wanted the 
visualization to do, reviewed the output, and made decisions about what 
to keep and adjust. We wrote the reflection and README ourselves and 
made sure the content matched what we actually built rather than 
something generic. Using AI to scaffold the initial structure let us 
spend more time thinking about what the tool should teach rather than 
fighting with layout and styling.

If we were to extend this further we would add a live C code snippet 
that updates alongside the visualization to show what the actual cast 
or overflow would look like in code, since that would tie the visual 
directly back to the vulnerability patterns we study in class.
