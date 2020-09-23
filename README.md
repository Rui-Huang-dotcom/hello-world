# hello-world
Just another repository
favourite_languages = {"jolin": ["java", "python"],
                       "victor": ["python"],
                       "hebe": ["c", "go"],
                       "seline": ["ruby", "haskell"],
                       }
for name, values in favourite_languages.items():
    if len(values) > 1:
        print("\n" + name.title() + " favourite language are: ")
        for value in values:
            print("\t" + value.title())
    else:
        print("\n" + name.title() + " favourite language is: ")
        for value in values:
            print("\t" + value.title())
            
