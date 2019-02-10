# HackTheSouth
Wildfire prediction project that was developed as part of #HackASoton hackathon by 5 students of the University of Southampton.
My team consisted of @marsianin88, @KacperKubara, @Chittawat and @umiisland

We gather data from various databases and we train a machine learning model that assigns probabilities of a wildfire to locations. We combine historical data with current weather data which we get through OpenWeatherMaps API, that can affect the possibility of a wildfire occuring. 
We also predict a suitable number of firefighters that would be necessary in case that disaster would occur. 

Also, we get satellite images of wildfires, and in case it is about a wildfire, then we automatically tweet certain warnings to citizens of that area, by tweeting a relevant message with the hashtag #[location]wildfires, so for example, "chilewildfires".

Finally, we display on our web application various news articles that are related to wildfires.
