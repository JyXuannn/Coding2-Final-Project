# Coding2-Final-Project
Video Link: https://www.youtube.com/watch?v=xE8MNRfDxMU&t=3s 


Description(The code is shown in the video)：

This project used the knowledge from weeks 5 and 6: puzzle solving and image processing (Histograms) respectively. The first riddle used the same knowledge as in week 5 and involved finding the 32nd power of 8. Once obtained, the URL needed to be modified and the second puzzle obtained.

The second question was inspired by Greek mythology: what animal walks on four legs in the morning, on two legs at noon and on three legs at night? The answer is humans. In the morning it is four legs because it refers to the young age, when it has to crawl on its hands. Noon refers to adulthood, when one walks on two legs, so it is two legs. Evening refers to old age, when one has to walk on crutches, so it is three legs.

For the third question you need to click on the blank to download the code and make code changes (the code to be changed in this step relates to the Week 6 points). After passing the last level you can get the file of the whole production process.


To run these files you need to install the environment and package， the following section is the installation code：

1. conda env

   create env of python 3.7.9

   ```
   conda create -n py37 python=3.7.9
   ```

   Linux:  

   ```
   source activate py37
   ```

   Windows: 

   ```
   activate py37
   ```

2. Install Package

   ```
   cd [project path]
   pip install -r requirements.txt
   ```

   **Tip: if you meet error , you try to install setuptools==45.0.0**

   ```
   pip install setuptools==45.0.0
   ```

   

3. Run system

   ```
   python manage.py runserver 
   ```
