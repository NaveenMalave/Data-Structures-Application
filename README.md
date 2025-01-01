# Data-Structures-Application

### Overview 
This application provides a graphical user interface (GUI) for various data structures: Array, Stack, Queue, Circular 
Queue, and Linked List. Each data structure is presented with options for manipulation and visualization, 
allowing users to interact with it through GUI buttons and inputs.

**Table of Contents** 
1. Main Frame: DataStructures
2. Array Frame
3. Stack Frame
4. Queue Frame
5. Circular Queue Frame
6. LinkedList Frame

**Main Frame: DataStructures**
The main frame, DataStructures, is the home screen for the applicaƟon. Here, users can choose from buƩons 
representing each data structure. Selecting a button opens a new frame where the chosen data structure can be 
manipulated. 

**Title:** "Data Structures"

**Buttons:**
-  Array: Opens the Array Frame 
- Stack: Opens the Stack Frame 
-  Queue: Opens the Queue Frame 
-  Circular Queue: Opens the Circular Queue Frame 
-  LinkedList: Opens the LinkedList Frame 
Each button calls its respective frame, iniƟalizing a new instance and making it visible.

### Array Frame 
The Array Frame allows users to manage an array by adding, removing, and viewing elements. 
GUI Elements 

**Size Input:** A field to set the iniƟal size of the array.

**Element Input:** A field to enter an element to add. 

**Buttons:**
- Add Element: Adds the specified element to the array. 
- Remove Element: Removes the specified element from the array. 
-  Display Array: Shows all elements currently stored in the array.
  
**Display Area:** A text area to show the current state of the array.

**Functionality**
- Adding Elements: The application checks for available space in the array and adds the entered element if 
possible. 
- Removing Elements: The application searches for and removes the specified element.
- Displaying Elements: A display function outputs all elements sequentially.

### Stack Frame 
The Stack Frame enables users to operate on a stack data structure, with opƟons for pushing and popping elements 
and viewing the stack’s content. 

**GUI Elements**

**Element Input**: A field to input an element to push onto the stack. 

**Buttons:**
- Push: Adds the element to the top of the stack. 
- Pop: Removes the element from the top of the stack. 
- Display Stack: Shows the current state of the stack.
  
**Display Area:** A text area to display the elements in the stack from top to bottom.
  
**Functionality**
- Push Operation: Adds an element to the top, as long as the stack is not full. 
- Pop Operation: Removes the element from the top, displaying an error if the stack is empty. 
- Display Operation: Shows all elements from the top of the stack to the bottom.

### Queue Frame 
The Queue Frame provides users with the ability to work with a standard queue, including enqueuing and dequeuing 
elements. 

**GUI Elements**

**Size Input:** Sets the iniƟal size of the queue.

 **Element Input:** Enter an element to enqueue.
 
**Buttons:** 
- Enqueue: Adds an element to the back of the queue. 
- Dequeue: Removes an element from the front of the queue. 
- Display Queue: Shows the current state of the queue.
  
**Display Area:** Shows all elements in the queue from front to rear. 
FuncƟonality

**Enqueue Operation:** Adds an element to the rear of the queue if space is available. 

**Dequeue Operation:** Removes the front element, showing an error if the queue is empty.

**Display Operation:** Displays all elements from front to rear.
  
### Circular Queue Frame 
The Circular Queue Frame allows users to interact with a circular queue, where elements wrap around once the end 
of the queue is reached. 

**GUI Elements**

**Size Input:** Sets the initial size of the circular queue.

**Element Input:** Enter an element to enqueue. 

**Buttons:**
- Enqueue: Adds an element to the queue at the rear position.
- Dequeue: Removes an element from the front posiƟon.
- Display Queue: Displays the elements in the circular queue. 
- Reset: Clears the queue and resets front and rear.
  
**Display Area:** Shows the circular arrangement of elements.
  
**Functonality**

**Enqueue Operation:** Adds elements at the rear, wrapping around if the end is reached. 

**Dequeue Operation:** Removes elements from the front, maintaining circular order. 

**Display Operation:** Outputs all elements, reflecƟng the circular layout.

**Reset:** Clears all elements, reseƫng front and rear.

### LinkedList Frame 
The LinkedList Frame gives users access to operaƟons on a singly linked list, including inserƟon, deleƟon, and 
traversal. 

**GUI Elements** 

**Element Input:** Field to input an element to insert. 

**Position Input:** Field to specify the posiƟon for inserƟon or deletion.

**Buttons:** 
- Insert: Adds an element at the specified posiƟon.
- Delete: Removes an element from the specified posiƟon.
- Display List: Shows the current state of the linked list.
  
