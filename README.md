# nlp
nlp basics
for line in open('charlie.txt'):
    for word in line.split():
        if word.endswith('ing'):
            print(word)
#python is a object oriented language in the 3rd line 
#word-object,variable
#endswith-method or operation
#'ing'-attribute
