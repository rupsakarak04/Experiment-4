#**EXPERIMENT 4 : Study of Set in Python**

##*AIM*: **To study the Set data type in Python and perform basic operations** 

*THEORY*:

In Python, a set is a built-in data type used to store a collection of unique and unordered elements. Sets do not allow duplicate values and automatically remove repeated elements, which makes them very useful for handling distinct data efficiently. Since sets are unordered, elements do not have fixed positions and cannot be accessed using index values. Python sets are mutable, meaning elements can be added or removed using methods such as add(), remove(), and discard(). Sets can store elements of different data types like integers, floats, strings, and boolean values, but they cannot contain mutable data types such as lists and dictionaries.

Sets support various mathematical operations like union, intersection, difference, and symmetric difference, which are widely used in solving real-life problems such as finding common elements, eliminating duplicates, grouping data, and comparing datasets. Python also provides an immutable version of sets known as frozenset, whose elements cannot be modified after creation.

In this experiment, different set operations were implemented to understand their working and practical applications in data handling.

*ALGORITHM*:

*Program 1: Creation and display of a set*

     Start the program.
     Create a set using curly braces {} with string elements.
     Store the set in a variable.
     Display the set using the print() function.

*Program 2: Set with different data types*

     Start the program.
     Create a set containing integer, float, boolean, and string values.
     Store the set in a variable.
     Print the set using print().
     
*Program 3: Removal of duplicate elements in set*

          Start the program.
          Create a set with duplicate elements.
          Store the set in a variable.
          Print the set.
          Observe that duplicate values are automatically removed.

*Program 4: Adding an element to a set*

           Start the program.
           Create a set with initial elements.
           Use the add() method to insert a new element into the set.
           Display the updated set using print().
           
*Program 5: Removing an Element from a Set*

          Start the program.
          Create a set with string elements.
          Use the remove() method to delete a specified element from the set.
          Display the updated set using print().

*Program 6: Set Operations (Union, Intersection, Difference, Symmetric Difference)*

           Start the program.
           Create two sets with integer elements.
           Perform union using the | operator.
           Perform intersection using the & operator.
           Perform difference using the - operator (set6 − set7).
           Perform difference in reverse order (set7 − set6).
           Perform symmetric difference using the ^ operator.
           Display the results of all operations.

*Program 7: Creation and Identification of Frozen Set*

            Start the program.
            Create an immutable set using the frozenset() function.
            Store the frozen set in a variable.
            Print the frozen set.
            Display the data type using the type() function.

*Program 8: Removing Duplicate Elements from a List Using Set*

            Start the program.
            Create a list containing duplicate student names.
            Convert the list into a set using the set() function.
            Store the unique elements in a new variable.
            Display the set of unique student names.

*Program 9: Finding Common Subjects Among Students*

          Start the program.
          Create three sets containing subjects chosen by different students.
          Use the intersection operator & to find common elements among all sets.
          Store the result in a variable.
          Display the common subject(s).

*Program 10: Sports Team Set operation*

          Start the program.
          Create two sets representing cricket team and football team members.
          Find students present in both teams using the intersection operator &.
          Find students present in only one team using the symmetric difference operator ^.
          Find students who play only cricket using the difference operator -.
          Find students who play only football using the difference operator - in reverse order.
          Display all results.
          
*Program 11: Finding Absent Students*

          Start the program.
          Create a set of all students.
          Create a set of students who are present.
          Subtract the present-students set from the total-students set.
          Store the result as absent students.
          Display the absent students.

          lgorithm 12: Removing an Element Using discard()

*Program 12 : Course*

         Start the program.
         Create a set containing course codes.
         Use the discard() method to remove a specified course code.
         Display the updated set of course codes.
          
*CONCLUSION:*

Thus, the experiment successfully demonstrated the use of sets in Python for storing unique elements and performing various operations such as addition, removal, intersection, union, difference, and symmetric difference. The concept of frozenset and the use of sets to eliminate duplicate values from lists were also studied. This experiment helps in understanding efficient data management techniques in Python programming.
