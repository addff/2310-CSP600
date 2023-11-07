# 2310-CSP600
# DEVELOPING LIVE KRAFCONNECT: THE HANDCRAFTED COMMUNITY USING GEOLOCATION WITH CONTENT RECOMMENDATIONS BASED ON USER PREFERENCES

## CHAPTER 1

## INTRODUCTION

### 1.1	Project Background

Nowadays, people live in a world where everything is at their fingertips. Individuals can stay fully informed about everything happening in their immediate surroundings only by staying home and scrolling their smartphones. Various social media have implemented live features, basically known as real-time updates, to ensure that users are constantly connected to the latest happenings. This functionality has been integrated into numerous social media platforms, allowing users to virtually connect with their environment in real time. In the ever-evolving landscape of social media, real-time updates have become a defining characteristic of these platforms. It's a concept that brings the digital world closer to real life, allowing users to experience and engage with events, discussions, and content as they unfold. This real-time interaction has transformed social media into a dynamic space where users can share their experiences, thoughts, and creations as they happen, fostering a sense of immediate connection with their peers and the world at large. The number of social media users has rapidly grown every year and is expected to keep growing in the future. As stated by Stacy (2023), more than 4.59 billion people around the world were using social media in 2022 and in 2027,  the number is anticipated to rise up to six million. 

Handcrafting is a beloved activity that people enthusiastically participate in. The sense of accomplishment during the creative process and the aesthetically pleasing results encourage individuals to pursue it consistently. Handcrafted items are typically created using basic tools and commonly characterized by artistic or traditional qualities (Dash & Mishra, 2021, p29). Crochet, knitting, pottery and basket weaving are common examples of handicrafts. The inspiration for these handicrafts depends on the individual, drawing from various sources such as people, scenery, and culture. Social media is a platform where people share numerous things without a limit. It is a source of inspiration that people use to get an idea for their handicraft project. Pinterest is an example of social media that serves as a vital wellspring of inspiration for consumers, significantly increasing their inclination to make purchases (Sheng et al., 2020). Furthermore, technology plays a crucial role in preserving and promoting handcraft skills over time. On social media like Facebook, Instagram and TikTok, crafters actively share their handcraft project progress, sell their patterns and engage with their followers. Social media has opened up new opportunities in the marketing industry, providing marketers with the means to raise product awareness among customers (Sriparna Guha et al., 2021). As technology continues to advance, the handcrafting world has also adapted to take advantage of these technological advancements.

Geolocation is a combination of geography and location. It is a discovery of the real-time geographic location of an object or person. Geolocation also usually refers to a technique to find the precise geographical points of a device. It helps people determine directions to their destination, locate nearby places and organize their journey. The implementation of geolocation in an application could be done through various methods which are GPS, WiFi and Google Maps API. GPS uses signals from multiple satellites to calculate latitude and longitude, while Wi-Fi approximates the device's location by comparing nearby Wi-Fi connections with known access points, considering signal strength and MAC addresses. Built-in GPS receivers access the location data. Google Maps API comprises a toolkit that empowers developers to incorporate a wide range of features, including map display and location search, into their applications. One of the applications that utilize geolocation as its main feature is Uber, a ride-hailing service, food delivery and freight transportation. Uber utilizes its technology platform to connect independent drivers with passengers seeking transportation services, retaining a portion of the fare as its commission (Willis and Tranos, 2021). Google Maps has been utilized to find the location of the driver and customer. In a statement, Uber acknowledged its reliance on external partners for software components in its products and services, highlighting the critical role of Google Maps in the mapping feature that underpins the functionality of its platform (Novet, 2019).

Learning about the user behavior throughout their pattern of using an application has been done by a system known as a content recommendation system. This learning resulted in displaying content that the user might like. Content-based recommender systems strive to suggest items that closely resemble those that have piqued a particular user's interest in the past (Zhang et al., 2020). Examples of applications that implement this system include e-commerce, social media and search engines. In the current landscape, an increasing number of news service providers are exploring recommendation systems to offer users personalized reading preferences (Zhou, 2023). This implementation has attracted users' engagement in using their application often. This is because users can save time from viewing content they are not interested in. The system operates by first defining user preferences, which are determined based on the content they have viewed, liked, and shared. This data is then compared with the keywords associated with the content and analyzed using complex algorithms to identify and recommend content that aligns with the user's preferences. As a result, users can access their preferred content within the application.

