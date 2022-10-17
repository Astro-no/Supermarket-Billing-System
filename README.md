# Supermarket-Billing-System
A C++ mini project on Supermarket Billing System
Explanation::
The code starts by declaring a variable of type supermarket called s. Next, the function AddProduct is declared and it has two parameters: xz and itemno.
The first parameter is an integer that stores the number of products in this supermarket.
The second parameter is a string that stores the name of each product in this supermarket.
 Next, three float variables are declared: price, qty, tax; these store the cost per unit for each product in this supermarket as well as how many units there are available for purchase at one time (price*qty).
Then two more variables are declared to store information about each individual product: name and dis.
Finally, four functions are defined which will be used later on when needed: Display(), InputFile(), DisplaySpecific(), Update().
The function AddProduct() starts by analyzing its parameters before calling AnalyzeProducts() with those values to get all the products stored in this supermarket's database.
After getting all the products from AnalyzeProducts(), they're added into an array called items using C++'s built-in array class std::vector<> .
This vector will hold all of our items so we can iterate through them later on when displaying them or adding new ones to our list
The code attempts to add a product to the supermarket.
void supermarket::AddProduct() { s.itemno=0; s.name=""; s.price=0; s.qty=0; s.tax=0; }
The code starts by declaring the variables that will be used in the program.
The first variable is itemno which stores the number of items in a product.
The second variable is name which stores the name of a product, and finally price which stores the price for a product.
The next line declares an input file to read from, followed by two functions: ShowProduct() and InputFile().
ShowProduct() displays all products on screen with their respective information such as item no., name, price, discount percentage.
It also prompts users to enter data into input file if they want to add new products or edit existing ones.
InputFile() reads data from user’s keyboard and then analyzes it before displaying it on screen along with other relevant information like item no., name, price etc..
The code is a function that takes the input from the user.
The program asks for the number of items, name of the product and price of the product.
The code above will ask for input from the user in order to calculate how much discount should be given on each item.
The code starts by declaring a variable called "found" which will be used to keep track of the number of products that have been found.
The code then opens a file called "home/desktop/Store.txt".
 This is where all the product information will be stored in text format.
 The next line starts an infinite loop, and it reads from the file until it finds a new product with itemno equal to no (the current item).
 If this happens, then s.ShowProduct() is executed, which displays the product on screen using cout<<endl;< li="" style="box-sizing: border-box; margin: 0px; padding: 0px; max-width: 1344px;">
 The code is used to modify the details of a product.
 The code starts with a while loop which will go on until the file is read and all the data has been entered.
 The first line in this loop reads in the contents of the file as it is written, and then checks if that particular item number exists.
 If it does exist, then it will show that product's information before adding a new one.
 The code starts by declaring a variable called no.
 This is the number of items that are to be deleted from the list.
 Next, it clears out any old data in the file and then prompts for an item number to delete.
 The user enters this into cin and then stores it in no.
 Then, fstream f2; is declared with ios::out so that all output goes to this stream instead of being saved on disk as text files would do normally.
 Next, a while loop starts where we read each line of text until we find one with an item number not equal to what was inputted into cin (no).
 If there is such a line, then s gets set back to its original value which will be null if there were no more lines left or else whatever was inputted into cin (no) otherwise.
After reading through all these lines and deleting anything not equal to what was entered into cin (no), finally another while loop starts where we write everything back onto disk before closing both streams again
 The code is used to delete a record from the file.
 The code opens a file called "Store.txt" in the home directory and then reads from it.
 If the file cannot be opened, an error message is displayed and the user is directed to go to the admin menu to create a new file.
The code opens a text file called "Store.txt" in the home directory and then reads from it.
The program checks if there are any records in this text file before opening it for reading by using fopen().
 If no records exist, an error message is displayed and the user is directed to go to the admin menu to create a new record.
 The code will delete the file "home/aditya/Miniproject/Store.txt" and rename it to "home/desktop/Store.txt".
 The code starts with a function called intro.
 The function has two parameters, the first is an integer that represents the number of lines in the text file and then it has a string that contains "SUPER MARKET".
 The next line prints out "BILLING" on one line.
 Then it prints out "PROJECT" on one line.
 The code will print the following: SUPER MARKET BILLING PROJECT
 The code starts by printing the menu.
 The user is then asked to enter a number between 1 and 7.
 If they enter a number, it will be used in the appropriate function of the code.
 The main menu is followed by an admin menu that has six options: create product, display all products, query product, modify product, delete product and view product menu.
 The code is a main menu.
