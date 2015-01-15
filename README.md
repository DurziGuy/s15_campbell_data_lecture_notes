# Lecture Notes for Data Engineering Spring 2015


## Lecture 1
---
##### Data Lifecycle
  *  Collection
    * Curation + Triage + Persistence
      * Curation - Prioritization as to which data adds the most value to a particular question. I.e. I want to answer a question, which sources of data are most appropriate
    * What is the best thing to look at to generate an appropriate answer
  *  Generation
  *  Cleanup
  *  Storage
  *  Processing/Analysis
  *  Query + Visualize + Act
    * Generally generates new questions


## Lecture 2
---

    Presentation for 1/22/15 - Github: PR Model, *PR's* vs Pull command, *Forking* vs Branching,  Merging Complications - How to Fix?
---
##### RESTful Services
  *  Approach for building service based system
    * Representation State Transfer - resources in which you can *Create Read Update Destroy* via URI
      * Web is example of REST
  * Can GET - Read, POST - Create, PUT - Update, DELETE - Destroy on any URI (/users) 
    * GET /users *"Give me a representation of this resource's current state"*
      * GET /users/:id *"Give me this particular user :id"*
    * POST /users *"Take this {data} and create a new user"*
    * PUT /users *"Here is a new version of this user, update it"*
    * DELETE /users *"Destroy all users"*
      * DELETE /users/:id *"Destroy user where :id = id"*
  * Query String
    * GET /search?name="alex"+awesome=true



