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

25/07/2024

I spent the past few weeks working on the “layman's terms” document, which I completed tonight. This document thoroughly investigated the quantum aspects of the problem and used Gemini/documentation for the more general coding aspects later in the algorithm. 

Now that this document is completed, I am more confident in understanding what is happening in the code. I will now return to creating a diagram based on this algorithm. My process will start with a rough diagram and then implement UML standardisation. I will then adapt to Carlos’ quantum extension of UML and implement the quantum UML profile diagram. Possibly, right after Carlos’ diagram, I will start writing the dissertation as I can begin discussing aspects like the background before having both diagrams completed. 

I have struggled to balance dissertation and internship work. I lose my memory regarding topics for the dissertation and have to spend time familiarising myself with the domain when returning to this work, a two-step forward, one-step back situation.
