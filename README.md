# Compressor
This is a project to investigate the potential of using chatbot style large language models as text encoders.

I have found that they can reduce string lengths by 20 to 30 percent, however with the size of these models and limited computing power available, 
this is not currently a viable text encoding method. 
Further work into greatly reducing the size of llms whilst keeping their capabilities would make this technique potentially useful in very low bandwidth text transmission

During work on this project, I found another potential usecase for this work. By spliting an integer into digits and using these as next word choices you can use the
complexitiy of the english language and the model's specific interpretation of what should come next to improve encryption ability. This can be further enhanced by 
adding a starting context string.
