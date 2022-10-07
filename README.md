# WLifts

## Abstract

According to The Global Health and Fitness Association (IHRSA), there were over 184 million members across almost 210,000 fitness and health facilities. Despite so many individuals concerned with their health, traversing the internet in search of reliable fitness knowledge is often daunting and overwhelming. Many new gym-goers will use articles and YouTubers such as Jeff Cavaliere, who has videos with upwards of 30 million views, to learn the basics of lifting and proper form. However, it is difficult to know if you are performing an exercise correctly without feedback before it is too late.

Existing workout apps such as [Onyx](https://www.onyx.fit/) only focus on correcting body exercises. Due to the lack of a resource to provide personalized help in weight-lifting, forums such as  reddit’s “formcheck” have amassed thousands of user’s asking for help with their form.

WLifts is an app that allows users to record themselves and receive live feedback on their form. The application would compare their body and joint positions to the ideal form and output a score that represents how close they are. WLifts would also provide feedback on how to fix their form. As such, our app will help beginners learn correct form so that they can work out safely. In order to achieve this, we plan on using computer vision and pose estimation to map out the joints of the users recording and compare them against the joints and body position of a professional performing the same exercise.

## Proof of Concept

In this notebook, we have created a proof of concept using the pretrained MoveNet model from TensorFlow and OpenCV for using the camera of the laptop.
