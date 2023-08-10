### Markov Chain

Markov Chain text generator uses the patterns it finds in existing text to create new text that follows similar patterns. It's like a creative way of guessing what words could come next based on what usually came next before.

1. **Words and Connections**: Imagine you have a bunch of sentences. In these sentences, some words often come after certain other words. For example, in the sentence "I like to eat ice cream," the word "to" often comes after "like." We're going to use these connections between words to create a text generator.

2. **Building Blocks**: We break down the sentences into individual words. These words are like building blocks for our generator. We want to know which words usually follow other words.

3. **Making Pairs**: We go through all the sentences and make pairs of two words. The first word is like a "starting" word, and the second word is what comes after it. We keep track of these pairs.

4. **Creating Choices**: Now, for each "starting" word, we list down all the words that came after it in the sentences. These words become the choices for the next word.

5. **Random Selection**: When we want to generate new text, we start with a "starting" word. We look at the choices for that word and randomly pick one of them to be the next word.

6. **Chaining**: We keep doing this: taking the last word we chose and looking at the choices for that word. We pick another word from those choices. This is like making a chain of words.

7. **Repeating**: We repeat this process until we have enough words to make a new sentence or piece of text.
