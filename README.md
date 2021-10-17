# FemmeHacks-App: More Info here >> https://devpost.com/software/coronavirus-cases-data-and-tracker-with-resources
**Inspiration**

As the spread of the Coronavirus (COVID-19) continues, society is becoming more and more isolated, and mental and physical detriment rates are rising. To prevent the spread and harmful effects of the virus, it is important that communities have easy access to local updates that are determining the spread in their area. It is especially valuable for college students to have access to such information, as students are in close quarters and, therefore, are at a higher risk of contracting the virus and also spreading it. The idea of creating a resource for college students to limit their chances of being exposed and getting COVID-19 during this unprecedented time was a clear choice for my team; we find this app a necessity and clearly appreciate its potential in making college a safer place for students in these unprecedented times.

**What It Does**

This app is essential for college students, especially those living on campuses, to get access to quick and easy Corona resources. This app has compiled the hotlines, records of cases, safety precautions, and more from numerous colleges, all in one place making it easy for students to become informed on how to stay safe. The user is welcomed to the app with a map separated in sectors based off of location and universities in the Philadelphia area. When the user scrolls down, they can access an input bar in which they can provide the sector in which they live. With this information, the app, with more development, would then output the schools near them as well as personalized location information (high contagion locations, highly populated sections, etc.). As the user continues down, they can view information about Covid at different schools such as the number of students, sector, and more. Additionally, to give this information clearly, the app provides scatter plots of the positivity rates at each school as well as links to Covid resources for each school. Farther down, the user has access to information about testing sites near them. When the user taps a link, it brings them to Google My Maps that list the testing areas within each of the 5 sectors. Additionally, links to buy PPE as well as hotlines to report large, unmasked, and non-socially-distant gatherings are listed for the user.

**How We Built It**

We used React Native and Expo to build our app and, after collecting and importing data from schools in Philadelphia, we used RStudio and ggplots to create graphics comparing the positivity rates at different schools. Additionally, we used Google My Maps to form graphics showing college locations, testing sites, and different sectors of the city. We used an assortment of a custom button and card components to display these images to the user clearly and simply. Our app is driven by an assortment of premade libraries including react, react-native, react-native-paper, and react-native-webview as well as numerous custom build JSX components.

**Challenges We Ran Into**

After initially wanting to collect data from all the schools in Philadelphia, we found that many schools did not have available data due to being 100% virtual. Some schools provided cumulative test result data, while others provided just the current weekly updates.

Our initial idea was to create an interactive map, but we struggled to implement the Google Maps API into our code. Our solution to this problem was to create maps using Google My Maps and customized it to fit the areas in the surrounding schools. Although it is not directly implemented into our app, it still provides a simple way for the user to understand the Covid rates in their vicinity.

**Accomplishments**

We are proud of all our hard work and dedication used to create this app along with our devoted teamwork. In the limited time given, our team divided and conquered difficult tasks that were later assembled into one huge project. We are proud of our communication skills used while developing this app as most of us were meeting each other for the first time, and 2) we each possessed skills in varying coding languages.

**What We Learned**

We learned effective collaboration and how to support one another regardless of where we stood as coders. We also learned the hard work that goes into web development and respect those who partake in it to improve public wellness.

**What's Next?**
We have decided to continue working on it and improve our code.
