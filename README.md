# sleeping_barber
The popular sleeping barber problem, implemented with pthreads, semaphores and mutexes in C.

<b>Input:</b>
<ul>
  <li> number of seats </li>
  <li> total customers </li>
</ul>
  
<b>Output: </b>
<ul>
  <li> average customers' waiting time in ms </li>
  <li> number of customers that were forced to leave </li>
</ul>
  
<b>Barber</b>: pthread <br>
<b>Customers</b>: pthreads

"<i>In computer science, the sleeping barber problem is a classic inter-process communication and synchronization problem between multiple operating system processes. The problem is analogous to that of keeping a barber working when there are customers, resting when there are none, and doing so in an orderly manner.</i>

<i>The analogy is based upon a hypothetical barber shop with one barber. The barber has one barber's chair in a cutting room and a waiting room containing a number of chairs in it. When the barber finishes cutting a customer's hair, he dismisses the customer and goes to the waiting room to see if there are others waiting. If there are, he brings one of them back to the chair and cuts their hair. If there are none, he returns to the chair and sleeps in it.</i>

<i>Each customer, when they arrive, looks to see what the barber is doing. If the barber is sleeping, the customer wakes him up and sits in the cutting room chair. If the barber is cutting hair, the customer stays in the waiting room. If there is a free chair in the waiting room, the customer sits in it and waits their turn. If there is no free chair, the customer leaves.</i>

<i>Based on a naïve analysis, the above decisions should ensure that the shop functions correctly, with the barber cutting the hair of anyone who arrives until there are no more customers, and then sleeping until the next customer arrives. In practice, there are a number of problems that can occur that are illustrative of general scheduling problems.</i>"

Source: https://en.wikipedia.org/wiki/Sleeping_barber_problem