### 1.2	Problem Statement

Currently, artisans and craftspeople are actively leveraging social media platforms like Facebook, Instagram, and TikTok to connect with potential customers and showcase their creations. While this approach has its merits, it also comes with significant drawbacks, such as challenges in locating local artisans, limited discoverability, and a lack of dedicated technology to facilitate seamless artist-client interactions.

1.2.1	Lack of a centralized platform to discover local artisans.

A handcrafter usually will create an account on as many platforms as they can to promote their handicraft. This is the best way to get a large amount of audience. Online platforms have provided artists with a means to exhibit and market their artwork to a worldwide audience, opening up fresh avenues for income and broadening their outreach (Shirbhate et al., 2023). Despite all the benefits, crafters might face challenges in the process of creating content that can attract audiences. Some artisans who prioritize the quality of handicrafts may lack technology proficiency. Artisans who create handcrafted items frequently encounter challenges in marketing their products online, primarily because they lack the necessary technical skills and resources (Shirbhate et al., 2023).  Hence, it is best for an application to offer various features that can ease the process of content posting users and help their content stand out and capture the audience's attention.

The lack of a centralized platform for discovering local artisans has presented some challenges to the handicraft community. Currently, artisans are relying on social media like Instagram, Facebook and TikTok to reach various goals such as showcasing their handicrafts. A study from Indonesian shows that in the promotional ground, 35% of handcraft business took place on several social media such as 46% on Facebook, 39% on X and 15% on blogging sites (Rianto Rohadi and Andretti Abdillah, 2013, as cited in Sriparna et al., 2021). While these platforms are universally used and the number of users of those platforms is outnumbered, they are not focused on a specific community. Thus, a handicraft community has difficulty having a stand-out page. Furthermore, these platforms implement content algorithms where the content shown to the user might change. As a result, it becomes difficult for artisans to reach their audience without paid promotion.

Live KrafConnect application would gather all local artisan over the world to share their thoughts and ideas about handicrafts. Users will have the capability to post about their handicraft projects to let the people around them acknowledge their skills.

1.2.2	Difficulty in locating local artisans in the nearest area.

People who are interested in learning handcraft could seek guidance from nearby local artisans to learn the handcraft. Learning with an expert will make the student understand the study better. By having a learner, people can determine whether what they learn is aligned with the expert or not (Ansyah et al., 2021). In finding a professional teacher, people need to determine the artisans who provide classes and have a good knowledge of handicrafts. The process of searching for the artisan will not be easy since there are no applications that help in finding them. 

Locating the nearby local artisans can offer a significant benefit for individuals. Users can seek advice and help from these artisans to gain a deeper understanding of handcrafting including details like the history or process of making it. Besides, from a commercial perspective, users can verify the quality of the handcrafted products they wish to purchase by visiting the local artisans’ store in person. These interactions between the user and the local artisans could foster community building, potentially leading to craft events or workshops being held. These events provide opportunities for neighbors to connect, exchange ideas, and enjoy themselves, contributing to a more inclusive and vibrant community (Stevenson, 2020).
 
To address the difficulty in locating these nearby local artisans, the Live KrafConnect application will show their location to the users by implementing geolocation. Therefore, users can meet and chat with each other to exchange ideas or engage in buying and selling.

1.2.3	Challenges in finding local artisans capable of crafting customized products that align with customer designs.

Everyone has their own interests and tastes. If the product does not meet their expectations, people are less likely to buy it. Buying custom-designed products is what everyone likes. Every individual who participated in the interviews, totaling 15 participants, expressed their enthusiasm for the concept of designing a product tailored to their preferences and having it created and delivered exclusively for them (Zhao et al., 2019). To illustrate, consider someone who is searching for a wedding dress. Finding a dress that matches their taste can be quite challenging. Ordering a dress from a store that offers customization based on customer preferences is a good solution.

