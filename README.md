MODULE 1 - VIDEO 1

In this lesson, I learned how tracing in LangChain helps monitor and debug language model applications by providing visibility into runs with metadata for better organization. I also practiced enabling tracing through environment variables.

enabled tracing,  
added metadata,                                                                                                                               
changed the 1st question to "What does @traceable do in LangSmith"

edited file: https://github.com/keshavbararia/keshavbararia-langsmith-MAT496/blob/main/module1/tracing%20basics.ipynb

original file: https://github.com/keshavbararia/keshavbararia-langsmith-MAT496/blob/main/source%20code/tracing_basics.ipynb

MODULE 1 - VIDEO 2

I learned that assigning specific run types in LangSmith makes LangChain outputs easier to interpret. i learned about various run types like llm,chain,retriever,tool, I also learned about reducing chunks using reduce_fn function.

Added run_type = llm                                                                                                                                 
Added run_type = tool                                                                                                                                
Added run_type = retriever                                                                                                                            
Used reduce_fn function                                                                                                                        
Changed Example to say goodbye to the user instead of greeting it which helped in understanding of run_type function.

edited file: https://github.com/keshavbararia/keshavbararia-langsmith-MAT496/blob/main/module1/types%20of%20runs.ipynb

original file: https://github.com/keshavbararia/keshavbararia-langsmith-MAT496/blob/main/source%20code/types_of_runs.ipynb


MODULE 1 - VIDEO 3

I learned multple ways to monitor runs in langsmith like with trace, wrap_openai and run tree apart from @traceable.

I removed traceable decorater and used with trace                                                                                              
Wrapped the OpenAI client using wrap_openai so that nested calls are automatically traced.                                                      
Changed 2 questions to create new examples.

edited file: https://github.com/keshavbararia/keshavbararia-langsmith-MAT496/blob/main/module1/alternative%20tracing%20methods.ipynb

original file: https://github.com/keshavbararia/keshavbararia-langsmith-MAT496/blob/main/source%20code/alternative_tracing_methods.ipynb

MODULE 1 - VIDEO 4

Learned how llms with chatbot interfaces work by grouping multiple traces using threads to answer questions with context relying on previous questions and to use metadata for extra information and filtering.

Changed the last question to prove that the question was answered on basis of previous question.

edited file: https://github.com/keshavbararia/keshavbararia-langsmith-MAT496/blob/main/module1/conversational%20threads.ipynb             
original file: https://github.com/keshavbararia/keshavbararia-langsmith-MAT496/blob/main/source%20code/conversational_threads.ipynb


