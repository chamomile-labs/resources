# resources

organize tomorrow

## operating systems
- [Lions UNIX book](https://joshnatis.github.io/readings/comp/Lions%20-%20A%20Commentary%20on%20the%20Sixth%20Edition%20UNIX%20Operating%20System.pdf)
- sel4
  + check out http://gernot-heiser.org/ and his advanced operating systems course http://www.cse.unsw.edu.au/~cs9242/current/, + his research lab and blog posts
- xv6
  + https://pdos.csail.mit.edu/6.828/2011/xv6.html
  + https://pdos.csail.mit.edu/6.828/2014/xv6/book-rev8.pdf
  + https://github.com/guilleiguaran/xv6
- eric raymond
  + maybe copy over links and titles here with short descriptions
- multics
  + find features from multics that didn't make it into UNIX, those that came afterwards, and those that were foundational for UNIX
  + https://multicians.org/multics.html
  + more about bcpl and cpl
  + more about ctss
  + i think rudd canaday ruddcanaday.com had some stuff about bcpl
  + https://www.multicians.org/fjcc1.html
- Plan 9
  + http://doc.cat-v.org/plan_9/
  + http://9front.org/
- Inferno
  + http://doc.cat-v.org/inferno/
- examine and rewrite weiss's demo files (upload them here)
- Andreas Kling [SerenityOS videos](https://www.youtube.com/watch?v=Fa9SwYfH2NI&list=PLMOpZvQB55bczV5_3DxTLDm37v_F6iCKA)
- [MINIX book](https://joshnatis.github.io/readings/comp/tanenbaum_woodhull_operating-systems-design-implementation-3rd-edition.pdf) by Tanenbaum
- Mach Kernel
- GNU Hurd
- Finish Operating Systems Dinosaur Book
- https://ban.ai/multics/doc/
- https://cs.nyu.edu/rgrimm/teaching/readings/
- https://www.cs.utexas.edu/users/dahlin/advice.html
- http://cs.brown.edu/courses/cs167/
- https://www.sigops.org/
- http://csl.snu.ac.kr/courses/4190.568/2020-2/2-systems.pdf
- https://www.microsoft.com/en-us/research/wp-content/uploads/2016/02/acrobat-17.pdf

```
Chapter 9 - Main Memory
	- Contiguous Memory Allocation, Paging, Structure of the Page Table, Swapping
  - http://compsci.hunter.cuny.edu/~sweiss/course_materials/csci340/slides/chapter09.pdf

Chapter 10 - Virtual Memory
	- Demand Paging, Copy-on-Write, Page Replacement, Allocation of Frames, Thrashing, 
	Memory Compression, Allocating Kernel Memory, Other Considerations
  -  http://compsci.hunter.cuny.edu/~sweiss/course_materials/csci340/slides/chapter10.pdf

Chapter 11 - Mass-Storage Structure
	- HDD Scheduling, NVM Scheduling, Error Detection and Correction, Storage Device Management, 
	Swap-Space Management, Storage Attachment, RAID Structure 
  - http://compsci.hunter.cuny.edu/~sweiss/course_materials/csci340/slides/chapter11.pdf

Chapter 12 - I/O Systems
	- I/O Hardware, Application I/O Interface, Kernel I/O Subsystem,
	Transforming I/O Requests to Hardware Operations, STREAMS
  -  http://compsci.hunter.cuny.edu/~sweiss/course_materials/csci340/slides/chapter12.pdf

Chapter 13 - File-System Interface
	- File Concept, Access Methods, Directory Structure, Protection, Memory-Mapped Files 
  - http://compsci.hunter.cuny.edu/~sweiss/course_materials/csci340/slides/chapter13.pdf

Chapter 14 - File-System Implementation
	- File-System Structure, File-System Operations, Directory Implementation,
	Allocation Methods, Free-Space Management, Effciency and Performance,
	Recovery, Example: The WAFL File System
  - http://compsci.hunter.cuny.edu/~sweiss/course_materials/csci340/slides/chapter14.pdf

Chapter 15 - File-System Internals
	- File Systems, File-System Mounting, Partitions and Mounting, File Sharing,
	Virtual File Systems, Remote File Systems, Consistency Semantics, NFS
  -  http://compsci.hunter.cuny.edu/~sweiss/course_materials/csci340/slides/chapter15.pdf

Chapter 18 - Virtual Machines
	- Benefts and Features, Building Blocks, Types of VMs and Their Implementations,
	Virtualization and Operating-System Components, Virtualization Research
  -  http://compsci.hunter.cuny.edu/~sweiss/course_materials/csci340/slides/chapter18.pdf

Chapter 19 - Networks and Distributed Systems
	- Advantages of Distributed Systems, Network Structure, Communication Structure,
	Network and Distributed Operating Systems, Design Issues in Distributed Systems,
	Distributed File Systems, DFS Naming and Transparency, Remote File Access,
	Final Thoughts on Distributed File Systems
  - http://compsci.hunter.cuny.edu/~sweiss/course_materials/csci340/slides/chapter19.pdf

Chapter 20 - The Linux System
	- Linux History, Design Principles, Kernel Modules, Process Management,
	Scheduling, Memory Management, File Systems, Input and Output,
	Interprocess Communication, Network Structure, Security
  - http://compsci.hunter.cuny.edu/~sweiss/course_materials/csci340/slides/chapter20.pdf

Chapter 21 - Windows 10
	- History, Design Principles, System Components, Terminal Services and
	Fast User Switching, File System, Networking, Programmer Interface
 - http://compsci.hunter.cuny.edu/~sweiss/course_materials/csci340/slides/chapter21.pdf

Chapter A - Influential Operating Systems
	- Feature Migration, Early Systems, Atlas, XDS-940, THE, RC 4000, CTSS, 
	MULTICS, OS/360, TOPS-20, CP/M and MS/DOS, Macintosh Operating System
	and Windows 16, Mach 16, Capability-based Systems—Hydra and CAP 18

Chapter C - BSD UNIX
	- UNIX History, Design Principles, Programmer Interface, User Interface,
	Process Management, Memory Management, File System, I/O System,
	Interprocess Communication

Chatpter D - The Mach System
	- History of the Mach System, Design Principles, System Components, Process Management,
	Interprocess Communication, Memory Management, Programmer Interface
```

## systems programming
* [Weiss's UNIX Systems Programming Course](http://compsci.hunter.cuny.edu/~sweiss/course_materials/cs82010/cs82010_spr13.php)
  - [Chapter 1: Introduction to Systems Programming](http://compsci.hunter.cuny.edu/~sweiss/course_materials/unix_lecture_notes/chapter_01.pdf)
  - [Chapter 2: Login Records, File I/O, and Performance](http://compsci.hunter.cuny.edu/~sweiss/course_materials/unix_lecture_notes/chapter_02.pdf)
  - [Chapter 3: File Systems and Directories](http://compsci.hunter.cuny.edu/~sweiss/course_materials/unix_lecture_notes/chapter_03.pdf)
  - [Chapter 4: Working with the File Hierarchy](http://compsci.hunter.cuny.edu/~sweiss/course_materials/unix_lecture_notes/chapter_04.pdf)
  - [Chapter 5: I/O and Terminal Control](http://compsci.hunter.cuny.edu/~sweiss/course_materials/unix_lecture_notes/chapter_05.pdf)
  - [Chapter 6: Interactive Programs and Signals](http://compsci.hunter.cuny.edu/~sweiss/course_materials/unix_lecture_notes/chapter_06.pdf)
  - [Chapter 7: Event Driven Programming: Timers and Asynchronous I/O](http://compsci.hunter.cuny.edu/~sweiss/course_materials/unix_lecture_notes/chapter_07.pdf)
  - [Chapter 8: Process Architecture and Control](http://compsci.hunter.cuny.edu/~sweiss/course_materials/unix_lecture_notes/chapter_08.pdf)
  - [Chapter 9: Interprocess Communication](http://compsci.hunter.cuny.edu/~sweiss/course_materials/unix_lecture_notes/chapter_09.pdf)
  - [Chapter 10: Threads and the Pthread Library](http://compsci.hunter.cuny.edu/~sweiss/course_materials/unix_lecture_notes/chapter_10.pdf)
  - [Exercise 1](http://compsci.hunter.cuny.edu/~sweiss/course_materials/csci493.66/assignments/exercise_01.pdf)
  - [Assignment 1](http://compsci.hunter.cuny.edu/~sweiss/course_materials/csci493.66/assignments/assignment_01.pdf)
  - [Assignment 2](http://compsci.hunter.cuny.edu/~sweiss/course_materials/csci493.66/assignments/assignment_02.pdf)
  - [Assignment 3](http://compsci.hunter.cuny.edu/~sweiss/course_materials/csci493.66/assignments/assignment_03.pdf)
  - [Assignment 4](http://compsci.hunter.cuny.edu/~sweiss/course_materials/csci493.66/assignments/assignment_04.pdf)
  - [Assignment 5](http://compsci.hunter.cuny.edu/~sweiss/course_materials/csci493.66/assignments/assignment_05.pdf)
  - [Graduate Assignment 1](http://compsci.hunter.cuny.edu/~sweiss/course_materials/cs82010/assignments/assignment_01.pdf)
  - [Graduate Assignment 2](http://compsci.hunter.cuny.edu/~sweiss/course_materials/cs82010/assignments/assignment_02.pdf)
  - [Graduate Assignment 3](http://compsci.hunter.cuny.edu/~sweiss/course_materials/cs82010/assignments/assignment_03.pdf)
  
* [Command-line Interface Guidlines](https://clig.dev/)

## compilers
- parser series (copy links on josh8.com/home)
- gotta read sipser
- learn about types
- text as a universal interface vs types

## computing history
- tuhs and coff
- open source stuff goes here too
- http://www.compsci.hunter.cuny.edu/~sweiss/resources/opensource_links.php#history-of-open-source-and-the-free-software-movement
- http://www.reedmedia.net/books/daemon-gnu-penguin/
- read more about xeroc parc
- read more about sun
- read more about dec

## programing languages
- [plzoo](https://github.com/chamomile-labs/plzoo)
- https://www.sigplan.org/

## audio programming
- web audio
- juce
- max/msp
  + dude youtube channel
- digital signal processing
- copy info from aberrant dsp email
- dlang plugin framework
- copy some youtube channels here
  
## tools
- tracers, profilers, debuggers
- testing!!!
- git
  + https://git-scm.com/book/en/v2
- make
  + https://github.com/stewartweiss/Make-Tutorial

## hardware
- look through hardware books and fill this in

## domain specific languages
- in the brian kernighan sense
- music/video/images

## networks
- unix networking envrionment
- how telephones work (i have one of the books from at&t)

## distributed and fault tolerant systems
- erlang
- distributed systems notes
- one road to AI (intelligent self correcting systems)

## document markup languages and typesetting systems
- scribe language
- \*roff lineage
- thoroughly learn \*roff
	+ "By convention, the macros have uppercase names to distinguish them from groff requests."
	+ "Requests are the low-level typesetting commands that form the heart of groff."
	+ Typesetting commands (visual) vs Document Processing commands (semantic)
	+ https://www.troff.org/using-ms.pdf
	
- reimplement phd as a single header library, extend with separate blog generator

## graphical programming
- x windowing system
- write a window manager
- abrash's graphics programming black book
- ionnis stamos computer vision

## philosophy
- bertrand russell
  + find books and their descriptions
- deleuze
	+ capitalism and schizophrenia
	+ bergson concept of time https://plato.stanford.edu/entries/bergson/
- Wittgenstein tracatus
- turing
	+ https://www.turing.org.uk/sources/index.html
- chomsky
	+ https://chomsky.info/
- marxists.org/archive/trotsky/works/index.htm
- [Philosophy of Language](http://danielwharris.com/teaching/364online/)
- [Bertrand Russell](http://danielwharris.com/teaching/380/)
- [Metaphysics](http://danielwharris.com/teaching/360/)
- [Alan Turing: Computing Machinery and Intelligence](http://danielwharris.com/teaching/268online/weeks/12/Turing.pdf)
- [John Searle: Minds, Brains, and Programs](http://danielwharris.com/teaching/268online/weeks/12/SearleMBP.pdf)

## physics
- a reminder of why i wanted to learn physics again: *how does long distance communication work? magic? to understand the internet maybe i can try to understand telephones first cause theyre seemingly magic too. explanations still take stuff for granted, not fundamental enough. start from the beginning? language --> giving a message to a messenger who travels and relays the message --> written language and couriers relaying written information --> MAGIC HERE... Heliographs and using light to send alerts at long distances (ok makes sense but very basic), telegraph sending signals through wires (wow did we really build long ass wires everywhere? huh.. is that feasible? if this was a program that seems like a brute force solution) (YOU ARE HERE 1: how do signals get sent through wires? what are wires?), WIRELESS long distance communication with radio waves (MAGIC! YOU ARE HERE 2: what are radio waves, what are waves? electromagnetism --> forces, electricity, etc)*
- https://www.wilsonamplifiers.com/blog/a-brief-history-of-long-distance-communication/
- cell tower?
- Wikipedia: [Semaphore](https://en.wikipedia.org/wiki/Semaphore), [Optical Communication](https://en.wikipedia.org/wiki/Optical_communication), [Optical Telegraph](https://en.wikipedia.org/wiki/Optical_telegraph#History), [Radio Waves](https://en.wikipedia.org/wiki/Radio_wave)
- Assorted Videos: [GCSE Physics - Radio Waves #65](https://www.youtube.com/watch?v=Ldnh0XlMVc0) | [How do Radios Work?](https://www.youtube.com/watch?v=drLxfjqZHVo) |  [Radio Waves](https://www.youtube.com/watch?v=sRX2EY5Ubto) | [How do antennas work?](https://www.youtube.com/watch?v=fSoXIqBlg9M) | [Waves: Light, Sound, and the nature of Reality](https://www.youtube.com/watch?v=Io-HXZTepH4) | [HAM Radio Basics- HAM 101](https://www.youtube.com/watch?v=Ow1hxClR5J8)
- Lectures: [Matt Anderson - Electromagnetic waves](https://www.youtube.com/watch?v=bwreHReBH2A), [Matt Anderson - Magnetism](https://www.youtube.com/watch?v=MNrrGLzvljk), [Matt Anderson - Electric Charge and Electric Field Part 1](https://www.youtube.com/watch?v=ZOqMQ0H0-0k) <-- LIFO lol
- Readings: [Robert Penrose - Road to Reality](https://joshnatis.github.io/readings/phys/road%20to%20reality-robert%20penrose.pdf)
- Unrelated stuff: [Noether's Theorem](https://www.youtube.com/watch?v=CxlHLqJ9I0A), assorted Feynman videos

## music
- spectral music (go through tabs copy over links)
- http://www.openmusiclabs.com/
- find that link from video on the_synth (nintendo)
- sculpting with noise
- ambient
- max msp

## visual art
- ffmpeg glitch
- nick briz

## misc
- find canonical programs to read
- maps

# papers
yes
- plan 9 papers
- dennis ritchie papers
- https://www.cs.cmu.edu/~crary/819-f09/
- http://cm.bell-labs.com/cm/ms/what/shannonday/shannon1948.pdf
- http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.72.2622&rep=rep1&type=pdf
- https://canvas.harvard.edu/courses/34992/assignments/syllabus
- http://www.cs.cmu.edu/~aldrich/papers/classic/
- https://www.cs.cmu.edu/~crary/819-f09/Hoare78.pdf
- http://web.eecs.umich.edu/~mosharaf/Readings/RPC.pdf
- http://www.pmg.csail.mit.edu/papers/osdi99.pdf
- https://en.wikipedia.org/wiki/List_of_important_publications_in_computer_science
- https://blog.acolyer.org/
- https://github.com/papers-we-love/papers-we-love
- upload papers files

# reading list
- K&R
- SICP
- GEB
- SCRIBE Reid Thesis
- FORTH post by Moore
- NAND2Tetris
- Lions UNIX
- Dragon Book
- TAOCP
- ucr100 - defense against the dark arts
- Networks Tanenbaum
- unix networking
- Gang of Four Design Patterns
- paul graham
- steve yegge
- computer architecture playlist
        - https://www.you[tube.com/watch?v=zLP_X4wyHbY&list=PL5PHm2jkkXmi5CxxI7b3JCL1TWybTDtKq
- algorithms
        - https://www.youtube.com/playlist?list=PLFDnELG9dpVxQCxuD-9BSy2E7BWY3t5Sm
        - https://www.youtube.com/watch?v=T0yzrZL1py0&list=PLUl4u3cNGP61hsJNdULdudlRL493b-XZf
- git plumbing and porcelain
- Programming pearls
- the mythical man month
- coders at work
- https://www.oreilly.com/openbook/opensources/book/
- the art of unix programming esr
- [https://ptgmedia.pearsoncmg.com/images/9780201615869/samplepages/020161586X.pdf](the practice of programming)
- the unix haters handbook
- Design and Implementation of the FreeBSD Operating System (McKusick)

## small reads
- logging:
	* [Logging 1](https://engineering.linkedin.com/distributed-systems/log-what-every-software-engineer-should-know-about-real-time-datas-unifying)
	* [Logging 2](https://web.archive.org/web/20120326213929/http://juliusdavies.ca/logging.html)
- [Joel Spolsky On Character Sets](https://www.joelonsoftware.com/2003/10/08/the-absolute-minimum-every-software-developer-absolutely-positively-must-know-about-unicode-and-character-sets-no-excuses/)
- [Richard Cook, "Resilience In Complex Adaptive Systems"](https://www.youtube.com/watch?v=PGLYEDpNu60)
- [Philosophers on GPT-3](https://dailynous.com/2020/07/30/philosophers-gpt-3/)
- [Robert Sapolsky Language](https://www.youtube.com/watch?v=SIOQgY1tqrU)
- smdiehl blog posts
- https://en.wikipedia.org/wiki/Tony_Hoare
- sqlite guild principles
- https://www.usenix.org/legacy/event/hotos05/final_papers_backup/red_team/red_html/paper.html
- https://www.seltzer.com/margo/teaching/CS508.19/background/p264-levin.pdf
- https://www.cs.princeton.edu/~chazelle/music/bach.html

## graduate school
- http://www.cs.umd.edu/~oleary/gradstudy/gradstudy.html
- https://web.archive.org/web/20050207033513/https://cs.indiana.edu/how.2b/how.2b.html
- http://www.cs.cmu.edu/~mleone/how-to.html
- https://www.cs.utexas.edu/users/dahlin/Classes/GradOS/13addsched.html
- https://www.cs.utexas.edu/users/dahlin/advice.html
- https://web.archive.org/web/20010816124728/http://www.cs.indiana.edu/mit.research.how.to.html
- http://lunadong.com/advice.htm
- 
