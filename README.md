# Guardians of the Globe

This is a web-application that allow you to manage your favorite heroes of the Guardians of the Globe crew.
The application consist in two submodules, one for the front-end which uses ReactJs with nextJS and an API written in Django with the REST framework.

The app seek to follow an understanding of both frameworks and some of the basic capabilities of them. For instance the handling of Server side rendering from next and other crucial advantages as well the easy and ready to follow API provide by the Django REST framework.

## How to install
You can go inside each module and clone the repositories, the steps to get started are indicated in each readme.

## App composition
* Authentication
* Heroes 
* Villains
* Sponsors
* Scheduler
* Fights

### What can we wait for?

### Authentication
The authentication uses the next-auth library. By using the next-auth library we setted up a middleware that allow us to protect all the pages from our application without the need of render anything until the user is logged in.

We also have three different methods to authenticate: Credentials, Google and Github.

In the case of Credentials the user would have to confirm their e-mail in order to be able to log in and also the user is able to change their password in case they need it as well.

### Heroes
The first entry page is the hero page. In the hero page we can find with the list of all of our heroes. We can see a brief description and also have different filters to order the list: name, age. 

We can click in a hero card and be able to see all of the information of a hero in particular. For instance a hero can have: multiple personal relationships, superpowers and be funded by different sponsors.

We can create a hero by clicking in the first card. To create a hero we need to give all of our hero details and once we are done, we can see our hero in our list right beside all of the rest of the crew.

### Villains
Villains in general have similar functionalities than our heroes. We can list to see them, create one, and eliminate as well. The main difference would be their characteristics/information.

### Sponsors
On the sponsors tab we can see the list of all of the sponsors. Those sponsors work with different heroes.

### Scheduler
The scheduler allow you to schedule the activities of every hero. You can choose any hero you want and assign the activities they need to do. You can add an activity for an entire day or with hours in specific.

By default you will see that some of our heroes are teenagers and they have different responsabilities than adult heroes. Finally, you can delete the events you desire as well.

### Fights
You can list the fights the heroes have had. Each fight has an id, a hero and the villain he/she fought against. You can delete the fight if you want too.





