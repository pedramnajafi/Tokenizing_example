# Tokenizing_example
In this example, we use tokenizing by sentence and by word to understand their functionality.

    from nltk.tokenize import sent_tokenize, word_tokenize
    example_string = """Muad'Dib learned rapidly because his first training was in how to learn. And the first lesson of all was the basic trust that he could learn. It's shocking to find how many people do not believe they can learn, and how many more believe learning to be difficult."""
    new_string = sent_tokenize(example_string)
    print(new_string)
    print("-----")
    word_string = word_tokenize(example_string)
    print(word_string)

