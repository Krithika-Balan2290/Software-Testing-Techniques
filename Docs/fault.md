#Fault Injection

Fault injection is a technique used for  improving the coverage of a test by introducing faults in test code paths, in particular error handling code paths. It is often used with stress testing. Robustness testing (also known as Syntax Testing, Fuzzing or Fuzz testing) is a type of fault injection testing used to test for vulnerabilities in communication interfaces such as protocols, command line parameters, or APIs.
The propagation of a fault through to an observable failure follows a well defined cycle. When executed, a fault may cause an error, which is an invalid state within a system boundary. An error may cause further errors within the system, therefore each new error acts as a fault, or it may propagate throughout the system and be observable. If error are observed within the system they are termed failures. This is termed as the fault-error-failure cycle and is a key mechanism in dependability.
There are two types of fault injection:
- Compile-time injection is an injection technique where the  code is modified to inject simulated faults into a system. One method is called mutation testing which changes existing lines of code so that they contain faults. A simple example of this technique could be changing 
```
a = a + 1 to a = a – 1
```
Code mutation testing causes faults which are similar to those unintentionally added by programmers.
A refinement of code mutation is Code Insertion Fault Injection which adds code, rather than modifying existing code. This is usually done through the use of perturbation functions which are simple functions which take an existing value and perturb it via some logic into another value.

- Runtime Injection techniques use a software trigger to inject a fault into a running software system. Faults can be injected via a number of methods and triggers can be implemented in a number of ways, such as: 
 
   - Time Based triggers: When the timer reaches a specified time an interrupt is generated and the interrupt handler associated with the timer can inject the fault
   - Interrupt Based Triggers: Hardware exceptions and software trap mechanisms are used to generate an interrupt at a specific place in the system code or on a particular event within the system, for instance access to a specific memory location.

Runtime injection techniques can use a number of different techniques to insert faults into a system via a trigger.
- Corruption of memory space: This technique consists of corrupting RAM, processor registers, and I/O map.
- Syscall interposition techniques: This is concerned with the fault propagation from operating system kernel interfaces to executing systems software. This is done by intercepting operating system calls made by user-level software and injecting faults into them.
- Network Level fault injection: This technique is concerned with the corruption, loss or reordering of network packets at the network interface.
These techniques are often based around the debugging facilities provided by computer processor architectures.


[Prev Page](https://github.com/Krithika-Balan2290/Software-Testing-Techniques/blob/master/Docs/code_coverage.md) | [Next Page](https://github.com/Krithika-Balan2290/Software-Testing-Techniques/blob/master/Docs/mutation.md)
 
 [Back to contents](https://github.com/Krithika-Balan2290/Software-Testing-Techniques/blob/master/Index.md)
