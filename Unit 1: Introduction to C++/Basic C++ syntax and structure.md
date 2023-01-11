<h2> Notes </h2>

By the end of this lesson, you should be able to:  

1. Understand the basic file structure of a C++ program, including the role of the main() function.

2. Write, compile, and execute a simple "Hello, World!" program.

3. Develop your first C++ game.



Now, after this brief introduction let's start by knowing how to set up our environment.



To start, open your preferred text editor. In my case, I'm using Visual studio code.
Create a new file and name it "main.cpp" where main is just the name of the file and "CPP" is the extension of the file, c plus plus

Now let's write our first piece of code and break it down.





![cout](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/d1msubvp9kkgqdm7ocit.png)





**line 1** we have what we call a pre-processor, _`#include`_ itself is used to import functions and code from another file, this is used to let us use functions that we or other developers wrote before. 





Whenever the compiler encounters a pre-processor which in our case is _`#include`_, it searches for the corresponding file that is written between the <> and goes to that file, retrieves all the code, and writes it in the header of our file, on the very top of our page.



_`#include <iostream>`_ is used to import the basic input/output functions such as reading user input and printing output to the console.





**line 3** we started our actual program by writing the main function. This is the entry point of our programme. We use the main function to organise our code as it is the indicator of where our programme starts its execution process.







**line 3** This is the actual step where we print out our first output, "Hello, world", `std::cout << "Hello, world";`



cout is the way for us to print something to the console, and it is spelt as _see-out_.





The `<<` operator is known as the insertion or put-to operator. **be careful not to mix it up with the shift operators**, they're both very similar. They're the same, but when it is used with cout it takes the value on the right and puts it to the value on the left, and in this case, we take the "Hello, world" string and pass it to the cout function for it to print it out.







Finally, we _`return 0`_ as an indication of the successful execution of the program.





Ah, finally, this was boring. Let's spice it up. I was thinking of a simple program that prints out two strings, not only one, but my problem is... how? but before that, let's have a general review of what we covered that could help us.



<table width="100%">

<thead>

<tr>

<th>Code</th>

<th>usage</th>

</tr>

</thread>

<tbody>

<tr>

<td><pre>#include < iostream > </pre></td>

<td>

<code>Used to import the standard input and output functions</code>

</td>

</tr>

<tr>

<td><pre>int main()</pre></td>

<td>

<code>Our main entry for the execution of the code</code>

</td>

</tr>

<tr>

<td><pre>std::cout</pre></td>

<td>

<code>used to print something to the console</code>

</td>

</tr>

</tbody>

</table>



Now that you've learned how to print something for the console, what about getting something from the console?



Maybe you already figured it out, we used c-out `cout` to print something... maybe there's c-in `cin`?



Well, yes, there's a `cin` and to our fortune, it's pretty similar to how `cout` works.





![cin](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/te6sg87bhpdvdiw7ogqe.png)



See? it's not that big of a difference they work similarly to each other, std::cin as of a way to take in input from the user instead of printing out.



But here we used `>>` instead of `<<` but it works the same, just the other way around. Instead of taking the value on the right and assigning it or putting it in the value on the left, we here, take the value on the left, which is our input `cin` and put it in the value on the right. Which is our age variable.



so if we type in `20` as our input, the variable `age` will be assigned this value and would act as if it is 20.



There's an easy way to differentiate between both, apart from the in and out, you can imagine it as an arrow, wherever the arrow is being shot at is where it is going to put its value in, and wherever it's shot from, it takes the value behind it with it.





this was the very basic input and output of C++, there'll be a small test on the github [repo](https://github.com/Moayed-Ellah/Unleashing-C-From-Basic-to-Advanced) along with an assignment of a small project.



If you have any questions, feedback or would like to know more about me. 

you can reach me out on my [LinkedIn](https://www.linkedin.com/in/moayedellah/), [github](https://github.com/Moayed-Ellah)
