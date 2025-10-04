# Introduction to LangSmith
course: https://academy.langchain.com/courses/take/intro-to-langsmith
## MODULE 1

### MODULE 1 - VIDEO 1

In this lesson, I learned how tracing in LangChain helps monitor and debug language model applications by providing visibility into runs with metadata for better organization. I also practiced enabling tracing through environment variables.

enabled tracing,  
added metadata,                                                                                                                               
changed the 1st question to "What does @traceable do in LangSmith"

edited file: https://github.com/keshavbararia/keshavbararia-langsmith-MAT496/blob/main/module1/tracing%20basics.ipynb

original file: https://github.com/keshavbararia/keshavbararia-langsmith-MAT496/blob/main/source%20code/tracing_basics.ipynb

### MODULE 1 - VIDEO 2

I learned that assigning specific run types in LangSmith makes LangChain outputs easier to interpret. i learned about various run types like llm,chain,retriever,tool, I also learned about reducing chunks using reduce_fn function.

Added run_type = llm                                                                                                                                 
Added run_type = tool                                                                                                                                
Added run_type = retriever                                                                                                                            
Used reduce_fn function                                                                                                                        
Changed Example to say goodbye to the user instead of greeting it which helped in understanding of run_type function.

edited file: https://github.com/keshavbararia/keshavbararia-langsmith-MAT496/blob/main/module1/types%20of%20runs.ipynb

original file: https://github.com/keshavbararia/keshavbararia-langsmith-MAT496/blob/main/source%20code/types_of_runs.ipynb


### MODULE 1 - VIDEO 3

I learned multple ways to monitor runs in langsmith like with trace, wrap_openai and run tree apart from @traceable.

I removed traceable decorater and used with trace                                                                                              
Wrapped the OpenAI client using wrap_openai so that nested calls are automatically traced.                                                      
Changed 2 questions to create new examples.

edited file: https://github.com/keshavbararia/keshavbararia-langsmith-MAT496/blob/main/module1/alternative%20tracing%20methods.ipynb

original file: https://github.com/keshavbararia/keshavbararia-langsmith-MAT496/blob/main/source%20code/alternative_tracing_methods.ipynb

### MODULE 1 - VIDEO 4

Learned how llms with chatbot interfaces work by grouping multiple traces using threads to answer questions with context relying on previous questions and to use metadata for extra information and filtering.

Changed the last question to prove that the question was answered on basis of previous question.

edited file: https://github.com/keshavbararia/keshavbararia-langsmith-MAT496/blob/main/module1/conversational%20threads.ipynb             
original file: https://github.com/keshavbararia/keshavbararia-langsmith-MAT496/blob/main/source%20code/conversational_threads.ipynb

## MODULE 2

### MODULE 2 VIDEO 1
Learned how to create a dataset on LangSmith and how to log examples to the dataset using client.create_examples.

I created a dataset and used client.create_examples to log examples.
Changed the question to one of the other questions already mentioned in the examples that were logged and observed the output.

edited file: https://github.com/keshavbararia/keshavbararia-langsmith-MAT496/blob/main/module2/dataset%20upload.ipynb             
original file: https://github.com/keshavbararia/keshavbararia-langsmith-MAT496/blob/main/source%20code/dataset_upload.ipynb

### MODULE 2 VIDEO 2
Learned how LLM-as-judge evaluators work to score system output. I also learned how to create auto evaluators in LangSmith using a similarity evaluator in the course.

I added a highly similar example achieving a similarity score 10 to test how well our model works.
Created an auto evaluator in LangSmith to compute similarity score just like we did in the code.

edited file: https://github.com/keshavbararia/keshavbararia-langsmith-MAT496/blob/main/module2/evaluators.ipynb                           
original file: https://github.com/keshavbararia/keshavbararia-langsmith-MAT496/blob/main/source%20code/evaluators.ipynb

### MODULE 2 VIDEO 3
Learned how to run experiments over a dataset which I made in LangSmith. I also learned how to run it over different dataset parts like version, split and specific points using example ids.

I used gpt 4o mini other than gpt4o and gpt 3.5 turbo                                                                                           
I tagged the earliest time version to "initial" to work on that specific dataset version.                                                          
I created a "crucial" split to experiment on the specific examples included in that split.                                      
Added 2 example ids to experiment on 2 specific examples.

edited file: https://github.com/keshavbararia/keshavbararia-langsmith-MAT496/blob/main/module2/experiments.ipynb                        
original file: https://github.com/keshavbararia/keshavbararia-langsmith-MAT496/blob/main/source%20code/experiments.ipynb

### MODULE 2 VIDEO 4
Analyzed experiment graphs which helped in seeing trends in our application performance and how it changed overtime, also how filters can be used to see different experiments. Learned how evaluators help in understanding how the model is performing.

Used filters to see the experiment by gpt 3.5 turbo.                                                                                           
Viewed complete input/output text for gpt 4o experiment in json/yaml format                                                                     
Used Feedback and metrics to see how the model performed.                                                                                  
Compared different experiments side by side on the basis of metrics.

### MODULE 2 VIDEO 4
learned how to run experiments in LangSmith to compare two different LLM prompts on the same dataset and to score summaries with an evaluator and run pairwise experiments to see which prompt gives better results.

Ran a comparitive analysis between 2 experiments (good and bad summarizer) using their experiment ids.

edited file: https://github.com/keshavbararia/keshavbararia-langsmith-MAT496/blob/main/module2/pairwise%20experiments.ipynb                      
original file: https://github.com/keshavbararia/keshavbararia-langsmith-MAT496/blob/main/source%20code/pairwise_experiments.ipynb
