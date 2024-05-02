### Self Healing RAG

This presentation is an overview of the code I have written with my senior design team to create a Self-Healing RAG retrieval system entirely locally on our schools high performance computing cluster.    
I cannot share the code of the project, however I have included a video and other files to showcase the RAG system working.   
The project has similarities to how the DocumentSummaryIndex from LlamaIndex works, with some key differences.

First, we introduce a self healing component that can improve summaries and therefore hit rate of the retrieval process.   
Second, we offer different retrievers that make use of both the summary and document index to retrieve results.   

There are slightly different approaches out there like RAPTOR, these are approaches we are looking into for further development.
