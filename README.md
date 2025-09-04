# ClassesAndObjectsInCpp

# Experiment 11 – Volume of a Cube (Using Classes in C++)

---

##  Aim
To study and implement the concept of classes in C++ to calculate the volume of a cube using different approaches:
1. Using direct data members (Public access).
2. Using a member function inside the class.
3. Using private data members with public functions.
4. Using input functions and display functions with encapsulation.

---

## 📖 Theory
- **Class:** A class in C++ is a user-defined data type that can hold data members (variables) and member functions (methods).
- **Objects:** Objects are instances of a class. They are used to access the members of the class.
- **Encapsulation:** Wrapping up data and functions together into a single unit (class).
- **Access Specifiers:**
  - **Public:** Members are accessible from outside the class.
  - **Private:** Members are hidden from outside and can be accessed only through public methods.
- **Member Functions:** Functions declared inside a class that operate on class data members.

In this experiment, we calculate the volume of a cube (`length × breadth × height`) using four different implementations to understand **class basics, member functions, encapsulation, and abstraction**.

---

## Algorithm 

### Experiment 11A – Volume using Public Data Members
**Algorithm**
1. Start the program.  
2. Define a class `cube` with public data members: `height`, `width`, `length`.  
3. Create an object of the class.  
4. Calculate volume as `height × width × length`.  
5. Display the result.  
6. End.  

---

### Experiment 11B – Volume using Member Function
**Algorithm**
1. Start the program.  
2. Define a class `cube` with public data members.  
3. Write a member function `volume()` that returns `height × width × length`.  
4. Create an object of the class.  
5. Call the `volume()` function and store the result.  
6. Display the volume.  
7. End.  

---

### Experiment 11C – Volume using Private Data Members
**Algorithm**
1. Start the program.  
2. Define a class `cube` with private data members (`height`, `width`, `length`).  
3. Write a public member function `volume()` to calculate `height × width × length`.  
4. Create an object of the class.  
5. Call the `volume()` function.  
6. Display the result.  
7. End.  

---

### Experiment 11D – Volume using Input and Display Functions
**Algorithm**
1. Start the program.  
2. Define a class `Volume` with public member functions: `input()`, `vol()`, and `display()`.  
3. Take user input for `length`, `breadth`, and `height` inside `input()`.  
4. Calculate volume in `vol()` as `length × breadth × height`.  
5. Display the result using `display()`.  
6. End.  

---

# Conclusion
- Implemented **basic class and object concepts** in C++.  
- Learned how to use **public and private access specifiers**.  
- Understood how **encapsulation** hides data using private members.  
- Demonstrated different ways of calculating volume using:  
  - Direct data members  
  - Member functions  
  - Private members with abstraction  
  - Input and display methods  

Hence, the experiment successfully demonstrated the calculation of volume using **C++ classes and objects** in multiple approaches.  

---
