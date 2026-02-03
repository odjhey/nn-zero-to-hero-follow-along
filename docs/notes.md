- understand this https://en.wikipedia.org/wiki/Maximum_likelihood_estimation
- understand `log`, that for `log(x) from 0 to 1` when x is 0 then log is infinity and 1 isto 0
- read more about exponentiation `exp(x)`, looks like it converts all numbers the +

- https://blog.ezyang.com/2019/05/pytorch-internals/
- tanh -> scales all to  -1 to 1
- understand math below (this is basic exponents)
  ```python
  lre = torch.linspace(-3,0,1000)
  lrs = 10**lre
  ```

- Part3 - activations, gradients, batchnorm cont https://youtu.be/P6sfmUTpUmc?list=PLAqhIrjkxbuWI23v9cThsA9GvCAUhRvKZ&t=4715
  skipped some above, continue later
  i think we'll learn about stacking linear layers alone and stuff here

- look at batchnorm as "centering the dataset" during training

- part4 - becomming a backprop ninja skipped, go back to this later when has more time

- Building makemore Part 5: Building a WaveNet
  get more comfortable with tensor dims and operations and views


- Let's build GPT: from scratch, in code, spelled out.
- Must reimplement own Linear and stuff for faster reading of codes
- again, too weak/slow with matrix operations
- B,T,C review
- got lost in implementing the residual pathway

- this crazy to me, i don't understand https://youtu.be/kCc8FmEb1nY?list=PLAqhIrjkxbuWI23v9cThsA9GvCAUhRvKZ
- read residual blocks when haz time https://youtu.be/kCc8FmEb1nY?list=PLAqhIrjkxbuWI23v9cThsA9GvCAUhRvKZ&t=5326

### Some final thoughts
- i somehow see how it works mechanically, but semantically still vague, whats the semantical meaning of each layer, of each computation.
- next few steps probably includes, review matrix operations, what each semantically mean
- also probably find a better mental model for embedding values 

### possible next steps
- lets write smaller models, and isolate and add more visuals to possibly see clustering etc
- possibly one (or all) from: copy/reference behaviour, induction pattern, bracket/structure tracking, semantic axis emergence, noise vs signal