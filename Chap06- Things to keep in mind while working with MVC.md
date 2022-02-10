## Things to keep in mind while working with MVC
1. Only View script will be Monobehavior class and the data will start executing from here because it gives permission to write void start and void update methods
2. In the Model script, we will fetch all the data. This data will then be passed to the Monobehavior class in View and the Controller script will take the decision here.
