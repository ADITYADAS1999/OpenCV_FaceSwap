# OpenCV_FaceSwap


<img src="https://user-images.githubusercontent.com/58718316/172165705-188a5104-1021-44ab-8fd9-120be1ce912d.png">

# Where the AI technology actually use

Technology with time has progressed a lot. Unimaginable things can be seen as real objects. Those small tiles in our phones are a prime example of this. Those applications are there for different kinds of uses. One such part of technology is Deep Learning. Most of the modern-day applications are based on this technology. 

 

Let us first try to know what deep learning is. Deep learning is an artificial intelligence (AI) function that mimics the human brain's processing of data and pattern creation in order to make decisions. It is an artificial intelligence subset of machine learning that uses neural networks to learn unsupervised from unstructured or unlabeled data. Deep neural learning or deep neural network are other terms for the same thing.

 

Deep learning applications include self-driving cars, virtual assistants, facial recognition, etc. In this blog, we are going to talk about facial recognition using deep learning techniques.

 # What is Facial Recognition?
 

Facial recognition is a method of identifying or verifying a person's identity by looking at their face. People can be identified in photographs, films, or in real-time using facial recognition technology.

 

This technology is used in various fields nowadays, even many smartphones have this feature where they unlock only when they recognize the face of their owner. Facial recognition comes under biometric security. Voice recognition, fingerprint recognition, and ocular retina or iris identification are all examples of biometric software. 


Although the technology is mostly utilized for security and law enforcement, there is growing interest in other applications. The facial recognition technology uses deep learning algorithms to identify and match the face with a database

How does Facial Recognition Work?
 

Due to advancements in AI, machine learning, and deep learning technologies, the facial recognition business is quickly developing. Facial recognition is a technology that can recognize a person only by looking at them. It uses machine learning techniques to identify, collect, store, and evaluate face characteristics so that they can be matched to photos of people in a database. 

# Face Detection
 

To begin, the system must find the face in the image or video. Most cameras now include a built-in facial detection feature. Snapchat, Facebook, and other social media platforms employ face identification to let users apply effects to images and videos taken using their apps. Many apps identify the person in the photo using this, they can even find a person standing in a crowd with this face detection technique.

 

# Face Alignment
 

To a computer, faces turned away from the focal point appear completely different. To normalize the face and make it consistent with the faces in the database, an algorithm is necessary. Using a variety of generic face landmarks is one method to do this.

 

The bottom of the chin, the top of the nose, the outsides of the eyes, different places surrounding the eyes and lips, and so on are examples. The next stage is to train a deep learning system to locate these spots on any face and turn it towards the center. This makes the face detection process much easier.

 

(Referred blog: Introduction to Neural Networks in Deep Learning)

 

# Face Measurement and Extraction
 

This phase entails measuring and extracting numerous characteristics from the face so that the algorithm can compare it to other faces in its database. However, it was initially unclear which traits should be collected and extracted until researchers realized that letting the deep learning system decide which data to gather for itself was the optimal method. 

 

Embedding is a technique that employs deep convolutional neural networks to teach itself to create numerous measurements of a face, allowing it to differentiate it from other faces.

 

# Face recognition
 

A final deep learning algorithm will compare the measures of each face to known faces in a database, using the unique measurements of each face. The match will be whatever face in your database comes closest to the measurements of the face in question.

 

# face Verification
 

Now, in the end,  the deep learning algorithms do the final act, which is, matching the face with other faces in the database. If the face matches then it is said to be verified, and if it doesn’t it remains unverified. This step is called face verification. Faces are compared in it to give the final result of a whole long process. But this step is a slightly complex one. 

 

The image can be compared to the database in one of two ways. If the image obtained and the image in the database are both 3-D, the matching procedure will go smoothly. However, because most government offices and other locations use 2-D databases, the comparison becomes more difficult. 

 

Before comparing, the 3-D picture must be transformed into a 2-D image. When compared to a still and stable 2-D image, a 3-D image will be alive and moving. As a result, when a 3-D picture is captured, it is transformed to 2-D by obtaining measurements from distinct places on the face. These measurements will then be translated to an algorithmic form, and therefore a 2-D picture will be created.

 

(Most related: Machine learning algorithms)

 

According to its aim, the comparison may also be divided into two categories. Verification is one of them, and identity is the other.

 

Verification: It is the process of identifying someone who claims to be an employee of a specific office. This sort of database comparison will only be carried out in a 1:1 ratio. That is to say,

 

