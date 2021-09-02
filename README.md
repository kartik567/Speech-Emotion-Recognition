# Speech-Emotion-Recognition

# Introduction 

**In Today’s era the speech has more important because using speech we detect what the feeling of person in various communication field the speech has more important, So What is speech, Speech is nothing but, humans express the feeling and thoughts using coherently sounds, speech emotion recognition easily understand the emotion, Speech is the foremost common way of communicating ourselves as people.** 

**It is as it were common at that point to expand this communication medium to computer applications. We characterize speech feeling acknowledgment (SER) frameworks as a collection of techniques that prepare and classify speech signals to identify the inserted feelings.**

**Speech Feeling Recognition (SER) is the errand of recognizing the passionate angles of discourse independent of the semantic substance. Whereas people can effectively perform this assignment as a common portion of speech communication, the capacity to conduct it consequently utilizing programmable gadgets is still an continuous subject of research.**



![image](https://user-images.githubusercontent.com/74303124/129658636-2ee0967b-c136-4a52-9301-783dc6dea2bf.png)

# Problem Statement  

**Verbal Communication is valuable and sought after in workplace and classroom environments alike. There is no denying the notion that Indians lack verbal communication and consequently lag in the workplace or classroom environments. This happens despite them having strong technical competencies. Clear and comprehensive speech is the vital backbone of strong communication and presentation skills. Where some occupations consist mainly of presenting, most careers require and thrive from the ability to communicate effectively. 
Research has shown that verbal communication remains one of the most employable skills in both the perception of employers and new graduates. Of the possible improvements to vocal presentations tone, disfluencies, and stutters, in particular, remain one of the most common and prominent factors of someone’s demonstration. Millions of people are affected by stuttering and other speech disfluencies, with the majority of the world having experienced mild stutters while communicating under stressful conditions.
 Research shows that mild disfluencies can be cured without medical help, just practicing speech regularly and constructive feedbacks are effective ways to improve. We, Data Scientists recognize this problem and say hello.**
 
 # Dataset Information
 
 **The RAVDESS is a validated multimodal database of emotional speech and song. The database is gender balanced consisting of 24 professional actors, vocalizing lexically-matched statements in a neutral North American accent. Speech includes calm, happy, sad, angry, fearful, surprise, and disgust expressions, and song contains calm, happy, sad, angry, and fearful emotions. Each expression is produced at two levels of emotional intensity, with an additional neutral expression. All conditions are available in face-and voice, face-only, and voice-only formats.**
 
**The set of 7356 recordings were each rated 10 times on emotional validity, intensity, and genuineness. Ratings were provided by 247 individuals who were characteristic of untrained research participants from North America. A further set of 72 participants provided test-retest data. High levels of emotional validity and test-retest intrarater reliability were reported. Corrected accuracy and composite "goodness" measures are presented to assist researchers in the selection of stimuli. All recordings are made freely available under a Creative Commons license and can be downloaded at https://www.kaggle.com/uwrfkaggler/ravdess-emotional-song-audio**

# Dependencies
**Python**

**numpy**

**pandas**

**matplotlib**

**Pillow**

**opencv-python-headless**

**plotly**

**requests**

**librosa**

**streamlit**

**tensorflow-cpu**

**keras**

# Some Audio track 

![HAPPY](https://user-images.githubusercontent.com/74303124/129659965-1403187b-e752-48ea-8ad6-15642aa969e0.png)




![FEAR](https://user-images.githubusercontent.com/74303124/129660006-c7bf449a-ff6e-447c-8722-a94927d3eb8c.png)

# Spectrogram
![MALE NEUTRAL](https://user-images.githubusercontent.com/74303124/129660201-1aed9b15-e1dd-431e-a0db-baed5bcbc4c7.png)


# Buildings Model 

**since the project is a classification problem, Convolution Neural Network seems the obvious choice. We also built Multilayer perceptrons models but they under-performed with very low accuracies which couldn't pass the test while predicting the right emotions.**

![TRAIN LOSS TRAIN ACCURACY](https://user-images.githubusercontent.com/74303124/129661002-e87aa3c0-7db0-44b7-8a58-508446094c1e.png)


# Challenges

**Large speech Dataset to handle**

**Annotating an audio recording is challenging. Should we label a single word , sentence or a whole conversation? How many emotions should we define to recognize**


**It is not an easy task to convert speech to emotion**


**Emotions are subjective, people would interpret it differently. It is hard to define the notion of emotions**


# Conclusion 

**So after all the things do we conclude the paper in this section first use EDA load the data and get intuition about data after that some techniques are use like Data augmentation, feature extraction and modelIn model we use six type of model starting from Machine learning to deep learning model in machine learning we use decision tree and KNN after that using deep learning model GRU, LSTM, CNN, MLP classifier This speech emotion recognition are use in various field like customer care, marketing etc.** 





