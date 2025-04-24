# StudentArrayList
Program Overview
This Java program stores and manages student data using an ArrayList. It provides functionality to sort student objects by name and roll number using custom comparator classes and a manually implemented selection sort algorithm. The program avoids using built-in Java sorting methods, showcasing a deeper understanding of sorting techniques.

Features
Student Object Structure:

Fields: rollno (int), name (String), and address (String).

Methods for retrieving field values (getRollno, getName, getAddress) and overriding toString() for better output formatting.

Custom Comparator Classes:

RollnoComparator: Sorts students by roll number.

NameComparator: Sorts students by name alphabetically.

Selection Sort Implementation:

Fully implemented selection sort for ArrayLists.

Sorts based on the provided comparator class, ensuring flexibility and customization.

Main Program:

Creates 10 student objects with sample data.

Demonstrates sorting by name and roll number using selection sort.

How to Run
Ensure Java is installed on your system.

Save the provided classes in separate .java files:

Student.java

RollnoComparator.java

NameComparator.java

SelectionSort.java

Main.java

Compile all files:

bash
javac *.java
Run the main program:

bash
java Main
