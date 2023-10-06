# A python Todo application

At first I wasn't really checking my notes nor asking questions and just trying different things out. Eventually I slowed down and thought over what I was doing. First I put in the list and the contents of the list which is `["get cash", "spend cash", "cry"]`. Second

while True:
    User=input("Would you like to add or remove a todo?")
    print(User)
    if User == "add": 
        print(Todo)

        Add=input("Enter an item:")

        Todo.append(Add)

        print(Todo)
    else:
        print(Todo)

        Delete=input("Select an item:")

        Todo.remove(Delete)
        
        print(Todo) 