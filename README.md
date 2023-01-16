# EfficiencyFunctions
- You can use tester files or your own original files
  - Part 1
    - Read the input one line at a time until you have read all lines. 
      Now output these lines in the opposite order from which they were read, but with consecutive duplicates removed.
  - Part 2
    - Read the input one line at a time and output the current line if and only if it is strictly
      larger than all other lines read so far or strictly smaller than the previously outputted line. If this
      is the first nonempty line you read, it is considered larger than anything you've read so far.
      (Here, larger is with respect to the usual order on Strings, as defined by String.compareTo()).
  - Part 3
    - Read the input one line at a time. If you read less than 1000 lines, then do not output
      anything. If you read less than 2402 lines, then output the 1000th line in sorted order of the
      input lines. If you read 2402 or more lines, then consider only the last 2402 lines, and output the
      1000th line in sorted order from the last 2402 lines. For full marks, your code should be fast and
      should never store more than 2403 lines.
  - Part 4
    - Read the input one line at a time and output the current line ℓ if and only if none of
      the previous lines starts with ℓ.
  - Part 5
    - Read the input one line at a time until you have read all lines. Output all the lines in
      sorted order (as defined by String.compareTo(s)).
  - Part 6
    - For this question, you may assume that every input line is distinct. Read the entire
      input one line at time. If the input has less than 901 lines, then do not output anything.
      Otherwise, output the line ℓ that has exactly 900 lines greater than ℓ. (Again, greater than and
      less than are with respect to the ordering defined by String.compareTo()). For full marks, you
      should do this without ever storing more than 901 lines.
  - Part 7
    - The input contains special lines: “***reset***”. Read the entire input and break it
      into blocks of consecutive lines 𝐵1, ... , 𝐵𝑘, where 𝐵1 is a block that contains one line, 𝐵2 – two
      lines, 𝐵3 – three lines, ... 𝐵𝑘 contains 𝑘 lines (or less). When you read the “reset” line, you add it
      to the current block and reset the size of the next block to 1. So that following strings are
      broken into blocks of size 1, 2, 3, ... lines, until you read another “reset” string and reset the size
      again. And so on. When you are done reading all the strings, output the blocks in reverse order
      𝐵𝑘, 𝐵𝑘−1, ... , 𝐵3, 𝐵2, 𝐵1 but preserving the order of the lines within each block.
  - Part 8
    - Assume your input consists of 𝑛 lines. Read the input one line at a time until you
      have read all lines. Treat the lines as if they are numbered 0, ... , 𝑛 − 1. Note, there can be
      duplicates. Output a permutation 𝜋0, 𝜋1, ... , 𝜋𝑛−1 of {0, ... , 𝑛 − 1} so that 𝜋0 is the number of
      the smallest line, 𝜋1 is the number of the second smallest line, ... , and 𝜋𝑛−1 is the number of
      the largest line. (Again, smaller, and larger refer to the natural ordering on strings). Your output
      should consist of 𝑛 lines, where line 𝑖 contains (the string representation of) 𝜋𝑖, for each 𝑖 ∈
      {0, ... , 𝑛 − 1}. The numbers for duplicates should be outputted in the same order in which the
      lines were read.
  - Part 9
    - Read the input one line at a time and output the current line if and only it has
      appeared at least 3 times before.
  - Part 10
    - For this problem you may assume that every input line is distinct. Read the input one
      line at a time and assume that the lines are numbered 0, ... , 𝑛 − 1. Your output should begin
      with the largest line in the input. Assume its number is 𝑖. Next, output the largest line among the
      lines numbered 𝑖 + 1, ... , 𝑛 − 1. Assume its number is 𝑗, where 𝑗 > 𝑖. Next, output the largest
      line among the lines numbered 𝑗 + 1, ... , 𝑛 − 1. And so on. The last line of your output will be
      the last line of the input. (Here, largest is with respect to the usual order on Strings, as defined
      by String.compareTo()).
