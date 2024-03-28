本地AI模型微調測試
-------------------

使用程式:</br>
[ollama](https://github.com/ollama/ollama)</br>
[AnythingLLM](https://github.com/Mintplex-Labs/anything-llm)</br>

載入訓練文件 </br>
1.里幹事.txt </br>
2.里長電話.txt </br>

訓練後對話結果_題問7題，錯誤2題，正確5題_參雜英文</br>
里幹事加里長通訊錄測試.json</br>


模型：Mistral 7B</br>
溫度：0.7 </br>
Number of vectors：2 </br>
Max Context Snippets：6 </br>
Document similarity threshold：.50 </br>
prompt: </br>
Given the following conversation, relevant context, and a follow up question, reply with an answer to the current question the user is asking. Return only your response to the question given the above information following the users instructions as needed.
