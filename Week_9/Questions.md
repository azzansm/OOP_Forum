1.
(a) By making use of an example from the above scenario, distinguish between a class and an instantiation of
a class. (3 points)
- Based on the above scenario, a class could be "Product" which has attributes such as name, price and quantity, along
with actions like adding new products and updating stock levels. On the other hand, an instantiation of the "Product"
class could be a particular product, like a "phone", which would have its own values for the attributes defined in the
class, such as "name" being "phone", "price" being "$566", and "quantity" being "23."

(b) By giving two example, explain how the principles of inheritance can be incorporated into the design of this
administration program. (4 points)
- Inheritance for Employee Hierarchy; this can be used to manage employee salaries. The base class would be "Employee",
which contains common attributes like name, job title, and salary. Then specific subclasses, such as "Manager", or
"Sales Personnel", could inherit from the "Employee" class and add additional attributes and behaviours specific to
each type of employee.
- Inheritance for Product Hierarchy; since there are multiple products that the company manages, company could
create a base "Product" class which defines the common attributes and methods shared by all products, such as name,
price and quantity. Subclasses can then be created for specific types of products, such as "Laptops," or "Phones."

(c) Describe how the use of libraries can facilitate the development of program like this company's
administration program. (3 points)
- Libraries can simplify development by abstracting away complex tasks, enabling developers to concentrate on the
specific functionality of the program rather than the details of how to implement it. This, in turn, can reduce errors
and simplify the development process.

2.
(a) Complete the constructor public SalesPerson(String id), from the SalesPerson class. (2 Points)
- Completed.

(b) Explain why accessor methods are necessary for the SalesPerson class. (3 points)
- Accessor methods are necessary because they enable access to the private data members of the class, which cannot be
accessed directly from the outside the class.

(c)
(i) Construct unified modelling language (UML) diagrams to clearly show the relationship between the SalesPerson
and Sales classes. (4 points)
![Diagram.png](images%2FDiagram.png)

(ii) Outline a negative effect that a future change in the design of the Sales object might have on this suite
of programs. (2 points)
- One of the negative effects is the compatibility issue between Sales and SalesPerson. Hence why, it requires
additional modifications.

(d) State the output after running this code. (4 points)
![Output.png](images%2FOutput.png)

(e) Construct the method calcTotalSales(), in the SalesPerson class that calculates the total value of the sales
for a specific SalesPerson object. (5 points)
- Completed.

(f) By making use of any previously written methods, construct the method highest(), that returns the ID
of the salesperson whose sales have the largest total value. (5 points)
- Completed.

(g) Construct the method addSales(Sales s, String id), in the Driver class, that will add a new Sales object s,
to the salesperson with a specified ID.
Note: You can assume that the ID is a valid one. (4 points)
- Completed.

(h) Suggest changes that must be made to the SalesPerson class and/or the Sales class to allow these calculations
 to be made. (3 points)
- In the SalesPerson class:
    Add an instance variable to keep track of the largest sale value and initialize it to 0.
    Add a method that returns an array of all the sales made by the salesperson.
- In the Sales class:
    Add a variable to store the value of the sale.

(i) Discuss the use of polymorphism that occurs in this suite of programs. (3 points)
- Two constructors in the SalesPerson class use overloading.
