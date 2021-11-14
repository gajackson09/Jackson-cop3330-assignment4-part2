# Assignment4-pt2 Help Screen
 
 This application creates and stores todo lists for the user.
 
 # How to create a list
 
 # How to update a list
 
 # How to remove an item
 
# Assignment4-pt2 Help Screen
 
 This application creates and stores todo lists for the user.
 
 # How to create a list
 
 # How to update a list
 
 # How to remove an item
 
    public static void help(){
        System.out.println("- help : This help message");
        System.out.println("- list : List all the items/containers of your todo list");
        System.out.println("- save : Save the data to a local temporary file");
        System.out.println("- load : Load the data from a local temporary file");
        System.out.println("- add_item <ID> <NAME> : Add an item/container to your todo list");
        System.out.println(" <ID> = 0 if you want to add to the root level, otherwise, use " +
                "the <ID> of a container you want to add to");
        System.out.println(" <NAME> (String) Is the name of the item you want to add. The " +
                "string cannot contain empty 'spaces'. For example, 'some item' " +
                "is not acceptable.");
        System.out.println("For example, to add an item named buy_milk to the root level, do: ");
        System.out.println(" add_item 0 buy_milk");
        System.out.println("- add_container <ID> <NAME> : Add an item/container to your todo list");
        System.out.println(" <ID> = 0 if you want to add to the root level, otherwise, use " +
                "the <ID> of a container you want to add to");
        System.out.println(" <NAME> (String) Is the name of the item you want to add. The " +
                "string cannot contain empty 'spaces'. For example, 'some item' " +
                "is not acceptable.");
        System.out.println("- delete <ID> : Delete a container / item using an ID");
    }
