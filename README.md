# structure_datatype
In C programming, a struct (or structure) is a collection of variables (can be of different types) under a single name. Structures (also called structs) are a way to group several related variables into one place. Each variable in the structure is known as a member of the structure. Unlike an array, a structure can contain many different data types (int, float, char, etc.).
# Why is it needed?
Lets understand this with an example , there is a student variable that may have its name, class, section, etc. So if we want to store all of its information, We can create different variables for every variable like a character array to store name, integer variable to store the class, and a character variable to store the section. But this solution is a little messy, C provides us with a better neat and clean solution, i.e., Structure. Storing data for a single student is easy, but imagine creating that many variables for 50 students or even 500 or more. So to handle this type of problem, we need to create a user-defined data type that can store or bind different types of data types together, this can be done with the help of structure in C.
# How to create a structure?
‘struct’ keyword is used to create a structure. Following is an example.

struct address

{

char name[50];

char street[100];

char city[50];

char state[20];

int pin;

};

# Limitations of C Structures
In C language, Structures provide a method for packing together data of different types. A Structure is a helpful tool to handle a group of logically related data items. However, C structures have some limitations.

The C structure does not allow the struct data type to be treated like built-in data types:

We cannot use operators like +,- etc. on Structure variables. For example, consider the following code:

# output
![image](https://user-images.githubusercontent.com/93450820/234491608-d47973b0-3e99-4167-834e-35723c96e52d.png)