**Display Area:** A text area to display the linked list elements in sequence. 
FuncƟonality

**Insert Operation:** Inserts an element at a specific position.

**Delete Operation:** Deletes an element from a specified position.

**Display Operation:** Outputs each element in the linked list from head to tail.

### GUI application using Swing to showcase different data structures

### Purpose
The application is designed as a graphical interface (using JFrame) to navigate through topics related to data structures like Arrays, Stacks, Queues, Circular Queues, and Linked Lists. Each topic is represented by a button, and clicking the button presumably opens a new frame with details or implementations of the respective data structure.

### Components Used
**JFrame:** The main window (DataStructures class) acts as the container for all UI components.

**JPanel:** A panel (contentPane) to hold the components and provide a layout.

**JLabel:** A label to display the title "Data Structures."

**JButton:** Buttons for different data structures, each with an event listener to handle user interactions.

### Core Functionalities

**Event Handling:** Each button has an ActionListener that triggers when clicked. The listeners create and display new frames (Array, Stack, Queue, etc.) representing the respective data structures.

**Navigation:** By invoking the setVisible(true) method on the new frames, users can navigate between different windows of the application.

### Design Details
**Colors and Fonts:** Buttons and labels have been styled using colors and fonts to enhance the visual appeal. For example:
- Background colors (Color.GREEN, Color.CYAN).
- Font styling (Font.BOLD, "Tahoma").
  
**Layout:** Absolute positioning (setBounds) is used to place components at specific coordinates on the panel.

 
<img src="https://github.com/NaveenMalave/Data-Structures-Application/blob/main/DSA%20Images/Screenshot%20(275).png" alt="">
**------------------------------------------------------------------------------------------------------------------------**

### DataStructures.java
<img src="https://github.com/NaveenMalave/Data-Structures-Application/blob/main/DSA%20Images/DataStrcture.png" alt="">
**------------------------------------------------------------------------------------------------------------------------**

### Array.java
<img src="https://github.com/NaveenMalave/Data-Structures-Application/blob/main/DSA%20Images/Array.png" alt="">
**------------------------------------------------------------------------------------------------------------------------**

### CircularQueue.java
<img src="https://github.com/NaveenMalave/Data-Structures-Application/blob/main/DSA%20Images/CircularQueue.png" alt="">
**------------------------------------------------------------------------------------------------------------------------**


### LinkedList.java
<img src="https://github.com/NaveenMalave/Data-Structures-Application/blob/main/DSA%20Images/LinkedList.png" alt="">
**------------------------------------------------------------------------------------------------------------------------**

### Queue.java
<img src="https://github.com/NaveenMalave/Data-Structures-Application/blob/main/DSA%20Images/Queue.png" alt="">
**------------------------------------------------------------------------------------------------------------------------**

### Stack.java
<img src="https://github.com/NaveenMalave/Data-Structures-Application/blob/main/DSA%20Images/Stack.png" alt="">
**------------------------------------------------------------------------------------------------------------------------**
 
 
 ## Technologies used

### 1.Java:
The primary programming language used to build the application.
Provides the foundation for object-oriented design and event-driven programming.

### 2. Libraries and Frameworks
**Swing (javax.swing):**
A part of the Java Standard Library, used to build the GUI components.
Includes classes like JFrame, JPanel, JButton, and JLabel for designing and implementing the user interface.

**AWT (java.awt):**
A lower-level GUI toolkit in Java.
Provides foundational classes like Color, Font, and EventQueue used for custom styling and event handling.

### 3. Event Handling
ActionListener (java.awt.event.ActionListener):
A key interface for handling button clicks and other user interactions.

### 4. IDE Tools (Optional, Not Code Specific)
**Integrated Development Environment (IDE):**
Tools like Eclipse, IntelliJ IDEA, or NetBeans are commonly used to develop Java Swing applications.
They help with designing, debugging, and running the application.

**JDK (Java Development Kit):**
The Java environment required to compile and run the application.
Includes the Java compiler (javac) and runtime environment (java).

### 5. Build and Deployment
**JAR Packaging:**
Once the application is complete, it can be packaged into a Java Archive (.jar) file for easy distribution and execution.

### 6. Operating System
**Platform Independence:**
Java's "write once, run anywhere" (WORA) philosophy ensures the application can run on any OS (Windows, macOS, Linux) with a compatible JVM installed.
  
 ## Authors

- [@NaveenMalave](https://github.com/NaveenMalave)
  ## 🔗 Links

[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/navanishwara-rao-malave-4ab6ba247)