Providing custom services is a common practice in commerce. The concept of mass customization, which involves offering customized products at pricing comparable to mass production, has been a practiced strategy in commerce for more than two decades (Hara, 2019, as cited in Anderson, 1997; Pine, 1997). Customers can make requests based on their desired design. There are levels in mastering a skill such as beginner, intermediate and advanced. A beginner might have limitations in creating a handcrafted item. Since they are still learning, they are not experts in all required techniques yet. However, intermediate and advanced levels individuals might be able to create their own designs and something more complex since they have many experiences. The challenge lies in locating individuals who have expert skills in making customized designs of handicrafts, which will, in turn, attract users to buy handcrafted items from them.

Based on user recommendations on handicrafts type, the Live KrafConnect application addresses this challenge by identifying the location of local artisans nearby using geolocation and content-filtering, who offer custom design services for handicrafts. Thus, users will be able to purchase the designs of handcrafted items they genuinely adore.

### 1.3	Objective

a)	To develop and design a Live Krafconnect: The Handcrafted Community using Geolocation with Content Recommendations based on User Preferences.

b)	To Evaluate the Performance of Geolocation Technology in Finding the Nearest Service Based on User Content Recommendations.

### 1.4	Project Scope

1.4.1	Target user

This application's targeted user is a handicraft enthusiast. The purpose of this application is to unite the handicraft community. Below are the functions that will be implemented in the Live KrafConnect application.

1.4.2	Functionality 

1.4.2.1	User registration / Login system

Upon accessing the application, a user must register an account to use the platform. The registration requires the user to enter their username, email address and password. The password will be encrypted by the system for security measures. Users can also sign up for the application using Facebook and Instagram accounts. The user will stay logged in to the platform unless the user logs out.

1.4.2.2	Content Recommendation Algorithm

The contents that appear on the user’s page depend on the algorithm of the user’s recommendation. The time users spend, the likes and shares on a particular content will influence the content recommendation algorithm.

1.4.2.3	Content Creation and Sharing Tools

Users can post content related to handicrafts in any type of media as this application supports image, video and text abides by the rules. On the other side, other users can report on content that is considered inappropriate. Also, users are allowed to share content with other users or platforms. 
  
1.4.2.4	Search Functionality

Users can search for content in the search section and filter the results by the type of handicraft, level of skills and location.

1.4.2.5	 Geolocation Integration

The implementation of geolocation technology in this application is to help users in finding local artisans nearby and events that are happening in their area. The location of the user will be handled with care and respect the privacy.

1.4.2.6	 Live Stream

A live stream is a medium for users to have an interactive live craft demonstration, a collaborative session with other users or to teach about handicrafts. Users can schedule their live stream to accommodate their availability or to maximize their reach during peak viewing times.

1.4.3	Technique

1.4.3.1	Content-filtering

Based on the time users spend, like and share certain content, it will influence the other posts that will appear on users' pages. This technique enables the system to learn and adapt to users' preferences as they use the application.

1.4.4	Technology

1.4.4.1	Geofencing

Geofencing technology will define the district where the user lives. By then, all the locations of local artisans that reside in the same district will be shown to the user. Every time the user enters a new district, a notification will pop up, showing the number of local artisans available in that district.

### 1.5	Significance

These are the significance of the application.

1.5.1	A centralized platform for local artisans.

The development of this application can significantly offer great recognition to local artisans. It can increase the visibility of artisans to a larger audience. This platform provides a space for artisans to freely express their ideas and display their handicrafts. In addition, they can be inspired by others' works by engaging with other user content and live streams. Local artisans can also build networking among themselves through a project collaboration or learning phase. They can interact with each other in the chatting section.

1.5.2	Easier to locate the nearest local artisans.

Using geolocation to track the nearby local artisans can be more convenient for users as they can find local artisans easily. This application will pinpoint local artisans’ locations. The application will find the artisans that live near the user and provide detailed information on the location of the registered artisans. Users can meet with the artisans, and indirectly build a community of handicrafts in the area. Events, workshops and car boots can be held in the neighborhood area to give exposure to handicrafts to the people.

1.5.3	Provide the location of the nearest local artisan offering handcrafted services based on customer designs.

By filtering the location of local artisans based on the user’s preferences using a content filtering technique, the spot of the artisan that provides the custom-based service can be determined. This approach would help the increase of sales for the artisans as it is visible to the community. The system will analyze the nearby local artisans and determine the one that provides custom design services. Then, the system will filter it again by referring to the user's recommendation. 
