# COVID-19 Assistive Chatbot
__COVID-19 Assistive Chatbot is an interactive tool to help patients get answers to their questions and for an assessment of symptoms related to coronavirus. This would enable sharing of information about COVID-19 instantly to people around the globe and would be accessible 24/7. This would aid people in multiple ways by providing accurate and needful information about the disease thus helping them to know about the virus distinctly and what next to do to get treated best. The COVID-19 aid specialized chatbot can also clear various doubts related to the disease.__

_This COVID-19 Assistive Chatbot is created using __Azure Cognitive Services, QnA maker and Web App Bot Service__ in Azure._

_It is deployed in Azure and acts as a full-fledged Web App Bot in the Azure platform._

_The name of the Azure Web App Bot is __"hey-bot"__._

__Firstly, a QnA Maker namely hey-bot was created in the Azure platform using Azure Cognitive Services.__

![Screenshot (778)](https://user-images.githubusercontent.com/83343293/154432169-75a3c7d3-7d64-43c1-8f9b-471b53faa9db.png)
https://portal.azure.com/#@hevanthikamoutlook.onmicrosoft.com/resource/subscriptions/72ca33ff-072b-4dab-908c-a9decafb3705/resourcegroups/azurebot/providers/Microsoft.CognitiveServices/accounts/hey-bot/overview

Then the knowledge base for the QnA Maker hey-bot was published.
![Screenshot (781)](https://user-images.githubusercontent.com/83343293/154433850-9053d534-74dd-4d24-83f8-f712f495e89a.png)
It was tested
![Screenshot (782)](https://user-images.githubusercontent.com/83343293/154434088-cf508abe-2732-4379-893a-f50889680c10.png)
The knowledge base was saved and trained.

_Sample code of the knowledge base_
_Sample HTTP Request - Postman_
POST /knowledgebases/02750aab-5e25-4328-85b2-35b79d5e6477/generateAnswer
Host: https://hey-bot.azurewebsites.net/qnamaker
Authorization: EndpointKey c07050da-545f-475d-9632-e3cdedda85f8
Content-Type: application/json
{"question":"<Your question>"}

__Then an App Service was created for the QnA Maker Bot.__

![Screenshot (786)](https://user-images.githubusercontent.com/83343293/154435643-fc835c95-deb7-4562-99b1-6b24a6899521.png)
![Screenshot (787)](https://user-images.githubusercontent.com/83343293/154435784-cea0d69e-b858-45a6-9780-77a656fc499e.png)
![Screenshot (788)](https://user-images.githubusercontent.com/83343293/154436123-cb723a41-87c0-407f-bfad-3c53e35c7612.png)
https://portal.azure.com/#@hevanthikamoutlook.onmicrosoft.com/resource/subscriptions/72ca33ff-072b-4dab-908c-a9decafb3705/resourceGroups/DefaultResourceGroup-EUS/providers/Microsoft.Web/sites/hey-bot-a585/appServices

__Finally, the Web App Bot (hey-bot) was created and deployed in Azure.__

![Screenshot (790)](https://user-images.githubusercontent.com/83343293/154438112-4415521e-3824-4d1a-b20b-6e51e961e140.png)
https://portal.azure.com/#@hevanthikamoutlook.onmicrosoft.com/resource/subscriptions/72ca33ff-072b-4dab-908c-a9decafb3705/resourcegroups/DefaultResourceGroup-EUS/providers/Microsoft.BotService/botServices/hey-bot/overview

_The Bot source code file from the Azure Web App Bot is added as a zip file by the name __hey-bot-src.zip__ in the repository._

__*The Web App Bot in tested using the Test in Web Chat feature.*__

![Screenshot (792)](https://user-images.githubusercontent.com/83343293/154439836-10c79399-4a01-42e5-bb16-db089aee56a4.png)

_Web App Bot deployed in Azure and its Test in Web Chat link is provided below:_
https://portal.azure.com/#@hevanthikamoutlook.onmicrosoft.com/resource/subscriptions/72ca33ff-072b-4dab-908c-a9decafb3705/resourcegroups/DefaultResourceGroup-EUS/providers/Microsoft.BotService/botServices/hey-bot/test

Some questions that can be asked to the ChatBot:
1. What is COVID-19?
2. How does COVID-19 spread?
3. How do I know if it's COVID-19 or just common cold?
4. What can I do to protect myself and prevent the spread of the disease?
5. Is there a drug or treatment for COVID-19?
6. How long is the incubation and transmission period for COVID-19?
7. How long does the virus survive on surfaces?
8. How can I protect myself?
9. What should I do if I get sick or someone in my house gets sick?
10. Should I use soap and water or hand sanitizer to protect against COVID-19?
11. What are the recommendations for someone who has symptoms of COVID-19?
12. What are the symptoms and complications that COVID-19 can cause?
13. When should I seek emergency care if I have COVID-19?
14. What is contact tracing?
15. What antiviral drugs are available to treat COVID-19?

__As an explorative approach, the Chatbot is put into usage in a simple custom website to indicate its use case. And hence this "COVID-19 Assistive Chatbot" built to succour Healthcare would wholly achieve its cause to provide vital, necessary and accurate timely information about the virus which is affecting people worldwide and help us fight against this disease strongly.__
# CHATBOT SITE LINK
https://sites.google.com/view/covid-19-assistive-chatbot/home

  
![Screenshot (757)](https://user-images.githubusercontent.com/83343293/152024860-49d081f0-d503-4b71-ade4-483a5adeadc3.png)
![Screenshot (755)](https://user-images.githubusercontent.com/83343293/152024917-86ae2d67-c607-4409-9df2-1af20002ed85.png)


