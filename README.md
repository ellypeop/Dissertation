# Log Book
**COMP8805/8800 Elly Sinden [ers31@kent.ac.uk](mailto:ers31@kent.ac.uk)**
## Aims & Objectives - Overall Project
- What are the learning objectives I intend to achieve throughout the project?
- Were these learning objectives achieved?
- Were there any other successes?

## Project Timeline
- Make a note of Aims & Objectives for any milestones during the project
- All decisions should be justified
- Record any insights gained (things you don’t understand) or advice given by peers
- Record mistakes and how they were rectified

### 16/01/2024

I wanted to pursue a main project related to quantum computing due to an interest in the topic. QUML presented an opportunity to work within this domain without heavily relying on physics knowledge, which I do not possess a strong background in. I contacted Carlos and read the paper linked in the forum - [Towards a Quantum Software Modeling Language](https://dl.acm.org/doi/abs/10.1145/3387940.3392183)

### 17/01/2024

I initially met with Carlos and was given additional reading: [A Quantum Software Modeling Language](https://link.springer.com/chapter/10.1007/978-3-031-05324-5_6). I understood that the project would be related to how quantum computers can be represented in UML. I believe UML is an achievable language to learn and base my main project on, and I would have the opportunity to better understand quantum computers.

### 18/01/2024

The early concept of the project was to implement a quantum extension to an already existing UML platform. I spoke with a friend who is a software engineer who recommended the open-source UML package Mermaid to create UML designs - [mermaid](https://github.com/mermaid-js/mermaid)
Before using this package, I needed a better theoretical understanding of UML as a practice. I also wanted to investigate the “go-to” UML packages for software engineers or people who use UML regularly.

### 19/01/2024

Carlos accepted me onto the project with him as my supervisor. I registered for the quantum computing module COMP8220 and attended the first lecture (Introduction to Linear Algebra). I will voluntarily participate in the module to gain an overall understanding of quantum computing while simultaneously learning UML.

### 24/01/2024

I read the government's National Quantum Strategy [NQS](https://www.gov.uk/government/publications/national-quantum-strategy)after attending a talk in the physics department that mentioned it. I believe it may illuminate relevant UK bodies related to quantum computing and that I could access more resources to further my understanding of quantum. Goal 3 in NQS aligned with Carlos' aim in the QUML paper: adoption of Quantum technologies in the UK, the goal being to integrate quantum technologies with industry end users, those without a core understanding of quantum physics.

### 01/02/2024

Researched links to UK Quantum organisations mentioned in NQS to source potential contacts or opportunities to practise using quantum software emulators. Focused on NQCC, so far, could only garner opportunities for paid courses but could do with further research.

### 07/02/2024

I am aware of IBM’s Qiskit, an open-source, Python-based quantum SDK. It has not yet been adequately investigated, but it is worth noting that it is possible to code in a quantum language and how this could be applied to UML.

### 11/02/2024

I started doing independent learning in linear algebra to build the understanding necessary for the first half of the COMP8220 module. However, it was proving difficult and taking time away from other tasks:

![](https://lh7-rt.googleusercontent.com/docsz/AD_4nXd-00ahSS1iXPWyRAH1-dEigmaGzp0RcoBQvleohrFgkKEfCpRITfUbTtSalpbJ6fQCZmXAmTXkI4SlOKGGg7a3FW4nmGjnJhOOJTkafviXJoNdz9tjD9pZ16ZLfUaB8qds5Ax4YzBbDnDPhJ8w9km-Scum?key=MtrDKbB_sX2MmzFn_dLBrg)

### 13/02/2024

I started reading UML @ Classroom, which is referenced in QUML and recommended by Carlos as a good resource for understanding the basic concepts of UML.

### 14/02/2024

First group meeting with Carlos and other students working on quantum-related projects. Carlos mentioned his new paper Q-Cosmic, which I’ll read after the meeting to discuss afterwards and give a broader understanding of quantum software engineering—we discussed what background knowledge we’d need for our projects, the first step, how to achieve it, and which technologies. The project proposal is due roughly 1st March and will be a concrete dissertation topic. We mentioned organising a regular reading group. What is a blockchain? Related to other peers' work

![](https://lh7-rt.googleusercontent.com/docsz/AD_4nXfUxJYohtS6wuw6C8IcR1pUx6RcHgsjmwDgimlmxhYOcXOR4XchaeWk7wWZkAISUp-MmqkLkBlv47l6LZGOzC0qfe8pZzexZcGKY-T3IxnCscQtnmhuRItd2jiwDMCitamQ3IEa3ukMzIPD-xvPc2265sYl?key=MtrDKbB_sX2MmzFn_dLBrg)

### 20/02/2024

I looked into the practicalities of UML and the people who use it. Feedback from Reddit states there are so many nuances to UML, and it is better to leave it ambiguous to avoid being incorrect, so they tend to employ a simplified version of UML. They would need a basic understanding of UML in the first place to do this. Anecdotal information from Reddit and friends who are software developers say they don’t use UML. However, friends who are technical business analysts mostly use sequence diagrams and use case diagrams. Sometimes, class diagrams. They use UML frequently but on a case-by-case basis. They have not used a communication diagram. States that business analysts and solution architects use it the most.

Links:

[WebSequenceDiagrams](https://www.websequencediagrams.com/) 
[What is Communication Diagram?](http://www.visual-paradigm.com/guide/uml-unified-modeling-language/what-is-communication-diagram) 
[C4 model](http://www.c4model.com) 
[UML Design Resources](http://www.gitlab.com/mail.umlcat/uml) 
[How often do you use UML?](http://www.reddit.com/r/softwaredevelopment/comments/x3fgx2/how_often_do_you_use_uml/) 
[Miro](http://www.miro.com) 
[Unified Modeling Language (UML)](http://www.sparxsystems.com/resources/user-guides/15.2/model-domains/uml-models.pdf)

Following this research, I’ve decided to expand on the work in the QUML paper and create an example of one of the other UML diagrams not included in the paper and how it can be used for quantum computing. I decided to leave investigating how to create a quantum extension for a UML package. I was now unsure how popular it would be if software developers said they don't use UML packages but instead do their diagrams based on UML diagrams. By creating an example of other UML diagrams for quantum, it could be adopted by different professionals either explicitly using UML or their variation of UML.  I want to start by creating a communication diagram as it’s related to sequence diagrams and can drill down into the communication between different quantum/classical elements.

### 21/02/2024

Second group meeting. To look into Grover and Shor algorithms, understanding quantum algorithms will aid in fully comprehending the UML examples provided in the QUML paper and creating other UML diagrams. We discussed Q-Cosmic; it's the beginning of thinking about how to quantify the size of the software before its existence to charge it in the future. Q-Cosmic: Hybrid Communication. Carlos suggested that to investigate communication diagrams further, look into Quantum State Preparation when moving from classical to Quantum and Quantum Measurement when moving from Quantum to classical.

### 12/03/2024

I started looking into quantum state preparation; it comes in many forms, as it's a technique to modify the quantum system to observe a quantum state. I found the following information related to the topic:

[Quantum state preparation of normal distributions using matrix product states](https://www.nature.com/articles/s41534-024-00805-0#:~:text=Quantum%20state%20preparation%20is%20an,applications%20in%20a%20variety%20of) 
[Preparation of Entangled States by Quantum Markov Processes](https://arxiv.org/abs/0803.1463) 
[On the reality of the quantum state](https://arxiv.org/abs/1111.3328) 
[What is a quantum "state preparation procedure" and what isn't](https://physics.stackexchange.com/questions/388148/what-is-a-quantum-state-preparation-procedure-and-what-isnt)
[What exactly does state preparation mean in quantum computing?](https://quantumcomputing.stackexchange.com/questions/34273/what-exactly-does-state-preparation-mean-in-quantum-computing)

After this research, I understand that it is the process of placing a quantum system into a specific state. Manipulating the system can be achieved through several means, including using quantum gates, quantum algorithms, applying electromagnetic fields, and controlling particle interactions.

I found the subject matter a little overwhelming, particularly regarding what route I would need to take to show the communication between classical and quantum computers effectively. I believe the next step is to go back to the basics of understanding the fundamentals of the quantum gates and read the relevant literature.

I have also attended Carlo's COMP8220 lectures and learnt the Deutsch algorithm. I need to take the same approach as learning classical computers and understand the difference between low-level (gates) and high-level (algorithms/code using an HLL) required in the communication diagram. 

I still need to read up on quantum measurement. However, from lectures and previous reading into quantum computing, I can understand why this works: By measuring a qubit, it collapses the quantum state and will be fixed at a 0 or a 1. 

I need to review linear algebra, as I’m still not confident about it, to better understand quantum gates. It would also help me grasp the algorithms better. I can continue to learn standard UML communication diagrams, but it will be easier to hold the QC aspect when understanding the fundamentals. 

I researched the low-level aspects that I didn’t fully understand before, particularly notations such as why the square root of ½ is used.

Links:

[Quantum Pies, Waves, and Grandma’s Kitchen: A Deep Dive into 1/sqrt(2)](https://medium.com/@anala007/quantum-pies-waves-and-grandmas-kitchen-a-deep-dive-into-1-sqrt-2-228a5c35b257#:~:text=In%20the%20quantum%20realm%2C%20particles,states%2C%20we%20get%20equal%20probabilities) 
[Why do I see 12√12 a lot in QM?](https://physics.stackexchange.com/questions/715091/why-do-i-see-frac1-sqrt2-a-lot-in-qm)

To summarise what I’ve learned, in quantum mechanics, probabilities are represented as probability amplitudes, which are complex numbers due to the wave-like nature of quantum particles. Magnitude squared by the probability amplitude gives the likelihood of a particular outcome (quantum state). ½ represents the probability, and the square root ½ represents the probability amplitude. Probability amplitudes can be negative or imaginary which reflects superposition principles. 

I’ve also made a note to look into Euler's formula.

### 13/03/2024

Third group meeting. I discussed my concerns with Carlos, who advised me to avoid getting bogged down in the details. I don’t need to understand the fundamentals of linear algebra and everything involved with quantum to complete the project; this would be impossible anyway. I left the meeting with some “breathing space” to collect myself and work out the best first steps. 

We discussed the properties of a good research paper when writing our own. The requirements are:
- abstract
- intro
- conclusion
- good title

It needs to leave the reader wanting more, each sentence adding further value, and avoid overselling what's written (good abstract, bad content). Original content should be 60%/70% with background information being 40%/30%.

I’ve opted to base the critical review on Carlos’ QUML paper as this is the basis for my project. We discussed what makes a good critical review:

- walk away understanding the reviewed paper
- understand what the results of the reviewed paper are about
- The reader doesn't need to read the reviewed paper; they can go off yours, and yours should be “better.”
- provide additional contributions to the reviewed paper 
- contribute something meaningful
- something no one has done before; useful, novel and with value
- results, strengths and weaknesses

Carlos mentioned that literature reviews are valid scientific output. They typically condense 100 papers into 1, so you don't have to read 100! He also advised us to spend half of our time on the main project and the other half on the modules due to their significance to our final marks. 

I’ve also made a note to look into Quantum Polarising Filters.

Reading recommendations:

- Systemisation of Knowledge (SoK) papers
- The New Scientist
- Quantum Computing for Computer Scientists by Mirco A. Mannucci and Noson S. Yanofsky
- Quantum Computation and Quantum Information by [Michael A. Nielsen](https://www.amazon.co.uk/Michael-A-Nielsen/e/B0058XJGHM/ref=dp_byline_cont_book_1) and [Isaac L. Chuang](https://www.amazon.co.uk/Isaac-L-Chuang/e/B005WHOMH8/ref=dp_byline_cont_book_2)

### 03/04/2024

Group meeting. We discussed the benefits of using Overleaf for the critical review and dissertation due to its professional formatting and ability to utilise and create a bibliography of Bibtex files for referencing. I need to confirm whether the dissertation and corpus are one unified document or separate. It would be helpful to obtain books on scientific writing/academic writing to understand better how to write a good dissertation. Carlos has recommended keeping it clear and concise as a general rule. 

Carlos advised me to use an assertive voice instead of a passive voice. I should not use the royal “we” or “I” but include the reader. For example, “We will study…” So we as in myself and the reader, not the royal we. 

Regarding critical review references, it would be helpful to compare other papers related to the subject matter during the evaluation that may have achieved what the reviewed paper didn’t. However, this is not essential.

### 04/04/2024

First project methods workshop. Notes were taken to consider as the project is research-based as opposed to developing a piece of software:

*   Research; not known or new perspective
*   Must be able to replicate the results you’ve discovered
*   Fit your work in the context of what others have done
*   Challenge well-established existing ideas
*   The right question, not the right answer (this has also been discussed in our group meetings)
*   Find ways your finding does not work to further discovery and improvements
*   Utilise [DBLP](https://dblp.org/) for sourcing research papers
    
Could QUML only apply in a particular context? Is it restricted in its design? 
My research:

*   Define specific research questions with Carlos. 
*   How does it interact with the broader field of knowledge?
*   Ask Carlos about prominent publications on quantum computing.

The organisation of research:

*   Set targets
*   Identify milestones
    
Don’t write your dissertation like a chronological logbook. Report in the order that makes the most sense to the user:

*   Introduce the concepts and base information that’s required to understand the paper
*   Establish what the base knowledge of the reader is
*   Write so it gives the reader base knowledge of the topic in the introduction

### 05/04/2024

I spoke with Carlos during the final lecture after having a “lightbulb” moment regarding UML communication diagrams and quantum. I asked whether a good question to ask is how UML communication diagrams can be used to illustrate the communication between classical and quantum computers, seeing as classical computers are needed to interact with quantum computers at present. Carlos advised that it was a worthwhile question to ask.

### 18/04/2024

I began preparing for the critical review. I referred to the critical review lecture slides, specification document and [Fong’s](http://eliassi.org/fong-sigcse.pdf) paper on structuring a critical review. In preparation for writing the review, I utilised the following GitHub repository [sort-google-scholar](https://github.com/WittmannF/sort-google-scholar) and searched papers under the term “Quantum UML”. It brought up the following papers. I read the latter two in full and about ten pages of the former:

[Quantum Software Engineering](https://arxiv.org/abs/2007.07047)
[Modelling Quantum Circuits with UML](https://arxiv.org/abs/2103.16169)
[Design of classical-quantum systems with UML](https://link.springer.com/article/10.1007/s00607-022-01091-4) 

The Quantum Software Engineering (QSE) paper is a fantastic resource that gives an overview of all aspects of the field and expands my understanding beyond just QUML and how it fits into the grand scheme of things relating to the domain of QSE. The other two papers (one being an extension of work to the other) give a different perspective on how to apply quantum to UML through UML profiles. This is a resource I can return to analyse more in-depth when applying quantum concepts to UML diagrams.

### 26/04/2024

Completed and submitted the critical review. I was able to lay a timeline of where QUML fits into the grand scheme of things in the development of QSE:

![image.png](/.attachments/image-c117b78e-9dd5-401b-b6fb-d4fda3d9832c.png)

I now better understand how new QSE and QUML fit into the grand scheme of things. Combined with the research papers relating to QSE, it feels more manageable, as there are many different applications within this, such as quantum programming languages, with the QUML principles and axioms that can also be applied. I don’t need to focus on the minute details, such as linear algebra, to understand how software engineering principles can be applied to quantum computing.

After completing the critical review, I can implement the design choices of bold text for textual information and double-line pictorial information and how to apply this to a new UML design. My next step in constructing UML designs is to recreate the examples in Carlos’ paper. This should give me an understanding of both Shor’s algorithm and how the examples utilise the rules of UML and their specific diagrams. I need to move away from the theoretical and apply the practical to solidify my understanding.

### 02/05/2024


I looked into recreating the use case diagram in the QUML paper. A software engineer I know had previously sent me information on [PlantUML](https://plantuml.com/)) (PUML) as an open-source Java library where you create UML diagrams through code. I was drawn to using this as I would enjoy the ability to implement UML through code and work on some practical coding work for the project.

I had also looked into Miro; however, the number of designs that could be created was limited.

I began learning how to construct a use case diagram in PUML and copying the example from the QUML paper. I used the inbuilt [Creole](https://plantuml.com/creole) markup to implement the bold text. However, there was no inbuilt functionality to create double dashed lines, which is necessary to indicate the quantum <<include>> relationship between the two use cases and for the use cases themselves:

![](https://lh7-rt.googleusercontent.com/docsz/AD_4nXe9eygBXzRjqQwIhXx7xn_kGQGjNJa9UsvJ-Izb9-c_caBQQsjxuBsJedjK4QnCCK5lxa7Mh-QRuV0RdKzne_6sLj4hcHNXKF4boaUkHVniUEQwfL6LBfONAUW3G-ohm-vq1sHfETihsc3GU__DiU2JmoUi?key=MtrDKbB_sX2MmzFn_dLBrg)

I would like to access the PUML GitHub repository and make my adjustments to include this functionality. Due to its open-source nature, PUML could be a good option for creating a quantum extension for UML. However, as this process is to solidify my understanding of both quantum algorithms and UML diagram structures through practical experience, I believe it would be better to spend my time finding a UML package where I can include these design functions immediately, as it would take me time to learn how to modify PUML. 

I investigated recommended applications and got mixed reviews for PUML. Some people enjoy using it, while others say it does not scale well as diagrams become more complex. There were also recommendations to use Mermaid (as previously suggested) as PUML is quite old now, and Mermaid is also open-source. However, as it’s older, could it also mean it’s more popular/has greater support for modifications?

Links:

[Is there any open source software for doing UML diagrams?](https://www.reddit.com/r/opensource/comments/bnb467/is_there_any_open_source_software_for_doing_uml/)
[PlantUML turns text into diagrams](https://www.reddit.com/r/programming/comments/ebes8j/plantuml_turns_text_into_diagrams/) 
[Hacker News](https://news.ycombinator.com/item?id=26980704#:~:text=Using%20PlantUML%20for%20UML%20is,be%20extracted%20from%20the%20diagram).
[Plant UML in VS 2022 community edition and push to Github?](https://www.reddit.com/r/learnprogramming/comments/13bkjbd/plant_uml_in_vs_2022_community_edition_and_push/)

I looked into the applications of PUML for communication diagrams via the forum and was linked to the following type of diagram:

[Component Diagram](https://plantuml.com/component-diagram#:~:text=By%20default%2C%20links%20between%20classes,%F0%9F%8E%89%20Copied)

I will return to this task and Miro (even if I have to pay for a subscription) as this seems a popular choice with software engineers already and hopefully has the versatility to incorporate the QUML design choices. Once I can fully replicate them, I will provide textual explanations of what they represent in the context of Shor's algorithm and the specific UML diagram. 

I also spent the day transferring diary notes into a Logbook following recommendations from [Les Johnson](https://www-cs-kent-ac-uk.chain.kent.ac.uk/people/staff/djb/LOCAL-ONLY/logbook.html)

### 28/05/2024

I returned to the project after finishing exams. I used Miro to recreate the use case diagram in Carlos’ paper. During this process, I created a Word document, “Analysing QUML Diagrams”, to break down the UML aspects and Q-UML; my thought process is to apply this to all the diagrams in the paper to get a sound understanding of how to use UML in this process, I’ll then move on to learning how classical systems interact with quantum systems and can create my own QUML diagrams of these processes.

I encountered the same roadblock as before: there isn’t a straightforward answer to creating double-lined connections. I emailed Carlos to ask how he made the diagrams for his paper. However, this shouldn’t hinder me from analysing the diagrams in the paper. I’ve completed the use case diagram and will now move on to the class diagram.

![](https://lh7-rt.googleusercontent.com/docsz/AD_4nXcDT_icd6WfFqCR8dHOXgOmHUuuDUMiy3pP98T1jraxToPi3e40W2aI6sDgepF2VjHEBoMattyz86aO3ZEgEoYPaGD0E0fmMFQBuJCjneadob8ct5BnrOUzDSLel6htvW9DwmrnQlsMi_1UhdnAuoY6XaxR?key=MtrDKbB_sX2MmzFn_dLBrg)

**An issue noted when going through class diagrams is that the book UML @ Classroom states that class names are centred and written in bold font. In QUML, quantum class names are bold, whereas classical names are not bold. This is a change to the standardisation of UML, so it’s worth investigating what the common practice is and whether a design change needs to be made for QUML, for example, using underlining rather than bold to denote quantum.**

**A minor note is that “m” was used instead of “*” to denote multiple in the aggregation between ShorApplication and ShorFactor.**

### 29/05/2024

Continuing with class diagram analysis. I finished running through the diagram and understanding the UML notations. I did not have a complete understanding of how this example represents Shor’s algorithm in code, so I looked at the following videos to piece together my understanding:

[Shor's Algorithm — Programming on Quantum Computers — Coding with Qiskit S2E7](https://www.youtube.com/watch?v=EdJ7RoWcU48)
[The Story of Shor's Algorithm, Straight From the Source | Peter Shor](https://www.youtube.com/watch?v=6qD9XElTpCE&t=27s)

It would be nice to have, but not a must-have, to understand this and fully summarise the diagram's operation. However, I will only spend a little time on this and continue with the following UML diagram. As my work will be based not on Shor’s algorithm but on the communication between classical and quantum computers, it’s not essential to understand Shor’s algorithm for now; this process is more to understand the UML notations through deciphering working examples. 

I also re-watched the following to refresh my understanding of Shor’s algorithm - [How Quantum Computers Break Encryption | Shor's Algorithm Explained](https://www.youtube.com/watch?v=lvTqbM5Dq4Q)

### 30/05/2024

I started the morning by quickly analysing the state diagram in QUML. This one is relatively straightforward (negating the fact I haven’t delved into the actual context of what the diagram represents, i.e. how Quantum Fourier Transforms work); however, it is worth bearing in mind when investigating how classical computers interact with quantum as there will be a state change when moving from classical to quantum information and visa versa. The initial plan had been to focus on communication diagrams and possibly others not depicted in the QUML paper; however, once I conduct my research into classical/quantum interaction, it should become more apparent which UML diagrams are required. So, rather than extending the Shor algorithm example and applying it to other UML diagrams to transform to QUML, I would consider another aspect of quantum software (classical/quantum interaction) and how this can be depicted through design.

Before moving on to Activity Diagrams, I wanted a better understanding of how we interact with Quantum Computers, so I looked at the following:

[Decoded: How Does a Quantum Computer Work?](https://youtu.be/uLnGp1WTNFQ)
[Quantum computing: Facts, fiction and the future](https://www.youtube.com/watch?v=rTx5nw3AgnY)

This led me to look further into Sycamore and [Google Quantum AI](https://quantumai.google/)and, following the roadmap, looked further into NISQ -
[Noisy intermediate-scale quantum era](https://en.wikipedia.org/wiki/Noisy_intermediate-scale_quantum_era) and [Beyond quantum supremacy: the hunt for useful quantum computers](https://www.nature.com/articles/d41586-019-02936-3)
[What is NISQ](https://www.quera.com/glossary/nisq)

I intend to use UML to model existing quantum architecture instead of a theoretical QC software algorithm. 

A potential topic to investigate could be error correction algorithms and quantum-based simulators.

I finished my reading session today and am interested in further exploring classical/quantum hybrid algorithms such as VQE, QAOA, and VQF. Tomorrow, I will investigate QAOA to see if it can be a good focus point for understanding a quantum/classical hybrid algorithm and how this can be illustrated via QUML. 

I will return to the topic tomorrow and watch this:

[Lecture 5.2 - Introduction to the Quantum Approximate Optimization Algorithm and Applications](https://www.youtube.com/watch?v=YpLzSQPrgSc)

Also, it would be worth looking into Qiksit and Cirq.

### 04/06/2024
I spent this period researching the QAOA algorithm. Some general links during these investigations were:  
  
[Solve utility-scale quantum optimization problems](https://learning.quantum.ibm.com/tutorial/quantum-approximate-optimization-algorithm)
Farhi, J Goldstone, S Gutmann - A quantum approximate optimisation algorithm
[Quantum Machine Learning - 18 - Quantum Approximate Optimization Algorithm (QAOA)](https://www.youtube.com/watch?v=N8e5nAk6KBQ)
[What is a Hamiltonian? Quantum Jargon Explained](https://www.youtube.com/watch?v=BusR0WQ_Gxo) - A video understanding Hamiltonians. This was necessary as Hamiltonians represent a system, and the algorithm seeks to find the ground state of a system.
[A tutorial on Quantum Approximate Optimization Algorithm (Oct 2020). Part 1: Theory](https://www.youtube.com/watch?v=AOKM9BkweVU) - This was the critical video used to attempt to understand the algorithm, with a link to a related GitHub repository: [QAOA_tutorial](https://github.com/rsln-s/QAOA_tutorial)

### 10/06/2024

I returned to researching the QAOA algorithm after having a week off. Relevant links include:
[Quantum optimization algorithms](https://en.wikipedia.org/wiki/Quantum_optimization_algorithms)
[BQP](https://en.wikipedia.org/wiki/BQP) - roughly the equivalent of classical P class (stated in YT video), determining the hardness of algorithms. 
[Hermitian matrix](https://en.wikipedia.org/wiki/Hermitian_matrix)
[Quantum vacuum state](https://en.wikipedia.org/wiki/Quantum_vacuum_state)
[Maximum cut](https://en.wikipedia.org/wiki/Maximum_cut)
[Combinatorial optimization](https://en.wikipedia.org/wiki/Combinatorial_optimization#cite_note-1)
[Optimization problem](https://en.wikipedia.org/wiki/Optimization_problem)
[A tutorial on Quantum Approximate Optimization Algorithm (Oct 2020). Part 2: Hands-on](https://www.youtube.com/watch?v=E0Sos_lR-kI)

I started writing informal notes on QAOA in a separate Word document to formulate better and understand the algorithm in my head. 

One aspect that could be represented in QUML is translating the classical problem formula to a Hamiltonian space.

Links to Pennylane, an open-source framework for Quantum ML, has videos and tutorials on writing the QAOA algorithm in PennyLane:
[QAOA: A different perspective | PennyLane Tutorial](https://www.youtube.com/watch?v=cMZcA2SQnYQ)
[Intro to QAOA](https://pennylane.ai/qml/demos/tutorial_qaoa_intro/)

To do: Look into Fourier expansion.

### 11/06/2024

Whilst reading a paper on QAOA (A Review on Quantum Approximate Optimization Algorithm and its Variants), I came across a section which discusses the VQE algorithm:

![](https://lh7-rt.googleusercontent.com/docsz/AD_4nXd8iVXWthUYO1DWt6eslC1-ooKw_ewOBs_MYCJC8sh9uDDa4oPXucqeRkDLV9EZWpRHKV5m_E31Xws4mD8QnI69xmCaSEz-CzsS-BnzdM4Uox4xkuxri-uQUu18wnGGRPvNniwrlcKhQIQ1Tv5kgArgUW_G?key=MtrDKbB_sX2MmzFn_dLBrg)

I was particularly drawn to implementing VQE on a hybrid classical/quantum system. My initial goal had been to source information on classical/quantum systems interacting with each other to represent via a UML communication diagram. 

I started to look into VQE using the following links:

[A variational eigenvalue solver on a photonic quantum processor](https://www.nature.com/articles/ncomms5213) - This is the original paper, which has information on the hardware used in the experiment, which could be used for a UML diagram

[The theory of variational hybrid quantum-classical algorithms](https://arxiv.org/abs/1509.04279)

[Variational Quantum Eigensolver | Qiskit Global Summer School 2023](https://www.youtube.com/watch?v=AhEnvYgoA34)—This video was the primary source for deepening my understanding of VQE. It also mentions how QAOA and VQE are essentially the same algorithms from different fields. QAOA is frequently demonstrated with the Maxcut problem; they both seek to find a global minimum, the system's ground state. The link to the related GitHub is [qgss-2023](https://github.com/qiskit-community/qgss-2023).

I decided to switch from QAOA to VQE as there would be no loss in prior work understanding QAOA. They are essentially the same algorithm as VQE, which has further information on the classical/quantum hardware and an IBM tutorial on how to code it in Qiskit. Although I could have used Pennylane, coding the algorithm to further my understanding and having some experience writing in Qiskit would be beneficial. Also, whereas QAOA is typically demonstrated via the Maxcut problem, VQE has the potential of being simpler, whereby tutorials just discuss how it seeks the ground state as opposed to applying it to a problem. 

I also looked into different software for UML diagrams, which would allow me to implement the graphical choices of Q-UML. The links were:

[drawio github](https://github.com/jgraph/drawio)
[drawio](https://www.drawio.com/)

I received a reply from Carlos regarding what he used in the Q-UML paper: Lucidchart. 

Links presented in the IBM YT VQE video which could be relevant:

![](https://lh7-rt.googleusercontent.com/docsz/AD_4nXfPczAxMG5QYQziKvYofg315oEiLwStfT_s5_8tZwoAtKvs73K0WpUqHtYtaSUK_eewpHuyWzLWIyfB4E8Ens_g4IFQ_lylws2l06LMwPgPzcGqadre0rlAsOvCYTfgrNcnwi3C7NlVe5mUuK0Kuf_n1m5-?key=MtrDKbB_sX2MmzFn_dLBrg)

Extract from the A Review on Quantum Approximate Optimization Algorithm and its Variants paper, going into detail on hybrid quantum/classical systems:

![](https://lh7-rt.googleusercontent.com/docsz/AD_4nXc_-9gAW4RmYGl_JUyAWS4CCM8KEl7w_IaSUhJ3oazp95MUSKT5ABD0CbITtfvKEi9fMBXOoleL70GBrkzLGembAyoFgXtpkxpIviJcuql6gqOaHh0F3l9NHpX2kP9DUfdLa0vityI3UNLnX01LK0Esosnh?key=MtrDKbB_sX2MmzFn_dLBrg)

### 11/06/2024

I attended workshops during this period. 

After deciding on VQE as the algorithm to base my UML designs, I returned to the following paper (Modelling quantum circuits with UML), which was included in my critical review. This was another approach to adapting UML for quantum systems, and I wanted to re-read it to understand better what it does differently to Carlos. Essentially, they use functionality in UML diagrams called profile diagrams, which can be adapted for niche fields, such as adapting quantum technologies. 

The authors followed up this paper (Design of classical-quantum systems with UML), which I will look into after.

Links from today:

[Profile_(UML)](https://en.wikipedia.org/wiki/Profile_(UML))
[UML Profile](https://www.uml-diagrams.org/profile.html)
[What is Profile Diagram in UML?](https://www.visual-paradigm.com/guide/uml-unified-modeling-language/what-is-profile-diagram/)

My current thought process focuses on communication diagrams representing classical and quantum interaction. I could apply different UML adaptations to this interaction, such as QUML, UML quantum profile diagram, and potentially a third one I constructed myself. I want to represent communication, the interaction between the physical systems, and a class diagram for the VQE algorithm. Another thought is whether to speak to Rogério about the best way to measure the effectiveness of these diagrams within the software engineering community. 

I started watching lecture recordings on modelling from software engineering. I am stuck on how to proceed, so I will email Carlos. 

Extract from the Design of classical-quantum systems with UML refers to it being a good idea to explore UML in its representation of fundamental QC properties:

![](https://lh7-rt.googleusercontent.com/docsz/AD_4nXeOup9pzdJNwTcQrFFokE7pvITJDHky7m9T5hduiyGav378qC03tJFLBj-jE51tvwpEd5_BIOQiUB6Vd8zv_yae46Qo5RshuWFY-Y_93uDRdu4jPZVIUTbf56MKcVUquKGviJ8uXK9-afhhvVQ0soR-vn-8?key=MtrDKbB_sX2MmzFn_dLBrg)

### 17/06/2024

I finished reading  Design of classical-quantum Systems with UML. Links from today:  
[UML Profile Diagram](https://www.youtube.com/watch?v=YS0jwXst5sg)

The conclusion of the paper has some good jumping-off points in directions of where the quantum UML profile could be applied next, which is worth investigating:

![](https://lh7-rt.googleusercontent.com/docsz/AD_4nXfIw5t9vcXowIAX5v7XyeIj2xhUpGmk6U9Mo-QxQJJj_I3UI_AhbMLCPH-b19JHzATAy-H8jxUlhfgkkErRECNaPvLVZior_1GwY8t5XLdrhXK47NYlQofsCG5Nz_BwfUYPHJ07NeknZzXgPO1rMco6J8-q?key=MtrDKbB_sX2MmzFn_dLBrg)
![](https://lh7-rt.googleusercontent.com/docsz/AD_4nXdw_AiCwvm49hxnfTkSIC8sFfV2OmPu85Vrm1sn34AS4ta_0kUtWy4eyOaCsyPQ8XM0n-tzjIsOHZyj-e0oJiRhba06MEy1L1LbTHSOE0Lzxiyuh8i_Wb8kMEB9CyhuLFBNr-BJFZlSTpisMcMUtKdO7i4U?key=MtrDKbB_sX2MmzFn_dLBrg)

I spoke with Carlos on Teams to discuss where I am now and the best steps going forward. Carlos thinks it is interesting to apply the two UML approaches, his and Perez-Castillo’s, and this is worth exploring. This could be used for both NISQ and standard QC systems. As I have spent time learning about QAOA and VQE, this would be a good place to start.

So, I will apply the two UML approaches to VQE rather than focusing on communication diagrams. I will start with a class diagram and break down how the algorithm operates; the next best step will be to code the algorithm in Qiskit following the IBM tutorial. Once I’ve had a go at working with it practically, I will start creating UML diagrams. 

Carlos advised that this would allow me to examine the strengths and weaknesses of the two UML approaches. I could also investigate other aspects beyond VQE, such as superposition and entanglement, as discussed in the paper, Grover’s algorithm, and how the UML approaches handle both NISQ and complete QC systems. However, having one complete piece of work is better than many half-baked pieces, so I will just focus on VQE for now. I sent Carlos a link to the UML profile and VQE paper.

I will start drafting the thesis layout's bare bones, and once this is done, I'll follow the IBM tutorial on how to write VQE in Qiskit. 

Links:
[Variational Quantum Eigensolver | Qiskit Global Summer School 2023](https://www.youtube.com/watch?v=AhEnvYgoA34&t=2319s)
[Eigenvectors and eigenvalues | Chapter 14, Essence of linear algebra](https://www.youtube.com/watch?v=PFDu9oVAE-g)
[Sean Carroll: Hilbert Space and Infinity](https://www.youtube.com/watch?v=9GV4QmQWJGU)

I have started a summer internship with Giftease, so I’ll have less time to focus on the dissertation for now; however, I have been granted a 3-month extension to my deadlines. I will attempt to work on the dissertation as and when I can during the internship.

### 18/06/2024
Links related to VGE algorithms:
[vqe-molecules.ipynb](https://github.com/Qiskit/textbook/blob/main/notebooks/ch-applications/vqe-molecules.ipynb)
[Instances and Extensions](https://learning.quantum.ibm.com/course/variational-algorithm-design/instances-and-extensions)
[Variational quantum eigensolver](https://learning.quantum.ibm.com/tutorial/variational-quantum-eigensolver) - started with this tutorial

I looked into following one of the above examples and coding in Qiskit. I used the [following tutorial](https://www.youtube.com/watch?v=oaAjxcIFLtM&list=PLOFEBzvs-VvrgHZt3exM_NNiNKtZlHvZ) on installing Qiskit and ultimately created a new environment via Pycharm to install and code in Qiskit. I then copied the code in the example, which uses real Quantum hardware to execute.

![](https://lh7-rt.googleusercontent.com/docsz/AD_4nXdy_QrD8ErSlmL8aPaHp6cFymkj2sXOGiuDUr5ax8lQL-gCn0FMwhJ0Uu8E-7CO7WqVQbP9OQXOdzArZwXafPatkqsqQ4uRzrHIMa5tdhWPKVbYwqALFq11KzrIfORKASB7WpOFCBgzHwqaNGnNAeObbAvb?key=MtrDKbB_sX2MmzFn_dLBrg)

At this point, I didn’t necessarily understand what was happening and became quite conscious that there’s only a 10-minute allowance monthly to use this hardware. I thought it could have been used on a quantum simulator rather than hardware.

My friend pointed out that I didn't need to write code for what I wanted to do, which is true. So, I will return to reviewing the IBM articles on VGE and select one to translate into a QUML class diagram.

### 01/07/2024

Whilst looking at the IBM learning page, I started looking into this - [Single systems](https://learning.quantum.ibm.com/course/basics-of-quantum-information/single-systems)

This was a helpful resource, but it gets down to the minute details when they may not be necessary for UML/VGE. 

I started building the VGE algorithm using [this tutorial]
(https://learning.quantum.ibm.com/tutorial/variational-quantum-eigensolver) in Lucidchart. I will continue with this. Links from today after the picture:

![](https://lh7-rt.googleusercontent.com/docsz/AD_4nXeTsWt9-ouwRygQBuZ8sLmouEOyxFgWJg8Zib9qn2RJvfGJ8DCgd1b4ZHb5EKvSPnY0la-OtAA066aHsm5vvc80Sj6sXnX7qetU2_5uIE1oPMrfAe0q-iIjapvgdBlFxQglza-75OoKUns0ew3ziS9NI4-A?key=MtrDKbB_sX2MmzFn_dLBrg)

Links:
[Variational Quantum Eigensolver](https://learning.quantum.ibm.com/tutorial/variational-quantum-eigensolver)
[SparsePauliOp](https://docs.quantum.ibm.com/api/qiskit/qiskit.quantum_info.SparsePauliOp)
[EfficientSU2](https://docs.quantum.ibm.com/api/qiskit/qiskit.circuit.library.EfficientSU2)
[Operator](https://docs.quantum.ibm.com/api/qiskit/qiskit.quantum_info.Operator)
[UML Class Diagram Tutorial](https://www.lucidchart.com/pages/uml-class-diagram)
[Build and deploy quantum programs with Qiskit Runtime](https://cloud.ibm.com/quantum)
[Instances and Extensions](https://learning.quantum.ibm.com/course/variational-algorithm-design/instances-and-extensions)
[Variational Algorithms](https://learning.quantum.ibm.com/course/variational-algorithm-design/variational-algorithms)
[Single Systems](https://learning.quantum.ibm.com/course/basics-of-quantum-information/single-systems)
[The Pauli matrices](https://www.youtube.com/watch?v=2MsVD9ufguk&t)
[Lucid Chart](https://lucid.app/documents#/documents?folder_id=home)

### 13/07/2024

Created a “VGE- Layman terms” Google doc to break down the elements of the algorithm I’m following ([Variational Quantum Eigensolver](https://learning.quantum.ibm.com/tutorial/variational-quantum-eigensolver)) into simpler terms so I could fully understand what the code was doing. 

I also watched some videos to refresh myself on the algorithm, as I had struggled to explain it simply when discussing dissertation progress with peers. 

Links:
[The Variational Quantum Eigensolver (VQE) in a Nutshell](https://www.youtube.com/watch?v=TWRUdBEC16o)
[The Variational Quantum Eigensolver — Programming on Quantum Computers — Coding with Qiskit S2E4](https://www.youtube.com/watch?v=Z-A6G0WVI9w)

### 25/07/2024

I spent the past few weeks working on the “layman's terms” document, which I completed tonight. This document thoroughly investigated the quantum aspects of the problem and used Gemini/documentation for the more general coding aspects later in the algorithm. 

Now that this document is completed, I am more confident in understanding what is happening in the code. I will now return to creating a diagram based on this algorithm. My process will start with a rough diagram and then implement UML standardisation. I will then adapt to Carlos’ quantum extension of UML and implement the quantum UML profile diagram. Possibly, right after Carlos’ diagram, I will start writing the dissertation as I can begin discussing aspects like the background before having both diagrams completed. 

I have struggled to balance dissertation and internship work. I lose my memory regarding topics for the dissertation and have to spend time familiarising myself with the domain when returning to this work, a two-step forward, one-step back situation.

### 19/09/2024

I used a Pycharm plugin to translate the code from [this tutorial](https://learning.quantum.ibm.com/tutorial/variational-quantum-eigensolve) (written as a Python file instead of a Jupyter notebook) into a class diagram, which I could use to understand class diagrams and then translate into the Q-UML format. It could not translate it into a class diagram, whether or not because it can’t recognise the Qiskit library or because the plugin needs internal classes within the file if it does not look for the external classes from libraries used in the code (i.e. SparsePauli0p, EfficentSU2).

This then raised the question of the most suitable UML diagram for constructing the first UML diagram of the VQE Qiskit tutorial code. I had initially considered constructing communication diagrams. However, a sequence diagram may be more suitable. It is similar to communication diagrams, whereby both are behavioural diagrams that demonstrate the dynamic interactions of a system; however, sequence diagrams are more commonly used.

The VQE algorithm consists of interactions between different classical and quantum modules to solve the problem; therefore, a UML diagram that illustrates a series of messages may be the most suitable initial diagram.   There is also the advantage that sequence diagrams have already been constructed in the QUML and quantum UML profile texts,  as opposed to communication diagrams, which would mean I would have direct references during their construction.

I began looking into sequence diagrams and their fundamental aspects, such as lifecycle dependency. I will now start translating the VQE Qiskit algorithm into a sequence diagram.

### 24/09/2024

I returned to the dissertation after the end of the internship last week and started creating the VQE Qiskit algorithm using Plant UML as a Pycharm plugin. A few months prior, I had some experience writing in PUML and felt this was less labour-intensive than constructing the diagram using a GUI, as PUML uses plain text code to construct the diagrams.

![](https://lh7-rt.googleusercontent.com/docsz/AD_4nXeN4MhgvhSXi2XIvMRBISkD6K0sxr8Pu4z7btMTASzqEWVy1tovxjR_rnvEbbbjTQubgs0c4rytQhAdsGKu64ZNhEwqOKpODFoA4cEzshna8RQycUQ8gTkKPb505-e6USDKOQi4rBgji5QWsaeAmJKj3Aae?key=MtrDKbB_sX2MmzFn_dLBrg)

Links:
[Variational Quantum Eigensolver](https://learning.quantum.ibm.com/tutorial/variational-quantum-eigensolver)
[Overview of Sequence Diagrams](https://plantuml.com/en-dark/why-sequence-diagram#:~:text=Sequence%20diagrams%20are%20a%20type,task%20flows%20in%20a%20system).
[Sequence Diagram](https://plantuml.com/sequence-diagram)
[SparsePauliOp](https://docs.quantum.ibm.com/api/qiskit/qiskit.quantum_info.SparsePauliOp)
[Target](https://docs.quantum.ibm.com/api/qiskit/qiskit.transpiler.Target)
[UML sequence diagram how to draw instance passed to another instance](https://stackoverflow.com/questions/63208214/uml-sequence-diagram-how-to-draw-instance-passed-to-another-instance)
[Preset Passmanagers](https://docs.quantum.ibm.com/api/qiskit/transpiler_preset)
[StagedPassManager](https://docs.quantum.ibm.com/api/qiskit/qiskit.transpiler.StagedPassManager)
[PassManager](https://docs.quantum.ibm.com/api/qiskit/qiskit.transpiler.PassManager)
[How to destroy a participant?](https://forum.plantuml.net/7758/how-to-destroy-a-participant)
[Operator](https://docs.quantum.ibm.com/api/qiskit/qiskit.quantum_info.Operator)
[EfficientSU2](https://docs.quantum.ibm.com/api/qiskit/qiskit.circuit.library.EfficientSU2)
[Explore the UML sequence diagram](https://developer.ibm.com/articles/the-sequence-diagram/)
[Methods in a Sequence Diagram](https://stackoverflow.com/questions/45884730/methods-in-a-sequence-diagram)
[UML Sequence Diagram](https://plantuml-documentation.readthedocs.io/en/latest/diagrams/sequence.html)
[Sequence Diagram: Background Loop](https://stackoverflow.com/questions/49803428/sequence-diagram-background-loop)
[minimize](https://docs.scipy.org/doc/scipy/reference/generated/scipy.optimize.minimize.html)

### 25/09/2024

I completed the first draft of VQE SD using PUML. I had to reconsider the order of the “Minimize” and “Cost Function” methods as Min is essentially an outer loop implementing the Cost Func within it. This, in turn, meant I’d included the loop and alt fragments with the alt depicting the verification process at the end of the search.

Modifications will likely be made to the message types (request and response); however, this can be reviewed when applying the QUML standard. I will now copy the PUML SD onto [Lucidchart](https://lucid.app/documents#/documents?folder_id=home) and apply QUML standards. I will re-read Carlos's paper to familiarise myself with the modifications.

![](https://lh7-rt.googleusercontent.com/docsz/AD_4nXdF_0qL5uYwcVbEAXGV9imMIQRcge3MBC1h1Y_-NPkJAv_vc-8n_0nPHwoCW3PzkRui02t9-JlPuQFxopnMxqrAfKqSR9uSpqBCzIRQD4ty-WuyVR15tpoq7WN16HZxUVoesXZfh5eezjOOWSdQol-do0-c?key=MtrDKbB_sX2MmzFn_dLBrg)

Links:
[Target](https://docs.quantum.ibm.com/api/qiskit/qiskit.transpiler.Target)
[EstimatorV2](https://docs.quantum.ibm.com/api/qiskit-ibm-runtime/qiskit_ibm_runtime.EstimatorV2)
[minimize](https://docs.scipy.org/doc/scipy/reference/generated/scipy.optimize.minimize.html)
[EstimatorOptions](https://docs.quantum.ibm.com/api/qiskit-ibm-runtime/qiskit_ibm_runtime.options.EstimatorOptions)

### 26/09/2024

I’ve started drawing up the SD as an SD using QUML in Lucid Chart

So far, I am confident with everything up to Hamiltonian (the first one!), but I need to assess whether ansatz would be considered a classical or quantum object. 

I’ve tried to refer to the documentation regarding the classes used to construct the instances. However, there doesn’t appear to be any information regarding whether they access classical or quantum hardware. I’ve had to use a combination of common sense and ChatGPT to make my assessment, which is that the information will be held classically until there is a need to access quantum hardware to search the parameter space.

Links:

[SparsePauliOp: num_qubits](https://docs.quantum.ibm.com/api/qiskit/qiskit.quantum_info.SparsePauliOp#num_qubits)
[numpy's complex128 conversion](https://stackoverflow.com/questions/31794782/numpys-complex128-conversion)
[QiskitRuntimeService](https://docs.quantum.ibm.com/api/qiskit-ibm-runtime/qiskit_ibm_runtime.QiskitRuntimeService)
[IBMBackend](https://docs.quantum.ibm.com/api/qiskit-ibm-runtime/qiskit_ibm_runtime.IBMBackend)
[Target](https://docs.quantum.ibm.com/api/qiskit/qiskit.transpiler.Target)
[NotebookLM](https://notebooklm.google.com/notebook/e511d0ad-28cb-4e4a-b965-ef3dcaa0b37e)

![](https://lh7-rt.googleusercontent.com/docsz/AD_4nXdBmZ1Oh1w4uiXGthGI3tcFUbSOhHWIgGEpP3yXdDF08XWz5oTOKssvx6riDwVGEcJhNwlxBmbK8zQreop0vybrsi0_AUzgKR67AePlTMLRj1fSv952gushgR4Zgu5rajImiK8LNVCsJwtpj-ZgMBEbtABl?key=MtrDKbB_sX2MmzFn_dLBrg)

### 27/09/2024

I finished transferring the SD to Lucidchart and implementing QUML notation on it. I now need to start drafting the early deliverable, which should be an overview of the dissertation's contents and a walkthrough and explanation of the QUML VQE SD. 

Links:

[Circuit Library](https://docs.quantum.ibm.com/api/qiskit/circuit_library)
[QuantumCircuit](https://docs.quantum.ibm.com/api/qiskit/qiskit.circuit.QuantumCircuit)
[PassManager](https://docs.quantum.ibm.com/api/qiskit/qiskit.transpiler.PassManager)
[Add and customize shapes in Lucidchart](https://help.lucid.co/hc/en-us/articles/16390096079764-Add-and-customize-shapes-in-Lucidchart)

### 02/10/2024

I started working on the dissertation plan to submit for the early deliverable due on the 5th alongside the Q-UML VQE SD. I completed the problem description/goals and objectives.

### 03/10/2024

Continuing with the early deliverable, keeping a record of resources used whilst drafting it.
[Information about Q-SE 2020](https://q-se.github.io/qse2020/)

Links:
[ICSE 2020](https://conf.researchr.org/home/icse-2020)
[First International Workshop on Quantum Software Engineering (Q-SE 2020)](https://www.researchgate.net/publication/350523166_First_International_Workshop_on_Quantum_Software_Engineering_Q-SE_2020)
[Quantum software engineering](https://librarysearch.kent.ac.uk/client/en_GB/kent/search/detailnonmodal/ent:$002f$002fSD_ILS$002f0$002fSD_ILS:1839317/ada?qu=quantum+software+engineering&d=ent%3A%2F%2FSD_ILS%2F0%2FSD_ILS%3A1839317%7EILS%7E0&h=8)
[A Quantum Software Modeling Language](https://link.springer.com/chapter/10.1007/978-3-031-05324-5_6)
[Design of classical-quantum systems with UML](https://link.springer.com/article/10.1007/s00607-022-01091-4)
[Towards a Quantum Software Modeling Language](https://www.researchgate.net/publication/347455308_Towards_a_Quantum_Software_Modeling_Language)
[ICSEW'20: Proceedings of the IEEE/ACM 42nd International Conference on Software Engineering Workshops](https://dl.acm.org/doi/proceedings/10.1145/3387940)
[Modelling Quantum Circuits with UML](https://arxiv.org/abs/2103.16169)
[Computing](https://link.springer.com/journal/607)
[Noisy intermediate-scale quantum era](https://en.wikipedia.org/wiki/Noisy_intermediate-scale_quantum_era)
[Variational quantum eigensolver](https://en.wikipedia.org/wiki/Variational_quantum_eigensolver)
[A brief overview of VQE](https://pennylane.ai/qml/demos/tutorial_vqe/)
[What is Profile Diagram in UML?](https://www.visual-paradigm.com/guide/uml-unified-modeling-language/what-is-profile-diagram/#:~:text=Etc-,Applying%20Stereotype%20of%20a%20Profile,keyword%20%3E).

### 04/10/2024

I’m worried about how much time I will have to complete all objectives listed in the early deliverable. I should not do the polling and prioritise cresting multiple UML diagrams.
Links:
[Improving information system design: Using UML and axiomatic design](https://www.sciencedirect.com/science/article/abs/pii/S0166361521001767)

### 05/10/2024

I finished the early deliverable and submitted it.

### 09/10/2024

Resumed face-to-face meetings with Carlos and his peers. This was very helpful; I spoke with Chris and Lee, establishing a core question: what is an Eigensolver? We talked to Carlos, who advised that it would be a way of finding all the eigenvalues (energy states) in a Hamiltonian.

I spoke with Jorge about when to determine if a Qiskit object is classical or quantum. He confirmed that my assumption was correct and that there would be some sort of translation process from the quantum object to a classical one for it to receive the classical information. Jorge also explained how increasing a circuit by the number of qubits increases the complexity in polynomial time, whereas increasing the Hamiltonian by adding more terms increases the complexity exponentially.

Carlos also reassured me that focusing on VQE and the two SD adaptations would be enough for the project. I mentioned that one of the objectives of the early deliverable was to create multiple diagrams and model fundamental quantum concepts. There won’t be enough time to do that effectively. It means there should be much to discuss for future work and when reflecting on the project.

Qiskit club meeting notes:

Questions:
*   Qiskit documentation confirming when the quantum hardware is accessed 
*   UML for quantum hardware and fundamental quantum properties
*   What is an eigensolver? (finding the eigenvalues of a system) eigensolver can be quantum and classical 
- Matlab
- Lanczos algorithm
- Quantum alternative to factoring, easy to verify, difficult to know, bqb complete
Sparse matrix - shallow circuit - depth (qubit count) breadth (circuit chain, has lack of coherency)

### 11/10/2024

I have moved on to translating the VQE SD to the quantum UML profile format. I have re-read the paper and have found it quite challenging to understand. I read the UML book on class diagrams because I thought it would help me understand the UML profile diagram.

UML profiles are lightweight extensions of UML, which is referred to as a meta-model. A class diagram shows how the UML diagrams are constructed, including stereotypes generated for the UML profile. The UML profile can be seen as a package applied to the diagram.

Links:

[UML Profile Diagram](https://www.youtube.com/watch?v=YS0jwXst5sg)
[What is a UML profile diagram and when is it used? [duplicate]](https://stackoverflow.com/questions/60267501/what-is-a-uml-profile-diagram-and-when-is-it-used)
[Profile Diagram - Unified Modeling Language(UML)](https://www.geeksforgeeks.org/profile-diagram-unified-modeling-languageuml/)
[Profile (UML)](https://en.wikipedia.org/wiki/Profile_(UML))
[What is Profile Diagram in UML?](https://www.visual-paradigm.com/guide/uml-unified-modeling-language/what-is-profile-diagram/)
[Creating a profile diagram](https://support.ptc.com/help/modeler/r9.3/en/index.html#page/Integrity_Modeler/rtsme/creating_a_profile_diagram.html)
[Profile Diagram](https://docs.staruml.io/working-with-uml-diagrams/profile-diagram)
[A Comprehensive Guide to PlantUML Activity Diagrams: Everything You Need to Know](https://www.webdevtutor.net/blog/comprehensive-guide-plantuml-activity-diagrams)

### 12/10/2024

Quantum UML profile paper refers to Carlos's first paper as a domain-specific language:
[Domain-Specific Languages Guide](https://martinfowler.com/dsl.html#:~:text=A%20Domain%2DSpecific%20Language%20)

"A Domain-Specific Language (DSL) is a computer language that's targeted to a particular kind of problem, rather than a general purpose language that's aimed at any kind of software problem. Domain-specific languages have been talked about, and used for almost as long as computing has been done."

During this project, I thought there was an issue with the fact that some software developers don’t even use UML and that the extent of their use of it would have just been during education. It made me think there should be some consideration for having a quantum UML adaptation, which can also be used more informally. I have come to realise that this possibly doesn’t matter; even if people don’t use UML, they will choose how they want to depict their informal diagrams, whether through colour, shape or text. The important thing is to consider how UML can be adapted effectively for quantum, as UML is the standard modelling language for system design.

I have had a crack at the UML Profile diagram. Having a clear explanation of the different stereotypes will be crucial. I will create a separate Word doc to define these stereotypes. I don’t think constructing the diagram afterwards would be too difficult. I think it will be good to start on the dissertation and start writing about the VQE algorithm first. Getting a clear understanding of this and referring to the meeting notes where we discussed eigensolvers will be beneficial in clearly understanding how each type of diagram should depict it.

Links:  

A Two-tiered Methodology to Extend the UML Metamodel
[Modelling Quantum Circuits with UML](https://arxiv.org/abs/2103.16169)
[24765-2017 - ISO/IEC/IEEE International Standard - Systems and software engineering--Vocabulary](https://ieeexplore.ieee.org/document/8016712)
[A Proposal for a Formal Definition of the Design Concept](https://link.springer.com/chapter/10.1007/978-3-540-92966-6_6)
[Design Patterns — Ten Years Later](https://link.springer.com/chapter/10.1007/978-3-642-59412-0_39)
[Towards model-driven quantum software engineering](https://scholar.google.co.uk/citations?view_op=view_citation&hl=sv&user=inoqxM8AAAAJ&citation_for_view=inoqxM8AAAAJ:Zph67rFs4hoC)
[Toward a standardized methodology for constructing quantum computing use cases](https://arxiv.org/abs/2006.05846v1)

### 13/10/2024

I wrote a Word document to understand the different stereotypes. I will then go through the VQE algorithm written in Qiskit to identify which stereotype should be applied to each element to construct the UML profile SD diagram. The dissertation should distinguish between the VQE algorithm and, when discussing methodologies, discuss Qiskit and Qiskit’s implementation of the VQE algorithm.

### 14/10/2024

I’ve tidied up the logbook, included the early deliverable in my overleaf dissertation draft, and updated the bibliography.

### 15/10/2024

I briefly reviewed the Lanczos algorithm, which finds the minimum and maximum eigenvalues and eigenvectors in hermitian matrices. 

Whilst watching the video, I used Chat GPT and google to clarify terms that came up:
  
**Eigenvector and Eigenvalue**
Eigenvector: A vector that stays in the same direction after a transformation.  
Eigenvalue: The factor by which the eigenvector is scaled during the transformation.  
  
**Why Matrices Have Eigenvalues and Eigenvectors**
They show how the matrix (transformation) stretches or compresses along specific directions (eigenvectors).  
  
**Orthogonal vs. Orthonormal**
Orthogonal: Vectors are perpendicular (90 degrees to each other).  
Orthonormal: Vectors are perpendicular and have a magnitude of 1.  
  
**Orthogonal Matrix**
It contains vectors that are both orthogonal and normalised (orthonormal).  
Its rows and columns are perpendicular and have a length of 1.  
  
**Hermitian Matrix**
A complex version of a symmetric matrix where A = A dagger (equal to its conjugate transpose).  
Every symmetric matrix with real entries is also Hermitian.  
  
**Transpose of a Matrix**
Switches rows and columns. A^T  flips the matrix over its diagonal.  
  
**Conjugate Transpose** 
Transpose the matrix and take the complex conjugate of each element.  
  
**Lanczos Algorithm**
An iterative method for finding a Hermitian matrix's smallest and largest eigenvalues/eigenvectors.  
It is efficient for large matrices as it reduces the matrix to a simpler tridiagonal form.

Links:
[Lanczos algorithm](https://en.wikipedia.org/wiki/Lanczos_algorithm)
[Hermitian matrix](https://en.wikipedia.org/wiki/Hermitian_matrix)
[The Lanczos Algorithm, Part 1/2](https://www.youtube.com/watch?v=0t7WJybTmFg)

### 16/10/2024

Qiskit Club 2nd Meeting Notes:

- Rendevous Games - find each other in a search space without communicating
- Artemis Moon Landing
- What is a wave function? A wave function describes a particle's quantum state, providing information about the probability of finding the particle in a particular position or state when measured.
- What is Born's rule? Born's rule states that the probability of finding a particle is the square of the wave function’s absolute value.
- What is Bayes rule? Bayes' rule calculates the probability of an event based on prior knowledge of conditions related to the event. It updates the probability as more evidence becomes available.

The topic discussed was Random Number Generation using QC.

*   Evolutionary algorithms (work done by Jorge). Fitness function = variation of the randomness
    
*   Fundamental entropy (ignorance) - non-randomness
    
*   Qubit to represent a bit, 8 bits for 256 number values (0 to 255)
    
*   Hadimard gates and CNOTS to randomise
    
*   Evolutionary algorithm to find the sequence of gates to pass randomness test (RNG test, ball/bull test?)
    
*   Different tests for different randomness
    
*   How do we prove randomness? Is this even possible?
    
*   Examples of binary sequences given with no information on how they were produced:
    
    *   101101011
        
    *   111111111
        
    *   Which one is more random? If we keep getting 1’s in our 1111 sequence, the probability of it not being random increases and the probability of getting 0 increases exponentially (probability of 1 * probability of 1 *, etc.)
        
*   RNG would have health tests that would not allow sequences such as 1111 or 0000
    
*   Kolmogorov complexity - shortest program complexity to output a sequence
    
    *   Complexity/Randomness/irreducible
        
    *   Programmes to write the sequence examples
        
        *   111111111 (print 1, repeat) less complex
            
        *   101101011(write a strong, print 1, print 0, print 1 etc.) more complex

### 18/10/2024

I started working on a Word document, “Defining VQE Qiskit Objects”, so I can label each element of the UML VQE diagram with its stereotype, if it has one, and write down a general explanation of each object's datatype. Once I can establish this for all elements in the VQE Qiskit algorithm, it will be easy enough to construct it as the UML diagram, and I can move on to writing the dissertation. It should also help clarify if I have done the QUML VQE SD correctly.

One thing to note is that Scipy imported the minimise function, and it takes the cost function as an argument. I’ve made it a quantum object in QUML VQE as it contains a quantum object, but I need to nail down whether or not this is the case.

Links:

[IBM](https://www.ibm.com/quantum)
[Upcoming sunset of backend.run](https://docs.quantum.ibm.com/announcements/product-updates/2024-9-20-backend-run)
[sparse_pauli_op.py](https://github.com/Qiskit/qiskit/blob/main/qiskit/quantum_info/operators/symplectic/sparse_pauli_op.py)
[PauliList](https://qiskit-community.github.io/qiskit-qec/stubs/qiskit_qec.operators.PauliList.html)
[pauli_list.py](https://github.com/Qiskit/qiskit/blob/main/qiskit/quantum_info/operators/symplectic/pauli_list.py)
[efficient_su2.py](https://github.com/Qiskit/qiskit/blob/main/qiskit/circuit/library/n_local/efficient_su2.py)
[Qiskit Runtime](https://docs.quantum.ibm.com/api/qiskit-ibm-runtime/runtime_service)
[Github Qiskit](https://github.com/Qiskit/qiskit/tree/main)
[QiskitRuntimeService](https://docs.quantum.ibm.com/api/qiskit-ibm-runtime/qiskit_ibm_runtime.QiskitRuntimeService)
[qiskit_runtime_service.py](https://github.com/Qiskit/qiskit-ibm-runtime/blob/main/qiskit_ibm_runtime/qiskit_runtime_service.py)
[IBMBackend](https://docs.quantum.ibm.com/api/qiskit-ibm-runtime/qiskit_ibm_runtime.IBMBackend)
[Target](https://docs.quantum.ibm.com/api/qiskit/qiskit.transpiler.Target)
[target.py](https://github.com/Qiskit/qiskit/blob/main/qiskit/transpiler/target.py)

### 19/10/2024

Continued with “Defining VQE Qiskit Objects”. I was unsure if the pass manager should be assigned the stereotype <<Quantum Driver>> as it involves some communication with the classical ansatz circuit to be backend compatible with a quantum computer; however, the information held is classical, and the transformations made remain classical, there is currently no interaction with quantum hardware, so I have decided that this remains a classical element. A note from the “The five Quantum UML Stereotypes” document:

The <<Quantum Driver>> lifeline is responsible for creating an instance of a <<Quantum Request>> object.
When communication is made to quantum hardware, this stereotype will be applicable.

Links:
[StagedPassManager](https://docs.quantum.ibm.com/api/qiskit/qiskit.transpiler.StagedPassManager)
[passmanager.py](https://github.com/Qiskit/qiskit/blob/main/qiskit/transpiler/passmanager.py)
[Transpile with pass managers](https://docs.quantum.ibm.com/guides/transpile-with-pass-managers)
[Transforming Quantum Circuits using Qiskit's Transpiler with Matthew Treinish: Qiskit Summer School](https://www.youtube.com/watch?v=MvX5OUK-tbE)
[Quantum processing units](https://quantum.ibm.com/services/resources)

### 21/10/2024

Continued with “Defining VQE Qiskit Objects”. I have changed the backend from classical to <<Quantum Driver>>. Although information regarding quantum hardware is stored classically, I did not consider the broader scope of what this object does. It will facilitate communication between the classical and quantum software when executed using the cost_func method.

Links:
[EstimatorV2](https://docs.quantum.ibm.com/api/qiskit-ibm-runtime/qiskit_ibm_runtime.EstimatorV2)
[estimator.py](https://github.com/Qiskit/qiskit-ibm-runtime/blob/stable/0.31/qiskit_ibm_runtime/estimator.py#L137-L160)
[RuntimeJobV2](https://docs.quantum.ibm.com/api/qiskit-ibm-runtime/qiskit_ibm_runtime.RuntimeJobV2#runtimejobv2)
[estimator.py](https://github.com/Qiskit/qiskit-ibm-runtime/blob/stable/0.31/qiskit_ibm_runtime/estimator.py#L46-L197)
[Session](https://docs.quantum.ibm.com/api/qiskit-ibm-runtime/qiskit_ibm_runtime.Session)
[session.py](https://github.com/Qiskit/qiskit-ibm-runtime/blob/stable/0.31/qiskit_ibm_runtime/session.py#L47-L399)
[Qiskit Runtime](https://docs.quantum.ibm.com/api/qiskit-ibm-runtime/runtime_service)
[minimize](https://docs.scipy.org/doc/scipy/reference/generated/scipy.optimize.minimize.html)

Completed all elements in “Defining VQE Qiskit Objects” and updated the VQE Quantum UML Profile Plantuml file. I will still need to review the messages to confirm they’ve all been assigned the correct stereotypes.

I’m unsure if I have defined cost_func correctly and have changed it from <<Quantum Driver>> to <<Quantum Request>>. I’ll continue with the messages for now and maybe come back to it in the future, but I think I can also create the diagrams and either move on with making class diagrams or start to write up the dissertation.

### 22/10/2024

I continued with “Defining VQE Qiskit Objects” to define the message types. I need to make a note regarding primitives and backend, which are two types: estimator and something else. I think this is relevant to discuss in the dissertation.

I’ve been using Notebook LM to bounce ideas off during this process. I’ve been able to upload the research papers, my document about quantum stereotypes and website links to the Qiskit documentation I’ve been looking into.  It’s not foolproof; it has given me incorrect information if I convince it, but it’s helpful as a sounding board.

Notes from Notebook LM:

You are correct in stating that access to the quantum hardware occurs when a primitive, like the Estimator, is executed via the .run() method.

Primitive Execution: The execution of a primitive triggers the submission of a job to the quantum backend.

Job Allocation: Both the backend and the session object play a role in managing the job allocation to the quantum hardware. The session helps prioritise jobs submitted within its context, while the backend manages the overall job queue and execution.

I have determined for now only to include <<Quantum Request>> and not <<Quantum Reply>> in my sequence diagram. This would probably be helpful to discuss as a Qiskit club. I have abstracted away from some of the requests/replies in the diagram (for example, one instance making a request to the other and the other replying with the information it obtains, just keeping it to the request).  In the shots loop, 10,000 iterations of the circuit are run, and a quantum reply is not received for all of them. Only the result will be obtained, which will be transformed into classical information when received; therefore, I have left the depiction as a classical reply.

I will keep it as I’ve done it, complete my UML Quantum Profile diagram, have it as the LucidChart version, and move on to transforming them into class diagrams of both quantum styles. My goal is to get this done before the end of the month, which will allow me to focus purely on the dissertation throughout November.

I adjusted the text's formatting, which made me think I needed to do this to the QUML version for consistency. 

I have now completed the VQE sequence diagrams for both UML versions. I will now move on to creating class diagrams.

Links:
[EfficientSU2](https://docs.quantum.ibm.com/api/qiskit/qiskit.circuit.library.EfficientSU2)
[EstimatorV2](https://docs.quantum.ibm.com/api/qiskit-ibm-runtime/qiskit_ibm_runtime.EstimatorV2)
[Introduction to Qiskit Runtime execution modes](https://docs.quantum.ibm.com/guides/execution-modes)
[Variational Quantum Eigensolver](https://learning.quantum.ibm.com/tutorial/variational-quantum-eigensolver)
[Introduction to Qiskit Runtime sessions](https://docs.quantum.ibm.com/guides/sessions)
[Session](https://docs.quantum.ibm.com/api/qiskit-ibm-runtime/qiskit_ibm_runtime.Session)

### 23/10/2024

Qiskit Club. Watched a talk from Joseph about his defence, discussing blockchains and quantum advantage.
Notes:
- Hash function, shah 256
- Super conducting quantum device vs other devices
- Grover = quadratic advantage. Shor = exponential advantage.

### 25/10/2024

Started on the Class Diagram, lots of links for today as having to clarify information for attributes and operations. Have finished the day at the CostFunction method, need to think of a way to represent the cost_history_dictionary attribute as it has several data types, I believe will need to just detail this as attributes in its own element on the diagram and then reference that in the CostFunction element. Link to refer to regarding this: [how to draw class diagram that shows a call to a static method of another class](https://stackoverflow.com/questions/13973119/how-to-draw-class-diagram-that-shows-a-call-to-a-static-method-of-another-class) & [attribute having multiple types in class diagram](https://stackoverflow.com/questions/52641841/attribute-having-multiple-types-in-class-diagram)

Information from ChatGPT:

To model a union of two different data types in PlantUML, you can define an abstract class for the general type and then create two concrete subclasses for the specific types. You would then indicate that the attribute in your main class uses the abstract class as its type. Here's how you can do this:

```
@startuml
abstract class CostHistory {
    +calculate(): float
}

class IterationCount {
    +value: int
}

class EnergyHistory {
    +values: List<float>
}

CostHistory <|-- IterationCount
CostHistory <|-- EnergyHistory

class SomeClass {
    +history: CostHistory
}
@enduml
```
Explanation:
- CostHistory: This is the abstract class representing the general data type.
- IterationCount: This subclass represents an integer type for the iteration count.
- EnergyHistory: This subclass represents a list of floats for energy values.
- SomeClass: This class uses CostHistory as the type for its history attribute.

Notes:
- Generalization Set: In UML, generalization indicates that subclasses inherit from a superclass, which aligns with the concept of union in type modeling.
- Disjoint and Complete: You can add notes or constraints to clarify that these subclasses are disjoint (no overlap) and complete (cover all possibilities).
- Abstract Type: The abstract class cannot be instantiated, which emphasizes that the attribute must be one of the subclasses.

This representation clearly conveys the structure to a reader and can be used to inform implementation in languages that support such constructs, like C++ or XSD.

For more on UML diagrams and PlantUML, you can check the official PlantUML documentation or UML specifications from the Object Management Group (OMG).

Links:

[SparsePauliOp](https://docs.quantum.ibm.com/api/qiskit/qiskit.quantum_info.SparsePauliOp)
[EfficientSU2](https://docs.quantum.ibm.com/api/qiskit/qiskit.circuit.library.EfficientSU2)
[TwoLocal](https://docs.quantum.ibm.com/api/qiskit/qiskit.circuit.library.TwoLocal)
[NLocal](https://docs.quantum.ibm.com/api/qiskit/qiskit.circuit.library.NLocal)
[What is a 'NoneType' object?](https://stackoverflow.com/questions/21095654/what-is-a-nonetype-object)
[UML Class Diagrams Reference](https://www.uml-diagrams.org/class-reference.html#:~:text=A%20primitive%20type%20is%20a,UML%2C%20for%20example%2C%20mathematically).
[Decompose](https://docs.quantum.ibm.com/api/qiskit/0.32/qiskit.transpiler.passes.Decompose)
[Circuit Library](https://docs.quantum.ibm.com/api/qiskit/circuit_library)
[UML Design class diagram: Class with another class as attribute?](https://stackoverflow.com/questions/27205917/uml-design-class-diagram-class-with-another-class-as-attribute)
[UML Best Practice: Attribute or Association](https://bellekens.com/2011/08/10/uml-best-practice-attribute-or-association/)
[Class Diagram](https://plantuml.com/class-diagram)
[Object Diagram](https://plantuml.com/object-diagram)
[Syntax Error: Object name with space characters](https://forum.plantuml.net/12676/syntax-error-object-name-with-space-characters?utm_content=cmp-true)
[What is Object Diagram?](https://www.visual-paradigm.com/guide/uml-unified-modeling-language/what-is-object-diagram/)
[EfficientSU2](https://docs.quantum.ibm.com/api/qiskit/qiskit.circuit.library.EfficientSU2)
[QiskitRuntimeService](https://docs.quantum.ibm.com/api/qiskit-ibm-runtime/qiskit_ibm_runtime.QiskitRuntimeService)
[IBMBackend](https://docs.quantum.ibm.com/api/qiskit-ibm-runtime/qiskit_ibm_runtime.IBMBackend)
[target.py](https://github.com/Qiskit/qiskit/blob/stable/1.2/qiskit/transpiler/target.py#L141-L1444)
[StagedPassManager](https://docs.quantum.ibm.com/api/qiskit/qiskit.transpiler.StagedPassManager)
[Preset Passmanagers](https://docs.quantum.ibm.com/api/qiskit/transpiler_preset)
[Built-in Functions: Int](https://docs.python.org/3/library/functions.html#int)
[SparsePauliOp](https://docs.quantum.ibm.com/api/qiskit/qiskit.quantum_info.SparsePauliOp)
[Built-in Functions: Complex](https://docs.python.org/3/library/functions.html#complex)
[PauliList](https://docs.quantum.ibm.com/api/qiskit/0.35/qiskit.quantum_info.PauliList)
[NLocal](https://docs.quantum.ibm.com/api/qiskit/qiskit.circuit.library.NLocal)
[n_local.py](https://github.com/Qiskit/qiskit/blob/stable/1.2/qiskit/circuit/library/n_local/n_local.py#L41-L1005)
[Decompose](https://docs.quantum.ibm.com/api/qiskit/qiskit.transpiler.passes.Decompose)
[DAGCircuit](https://docs.quantum.ibm.com/api/qiskit/qiskit.dagcircuit.DAGCircuit)
[QuantumCircuit.decompose() should take which gate(s) to decompose](https://github.com/Qiskit/qiskit/issues/2906)
[Class Diagram](https://plantuml.com/class-diagram)
[SparsePauliOp](https://docs.quantum.ibm.com/api/qiskit/qiskit.quantum_info.SparsePauliOp)

### 28/10/2024

Continued with class diagram, realised I had missed that the ansatz needs to pass the number of params in the creation of x0 when creating SD, helpful to do both a static and dynamic diagram when understanding full scope of the algorithm.

**I’m making a design choice to use specific classes in the tutorial such as EfficentSU2 as opposed to general QuantumCircuits, need to think about this when discussing the diagrams in the dissertation.
Do I mark down the ansatz as Quantum Circuit, _CircuitsT or EfficentSU2? I’m going to make the decision to use EfficentSU2 as we’re speaking strictly about this tutorial, but it’s a design choice to consider.**

Just remember:

![](https://lh7-rt.googleusercontent.com/docsz/AD_4nXcU6iFDUzqyqcEkvhhVr4qpXqOad466ukkRhFhzPoBQhN3VrbbcWsxAl8NVNDXfHyzhyqTo9qbM_MU2mPGoBkJhJp0wXMhwbo194YkE7R8u3ZO4yBmmWhw8BsWyKzuuN1VS9gD2zdhaoVKXwUsopLA7k3VZ?key=MtrDKbB_sX2MmzFn_dLBrg)

decompose was originally QuantumCircuit

![](https://lh7-rt.googleusercontent.com/docsz/AD_4nXe8FVKTwdAlW86yUIr4xfgz9qUV7R-QlUgEMiyPv5P9yMsxUpM8aPLMykgrgU89Tsxe9xYqsNoArnp9ERiYkdPSN3-OKz7lf8q-SnRm-OPrTck032LlQ4V5uUBBjtZLXNaiadQ3y3BqG2vwkg4GMhdpoQE?key=MtrDKbB_sX2MmzFn_dLBrg)

run circuits: was originally circuits: _CircuitT

I’ve finished the Class diagram in Plant UML, it looks quite messy in all honestly and not as satisfying as when creating the Sequence Diagram. I think I still need to make some revisions in particular to go over muplicities, public/private/protected and make and changes to include notes and improve illegibility. I will do this however when going over it in LucidChart.
I’ve set up a repo on GitHub for the project so all the work will automatically update there. I will move my logbook on to there also and have it set up as a Readme file. 

Links:

[EfficientSU](https://docs.quantum.ibm.com/api/qiskit/qiskit.circuit.library.EfficientSU2)
[numpy.ndarray](https://numpy.org/devdocs/reference/generated/numpy.ndarray.html)
[PrimitiveResult](https://docs.quantum.ibm.com/api/qiskit/qiskit.primitives.PrimitiveResult)
[EstimatorV2](https://docs.quantum.ibm.com/api/qiskit-ibm-runtime/qiskit_ibm_runtime.EstimatorV2)
[RuntimeJobV2](https://docs.quantum.ibm.com/api/qiskit-ibm-runtime/qiskit_ibm_runtime.RuntimeJobV2)
[numpy.random.rand](https://numpy.org/doc/2.0/reference/random/generated/numpy.random.rand.html)
[numpy.random.random](https://numpy.org/doc/2.0/reference/random/generated/numpy.random.random.html)
[Session](https://docs.quantum.ibm.com/api/qiskit-ibm-runtime/qiskit_ibm_runtime.Session)
[EstimatorOptions](https://docs.quantum.ibm.com/api/qiskit-ibm-runtime/qiskit_ibm_runtime.options.EstimatorOptions)
[QiskitRuntimeService](https://docs.quantum.ibm.com/api/qiskit-ibm-runtime/qiskit_ibm_runtime.QiskitRuntimeService)
[Backend](https://docs.quantum.ibm.com/api/qiskit/qiskit.providers.Backend)
[minimize](https://docs.scipy.org/doc/scipy/reference/generated/scipy.optimize.minimize.html)
[OptimizeResult](https://docs.scipy.org/doc/scipy/reference/generated/scipy.optimize.OptimizeResult.html)
[matplotlib.pyplot.subplots](https://matplotlib.org/stable/api/_as_gen/matplotlib.pyplot.subplots.html)
[matplotlib.figure](https://matplotlib.org/stable/api/figure_api.html)
[matplotlib.axes](https://matplotlib.org/stable/api/axes_api.html)
[matplotlib.pyplot.plot](https://matplotlib.org/stable/api/_as_gen/matplotlib.pyplot.plot.html)

### 29/10/2024

While using Lucid Chart, I discovered a diagram as a code feature that allows you to write in Mermaid. This may have been the best avenue to explore; Plant UML was suitable for sequence diagrams but looks incredibly messy for a class diagram.

The Dict object depends on cost_function; it can't exist outside of it as that's where it's created. Or either aggregation/composition. I need to go through the book to confirm. This may also need to be the case when considering the cost_func relationship to minimize. 

I finished translating the diagram to Lucidchart, but it's still messy. Rupert suggested splitting the diagram; both cost function and minimize take other classes as parameters; it may be better to have cost_function as a separate diagram, which is appended to the main one with minimize. Also, I believe I might need to make QiskitRuntimeWService an abstract class, as it invokes a Backend object (which can't be called directly) and a target object; I've amalgamated these two into the QiskitRuntimeService. Still, it's perhaps lacking in accuracy (I have recorded target as an attribute of QiskitRuntimeService, which isn't necessarily true).

I'm reviewing the UML book and the Class Diagram chapter to make adjustments as I go to the diagram. I've included multiplicities of the attributes so far and tested whether the args for minimise need to be ordered (they do). I confirmed that all parameter prepends can remain default to in; no out parameters exist.

I will continue tomorrow with visibility markers. 

### 30/10/2024

While partway through the visibility markers, I came to a point where I needed to clarify how to depict QiskitRuntimeService. This is used as the main object when interacting with an IBMBackend object, which it creates; the IBMBackend object is what interacts with the quantum hardware. QiskitRuntimeService manages logging in to an IBM cloud account and other matters; it is not an abstract class, as I had thought it might need to be. It is a  wrapper class. The IBMBackend object contains the attribute "target" required to generate the pass manager. I have created an IBMBackend object in the class diagram with a target attribute and showed it as a dependency on QiskitRuntimeService.

I was unsure if this also needed to be included in the sequence diagram, but I've decided it doesn't. An instance of IBMBackend is never created; it is interacted with through QiskitRuntimeService. I've shown that QiskitRunTime uses the target attribute by passing constraints to the pass manager.

I'm going to return to visibility after I've spoken to a friend about it. I believe most everything in Python is public, but I may need to consider how things should be depicted in the UML diagram. For example, the least_busy() method for QiskitRuntimeService should only be accessed in this class in the context of this diagram, so should it be shown as private? Or should I omit visibility, as Python and Qiskit should be public attributes and methods?

I can put a pin in this for now. I think the most pressing matter is making the diagrams more legible and whether I need to split them up and combine them.

I spoke to a friend; Python is inherently public anyway. I had given the example of whether least_busy should be considered private in the context of it only being used with QiskitRuntimeService, but this isn't the correct understanding. It could be calling separate private methods to execute the operation, but least_busy remains public. It may be best to remove visibility, as the attributes and methods are all visible.

Discussed _CircuitsT and me using EfficentSU2 instead as datatype, which is the correct design choice as we're not worrying about all circuits, just efficentsu2 in the case of this algorithm

He was concerned that this appeared to have some data flow aspects. I need to revisit how I've written the reading directions. I've considered them more as data flows when they are not. 

I've now revised the diagram to adjust the reading directions, as I'd been considering them as data flows instead. I've also separated minimize so it looks clearer. So today, I've covered visibility, reading directions, and made visual adjustments. I will continue reviewing the book and making adjustments. I will try to get this done in the next couple of days, and then I just need to create a Carlos version; diagrams will be done, and I will move on to the dissertation!

I've managed to assign the multiplicities of the attributes correctly. I've gone over the reading direction and association names again, so this has been changed to include general reading direction information, the multiplicities with the attributes where necessary, and anything where one element is passed to another. I've left notation as it should be clear. I am now happy with the diagrams, i feel like I could keep going over the book and over them but concious of time and think it will be best to move on and anything missed can be discussed in the disseration. I will focus the rest of the week on their compliance with the Quantum UML profile and QUML format. I aim to finish this by the end of this week so I can start the dissertation next week.

Links:

[Visualize Circuits](https://docs.quantum.ibm.com/guides/visualize-circuits)
[Runtime Service](https://docs.quantum.ibm.com/api/qiskit-ibm-runtime/runtime_service)
[UML Dependency](https://www.javatpoint.com/uml-dependency)
[Class diagram multiple classes uses same class](https://stackoverflow.com/questions/40782470/class-diagram-multiple-classes-uses-same-class)
[Splitting up a UML Class Diagram](https://stackoverflow.com/questions/35398607/splitting-up-a-uml-class-diagram)
[Should I use public attributes or public properties in python](https://stackoverflow.com/questions/4555932/should-i-use-public-attributes-or-public-properties-in-python)
[Python private method for public usage](https://stackoverflow.com/questions/47260380/python-private-method-for-public-usage)
[Diagrams dependency relationships](https://www.ibm.com/docs/en/dmrt/9.5?topic=diagrams-dependency-relationships)
[UML Dependency](https://www.javatpoint.com/uml-dependency)
[Diagrams association relationships](https://www.ibm.com/docs/en/dmrt/9.5?topic=diagrams-association-relationships)
[UML aggregation vs composition](https://www.visual-paradigm.com/guide/uml-unified-modeling-language/uml-aggregation-vs-composition/)

### 31/10/2024

I'm cross-referencing the VQE CD with the quantum UML profile paper. The class stereotypes should remain consistent with the SD, as classes are the same as elements in an SD. I'm trying to establish which operations would be considered `<<quantum request>>`. Confident with the estimator.run() being a quantum request. Decided that it is also apt for cost_func and minimize. Going by the diagram in the paper:

**![](https://lh7-rt.googleusercontent.com/docsz/AD_4nXe_boqqCTFhv2Ke3J9CF0uokgcE97HOo0SWnotkRKv80maPfMyxiZFLiqVbzgBBSKXjAZP8dC2n9AGe6WMambHS0uQVcAJd5RlNiz3HYvOCmKCUbd2i9K8J1gQXhsUyxXOrQq03FekHeHwpXCMwhlxIUb0?key=motv2d2Rg4YZJ0mtbUZwtg52)**

I think it's correct, as both methods call the quantum request algorithm.

Also, considering whether or not the diagram should be split into packages, I think I can omit this for now as I'm essentially going through a classical-quantum logic package (referring again to the example diagram in the paper)

I think it's safe to move on to making a copy for the QUML format now. Once that's done, I can spend the rest of the week comparing diagrams to the book chapter, seeing if I can make any additional adjustments before finalising the diagram.

Working on the QUML diagram, the paper notes that anything that contains quantum functionality should be considered quantum. You also need to mention this for attributes and operations and their datatypes. For example, with the estimator object, I have stated that the RuntimeJobV2 is quantum. Even though it is classical, it manages communication with quantum hardware, so I should mark it as a quantum data type. 

Another question: Should I mark the parameters for cost_func and minimise as aggregated relationships and not communication? Does it become part of it?

I am also wondering about creating packages for the quantum driver section, the minimise section and the remainder. 

Determined a target object (attribute of IBMBackend) will remain classical as it does not interact with quantum hardware. At a point of contention with QRS(QiskitRuntimeService) as it has two operations which return IBMBackend as a datatype; however, the operations themselves don't inherently need to access quantum hardware—determined to have the datatype as bold and the operation as not bold to distinguish classical/quantum. 

Primitive Result object: The backend(QRS) will manage communication with quantum hardware; the PR object contains info from quantum operation classically; it would be the backend that communicates this info to it via a classical channel. Therefore, PR is a classical data type.

## Topics to Research

- Mermaid
- NQCC
- Qiskit
- Blockchain
- UML - differentiate string and integer?
- Q-Cosmic
- Quantum State Preparation
- Quantum Measurement
- Grover’s Algorithm
- Shor’s Algorithm
- Quantum Probabilities (Probability Amplitude)
- Euler’s Formula
- Quantum Polarising Filters
- Systemisation of Knowledge (SoK) papers
- The New Scientist
- Quantum Computing for Computer Scientists
- Quantum Computation and Quantum Information
- DBLP
- PUML
- Miro
- Microsoft Quantum
- Cirq
- VQE
- QAOA
- VQF

## To-Do List

- I need to confirm whether the dissertation and corpus are one unified document or separate documents. To better understand the process of writing a good dissertation, it would be useful to obtain books on scientific or academic writing.
  
- Define specific research questions with Carlos. 

## Evaluation

- How I approached this piece of work:
- What I found easy
- What I found difficult
- If I were to do it again, I would do the following differently
- What I learned is
- I would like specific feedback on

           
