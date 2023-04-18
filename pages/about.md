---
layout: page
title: Dorm Doors at IU
permalink: /about/
---

Our project focuses on the subject of dorm doors, specifically why students decide to decorate their dorm doors. We took pictures of different dorm door decorations we found around IU and interviewed some of the students whose doors were included. There were many different reasons for why a student decided to decorate their doors- some wanted to decorate to celebrate a specific holiday (i.e. hearts for Valentine’s Day) while others wanted to use it as a way to connect with people on their floor. Dorm door decorations give students a blank canvas to express and introduce themselves to a whole floor of people they may have never met before. For some, the way their dorm door is decorated may be a way for them to be recognized by others on their floor or even be an opportunity for conversation with someone new. Dorm door decorations attract the attention of everyone on the floor because these are decorations they walk past everyday when you walk down the halls.  Dorm doors have become an interesting topic of conversation that we wanted to explore more in our project. 

From the data collected, we found that the majority of people we observed decorated their doors with message boards and/or images. This shows that people use their dorm doors to show their interests with different images and connect with the community by writing on their message boards different surveys or updates on their life. Passersby can interact with doors by responding to surveys or writing their own messages for the door owner. We found through our interviews that students generally received the same message that the door owners were trying to send. 



**The skills needed to create Wax sites are agnostic.**  
This means they are largely transferable for use in other digital projects. 'Learning Wax' does not mean learning how to use a platform. It involves learning the fundamentals of web development, data management, and [plain text editing](https://zapier.com/blog/beginner-ultimate-guide-markdown/) while leveraging a few great open source libraries and frameworks along the way.

**However, Wax is also great for teaching or learning the skills above!** For examples of digital pedagogy via the creation of Wax exhibitions, check out [this workshop](https://studentcouncil.college.columbia.edu/events/introduction-minimal-computing-humanities-building-exhibit-primary-sources-using-wax), [this GitHub repository](https://github.com/stylerevolution/stylerevolution.github.io), and [this custom Wax site](https://stylerevolution.github.io/).

**Wax is also phenomenal for professionals who play a facilitating role**, such as Digital Scholarship Librarians or Coordinators. With some practice, Wax substantially reduces the time to production and post-production maintenance costs for you and your team. In the most common scenario, students, faculty, colleagues or any other collaborators just have to provide you with a properly formatted spreadsheet and the text for the exhibits. The extras are up to you.


## So what does the Wax workflow *look like?*

Below is a diagram to give you a zoomed-out view. In summary, you create a file of metadata records for your collection (in CSV, YAML, or JSON format), organize your collection image files, and put both in the Jekyll site folder. After updating your configuration, you run a few command line tasks to prepare the data and metadata for use by the Jekyll site. Jekyll then uses special layouts and Wax components to build the exhibit and spits them out as static pages ready to publish.

From there, you can run tests on your site to catch errors and decide where and how to put it online or in offline media.

<a href="{{ '/img/wax_workflow.jpg' | absolute_url }}">
  <img src="{{ '/img/wax_workflow.jpg' | absolute_url }}"/>
</a>
