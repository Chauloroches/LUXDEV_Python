###  What is garbage collection in the context of Python, and why is it important? Can you explain how memory management is handled in Python?
    1.1 Garbage collection is the automatic freeing up memory by removing objects that are not in use or unreachable and Python uses automatic memory managementto do itas shown below
            valA = [10, 50, 100]
            valB = valA
            del valA
            del valB
    1.2 why is it important?
            a. Optimizes Performance
            b. Simplifies Development
            c. Improves Application Stability
    1.3 Can you explain how memory management is handled in Python?
            a.Reference Counting: Tracks the number of references to an object until it reaches zero then the memory frees.
### What are the key differences between NumPy arrays and Python lists, and can you explain the advantages of using NumPy arrays in numerical computations?
    2.1 What are the key differences between NumPy arrays and Python lists
            a. Numpy arrays are fast and memory-efficient qwhile python lists are slower and less efficient
            b. Numpy arrays are multi-dimensional while python lists are nested for higher
            c. Numpy arrays have extensive mathematical support and python lists have limited buld-in functions
    2.2 Explain the advantages of using NumPy arrays in numerical computations?
            - It has faster operations and memory efficiency
            - Efficient storage and array broadcasting
            - It has built-in functions
### How does list comprehension work in Python, and can you provide an example of using it to generate a list of squared values or filter a list based on a condition?
    3.1  In Python it simplifies the process of generating lists and allows for elegant and readable one-liners, hence makes code easier to maintain.
    3.2  can you provide an example of using it to generate a list of squared values or filter a list based on a condition?
                #####filter
                num = [0, 1, 2, 3, 4, 5, 6, 7, 8, 9,10]

                nums = [x for x in num if x % 2 == 0]
                print(nums)

                ##### Generationg list of square value
                squared = [x**2 for x in range(20)]
                print(square)
####  Can you explain the concepts of shallow and deep copying in Python, including when each is appropriate, and how deep copying is implemented?
    4.1 Can you explain the concepts of shallow and deep copying in Python
                a. Shallow Copying - Creation of object copy of the original object but not copy of nested object. Instead, it copy reference to the nested object.
                b. Deep copying - Creation of completely independent copy from the original one, where changes to the copy should not affect the original copy.
    4.2 Including when each is appropriate, and how deep copying is implemented?
                a. Shallow copying - Appropriate when you want a new object but can share references to the nested objects.
                b. Deep copying - When you need a completely independent copy, where changes to one object should not affect the other.
###  Explain with examples the difference between list and tuples
    5.1 Lists - myList = [1, 2, 3]
                        a. Mutable,Square brackets,Dynamic or frequently changing data and Slower due to mutability
    5.2 Tuple - myTuple = (1, 2, 3)
                        b.Immutable,Parentheses,constant data and Faster and more memory-efficient
                        



            
