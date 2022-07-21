## Classes and Objects
- classes are templates to create an object
- objects are an encapsulation of variables and they get their variables and functions from classes
- Example of a class 
- class MyClass:
      variable = "blah"

      def function(self):
          print("This is a message inside the class.")
- To accese a variable inside of an object 
  - class MyClass:
      variable = "blah"

      def function(self):
          print("This is a message inside the class.")

  myobjectx = MyClass()

  myobjectx.variable
  
  ## Recursive
  - A recursive function is a function defined in terms of itself via self-referential expressions.
  - Example of a recursive function
  - n! = n x (n−1) x (n−2) x (n−3) ⋅⋅⋅⋅ x 3 x 2 x 1
    n! = n x (n−1)!
