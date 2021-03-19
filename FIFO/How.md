h1 align="center">FIFO Applications</h1>
<b> What is FIFO?</b>
<p></p>
<p><b>FIFO</b> stands for <b>First In, First Out</b>. It is a way of processing and retriving the data. In FIFO system the first element is processed or servered first and the element which comes next to first element will be processed next.</p>

Real Life Example:

  <img src="https://media.geeksforgeeks.org/wp-content/uploads/FIFO.jpg">

  * In a ticket counter people take their ticket and go in an organized manner
  * In the line (Queue) at the ticket counter the first person get's the ticket first.
  * The person next to the first person will get the ticket next.
  * In this manner, the person who enter the queue last will get ticket at last.

This is known as FIFO System.


<hr>


<p><b>First in, First out</b> system of approach is used in :-</p>

1. Data Structures:<br/>
There are data structures like queue and other variants of queue where we use FIFO approach of processing the data.
2. Disk Scheduling Algorithms:<br/>
Disk controllers use FIFo as a disk scheduling algorithm for ordering dist I/O Requests.
3. Communications and Networking:<br/>
FIFO system is used in communication network bridges, switches and routers in computer networks to hold data packets enroute to their next destination.

Program example foe FIFO implementation in Queue:

``` java

// Java program to demonstrate 
// working of FIFO 
// using Queue interface in Java 
  
import java.util.LinkedList; 
import java.util.Queue; 
  
public class QueueExample { 
    public static void main(String[] args) 
    { 
        Queue<Integer> q = new LinkedList<>(); 
  
        // Adds elements {0, 1, 2, 3, 4} to queue 
        for (int i = 0; i < 5; i++) 
            q.add(i); 
  
        // Display contents of the queue. 
        System.out.println("Elements of queue-" + q); 
  
        // To remove the head of queue. 
        // In this the oldest element '0' will be removed 
        int removedele = q.remove(); 
        System.out.println("removed element-" + removedele); 
  
        System.out.println(q); 
  
        // To view the head of queue 
        int head = q.peek(); 
        System.out.println("head of queue-" + head); 
  
        // Rest all methods of collection interface, 
        // Like size and contains can be used with this 
        // implementation. 
        int size = q.size(); 
        System.out.println("Size of queue-" + size); 
    } 
} 
```

```
Output:

Elements of queue-[0, 1, 2, 3, 4]
removed element-0
[1, 2, 3, 4]
head of queue-1
Size of queue-4
```


<hr>

 Contributed by <a href="https://github.com/ShyamKumar1">Shyam Kumar</a> With 💜. 

 Reach me on
<p align='center'>
  <a href="https://www.linkedin.com/in/shyam-kumar-9b9841157/"><img src="https://img.shields.io/badge/linkedin-%230077B5.svg?&style=for-the-badge&logo=linkedin&logoColor=white" /></a>&nbsp;&nbsp;&nbsp;&nbsp;
  <a href="https://www.instagram.com/_smiling_storm_/" target="_blank"><img src="https://img.shields.io/badge/Instagram-%23E4405F.svg?&style=for-the-badge&logo=instagram&logoColor=white" alt="Instagram"></a>&nbsp;&nbsp;&nbsp;&nbsp;
  <a href="mailto:shyam.ceolife@gmail.com?subject=Olá%20Punit"><img src="https://img.shields.io/badge/gmail-%23D14836.svg?&style=for-the-badge&logo=gmail&logoColor=white" /></a>&nbsp;&nbsp;&nbsp;&nbsp;
  <a href="https://www.facebook.com/shyam.george15/" target="_blank"><img src="https://img.shields.io/badge/Facebook-%231877F2.svg?&style=for-the-badge&logo=facebook&logoColor=white" alt="Facebook"></a>&nbsp;&nbsp;&nbsp;&nbsp;
</p>
