Download Link: https://assignmentchef.com/product/solved-ve482-homework-3
<br>
<h1><strong>Ex. 1 — </strong>General questions</h1>

<ol>

 <li>Why would a thread voluntarily release the CPU?</li>

 <li>What is the biggest advantage/disadvantage of user space threads?</li>

 <li>If a multithreaded process forks, a problem occurs if the child gets copies of all the parent’s threads. Suppose that one of the original threads was waiting for keyboard input. Now two threads are waiting for keyboard input, one in each process. Does this problem ever occur in single-threaded processes?</li>

 <li>Many UNIX system calls have no Win32 API equivalents. For each such call, what are the consequences when porting a program from a UNIX system to a Windows system?</li>

</ol>

<table>

 <tbody>

  <tr>

   <td width="102"></td>

  </tr>

  <tr>

   <td></td>

   <td></td>

  </tr>

 </tbody>

</table>

<h1><strong>Ex. 2 — </strong>C programming</h1>

<em>The code of this exercise will be reused in future labs.</em>

The goal of this exercise is to improve the programming skills and get more familiar with pointers and function pointers.

<ol>

 <li>Implement a linked list structure containing two pointers of type char and void. It should be possible to at least add elements to the list.</li>

 <li>Knowing that the void pointer in the structure could contain some char*, int, or double, write a search function for this linked list.</li>

 <li>The linked list will store elements read from an ASCII file where each line is in the format somestring=somedata. The type of the data is defined in the filename; for instance a file containing unsorted integers will be named txt. Implement the necessary functions to read and write such files.</li>

 <li>Use a function pointers to compare and sort the elements from the structure with respect to the data field. Implement the following sorting orders: increasing, decreasing, and random. The filename is txt, where sortingtype is rand, inc, or dec.</li>

 <li>Write a function to test the implementation.</li>

</ol>

Sample output:

<h1><strong>Ex. 3 — </strong>Research on POSIX</h1>

Write a few paragraphs about the POSIX standards. What are they, why do they exist, what kind of things are included in the norms.