Identity: The image obtained will be compared to all of the photos in the database in a 1: N ratio to identify a thief or a perpetrator. Take a look at the graphic below to see how the comparing process works.

 

In most cases, the comparison is done using three distinct templates. They are;

 

Vector Template: This template is used to do a fast database search in both 1:1 and 1:N ratios.

 

LFA (Local Feature Analysis): This template is based on the vector template. This is a more difficult search.

 

Surface Texture Analysis [STA]: This is the most difficult of the three search templates. It follows the LFA, and the search is focused on the image's skin characteristics, which carry the most information.


 

When these templates are integrated into face recognition software, the system can detect and identify the individual even when his expressions vary, such as smiling, frowning, or blinking. The software's accuracy is unaffected by the development of a moustache or beard.

 

 

# Uses of Facial Recognition
 

Nowadays, facial recognition is used in many industries across the globe. Here we are mentioning the 7 best uses of it.

 

# Unlock Phones
 

Face recognition is currently used to unlock a range of phones, including the newest iPhone. This technology is a strong technique to secure personal data and ensure that sensitive data is unavailable to the offender if a phone is stolen.

 

# Smarter Advertising
 

By making informed estimates regarding people's age and gender, face recognition has the potential to make advertising more targeted. Companies like Tesco are already planning to put displays with built-in facial recognition at petrol stations. It'll only be a matter of time until facial recognition is widely used in advertising. Learn more about how Tesco uses big data analytics.

 

# Find missing people
 

Face recognition may be used to track missing children and human trafficking victims. As long as missing people are entered into a database, law enforcement can be notified if they are identified by facial recognition in a public place, such as an airport, retail store, or other public areas. 

 

# Protect Law Enforcement
 

Face recognition applications on mobile phones are already assisting police officers by allowing them to quickly identify people in the field from a safe distance. This can assist them by providing contextual information about who they are working with and whether they should continue with caution. 

 

For example, if a police officer pulls over a wanted killer during a normal traffic stop, the officer will immediately recognize that the suspect is armed and dangerous, and will call for backup.

 

# Identifying People on Social Media
 

When Facebook members appear in photographs, Facebook utilizes facial recognition technology to instantly recognize them. This makes it easier for individuals to discover images in which they appear, and it also allows them to recommend when certain persons should be tagged in photographs.

 

# Tracking Student Attendance
 

Face recognition can track kids' attendance in addition to making schools safer. In the past, attendance slips allowed students to sign another kid in who was skipping class. 

 

However, many schools already use facial recognition to guarantee that pupils do not skip class. Students' faces are scanned with tablets, and their images are compared to a database to verify their identities.

 

# In Forensic Investigations
 

By automatically detecting persons in surveillance footage or other recordings, facial recognition can help forensic investigations. Face recognition software may also be used at crime scenes to identify people who are dead or asleep. 


<img src="https://user-images.githubusercontent.com/58718316/173589076-8228dd5b-b399-4117-ab7e-676fe70148be.jpg">


<img src="https://user-images.githubusercontent.com/58718316/173589091-684825e9-7d6b-4762-a7b6-09e33a3b5068.png">






# What Is AI, ML & How They Are Applied to Facial Recognition Technology



Technology has evolved from being a problem-solving force to a purpose-driven entity for humans. Looking back at the 1990s, technology was limited to computers, the internet, emails, wired telephony, but advancements in technology have led to a sweeping change in its role as an indispensable necessity in our lives and society. One of the key advances is the advent of artificial intelligence (AI) and machine learning (ML), which were conceptualized to replace human intervention for mundane tasks or even handle mission-critical applications and contribute to safeguarding. In the subsequent sections, we will see the expanse of AI and ML in various use cases as well as understand their role in one of the most advanced forms of biometric security — facial recognition.


# What Is Artificial Intelligence (AI)?
AI is a technology that simulates human intelligence processes using machines to make cognitive decisions. From recognizing faces on your mobile lock screen to self-driving cars, AI has unleashed a new realm of leveraging technology.

# How Does AI Work?
AI uses a set of unstructured data to analyse information patterns using AI algorithms and correlate the information to provide outcomes. Being programmed to make cognitive decisions, AI augments various forms of automation by harnessing neural networks, machine learning, and deep learning to arrive at a decision.

# Where Is AI Used?
Artificial Intelligence is an integral part of various applications and SAS software. Some of the popularly used applications include image recognition, speech recognition, natural language generation, sentiment analysis, and chatbots to name a few.

