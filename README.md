
<p style="text-align:center;"> <img style="float: middle;" src="https://user-images.githubusercontent.com/31522126/73979783-d8886f80-48fc-11ea-870c-7d60bae6ef26.png" width=250 height=250></p>


## __Background__

* __Employment__:

* Postdoctoral Research Associate at the University of Cambridge, United Kingdom. <br>
    &nbsp;&nbsp;&nbsp;&nbsp;[Computer Architecture group](https://www.cl.cam.ac.uk/~tmj32/research/group.html) <br>
    &nbsp;&nbsp;&nbsp;&nbsp;Advisor: Prof. Dr. Timothy Jones
            
* __Education__:
  * PhD (2018 - Jan, 2024) - University of Delaware, USA <br>
                        Advisor: Prof. Dr. Rudolf Eigenmann
  * B.E (2012 - 2016) - University of Mumbai, India


## __Formal CV__
You can find my CV here : [Akshay's CV](https://akshayud.me/Akshay_CV.pdf)

## __Principal Research Interests__
  * Compiler Optimization techinuqes
  * Hardware-Software co-design
  * Automatic Parallelization
  * High Performance Computing
  

## __Publications__

### __Conference Proceedings__

* Márton Erdős, Utpal Bora, __Akshay Bhosale__, Alexandra W Chadwick, Bob Lytton, Giacomo Gabrielli,
Richard Cooper, Yuxin Guo, and Timothy M. Jones, “Loopfrog: In-core hint-based loop
parallelization,” in Proceedings of The 58th IEEE/ACM International Symposium on Microarchitecture,
Seoul, Korea, 2025, (Accepted to appear).

* Yuxin Guo, __Akshay Bhosale__, Alexandra W Chadwick, Utpal Bora, Márton Erdős, Giacomo Gabrielli,
and Timothy M. Jones, “Ghost threading: Helper-thread prefetching for real systems,” in Proceedings of
The 58th IEEE/ACM International Symposium on Microarchitecture, Seoul, Korea, 2025, (Accepted to
appear).

* __Akshay Bhosale__ and Rudolf Eigenmann. [Recurrence analysis for automatic parallelization of
subscripted subscripts](10.1145/3627535.3638493) in Proceedings of the 29th ACM SIGPLAN Symposium on Principles and Practice
of Parallel Programming, ser. PPoPP ’24, Edinburgh, United Kingdom: Association for Computing
Machinery, 2024, pp. 392–403, isbn: 97984007043522403.


* __Akshay Bhosale__ and Rudolf Eigenmann. [On the automatic parallelization of subscripted subscript patterns using array property analysis](https://dl.acm.org/doi/10.1145/3447818.3460424). In Proceedings of the ACM International Conference on Supercomputing (ICS '21). Association for Computing Machinery, New York, NY, USA, 392–403. 2021. [Erratum](https://akshayud.me/Erratum_ICS2021.pdf)

### __Journal Articles__

* __Akshay Bhosale__, Parinaz Barakhshan, Miguel Romero Rosas. [Automatic and Interactive Program Parallelization Using the Cetus Source to Source Compiler Infrastructure v2.0](https://www.mdpi.com/2079-9292/11/5/809). Special Issue "Program Analysis and Optimizing Compilers for High-Performance Computing", Electronics. 2022; 11(5):809.


### __Workshop proceedings__

* __Akshay Bhosale__ and Rudolf Eigenmann, “Compass: A combined parallel subscripted subscript
benchmark suite,” in 36th International Workshop on Languages and Compilers for Parallel Computing
(LCPC), Lexington, KY, USA, October 11–13, (Accepted to appear), 2023, p. 221.


* __Akshay Bhosale__, and Rudolf Eigenmann. [Compile-time Parallelization of Subscripted Subscript Patterns](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9150392) 2020 IEEE International Parallel and Distributed Processing Symposium   Workshops (IPDPSW). IEEE, 2020.

### __Patents__

* Richard Cooper, Giacomo Gabrielli, Bob Lytton, Marton Erdos, Alexandra Winifred Chadwick,
__Akshay Bhosale__, Utpal Bora, and Timothy Jones, “Handling reductions in micro-threaded code,”
Patent Application No.: 202 511 074 400, Application filed in India, 2025.

* Giacomo Gabrielli, Bob Lytton, Richard Cooper, Alexandra Winifred Chadwick, Marton Erdos,
Yuxin Guo, Utpal Bora, __Akshay Bhosale__, and Timothy Jones, “Support for parallel function
continuations,” Patent Application No.: 202 511 074 398, Application filed in India, 2025.

* Giacomo Gabrielli, Bob Lytton, Ali Zaidi, Utpal Bora, __Akshay Bhosale__, Marton Erdos, and
Timothy Jones, “Memory aliasing discriminators,” Patent Application No.: 202 511 074 399, Application
filed in India, 2025.

### __Published Posters__

* Alexandra W. Chadwick, Márton Erdős, Utpal Bora, Akshay Bhosale, Bob Lytton, Yuxin Guo,
Richard Cooper, Giacomo Gabrielli, and Timothy M. Jones, [The future of instruction-level parallelism
(ilp)](10.1109/ISPASS64960.2025.00040), 2025 IEEE International Symposium on Performance Analysis of Systems and Software (ISPASS), 2025.


## __Projects__

### __Speculative Task-Parallelization__
The ParaSol project funded by the Engineering and Physical Sciences Research Council (EPSRC) UK, seeks to develop compiler analyses and transformations to extract parallelism for future processors. I successfully implemented optimization techniques (in C++) to take advantage of and improve instruction-level parallelism for efficient speculative execution of application codes. The techniques have been incorporated into the ParaSol compiler, developed using the industry standard LLVM infrastructure. 

### [Software Prefetching](https://github.com/CompArchCam/GhostThreadingCompiler/tree/release/20.x)
Implemented a compiler transformation pass (in LLVM) to automatically extract helper thread for prefetching data in a Simultaneous Multi-threading (SMT) execution context.

### [Advanced Compiler Analysis Techniques for Irregular Computations](http://subscripted-subscript.akshayud.me/)

Implemented an Analysis technique and extended the related Dependence Test for compile-time automatic parallelization of Subscripted Subscript patterns using the [Cetus](https://sites.udel.edu/cetus-cid/) Source to Source translator which translates from C to C annoted with OpenMP. Details in the publications listed above.


## __Professional Service__

* __Committee Member__ : International Symposium on Code Generation and Optimization (CGO) - ACM Student Research Competition (SRC), 2025, Las Vegas, USA.

* __Program Committee Member__ : The International Conference for High Performance Computing, Networking, Storage, and Analysis (SC), 2024, Atlanta, USA.

## __Supervision Experience__

* Course Supervisor, Lent Term 2025, Course on Optimizing Compilers, Department of Computer Science and Technology, University of Cambridge.

* Supervisor, Undergraduate Final Year Project titled "A JIT Compiler for BEAM bytecode to RISC-V"

## __Internships__ 

* At the [Pacific Northwest National Lab](https://www.pnnl.gov) <br>
  In this project we implemented a Python frontend for a Domain Specific Compiler base on [MLIR](https://mlir.llvm.org) for Computational Chemistry applications. The compiler is called [COMET](https://github.com/pnnl/COMET). 


## __Leadership__

* __University of Delaware__
  * VP Student Affairs (2020 - 2021) - [Graduate Student Government](https://sites.udel.edu/gsg/)
  * International Student Leader (2018 - 2019) - [Office of International Students and Scholars](http://www1.udel.edu/oiss/)
  * Team Lead - [Blue Hen iBuddy Global Mentoring Program](http://www1.udel.edu/oiss/isac/mentor)
  

## __Contact Info__

Department of Computer Science <br/>
William Gates Building, JJ Thompson Ave <br/>
Room SC07 <br/>
University of Cambridge <br/>
Cambridge,Cambridgeshire,UK

<head>
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css"> 
</head>
<body>
<p>
<i style="font-size:24px" class="fa">&#xf0e0;</i> &nbsp;  asb227@cam.ac.uk </p>
</body>


<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
</head>
<body>
<i style="font-size:30px" class="fa">&#xf08c;</i>&nbsp; &nbsp;
<a class="LI-simple-link" href='https://in.linkedin.com/in/akshay-bhosale-a0b5b1103?trk=profile-badge'>Linkedin</a><br /><br />
<i style="font-size:24px" class="fa">&#xf09b;</i><a href= 'https://github.com/akshay9594'>&nbsp;&nbsp;&nbsp;&nbsp;Github</a>
</body>
