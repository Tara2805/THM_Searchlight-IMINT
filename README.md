# OSINT CHALLENGE
## THM_Searchlight-IMINT

#### Description

In this room we will be exploring the discipline of IMINT/GEOINT, which is short for Image intelligence and geospatial intelligence.

This room will introduce you to several topics within IMINT, among them: 

1. Getting into the right mindset and how to be analytical 
2. Visually extracting key data points from an image or video
3. Applying different tools to assist you in geolocation and answering context questions

The flag format is: sl{flag} - this means that every answer needs to be submitted within the brackets, sl{your answer}. No capitalization is needed. 

#### Walkthrough

### Task2 
Before we can apply a tool or a methodology for finding the location of an image, we should use our eyes to scan the image for important information. Extracting key data points from the image will allow you to apply the right tool, craft a good Google search or identify which part of the world the image might have been taken in. 

There are 5 elements of IMINT that you should consider when looking at an image, according to Geoint expert Benjamin Strick:

- Context
- Foreground
- Background
- Map markings
- Trial and error


A geolocation challenge like this lacks one important factor, which is the context or the source of the image. In real-world cases, you usually have a context in which the image was produced or shared, usually called context clues. Most of these challenges will not have context clues but you may find clues in the titles and descriptions, or if you're stuck you can use the hint function. 

Here are some questions you should ask yourself while looking at the upcoming challenges:

- Are there any obvious data in the image that reveals the location, like a street name or storefront signs?
- Can you determine the country or region of the image by, for instance, which side of the road they drive on, language or architectural characteristics that may reveal a country or continent/region?  
- Do you recognize road sign styles, nature and environmental characteristics, or popular motor vehicle brands or vehicle types? 
- What is the quality of any visible infrastructure like? Is the road paved or do you see gravel roads? 
- Do you see any unique landmarks, buildings, bridges, statues or mountains that can help you geolocate the image?

Download the attached image and answer the question below - good luck! 

#### Question
What is the name of the street where this image was taken?

#### Answer
Just examine the image, it says the name of the street on the sign

**Flag:** sl{carnabystreet}

### Task3
The last challenge wasn't really a challenge, was it? 

Let me introduce you to your first tool, Google! If you see anything in the image that can be extracted into a keyword, phrase, a company name, telephone number or any other question you may have as a result of scanning the image up and down: GOOGLE IT!

Here is a short introduction to what we call **'dorking'**, the art of using Google search queries to have Google return specific types of data.

When geolocating a picture finding the exact location is key, but we may need to answer other questions about the location or the image as well, usually referred to as context questions.

![alt text](/Images/task3.jpg)

#### Question
Which city is the tube station located in?

#### Answer
**Flag:** sl{london}

#### Question
Which tube station do these stairs lead to?
**Flag:** sl{picadilly}

#### Question
Which year did this station open?
**Flag:** sl{1906}

#### Question
How many platforms are there in this station?
**Flag:** sl{4}

### Task4
Good job solving the last challenge! You were able to find the location of the image and by doing that, you could answer contextual questions about the location. This challenge will also require you to do some 'Google dorking' to answer the questions below. 

Scan the image for data and remember the questions from the introduction - Do you see anything in the image that can be used in a search query or help you narrow down the potential location?

![alt text](/Images/task4.jpg)

#### Answers
I simply googled *YVR Connects*, found the same image online and determined it to be YVR Airport, Canada.

#### Question
Which building is this photo taken in?
**Flag:** sl{vancouver international airport}
#### Question
Which country is this building located in?
**Flag:** sl{canada}
#### Question
Which city is this building located in?
**Flag:** sl{richmond}

### Task5
A friend of mine contacted me asking if I could help them locate a coffee shop that is supposed to serve the best lunch there is. They told me the coffee shop is somewhere in Scotland, and he sent me these two pictures. Do you think you could locate it and answer the questions below for me?

![alt text](/Images/task5A.jpg)
![alt text](/Images/task5B.png)

#### Answers
We see in the background a popular shop chain. Search *the edinburgh woolen mill on corner* on Google, an article on the<a href="https://www.dailyrecord.co.uk/news/local-news/edinburgh-woollen-mill-group-rescued-23320228">Daily record</a> is returned and shows the same store, with the location noted.

![alt text](/Images/task5location.png)

#### Question
Which city is this coffee shop located in?
**Flag:** sl{blairgowrie}

#### Question
Which street is this coffee shop located in?
#### Answer
As we have the EWM location, we can go on Maps and find the coffee shops details

![alt text](/Images/task5coffee.png)

**Flag:** sl{allan street}

#### Question
What is their phone number?
**Flag:** sl{+447878 839128}

#### Question
What is their email address?
#### Answer
Go the coffee shops Facebook page, which is linked on their Maps information. In the Facebook details the email address is listed. 
**Flag:** sl{theweecoffeeshop@aol.com}

#### Question
What is the surname of the owners?
#### Answer
Search "The wee coffee shop" "owner"
**Flag:** sl{Cochrane}

### Task6
One of the methods for geolocating an image is to do an image reverse search. This means that we are searching for the image itself online, and if the image has been indexed by search engines we may find the exact image or we can do a visual search or crop search to help us find similar images. 

![alt text](/Images/task6.png)

#### Question
Which restaurant was this picture taken at?
#### Answer
We performed a reverese image search with the image provided and found all necessary details from a related Trip adviser. 
**Flag:** sl{katz's deli}

#### Question
What is the name of the Bon Appétit editor that worked 24 hours at this restaurant?
#### Answer
Performed a special search, seen in the image. W find the YouTuber who worked here for 24 hours. The YouTube channel is 'Bon Appétit'. The editors name we're looking for is in the video description. 

![alt text](/Images/task6B.png)

**Flag:** sl{Andrew Knowlton}

### Task7
This challenge will require you to apply some the techniques I have touched on so far: Scanning the image for visual clues, reverse image searching and Google dorking. Tools should not be your primary focus - don't underestimate how far you can get with dorking and scrolling search results. 

![alt text](/Images/task7.png)

#### Question
What is the name of this statue?
#### Answer
We performed a reverese image search with the image provided. This returned the Location as bloggers would publish this information openly, however they did not mention the name of the statue. So I searched "motorcycle on a reindeer statue" and found the statues details.
**Flag:** sl{Rudolph the Chrome Nosed Reindeer }

#### Question
Who took this image?
#### Answer
By searching "Rudolph the Chrome Nosed Reindeer oslo", we get this <a href="https://www.visitoslo.com/en/articles/outdoor-sculptures-in-oslo/">website </a>

![alt text](/Images/task7authoer.png)

**Flag:** sl{Rudolph the Chrome Nosed Reindeer }