AI offers a slew of characteristics that look promising for the products of tomorrow. AI can automate frequent, high-volume tasks by learning and discovering through data. Secondly, it adds intelligence to products in the areas of automation, conversational platforms, smart machines, and bots. Thirdly, it is capable of self-learning through algorithms by finding structure and regularities. Next, AI performs a deep dive of the data sets to facilitate building complex products like fraud detection systems. Further, AI uses deep learning to ensure incredible accuracy by progressively analyzing the inputs. Lastly, Artificial Intelligence helps in monetizing data for businesses to stay ahead of the curve.


<img src="https://user-images.githubusercontent.com/58718316/173840814-20679ad6-aa26-422c-94ab-bbca53080e10.png" height=200 width=200>




# What Is Machine Learning (Ml)?

Machine Learning is a subset of AI that mainly focuses on using data and algorithms to mimic human learning. It uses statistical methods to train algorithms to classify or predict and even provide insights into data mining projects. Terms like deep learning and machine learning and sometimes neural networks are generally interchangeably used in the industry. However, there are subtle differences between these technologies. A neural network is a subset of deep learning while deep learning is one of the arms of machine learning.

Simply put, deep learning involves training algorithms with minimal human intervention. It converts unstructured data to manageable groups for processing through a process known as dimensionality reduction.

On the other hand, neural networks also known as artificial neural networks comprise node layers – an input layer, multiple hidden layers, and an output layer. Each of the nodes has an associated weight and threshold and is connected to the other nodes. Basically, if the value of any output layer exceeds its threshold, data is sent to the next layer of the network. Neural networks are of two types: basic neural networks and deep neural networks. In the basic neural network, two or three layers are present whereas a deep neural network consists of more than three layers.

# How Does ML Work?
An ML algorithm has three components:

- Decision process
- Error Function
- Model Optimization
In the decision process, an initial input is analysed to make a prediction or estimation of the pattern in the data. In the second phase, the prediction is evaluated based on existing examples. In the model optimization phase, discrepancies between the model estimates and known examples are reduced and optimize the weights until a preset accuracy threshold has been achieved.

# Where Is ML Used?
ML is widely used for automatic speech recognition using natural language processing to convert human speech into text. Moreover, speech recognition is used in mobile devices to facilitate voice search. Secondly, it is gaining popularity as a touchpoint for customers on websites and apps by answering frequently asked questions around pricing, shipping, delivery, feedback, and returns. Moreover, ML is being used in virtual assistants and voice assistants to perform mundane tasks.

ML is used in computer vision to derive meaningful insights from images, videos, and visual inputs, especially in the field of radiology and self-driving cars. In marketing, ML is used for analyzing consumer behaviour patterns to devise cross-selling strategies and give recommendations to consumers on e-commerce websites.

# What Is Facial Recognition?
Facial recognition is one of the front-runner applications of AI. It is one of the advanced forms of biometric authentication capable of identifying and verifying a person using facial features in an image or video from a database.

# Why Is Facial Recognition So Important Now?
In recent years, there have been increased investments in facial recognition technology. Venture funding in facial recognition start-ups has seen a huge uptick in 2021. With advancements in this technology, new use cases and business models in the field of advertising, healthcare, security, proctoring, airports, etc.

# How Does Facial Recognition Work?
Face recognition uses AI algorithms and ML to detect human faces from the background. The algorithm typically starts by searching for human eyes, followed by eyebrows, nose, mouth, nostrils, and iris. Once all the facial features are captured, additional validations using large datasets containing both positive and negative images confirm that it is a human face. Some of the common techniques used for facial recognition are feature-based, appearance-based, knowledge-based, and template matching. Each of these methods has its advantages and disadvantages.

Feature-based methods rely on features such as eyes or nose to detect a face. The outcomes of this method could vary based on noise and light. Further, appearance-based methods use statistical analysis and machine learning to match the characteristics of face images.

In a knowledge-based approach, a face is recognized based on predefined rules. This could be challenging considering the efforts needed to define well-defined rules. Whereas template-matching methods compare images with previously stored face patterns or features and correlate the results to detect a face. However, this method fails to address variations in scale, pose, and shape.

# Conclusion
Artificial Intelligence and machine learning offer a multitude of opportunities and endless possibilities to work for the betterment of the world. However, it is essential to pay attention to the ethics and privacy of people while dealing with data. Data storage, management, and security are the other aspects that will play an important role in making these technologies invasive.
