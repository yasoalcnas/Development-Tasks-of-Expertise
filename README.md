# Development-Tasks-of-Expertise
Development tasks of expertise and application on courses.

the_name = input("what is your name ?")#.capitalize().split()
the_mal = input("what is your gmail ?")#.split()

the_username = the_mal[0:the_mal.index("@")]
the_doman  = the_mal[the_mal.index("@") + 1:]

the_name = the_name.capitalize().split()
the_mal = the_mal.split()

print(f"your name {the_name}, your gmail {the_mal}")
print(f"your username ({the_username}) && your doman ({the_doman})")

