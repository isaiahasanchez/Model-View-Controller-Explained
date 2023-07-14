# Model-View-Controller Explained
By Isaiah Sanchez

This article serves to explain the MVC in a beginner friendly manner and uses Game of Thrones as an analogy to hopefully help make it more clear.


![MVC](https://github.com/isaiahasanchez/Model-View-Controller-Explained/assets/124002003/a72fb0fc-d65b-4701-b31f-889c11342740)



Now lets talk about each component. 

![2](https://github.com/isaiahasanchez/Understanding-Model-View-Controller-Framework/assets/124002003/de30ee6d-514d-4117-9960-27bf8a45a140)

The Model is the portion of the system that is responsible for getting and manipulating the data, and logic of the application. It interacts directly with the data base. The model gets its request from the controller, parses that info and uses that request to search the database for the information it needs. It then speaks back to the controller the data requested.

![3](https://github.com/isaiahasanchez/Understanding-Model-View-Controller-Framework/assets/124002003/02dea77a-3369-4d74-b7a8-0f9214603b8c)

The View deals with the UI which is what the user sees on their end. Typically view will also gets the request from the controller for what and how to present the data and its the views responsibility to parse that request and generate the template for what the user will eventually see on the browser. This is typically in the form of HTML/CSS or whatever Template Engine is being used like handlebars, Jinja, Pug, EJS etc. 

![4](https://github.com/isaiahasanchez/Understanding-Model-View-Controller-Framework/assets/124002003/9d4b0a59-69ee-41a5-a402-d56b5633b6bd)

The Controller is the part of the system that is essentially the brains or director of it all. The Controller is responsible for taking in and processing what the user requested and then passing on the appropriate request to the model and view acting as an intermediary between the two. Typically the Controller does not interact with the database itself but rather delegates the orders to the model and receives the data request back. The controller then interacts with the view to render the final presentation.

![5](https://github.com/isaiahasanchez/Understanding-Model-View-Controller-Framework/assets/124002003/f7752558-5f7a-47bd-bbb3-45b400c32f6b)

Bonus Portion: The Router may play a part in certain MVC systems by handling the routing and directing of requests to the appropriate controller. It acts as a traffic controller, receiving incoming requests and determining which controller should handle them. The router ensures that each request is routed to the correct controller based on predefined routes and URLs.


![6](https://github.com/isaiahasanchez/Understanding-Model-View-Controller-Framework/assets/124002003/31326048-5f0a-4291-a591-1078a2975d4b)


It is needed as a way to organize the interactions between the user, server and database so that system processes can be completed in an organized and streamlined manner. Benefits include code reusability, allows test driven development and full control over HTML and URLs. Overall, it also allows code at a bigger scale to be worked on by multiple developers without breaking or blocking one another’s work. 

There are other approaches as well including MVVM, HMVC, and MVP but MVC is one of the most popular

Some examples of frameworks that can utilize the MVC include:

Ruby on Rails, Django, Codeigniter, Laravel, Express, Angular and Zend.





![7](https://github.com/isaiahasanchez/Understanding-Model-View-Controller-Framework/assets/124002003/976428d0-33c7-4d6e-9118-e4869c909f73)

![8](https://github.com/isaiahasanchez/Understanding-Model-View-Controller-Framework/assets/124002003/d746ba7e-70e3-403b-81fb-29e9d67a5538)

![9](https://github.com/isaiahasanchez/Understanding-Model-View-Controller-Framework/assets/124002003/b8f33032-5262-4da2-a7dd-4018b0082e36)

![10](https://github.com/isaiahasanchez/Understanding-Model-View-Controller-Framework/assets/124002003/463affbb-2f94-43bb-9f3f-5f5efca5518c)

![11](https://github.com/isaiahasanchez/Understanding-Model-View-Controller-Framework/assets/124002003/73198c20-a54f-4a30-b129-fbbe319a4ba1)

________________________________________________________________________________________________________________________________________________

OK Now lets end it with a little analogy to give you another way to conceptualize this system.

We are in the world of Game of Thrones, a fantasy world with medieval-type characters. 

![12](https://github.com/isaiahasanchez/Understanding-Model-View-Controller-Framework/assets/124002003/c50f8114-4c30-47da-963b-743aca925ebc)


Therefore, he makes his requests to his workers beneath him, and they fetch him any stories or knowledge he wants. Today, he wants to learn everything there is to know about the history of Large Blue Dragons. So, here's how it goes.


![13](https://github.com/isaiahasanchez/Understanding-Model-View-Controller-Framework/assets/124002003/dad847f0-260d-44f1-972a-75f76a399c8c)

His job is to run to a room in the castle called the Controller room, filled with many workers who all go by the title Castle Controller.

![14](https://github.com/isaiahasanchez/Understanding-Model-View-Controller-Framework/assets/124002003/7241d6aa-8292-4152-a281-9fdba2d7589e)

Each Castle Controller specializes in understanding exactly what the king writes on his notes (especially since the king has terrible penmanship and grammar). Any info that the king needs always comes through the Castle Controllers (some people say the Castle Controllers are the real leaders of the castle, but don't tell the king that).

Once the Castle Controller has figured out exactly what the king wants, he goes into the next part of the castle called the Model Room. 

![15](https://github.com/isaiahasanchez/Understanding-Model-View-Controller-Framework/assets/124002003/42316e6c-e1c3-4bb7-935c-e8ec0869c1c8)

The Castle Controller would do it himself, but he's a better leader than a reader. The Bookworm Model searches all the books for the info that was requested.
![16](https://github.com/isaiahasanchez/Understanding-Model-View-Controller-Framework/assets/124002003/06e34e57-d0a6-40bd-a71d-2aa63b8bd385)

The process is over right? Not quite. The Castle Controller can't give the boring scribbled scroll to King User. King User would fall asleep trying to read that.

![17](https://github.com/isaiahasanchez/Understanding-Model-View-Controller-Framework/assets/124002003/caa1351a-366a-4634-a0ab-ec5249c5078c)

Once again, the Castle Controller would do it himself, but he was never a good artist growing up. 

![18](https://github.com/isaiahasanchez/Understanding-Model-View-Controller-Framework/assets/124002003/5eadb528-f65d-4852-a99b-9c09211342a7)


Hopefully this story and article provided a fun way to understand the MVC. Thanks and happy coding!
