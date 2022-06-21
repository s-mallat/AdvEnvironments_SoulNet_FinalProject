<img width="1678" alt="Screenshot 2022-06-21 at 9 58 44 am" src="https://user-images.githubusercontent.com/92052904/174760594-ee183847-06c9-4f08-a2b6-41c5116f5a02.png">

# Creative Making: Advanced Visualisations <br> & Computational Environments

## SoulNet (Project Introduction)

SoulNet is an interactive installation created by **Adam Code, Alexandre Tarek,  Lea Ho, Lexin Zhou, Orsolya Szantho, Sali Mallat, and Sixiong Sheng.**  It is a critical exploration of the relationship between our engagement with virtual worlds and our physical freedom. The interactive installation stages a fictional demo set in the near future, asking us to consider which parts of our physical reality are we willing to give up in order to experience a promised virtual paradise.

## Disclaimer

This project was brought to life with the effort and hardwork of **seven** awesome people at CCI, UAL. This repository will include **only the write up of my contribution in this project and personal documentation of the process.** The code and project files are not included in this repo, but I have attached a link below to the repo that contains all the code and project files for a holistic view of every member's efforts to bring this project to life.

---

# Link To Code Repository: <br> https://github.com/adamdavidcole/unreal-free-float-game
## The above link contains all the unreal files, arduino and processing code.

---
# Link to Video Documentation: <br> https://www.youtube.com/watch?v=XkymM3IcORg

---

## My Contribution & Write-up

For the final iteration of this installation, I was involved in both the physical and the virtual development. To start with the unreal part of the project, I was responsible for creating the graphics and overall design of the game. I created the materials, particle systems, modeled the game objects and animated them on Blender. The challenge of creating the graphics and effects was achieving a design that is impressive enough to keep the user engaged, even addicted to the gameplay. The user engagement was a very important factor through out the decision making process of putting the graphics together and what kind of mood and vibe the game communicated. This is because the installation forces users to position themselves in awkward and uncomfortable body positions to play and interact with the virtual game. Therefore, the actual gameplay needed to be powerful and smooth to keep them playing and engaged. In other words, it was a situation of whether or not the user is willing to give up comfort to keep playing and make more pretty graphics. From the response we had at the show, the answer is yes, most people are more than willing to give up comfort and restrain their movements to keep exploring the virtual world. 

<img width="1565" alt="Screenshot 2022-06-21 at 12 53 47 pm" src="https://user-images.githubusercontent.com/92052904/174793050-60299211-a99a-43e9-ad76-987d8d14c3d7.png">

As our game had only one camera angle / perspective, I wanted to add a layer dimensionality to an otherwise flat two-dimensional world. To delve slightly deeper into the technical side of things, I would say the biggest game changer for the graphics of the game was the introduction of the dynamic trail or the dynamic ribbon system. Through various iterations and after numerous tutorials on particle systems, creating and merging materials, I was able to create dynamic materials that animate overtime to avoid a static and flat look. The trail is an example of that dimensionality and dynamic design as it is constantly shifting, animating, and gracefully flowing around the space the longer the user engages with the installation. 

<img width="1741" alt="Screenshot 2022-06-21 at 12 55 26 pm" src="https://user-images.githubusercontent.com/92052904/174793451-44e97401-7c14-4c90-8efb-3abc0cca33f1.png">

<img width="1735" alt="Screenshot 2022-06-21 at 12 55 36 pm" src="https://user-images.githubusercontent.com/92052904/174793465-671bdfd7-f6c1-4446-b8fe-bf0c71dfd752.png">

<img width="1752" alt="Screenshot 2022-06-21 at 12 55 47 pm" src="https://user-images.githubusercontent.com/92052904/174793474-351d442f-4cc3-407c-ab83-fcaae919bbe3.png">

![Screenshot 2022-06-21 at 12 55 09 pm](https://user-images.githubusercontent.com/92052904/174793676-4039077a-27c4-4ac8-b4c4-295d10bad6ef.png)


The creation of all materials and particle systems consisted of a rigirous process of layering different textures, materials on top of other materials, and merging multiple particle systems to create the effects needed. The challenge in this part was twofolds, the first was the memory issues and making sure that the overall project files don't exceed a certain size since this is a multi-faceded project with many layers. This was an issue for us mostly because all team members owned a macbook with exception to one person who operated a windows machine. Furthermore, the memory restraint affected my decisions on what kind of game objects to model, how many faces and vertices they have and how to best animate them in Blender. The second challenge was getting the files to load and compile correctly on different machines. I originally used many materials from the epic games marketplace but quickly had to remove all of them and replace them with starter content textures and build my own materials on top of them to make the migration process smoother and avoid running into issues later on.

(Image of particle system, material blueprints)

Moving on to the physical part of the installation, I was responsible for designing and building the hand stations, as well as designing the structure of the wiring from laptop and projector to six different stations. The overall design of the stations went through different iteratives stages while building upon the idea of affordances and the relationship between the stations and the users, as well as how effective the physical design is at communicating the project goals. The elements of the stations were created using plywood carved out using the laser cutter and the hemispheres created through 3D printing. The decision to make the stations close to the group in terms of height was made for conceptual and practical reasons. I envisioned the stations as flexible pieces that we can easily move around to accommodate the small space at the show, and with the limited budget and resources we had, the decision to make short stations was a more logical one and added more to the conceptual aspect of giving up comfort for virtual exploration. The simple choice of making shorter stations is one example of many of the thought process behind the design. This is because we needed the users to understand that these are hand stations not foot station for instance. Therefore we added five different touch points instead of a singular big one inside the hemispheres to lead the user to bend over and use their hands to activate the installation. Creating the stations made me think and appreciate the effort that goes into creating so many cool gadgets around us where we don't even see the inner workings or wiring. Lastly, the conceptual storyline for the project needed to be narrated in element of the project from the virtual to the physical part. Therefore, the endresult is sleek futuristic design that affords the user to position themselves awkwardly to gain access to the virtual promise of immersion and freedom.
