# Multithreading vs Multitasking

> *Simply put, Multitasking is handling of different processes at the same time while Multithreading is handling multiple threads of the same process simultaneously.*

But it's not THAT simple to be honest!

## Examples:

When we are coding on our computers whilst listening to music and reading a blog post from our favourite blogger, we're actually **Multitasking**. But on the hand the our IDE i.e. Visual Studio for example is busy **Multithreading** because it is letting you enter new code, checking continuously for errors, and updating your code as you're saving it on the go.

<img src="https://media.geeksforgeeks.org/wp-content/uploads/20191229191005/Untitled-Diagram-227.png" alt="enter image description here">

### Compared to...

<img src="https://media.geeksforgeeks.org/wp-content/uploads/20191229182041/Untitled-Diagram-3511.png" alt="enter image description here">

## 3 Key Differences:

1) Always remember that in **Multitasking**, several processes are executed concurrently, while in multi-threading multiple threads execute either same or different part of program multiple times simultanously.
  
  
2) **Multithreading** is happening inside of multitasking. In multitasking, CPU switches between multiple programs to complete their execution in real time, while in multithreading CPU switches between multiple threads of the same program. Remember, switching between multiple processes has more context switching cost than switching between multiple threads of the same program.
  
3) **Processes** are heavyweight as compared to **threads**, they require their own address space, which means multitasking is heavy compared to multithreading. Interprocess communication is expensive and limited and context switching from one process to another is expensive and limited.
