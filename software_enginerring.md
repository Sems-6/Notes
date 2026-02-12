## 10 marks
----------
### Software requirement specification characteristics of SRS
----------
- 1.correctness
- 2.completeness -> functionality performance design attributes
- 3.consistency
- 4.unambiguous
- 5.Ranking for stability
- 6.modifiability
- 7.verifiability->specified document verified
- 8.traceability->enhancement origin of each requirement is clear
- 9.design independence
- 10.testability
- 11.understandable by customs
- 12.right level of abstraction

### Cohesim and types
----------
degree of which elements of module are functionally dependent

- function
- sequence
- communication
- procedural
- temporal


####

- it consist of set of function code algorithm and logic to perform the task
- Data
    - Variable and data structure the module operate on
- Interface
    - it define method that interacting with other modules

----------
### Key characteristics of module

- Encapsulation
    - a module hides the implementation details exposing only necessary through well defined
    that is called Encapsulation
- Reusability
    - a module across multi project or system
- Independence
    - module can be design to minimize the dependencies on other modules making them
    easier to update
- High cohesion
    - Each module can focus on single task or closely related task
- Low coupling
    - Module should have minimal dependencies to reduce impact of changes in one module

#### Benefit of modularisation

- Improve maintainability easy to locate.
- easier to locate and fix the bug.
- enhance the reusability.
- module can be reused to scalability.
- new feature can be added by integrating without affecting the existing one.
- reduce complexity.
- breaking down the system into smaller part simplify the design.

### Data coupling
----------
- is based on the fact that the communicate by passing only data . Then module are set to be
    data couple
- Components are Independent
 - Eg - customer willing
- the complete data struct is passed from to another one
- it involve trapped data and it was made by designer

### control coupling
----------
- module can communicate by passing control communicate
- Ex:
    - short function that takes comparison function as an short argurment


### External coupling
----------
- the module depend on other coupling to a particular type of hardware
- Eg :
    - Protocol design for

### common coupling
----------
- such as global data structure the changes in global data tracking back to all modules
    which access the data to evaluate the affect of changes
- it reduce ability to control data access and reduce

###
----------
- one module can modify the data of another module are control is passed form one module to
    another module
- This is the worst form of coupling

### Sequential coupling
----------
- it occur when output of one module depend of another module
- this type of coupling can be diff to maintain and modify

### functionally coupling
----------
- functionally coupling occur when two module depend on each other functionality.
- tightly couped and diff to maintain

### Component coupling
----------
- interaction between the two classes where the class has variable of another class
- where is Component coupling there will be interaction coupling

### External design
----------
- conceiving planning and specification characteristics of model
- external design consent with refining the requirement and establishing high level of
    structure view
- it include user display
- format and external device

### architectural design
----------
- consist with conceptual design of the structure
- Identify internal processing function
- decomposing high level function
- establishing the relationship among the function , data stream and data store

### Detailed design
----------
- Include of specs of algorithm
- Implement the function
- concrete data structure that Implement data store
- the actual interconnection among the store
<!-- TODO: -->
### External design [[software_enginerring#External design]]
----------
1. SRR -> software requirement review
2. PDR -> preliminary design review
3. CDR -> Critical design review

### three level of abstraction
----------
1. functional abstraction
2. Data abstraction - involve specs of data type/object
    - eg : Stack
3. Control abstraction - used to design affect w/o stating exact mechanism of control

### Structure
----------
- fundamental of something i forgot to note
- more manageable unit
- with well define relationship

### Information riding
----------
- function at design concept
- the design should begin with a list of ..
- used as a principle design for architectural design of the system.

### Concurrency
----------
- Independent process can be activated simultaneously if multi pro
- on a single processor , it can be interleaved execution time
- necessary for se to concurrent software design
- the study of the aesthetic is a combination of design functionality.
- Visual and emotional connection and user communication

### DFD
- In this level entire s/m is represented babble with input and output indicated bu in coming & out going arrows.
- each process in level 1 represent the sub fns of every process represents the basic functionalities.
  the leves are increased each bubble gets define.
  eg:
   external entery: |==|
   process: 0
   store:==
   flow: ->

- Level 0 DFD:
 railway eservation
    ~ passenger
        ~train schodloing
            ~reservation


