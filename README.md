# yy
def shuffle_sentences(sentences):
    random.shuffle(sentences)
    return sentences

print("Enter 4 sentences:")
user_sentences = [input(f"Sentence {i+1}:")for i in range(4)]
shuffle_sentences =shuffle_sentences(user_sentences)
print("\nShuffled sentences:")
for sentence in shuffle_sentences:
    print(sentence)
