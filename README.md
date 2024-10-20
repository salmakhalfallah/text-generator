The infinite monkey theorem is a theorem that states that, if a monkey sat in a room for an infinite amount of time typing random keys, eventually the works of William Shakespeare himself could be recreated by said monkeys. This project attempts to speeden up that process.

This is a project in which a text file is inputted (in this case, the Merchant of Venice by Shakespeare), and a generative text attempting to duplicate the inputted text file is the output.

This implementation is done through a binary search tree. Every string in the input file of a specified window size is inputted into the binary search tree as well as its next character. The prediction is done through the binary search tree and a randomized "next" character based previously analyzed behavior of the input text.
