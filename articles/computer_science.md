# Deep Dive Into Computer Science

As the name suggests, Computer Science is the science of computer (yeah, really...).
Because coding is to Computer Science what flying an airplane is to aeronautics, or sewing is to fashion. You get the gist.

If you want to be serious about programming, you need to know a bit about the majot areas of CS. It might not seem super useful at first, but like compound interests it will prove of great value over time.

## What Are The Major Areas Of Computer Science

If we had to divide CS into major areas, here is an attempt to get some clarity, in a bottom-up fashion. Note that there might be some overlap between these areas.

- **Computer Organization** (or **Computer Architecture**): How does a computer actually work deep inside (logical gates, memory, CPU, etc)
- **Compilers**: they bridge the gap between your neat code and actual instructions executed by the machine
- **Operating System**: This drives every code you are going to implement, so better know what this block box is (process, thread, virtual memory, concurrency, I/O)
- **Algorithms and Data Structures**: Every efficient code is based on smart algorithms and data structures, the most known being arguably the hash map (which goes far beyond an "array with a nice way to index")
- **Database**: you might have heard of this one...
- **Networking**: what the heck is Internet after all? how does all that stuff (wifi, http, tcp/ip, ethernet, dns, you name it) come together?
- **Distributed Systems**: the personal computing device has seen its end for a long time already, with many things move to the cloud - getting a grasp of of that stuff work is actually pretty relevant
- **Machine Learning**: not quite sure if it fits into Computer Science per se, but given the growing popularity if the domain it never hurts to know a little beyond the buzz words
- **Tools**: not exactly an area, but still something to get familiar with (unix utilities, git, shell, etc)
- **Methodology and Philosophy**: might sound a little BS at times, but we all have heard about concepts such as Agile, Scrum, Design Patterns and the likes.

## An Attempt For A Study List

There are many way to self-study Computer Science, which obviously depend on your personal goals and interests. A reasonable path would be first to have a broad overviews of the major areas before delving deeper into such and such topics.

There is one unavoidable topics you should probably start with after you have finished the Wagon, that is **Networking**. You cannot be serious about web development if you are shaky about basic things such as http, dns or tcp/ip. This is not difficult (while you can certainly spend indifinite time refining your understanding of subdomains of this topics), and it would be the best investment you have done in terms of CS.

Learn one programming language inside-out - preferably Python, because it is increasingly becoming the lingua franca, but if you want to stick to Ruby this is definitely not a bad choice either. There should be no syntaxic idioms you do not understand, and you should read the whole documentation. Don't worry, this is not so long. In addition to making you a power user of your weapon of choice, it will open your chakrha on virtually all CS topics.

Even if you don't want to specialize in it, learning a bit about **Operating System** is just mandatory. After all, this is the system that executes the code you build, it should not be a complete black box. For instance, if you have ever wondered what a pointer was or how to make use of multicores computers, this is the go-to subject.

All this run on actual machines, so knowing about **Computer Organization** (even if just at the cocktail-party literacy) really helps. For instance: what is a cache memory? how are Intel's CPUs different from ARM's?

Same goes for **Distributed Systems**: what is a datacenter? how are computations run in parallel? What is a CDN?

Frankly the rest is quite optional, depending on what you work on. For instance unless you intend to create your own programming language, well, having an in-depth knowledge of compilers might be satisficing but not exactly useful...


## Some Useful Resources

- A great place to start is the well-named [teachyourselfcs](https://teachyourselfcs.com/). You could probably skip "Programming", "Math for CS" and "Languages and Compilers", for the reasons mentioned above.

- The one book that was an epiphany from some of us is the [Elements of Computing Systems](https://www.nand2tetris.org/), dubbed the "From NAND To Tetris" book. You will learn to build a fully functional (while limited) computer starting from the very basic blocks up to a video game! That gives an overview of Computer Organization, Compilers and (a little) Operating Systems. If you complete it (1 month), you will be ahead of the game.

- In case you want to dig deeper into these specific areas, maybe the Tanenbaum book is more accessible than the Hennessy and Patterson recommended in teachyourselfcs.

- If you want to know more about Distributed Systems, there is a great [github page](https://github.com/donnemartin/system-design-primer) with tons of useful links.

- One book to read before dying: [The Linux Programming Interface](https://en.wikipedia.org/wiki/The_Linux_Programming_Interface). This is more of a reference book than a story you could read chapters after chapters, but if you skim through it you will get a global picture about the way linux works (what is a signal after all? or a system call?)

- Don't forget to read the official documentation of your favorite programming language!

- Finally, stay tuned to the [Hacker Newsletter](https://hackernewsletter.com/). Like in Highlander, if there can only be one, be it that one.
