Exercise 1 - Theory questions
-----------------------------
 
 ### What is the difference between concurrency and parallelism?
 > Parallelism is when multiple tasks run at the same time, while cuncurrency is when multiple task can be cumputed simultaneously because the processor swaps between the tasks, which makes the illusion of parallelism. 
 
 ### Why have machines become increasingly multicore in the past decade?
 > Because it increases the speed of processing because it is possible to do multiple task at once. 
 
 ### Why do we divide software (programs) into concurrently executing parts (like threads or processes)?
 (Or phrased differently: What problems do concurrency help in solving?)
 > Conurrently execuing parts will improve the run time of a problem since several tasks will be completed at once. 
 
 ### Does creating concurrent programs make the programmer's life easier? Harder? Maybe both?
 (Come back to this after you have worked on part 4 of this exercise)
 > Maybe both. It increases efficiancy but also introduce a set of problems such as...
 
 ### What is the conceptual difference between threads and processes?
 > A process provides resources and memory needed to execute a program, and within this process, there can be one or more threads sharing the same resources and memory as the proces has provided. The threads will execute instructions concurrently. 
 
 ### Some languages support "fibers" (sometimes called "green threads") or "coroutines"? What are they?
 > Fibers are a light version of executing a thread, where the fibre yield themselves to run another fiber instead of the threads depending on the kernel's scheduler to prevent a thread and resume another.

 ### What is the Go-language's "goroutine"? A C/POSIX "pthread"?
 > Goroutines are also a light verson of threads. It is methods or functions that run concurrently. There can be severeal goroutines on one thread.
 Pthreads are an execution model thath exisist independently from the programming language and parallel execution model. Each single work flow is referred to as a thread, and is controlled by calls to an API.

 ### In Go, what does `func GOMAXPROCS(n int) int` change? 
 > It changes the limit of the number of CPUs that can execute user-level Go code simultaneously. 



 
 
 
 
