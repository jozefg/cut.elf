# cut

A simple proof of cut elimination for a intuitionistic sequent
calculus. The calculus has 5 connectives: implication, conjunction,
disjunction, true, and false.

The file `logic.elf` formalizes the syntax and typing judgment for the
logic and `cut.elf` proves cut elimination. Note that this is an
extrinsic cast of the logic rather than the intrinsic version found on
the Twelf wiki. Read the code for `cut` for a gist of how the proof
works and `of/cut` (the actual theorem) for the gory details.
