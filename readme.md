This is tutorial to langchain agent 

#module 1 
covers
	invoke , respones , streaming message to reduce latency ,
	lanchain.messages like user message - HUMANMESSAGES , 
	system_prompt , AI _MESSAGES 

unit 1:
      
       in this 2nd unit we learn how to give human msg using a varible 
  	using detailed system prompt 
   	using few shots likely 2 examples instead of previous 0 shot in system messages 
	using structured prompt in system messages as key:value 
	using pydantic BaseModel which automatically validates the outputs 
 
unit 2 :
	
	we learn to use tools from lanchain.tools - tool packages 
	we create tools using @tool decorator 
	we use tool by giveing the list of tools while creating agent 
	example the check prime tool we created can be used to to check 2 no's at the same time 
	we see tool call using .tool_calls

