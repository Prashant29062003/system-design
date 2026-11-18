# 4 Steps process

## How to Design Any Complex System: A 4-Step Process

1. **Requirements**
    - Functional Requirements - What it does? (Like what user does eg. )
    - Non-functional Requirements - How well it does it? (this is for )

2. **Capacity Estimation** - Scale 
    - -> Traffic
        - DAU(Daily Active User)
        - MAU(Monthly Active User)
        - At Peak how our system behaves (like, black Friday sale)
        - Read to Write Ratio (eg. 1 Lac request we get what it does read heavy or write heavy? -> this helps to take decisions) 
    - -> Storage
        - DB, File, Media, Data Growth
    - Bandwidth
    - compute
    - cost
    
3. **High Level Design (HLD)**
    - we are making the high level connecitions and how overall system works and interact with each other
    - [] -> [] -> []
       |    |     |  
       []->[] -> [] -> []

4. **Low Level Design (LLD)**
    - Here we zoom-in to the high level design of each box and decide
        - API, Interfaces, Dependency, Business logic structure, Database Schema

5. Implementaion (Code)


> NOTE: If any requirement change we have go back from 4th step to 1st (Iterative steps) 
- System design are interdependent, highly iterative and recursive 