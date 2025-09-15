
<p align="center">
<h1 align="center">AI Chatbot for Exclusive Ski Resort

</h1>
</p>

<p align="center">
<img src="https://img.shields.io/badge/Voiceflow-143055?logo=voiceflow&logoColor=white" />
<img src="https://img.shields.io/badge/Make.com-2D2D2D?logo=make&logoColor=white" />
<img src="https://img.shields.io/badge/Airtable-18BFFF?logo=airtable&logoColor=white" />
<img src="https://img.shields.io/badge/Gmail-D14836?logo=gmail&logoColor=white" />
<img src="https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black" />
<img src="https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white" />
<img src="https://img.shields.io/badge/Vercel-000000?logo=vercel&logoColor=white" />
<img src="https://img.shields.io/badge/GitHub-181717?logo=github&logoColor=white" />
</p>


<p align="center">
    <img src="./assets/website.png" width="320"/>
  <img src="./assets/chatsample.png" alt="Chat sample" width="350"/><br/>
  <em>Example of MU Bot Designs</em>
</p>


<p align="center">
This AI-Chatbot was built using Voiceflow. You can test out the demo from Vercel here:<br>
🚀 <a href="https://resort-ai-chatbot-omega.vercel.app"><b>Live Demo</b></a> <br>
</p>


## Business Problem
Mountain Universe Resort is a all-inclusive, well-known boutique ski resort in Switzerland. They had received inquires 24/7 about new reservations, rescheduling and cancellations, and frequently asked questions about the resorts itself such as their amenities, rooms, restaurants, etc. Having an AI chatbot to do these tasks would help Mountain Universe resort to reduce repetitive manual tasks and increase conversion booking rate by having this seamless reservation experience, especially during outside local working hours.


## The Development Stages

<p align="center">
  <img src="./assets/stages.png" alt="The Stages" width="800"/><br/>
  <em>The Development Stages </em>
</p>

#### Fun Fact!
I chose the name Mountain Universe and MU Bot to match my initial MU! 😝

## The Chatbot Workflows

MU Bot has three  main workflows which are:

1. Make new reservations; 
2. Manage their reservations: canceling or rescheduling;
3. Resort Information: answer FAQ about the resort, such as its amenities, restaurants and cafe, rooms and contact information.

<p align="center">
  <img src="./assets/MUbot.png" alt="The workflow" width="800"/><br/>
  <em>The Workflow of MU Bot </em>
</p>

## The Model
- Rule-based Model: predefined rules that gives pre-defined answers which applied to questions that needs answers to be accurate.
- Artificial Intelligence: Natural Language Understanding (NLU) is by utilizing of the knowledge base to recognize and understand the users’ intents before activating the rule-based model.

## Framework & Tools:

<p align="center">
<img src="https://img.shields.io/badge/Voiceflow-143055?logo=voiceflow&logoColor=white" />
<img src="https://img.shields.io/badge/Make.com-2D2D2D?logo=make&logoColor=white" />
<img src="https://img.shields.io/badge/Airtable-18BFFF?logo=airtable&logoColor=white" />
<img src="https://img.shields.io/badge/Gmail-D14836?logo=gmail&logoColor=white" />
<img src="https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black" />
<img src="https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white" />
<img src="https://img.shields.io/badge/Vercel-000000?logo=vercel&logoColor=white" />
<img src="https://img.shields.io/badge/GitHub-181717?logo=github&logoColor=white" />
</p>


<p align="center">
  <img src="./assets/Framework.png" alt="The workflow" width="800"/><br/>
  <em>The Framework and Tools </em>
</p>

- Voiceflow was as the framework where AI chatbot agent was developed
- Airtable served as guests database where guests and reservation details stored and retrieved through API
- Make.com was the integration platform that fetched information from Airtable and using webhook to send booking confirmation emails via Gmail


## Email Confirmation

Whatever the completed action taken by the user is, whether making new reservation, reschedule, or cancellation, the user will get email confirmation, like shown below:

<p align="center">
    <img src="./assets/new_booking.png" alt="The workflow" width="380"/>
  <img src="./assets/reschedule.png" alt="The workflow" width="310"/><br/>
  <em>Automated Email Confirmation </em>
</p>