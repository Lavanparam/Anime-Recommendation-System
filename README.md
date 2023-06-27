# <p style="padding:10px;background-color:orange;margin:0;color:black;font-family:newtimeroman;font-size:150%;text-align:center;border: 15px 50px;overflow:hidden;font-weight:500">Constructing a recommendation system for anime</p>

<p style="text-align:center; ">
<img src="https://cdn.donmai.us/original/0b/38/0b38a5da446f969e771f51151a321aba.jpg" style='width: 800px; height: 400px;'>
</p>


<p style="text-align:justify; ">
    
Since young, my friends and I have occasionally enjoyed watching various anime. Having been born directly into a golden era of anime, we always had an endless selection of things to watch but struggled to find anime similar to the ones that we had enjoyed. Even today, we're still searching for hidden gems that might be out there. Being unsatistfied with the recommendations given by streaming platforms, I decided that I'd take a stab at building my own recommendation system. I thought it would be fun an something practical that I could use. 

I eventually found a really cool anime series called Memories from 1995. It features 3 independent films of which my favourite was Magnetic Rose- one of the best anime films i've ever seen. I'd highly recommend. 

</p> 


# <p style="padding:10px;background-color:orange;margin:0;color:black;font-family:newtimeroman;font-size:100%;text-align:center;border: 15px 50px;overflow:hidden;font-weight:500">Data</p>

This dataset contains information on user preference data from 73,516 users on 12,294 anime. Each user is able to add anime to their completed list and give it a rating and this dataset is a compilation of those ratings.

**anime.csv**

* **anime_id :** myanimelist.net's unique id identifying an anime.
* **name :** full name of anime.
* **genre :** comma separated list of genres for this anime.
* **type :** movie, TV, OVA, etc.
* **episodes :** how many episodes in this show. (1 if movie).
* **rating :** average rating out of 10 for this anime.
* **members :** number of community members that are in this anime's
"group".

**rating.csv**

* **user_id :** non identifiable randomly generated user id.
* **anime_id :** the anime that this user has rated.
* **rating :** rating out of 10 this user has assigned (-1 if the user watched it but didn't assign a rating).

# <p style="padding:10px;background-color:orange;margin:0;color:black;font-family:newtimeroman;font-size:100%;text-align:center;border: 15px 50px;overflow:hidden;font-weight:500">Approach</p>

### Here is a breakdown of my approach to the project:

1. Basic Data Exploration
2. Exploratory Data Analysis (EDA)
3. Building a Recommendation System
4. Buidling Out a More Specific Content Based Anime Recommendation System 


### Future Considerations 

It would be cool to build a more sophisticated recommendation system for anime with a larger dataset. I've never really explored a recommendation system using an unsupervised approach such as a neural network. It does sound iteresting but i'd need to do further research into how I would evaluate each approach against one another.
