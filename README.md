# Crypto-priject
Secure Sending Images using Serpent Algorithm 
Project Study:
The program we implement will mainly focus on sending secured images between two users. The input of our program is a colorful image.
at first, we had a couple of meetings to understand what we have to do, what are the requirements of the project, what do we need to prepare and how to divide the work between us.
After these couple of meetings, we gathered as many questions needed to ask Renata about to get more knowledge on what we need to do and to fully understand the project’s subject.
Then, we have studied the Serpent Algorithm, RSA and digital signature and how they work step by step, we prepare many images that we want to work on, since each one of the images had a different size.
Serpent algorithm works on 128-bit block size, so, if the image size is not divided by 128, so we decide to expand the image size in order to appropriate the Serpent Algorithm demands. 
Project flow:
After we are done with the meeting with Renata. We divided the project into steps as below:
Each one of us gets a subject (Algorithm) to gather as much information as he can and to be able to fully understand the algorithm and the implementation of the subject so he would explain it to us step by step.
Two days later of studying the subjects, we have appointed a meeting, so we discussed the algorithms we had learned.
We started to build the basis of the project by starting to implement importing an image and convert it to a matrix of pixels, then we divided this matrix into blocks and each block we convert it into string before the encryption.
We did a meeting to understand how to make a connection between these 3 algorithms (Serpent Algorithm, CBC and RSA).
We implement the Serpent algorithm (encryption and decryption that used the same key), then after we assured that the algorithm implementation worked perfectly, we started to implement the CBC mode, then we implement the RSA.
After we completed all these steps, we started to implement the digital signature in order to check if the delivered image is the same as the sent image (authentication).

Conclusions:
In our daily life there are millions of images being sent, the majority of them are important so if anyone could obtain them it will lead to many problems, so this project assure secured sending images to the right person without interfering from any one else .
