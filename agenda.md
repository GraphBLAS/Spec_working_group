# GraphBLAS Spec Working Group Meeting Agendas


- [X] July 7, 2020
   >  Initialization in the distributed API
    
- [X] July 14, 2020
  > Continuation of initialization in the distributed API.
  > Logistics for future meetings
  
- [X] July 21, 2020    
   > Discuss feature lists from the Anaconda folks and from Gabor (https://docs.google.com/document/d/17gADsjqNhGHSK1RPCL8B4VjPYrHFF85T0-cvk4l4mss/edit?usp=sharing)  

- [X] July 28, 2020
   > Discuss issues from July 21 meeting (vote on items from the Anaconda folks and from Gabor ... Scott will prepare a spread sheet we can use to recored our votes).
   > https://docs.google.com/document/d/10-rW8kI4bI-I7HXVQTwGrtQ-et2B2oacRUIMwqf0YnQ/edit#heading=h.2lgw5acxkxbj
   
- [X] August 11, 2020
   > Serialization, import/export, and associated data structures.
   > Conclusion: Two possible API additions: (cross-platform) import/export to file and (implementation-specific) serialization to void\* array of bytes + a length.  Controversial question: should we allow a zero-copy serialization method (e.g. an array of void\* arrays and lengths)?  Larger question: should we introduce *views* to allow zero-copy submatrix extraction?

- [X] August 18, 2020
   > Discuss serialization doc: https://docs.google.com/document/d/10-rW8kI4bI-I7HXVQTwGrtQ-et2B2oacRUIMwqf0YnQ/edit#heading=h.2lgw5acxkxbj

- [X] August 25, 2020
   > Ben will create a serialize/deserialize, input/output API.  Discuss.
   > Discuss long-term plans for agenda.

- [X] September 1, 2020
   > Scott will take ten minutes at the beginning of meeting to discuss select.
   > Ben will fix issues pointed out in import/export API.  We will all brainstorm about how to deal with hypersparse.
   
 
- [X] Future meetings ... Date not specified
   > Discuss the implications of adding a GrB_Scalar object 
   > Discuss the proposed new error model.  Jose has been discussing this with this with Tim Davis and wants to update us the issues they've identified.

