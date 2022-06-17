# Key-Terms to keep in mind

- ## **<span style='color:#4682B4'>Markdown</span>**

Markdown is a lightweight markup language for creating formatted text using a plain-text editor.
To have more details on the way of coding, see the page [MapremièrepageMarkdown](https://github.com/elebail202/Markdown/blob/13e5c12f73a4aa0eec7db93008f602c7a65848f8/Mapremi%C3%A8repageMarkdown.md).


- ## **<span style='color:#4682B4'>CSS</span>**

Cascading Style Sheets (CSS) is a style sheet language used for describing the presentation of a document written in a markup language such as HTML. CSS is designed to enable the separation of presentation and content, including layout, colors, and fonts.    

- ## **<span style='color:#4682B4'>HTML</span>**

The HyperText Markup Language or HTML is the standard markup language for documents designed to be displayed in a web browser. HTML elements are the building blocks of HTML pages. With HTML constructs, images and other objects such as interactive forms may be embedded into the rendered page. HTML provides a means to create structured documents by denoting structural semantics for text such as headings, paragraphs, lists, links, quotes and other items.

- ## **<span style='color:#4682B4'>Git</span>**

Git is software for tracking changes in any set of files, usually used for coordinating work among programmers collaboratively developing source code during software development.
To know more about the usuals git commands, visit [UsualCommandsOnGit](https://github.com/elebail202/Markdown/blob/af2347e475d9927883e73df69aa3d13f58ff37d8/UsualCommandsOnGit.md)

- ## **<span style='color:#4682B4'>Software requirements + requirements engineering + requirements elicitation</span>**

<div align="center"><span style='color:#00bfff'>WHAT IS SOFTWARE REQUIREMENTS ?</span></div>

The software requirements are `description of features and functionalities of the target system`. Requirements convey the expectations of users from the software product. The requirements can be obvious or hidden, known or unknown, expected or unexpected from client’s point of view.


<div align="center"><span style='color:#00bfff'>WHAT IS REQUIREMENTS ELICITATION ?</span></div>

Requirements elicitation is the practice of `researching and discovering the requirements of a system` from users, customers, and other stakeholders. Requirements elicitation practices include interviews, questionnaires, user observation, workshops, brainstorming, use cases, role playing and prototyping.
Requirements elicitation is a part of the requirements engineering process, usually followed by analysis and specification of the requirements.


<div align="center"><span style='color:#00bfff'>WHAT IS REQUIREMENTS ENGINEERING ?</span></div>

--- 

>“The idea of human-centered design is crucial – the real goal of an engineering process is to improve >human activities in some way, rather than to build some technological artifact.”

Requirements engineering applies to the development of **all software-intensive systems**, but **not** necessarily to the development of **all software**.

### <span style='color:#aaccff'>Basic Concepts</span>

Requirements Engineering provides a framework for **understanding the purpose of a system** and **the contexts** in which it will be used. It **bridges the gap** between **recognition of a problem** to which we can apply computer technology and the task of building a system that can **solve this problem**.
In seeking to describe the purpose of a computer system, we need to **look beyond the system itself**, and into the human activities that it will support (the **needs of the users**). Human activities may be complex and so requirements engineering techniques offer ways of dealing with complexity so that we can **understand problems** better (complex problems --> simpler ones).
We need to first consider what types of projects need requirements engineering.

### <span style='color:#aaccff'>Software-Intensive systems</span>

What does *Software-Intensive systems* means ? Much more than just software or software + hardware (= computer systems). These computer systems are useless unless when they are placed in some human context where they can support human activity. **Software-Intensive systems = computer system** (software + hardware) **+ human activity**.
Software is both **complex** and **adaptable**. Its design is frequently inseparable from the task of designing the human activities supported by that software. But a cycle of **continuous change** is inevitable (new computer technology changes human activities and people adapt themselves to these technologies).

### <span style='color:#aaccff'>Fitness for Purpose</span>

System badly designed if it is not suited to the purpose for which it was intended. We define **quality** in terms of **fitness-for-purpose**. Investigation of the **purpose** is necessary. Otherwise, we cannot assess its quality.

### <span style='color:#aaccff'>Complexity of Purpose</span>

Complex because it involves a high degree of interaction between people, software and hardware.
The design of Software-Intensive systems belong to a class of problems known as **wicked problems**. They have the following characteristics :
-	No definitive formulation of the problem (each one has his version)
-	There is no stopping rule (never solved entirely and lead to new insights)
-	Solutions are not right or wrong but better or worse
-	No objective test of how good a particular solution is
-	No pre-existing set of potential solutions and no well-described set of features of these solutions
-	Every wicked problems is essentially unique (because each is sufficiently complex)
-	Every wicked problem can be considered to be a symptom of another problem (hard to isolate the problem)
-	The designer has no “right” to be wrong 
Arriving to an **agreed statement of the problem** is a problem for wicked problems.

### <span style='color:#aaccff'>Dealing with complexity</span>

Requirements Engineering offers a number of techniques for dealing with complexity of purpose. Three general principles are very useful :
-	**Abstraction**, ignoring the details so that we can see the big picture.
-	**Decomposition**, breaking a set of phenomena into parts so that we can study them independently.
-	**Projection**, adopting a particular view/perspective and describing only the aspects that are relevant to that perspective.
These principles are used all the time and allow to better deal with complexity. The requirements engineering is done when the component’s purpose is known and its interface standardized. 
The idea of re-usable components brings us to a fourth principle for dealing with complexity : **modularity**. Modularity is concerned with finding structures that are stable over time and across different contexts. Produces robust design, allows us to handle evolution of the requirements over time.

### <span style='color:#aaccff'>Defining Requirements Engineering</span>

**_Requirements Engineering (RE)_**: set of activities concerned with identifying and communicating the purpose of a software-intensive system, and the contexts in which it will be used. Hence, RE acts as the bridge between the real-world needs of users, customers, and other constituencies affected by a software system, and the capabilities and opportunities afforded by software-intensive technologies.
Specifications on both words :
-	*Requirements* : it suggests that there is someone out there doing the ‘requiring’. It could be a list of features demanded by the customer/diverse set of people.
-	*Engineering* : it suggests that the RE is an engineering discipline in its own right.
If developers do not have an adequate understanding of the purpose they will find it hard to build a system that suits its purpose.

### <span style='color:#aaccff'>Importance of Requirements Engineering</span>

The major determining factor in each case is how well the organizations involved understand and manage their requirements and not just luck (good or bad).

### <span style='color:#aaccff'>The cost of fixing errors</span>

Most of the projects follow a **standard sequence** of phases : requirements analysis, design, coding, development testing, acceptance testing and operation. Errors made in a particular phase cost more to fix the longer they are left undetected. The relative cost of fixing errors do **not necessarily depend on the order** in which things are done **but the number of other decisions** that are based on it.

### <span style='color:#aaccff'>The causes of project failure</span>

In one initial study, 16% of projects were successful (= completed in time and within budget, with all features and functions as originally specified). Then, in a later one, 26% of the projects. Smaller projects are easier to manage and hence it is easier to control costs and schedule. The top three **success factors** are :
-	User involvement
-	Executive management support
-	Clear statement of requirements
The top three **factors leading to failure** were :
-	Lack of user input
-	Incomplete requirements and specifications
-	Changing requirements and specifications

### <span style='color:#aaccff'>Human-Centered Design</span>

**Study of human activities** is a crucial part of RE. The ultimate goal of all design processes is to change human activities to make them more effective, efficient, safe, enjoyable…

### <span style='color:#aaccff'>Soft Systems</span>

**In Soft Systems method**, one makes sense of a set of activities by treating them as a subject system, and then one creates a system for making interventions to improve the subject system, where evaluation of something as an ‘improvement’ is judged with respect to a particular worldview.
We will use soft systems ideas to **identify and characterize human activity systems**, so that we can study how to operate. We will ask how to design the human activities and the software to fit together.

### <span style='color:#aaccff'>Studying human activities</span>

Need to draw on **ideas from psychology and sociology** because we need to address both cognitive and social processes that underlie work activities.

### <span style='color:#aaccff'>What do Requirements Analysts do ?</span>

There is **no ‘one way’** to do RE. Many different possible processes for building software-intensive systems and RE has a role in each of them. However, there are a number of activities essential to RE that need to be addressed in one way or another in any RE process.
-	Which problem needs to be solved ?
-	Where is the problem ?
-	Whose problem is it ?
-	Why does it need solving ?
-	How might a software system help ?
-	When does it need solving ?
-	What might prevent us from solving it ?