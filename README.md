# FYP_PROJECT


Topic:
An Interactive approach to Cricket shots classification through Deep Learning.
-
Supervisor:
Ms. Farah Sadia
Co-Supervisor:


Team Members:
-
Anas Sohail [19k-1354]
Umer Zaidi Syed [19k-0304]
Osama Shibli [19k-0142]


Videos uploaded in huge volumes onto various streaming platforms consisting of YouTube and Vimeo play a vital function within the era of data communication. Simultaneously, reading information from these videos is critical trouble. While working with video statistics, making crucial selections even as constantly monitoring what's converting in their frames is a primary concern. The same can be said for numerous sports highlights. Cricket is one of these, thriving with a massive following all over the globe. A match that includes the ICC Men’s Cricket World Cup 2019 hits a worldwide audience of no much less than 1.6 billion, making it one of the well-regarded events ever. This extensive reputation and sizeable fan base create a business factor for working on cricket data. Cricket videos require analysis to develop an unbiased, equitable, and sensor-based commentary system. 
Moreover, detecting cricket on the basis of different types of cricket shots can be helpful for both coaches and sports analysts. Coaches and cricket experts have to regularly understand the weaknesses of different teams and adjust their game plans on the basis of those findings. In this context, it is vital to extract information from cricket data. Image recognition has always been a main part to computer vision projects hence we will also be using image normalization techniques on different frames in our video’s dataset, cleaning the irrelevant parts and only taking the part of the video in which, the shot had been executed. 



We will review existing Cricket shot classifier approaches from Past Research Papers. Our main purpose of doing this is to get a base line of the accuracy and efficiency. This will give us a good starting point for developing our own model for classifying cricket shots. We will also be implementing one model from a past research paper onto our selected dataset. This will help is finding deficiencies but also help us to improve our model by comparing it to that model and avoiding the same issues. Furthermore, we will be implementing CNN model which is widely used in image recognition in computer vision.
We will try to cover most common cricketing shots like Cover Drive, Flick, and Straight Drive etc. with some other activities like batsmen’s posture when playing the respective shot.
Tentatively we have a dataset of about 6 hours of videos which are highlights of different cricket matches, we will be adding more data which will mainly be videos specifically related to a shot played by the batsman. Irrelevant data will be cleaned from ‘matches highlights’ data and only the main shots will be picked.
Some of the models Which were mentioned in the research papers and are previously used are CNN and GRU (Specific model of RNN).


Dataset video quantity for 10 cricket batting shots.
Name            Training Set    Test Set
Cover Drive         153         35
Defensive Shot      157         35
Flick               146         35
Hook                146         35
Late Cut            147         35
Lofted Shot         151         35
Pull                144         35
Square Cut          160         35
Straight Drive      154         35
Sweep               159         35
