# MetaSpeak

<img width="567" alt="medium" src="https://github.com/SamPom100/hack-harvard/assets/28206070/168c6b40-71a0-4a25-a30b-bd1f9fbea3dd">


This project won HackHarvard 2022.
[https://devpost.com/software/metaspeak](https://devpost.com/software/metaspeak)


### The Team
<img width="315" alt="Screenshot 2023-06-06 at 1 18 25 PM" src="https://github.com/SamPom100/hack-harvard/assets/28206070/b1145132-1d15-4d45-8405-af781e8bf4f3">




# The Metaverse is the next big computing platform

## We believe it's essential to consider the needs and requirements of everyone on this journey to the future

# Building an more inclusive Metaverse
For HackHarvard, we developed VR app backed by a custom a ASL Neural Network and Speech-To-Text Engine powered by AssemblyAI to help people with disabilities access more online.

# Description
Our app, running locally on a Meta Quest 2, uses sockets to communicate scanned 3D hand positions over a TCP connection from the Quest to the Server running the ASL Classification Model and Speech-To-Text engine, then returning the outputs back to the Quest to display the visual VR effects.

# Live ASL Translation
<img width="467" alt="medium" src="https://res.cloudinary.com/devpost/image/fetch/s--PghhGZTB--/c_limit,f_auto,fl_lossy,q_auto:eco,w_900/https://i.imgur.com/o2TnhKW.png">
We built a custom neural network to enable deaf mute people to communicate effectively in the Metaverse. This model captures hundreds of hand data points in real time to analyze and determine live which ASL signs people make, then converts them to text and returns it for others to see.

# Live Speech-To-Text
<img width="467" alt="medium" src="https://res.cloudinary.com/devpost/image/fetch/s--84Blb8qa--/c_limit,f_auto,fl_lossy,q_auto:eco,w_900/https://i.imgur.com/AUUhzly.png">
Capturing sound from the Metaverse and local microphones, we pass the audio to AssemblyAI's Speech-To-Text API and return the translation, enabling easy access for those hard of hearing.

# Live Multiplayer Conversation
<img width="467" alt="medium" src="https://res.cloudinary.com/devpost/image/fetch/s--OKtu5Sw4--/c_limit,f_auto,fl_lossy,q_auto:eco,w_900/https://i.imgur.com/f1ZPsoL.png">
To help people interested in learning sign language, we've integrated Google's GPT-3 into our project. GPT-3 will read your ASL to Text translated conversations and reply accordingly, a perfect practice partner.

# Challenges
Capturing and modeling hand data in 3D point spaces
High bandwidth socket connections
Neural Network learning and accuracy
Rendering virtual environments with high FPS and fidelity

# Next Steps
We're excited about the progress we've made in two short days and are looking forward to expanding the project by integrating it with apps like Horizon Worlds, VR Chat, and other popular platforms.

In addition, a future improvement is converting our model from ASL-To-Text to ASL-To-Speech. Doing so would greatly improve the inclusiveness of deaf mute people in everyday Metaverse interactions.
