# Relocation Mechanism for MZPE in a Windows-like system

The Windows-like system, named HAL9000, is a didactic OS used by the Technical University of Cluj-Napoca. Since this is an internal project, I am not able to upload any related source code file. So, the diffs should be visualized by using an external tool (any online git diff viewer).

For the semester project, to pass the laboratory exam I implemented a mechanism for relocating MZPE. This project is unique. By his uniquely, it means that I was the only student o implement such a mechanism. The alternative to passing the subject would be to fully participate in every session and take the final exam.

The uploaded diffs are enough to understand how I implemented this mechanism. Before reading this code, I would highly suggest taking a look over MZPE (incomplete :-)) documentation.

The implementation is 100% original, so if are using it in a sistem, be aware that it has no security checks.

To visualize my changes you can use: https://diffy.org/
For any other related questions, or for sending me an appreciation (believe me, I have done a lot of research to find how the data should be parsed), send me a dm.

The action is in **\_MmuApplyRelocations** method. ;-)
