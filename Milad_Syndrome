def milad(word1,word2):
    list = 'sh','ch','zh','gh','kh'
    new_word = word2[:1] + word1[1:] + ' ' + word1[:1] + word2[1:]
    if word1.startswith(list):
        new_word = word2[:1] + word1[2:] + ' ' + word1[:2] + word2[1:]
    
    if word2.startswith(list):
        new_word = word2[:2] + word1[1:] + ' ' + word1[:1] + word2[2:]
        
    return new_word
w1 = input('Tell Me your first word:')
w2 = input(' tell me your second word:')

print(milad(w1,w2))
