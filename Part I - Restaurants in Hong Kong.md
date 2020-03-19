# Restaurants in Hong Kong

### How to choose a restaurant in Hong Kong

## Problem background:

Hong Kong is a financial center, a special administrative region and with a population of over 8 milion people. It is a crowded city and congested. And undoubtedly there are many choices for accomondation. However, a majority of land in hong kong are nature, only less than 10% is residential or so called city area. Perhaps you've never seen so many mountains in your life and you decided to reserve some time for mountains. There are three main region, HK island, New Territories and Kowloon.

Hong Kong is a food paradise due to its multicultural characteristics. Hong Kong is already really crowded, that means there are restaurants everywhere, perhaps too much and too confusing. Yet you want to let the statistics decide for you.

## Problem description:

Suppose i travel and keep changing places very frequently. This is very hectic and plus i get to experience very different types of environment, of which i donot have much knowledge about. In such situation, food can be an important factor for decided how you rate your trips and plus also recommmending it to the people. Food can also attract people around to world to try it out if it were to be the best. In such scenarios, we need to find the right place, at reasonable cost, to serve us the best possible way. So there are few questions that must be addresed, such as :

How many types of foods are available in the restaurant ?
which is the most nearest to me with good rating ?
How many "similar" restaurants are available near by me ?
Do the "similar" restaurants cost more ? if so, what speciality do that have ?

To address such question, XXYZ company's manager decides to allocate this project to me not just to find out solutions to the questions but also build a system that can help in recommending new places based on their rankings compared to the previously visited by me.

Expectations from this recommender system is to get answer for the questions, and in such a way that it uncovers all the perspective of managing recommendations. It is sighted to show :

What types of restaurants are present in a paeticular area ?
where are the similar restaurant present based on a preference to particular food ?
How do different restaurants rank with respect to my preferences ?

## Target audience:

Target audiences for this project does not limit to a person who keeps travelling but everyone. People could simply decide to look for a similar restaurant all the time because they are addicted to a specific category of food. People who rarely use restaurants would prefer to have the most rated restaurants nearby them and all this could be easily handed by our recommender system. So target for this project is basically everyone who is exploring different places or similar places.

## Success rate:

With restaurants evolving, new food categories emerge, hybrid food starts to be more popular, we need a system that could help us access vast number of food varieties. It is impossible for a person to ask each and everyone about their visit to a particular place and also not everyone remembers everything. On the other hand, Computers are good at remembering things, and with Machine learning to its peak, it high time technology will by our personal guidence and help us personally based on our likes and dislikes. So people would care about this project as their personal assistance and success rate could certainly increase with time.

## Data requirements:

To find a solution to the questions and build a recommender model, we need data and lots of data. Data can answer question which are unimaginable and non answerable by humans because humans do not have the tendency to analyse such large dataset and produce analtics to find a solutions.

Let's consider the base scenario :

Suppose I want to find a restaurant, then logically, i need 3 things :

    Its geographical coordinates(latitide and longitude) to find our where exactly it is located.
    Population of the neighborhood where the restaurant is located.
    Average income of neighborhood to know how much is the restaurant worth.
Lets take a closer look at each of these :

    To access location of a restaurant, its Latitude and Longitude is to be known so that we can point at its coordinates and create a map displaying all the restaurants with its labels respectively.

    Population of a neighborhood is very important factor in determining a restaurant's growth and amount of customers who turn up to eat. Logically, the more the population of a neighborhood, the more people will be interested to walk openly into a restaurant and less the population, less number of people frequently visit a restaurant. Also if more people visit, better the restaurant is rated because it is accessed by different people with different taste. Hence is is very important factor.

    Income of a neighborhood is also very important factor as population was. Income is directly proportional to richness of a neighborhood. If people in a neighborhood earns more than an average income, then it is very much possible that they will spend more however not always true with very less probability. So an restaurant accessment is proportional to income of a neighborhood.

## Data Collection:

Unluckily, no one seemed to care about the precise district and towns in Hong Kong to create a csv for them. I had to go to the Wikipedia, and extra few different tables, remove elements to create a dececnt town csv.

![image.png](attachment:image.png)

I had to remove those 'formerly' elements

![image.png](attachment:image.png)

I got most of the location using geopy.

Here is all the subway stations in Hong Kong, well, the stations are literally a town on its own.

![map.jpg](attachment:map.jpg)


```python

```
