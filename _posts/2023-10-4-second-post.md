# A python Todo application

At first I wasn't really checking my notes nor asking questions and just trying different things out. Eventually I slowed down and thought over what I was doing. First I put in the list and the contents of the list which is:

`["get cash", "spend cash", "cry"]`

 Second then I put while true so that it will continously ask for any additions or continously ask if you want to remove anything. The code then askes the user what they would like to do. It looks like this:
while True:

`    User=input("Would you like to add or remove a todo?")`

Then I printed the response so that my code can either select whether the user wants to remove or add an item to the list using an if statement which can make an selection on a item based on the input then it responds accordingly to the selection. If you would like to add then I set the choice the user would choose to add so that when the user types in an item it then adds an item. Then print the list so that the user can see the current list. Then the user can put what they want to add with another input on the add variable. Then I put the variable to append so that it can be added to the list. Then print the list so that the user can see the current list. It looks like this:

` print(User)
    if User == "add": 
        print(Todo)

        Add=input("Enter an item:")

        Todo.append(Add)

        print(Todo)`

 I put an else statement so that the other selection that doesn't correlate with add can be set to remove an item. So the user would type anything like delete so an item is removed. Then print the list so that the user can see the current list. Then the user can choose what they want to delete with another input on the delete variable. Then I put the variable to remove so that it can be removed from the list. Then print the list so that the user can see the current list. It looks like this:

    `else:
        print(Todo)

        Delete=input("Select an item:")

        Todo.remove(Delete)
        
        print(Todo)`