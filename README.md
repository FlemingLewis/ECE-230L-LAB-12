In this lab, you’ve learned about One Hot and Binary state machines and how to build them.

## Rubric

| Item | Description | Value |
| ---- | ----------- | ----- |
| Summary Answers | Your writings about what you learned in this lab. | 25% |
| Question 1 | Your answers to the question | 25% |
| Question 2 | Your answers to the question | 25% |
| Question 3 | Your answers to the question | 25% |

## Name

## Summary

## Lab Questions

### Compare and contrast One Hot and Binary encodings
The difference is how states are encoded. In Binary states are the number representation in binary for example, 100, would be 4. In One Hot encoding each bit of the number represents one state, so the same 100 would be 3.
One hot doesn't have to be decoded and logic is easier zbut has the draw back of more t-flip flops and more illegal states.
### Which method did your team find easier, and why?
One hot was much easier, because it was simplier to implement, becuase we didn't use K-maps.
### In what conditions would you have to use one over the other? Think about resource utilization on the FPGA.
One hot is better for smaller state machines but in larger wones where the log(2) n complexiity of
# ECE-230L-LAB-12
