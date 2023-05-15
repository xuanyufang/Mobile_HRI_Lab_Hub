# Umbrella Bot Final Report 

**Xy Fang (xf48)**

>   Collaborator: Yuxiang Chen (yc825) & Yutong Zou (yz2664)


## 0. Idea Development
We started this project with the idea that we could make the umbrella move. Nearly everyone had the experience of walking in the rain, holding an umbrella with one hand, and finding it difficult to hold other stuff. Therefore, we developed the idea that we could make the umbrella automatically follow people and shelter them while they’re walking. Our original idea also includes a mobile working station that’s installed beneath the umbrella, which allows people to work outdoors regardless of the weather. People could also use the workstation protected by the umbrella to charge their electronic devices. However, we have given up on the workstation part due to time and prototyping issues which will be explained in detail in Section 1.


## 1. Prototyping

*  Cardboard


We first started with a cardboard prototype just to see whether it would move. The good news is, it does, the bad news is, not for long:

[![BalletBot](https://github.com/xuanyufang/Mobile_HRI_Lab_Hub/assets/42874337/e757b0fb-856e-4474-87ca-d3cb766eeeb9)](https://www.youtube.com/watch?v=AvoLztTPKl8)


* Wood + Acrylic


After a couple of cardboard prototypes, we transit to actually make this robot happens. Recognizing the difficulties of supporting a tall structure of an umbrella, we have planned to use the thick wooden board to build a steady base. We started with laser cutting & hand sawing most of the wood structures and then used wood glue and zip ties to build a four supporting-wheel base. 

![image](https://github.com/xuanyufang/Mobile_HRI_Lab_Hub/assets/42874337/4f035c09-a779-4111-9712-a15ad68715c6)

We have tested different versions of how we arrange all the electronics to control the hoverboard, and settled down with an acrylic board with a layout to balance the weight on top:

![image](https://github.com/xuanyufang/Mobile_HRI_Lab_Hub/assets/42874337/3dfc17d6-3b11-4ade-a384-6a374141f045)

For supporting the umbrella structure, we first tested a cardboard pillar, which was tested to be unstable when it’s attached to the base. So we eventually transfer to a tripod, which has a separate design of support wheels of its own (3) and will be able to stand on its own and detach from the base of the hoverboard.

![image](https://github.com/xuanyufang/Mobile_HRI_Lab_Hub/assets/42874337/9e07feb5-750e-4727-9570-daf88599e957)
![image](https://github.com/xuanyufang/Mobile_HRI_Lab_Hub/assets/42874337/0353eee1-f693-473f-b16d-e720275b52cb)

* Difficulties


Our major challenges mainly lie in how to support the umbrella structure. We have created attachment structures from all three angles for the tripod, and use 7 driven wheels to balance the motion.
In order to improve the interaction between the robot and users, we have also considered a number of scenarios that might be facing, for example, on a rainy day, it might need to cover up all the electronic parts. We have also considered how to replace and recharge all the batteries. 

## 2. Design and Features
### 2.1 Final Design
Our final design includes a clear and steady base and an adjustable umbrella.
![image](https://github.com/xuanyufang/Mobile_HRI_Lab_Hub/assets/42874337/794beb95-16e9-4747-b974-4bf226dc5aab)
![image](https://github.com/xuanyufang/Mobile_HRI_Lab_Hub/assets/42874337/c5a0feae-0b6f-4916-bac5-657432d93a20)

* Steady Base

![image](https://github.com/xuanyufang/Mobile_HRI_Lab_Hub/assets/42874337/44ab937c-4d3d-47a0-83c7-b4479615e173)

We have used multiple omni wheels to steady the movements of the hoverboard. With two wooden sticks installed on both sides of the hoverboard, we wouldn’t have to worry about the Umbotella would crash into pieces when running on a rough road.

* Clear Acrylic Cover

![image](https://github.com/xuanyufang/Mobile_HRI_Lab_Hub/assets/42874337/ab907d40-c73e-469a-bb8a-eae743d70d52)

We have made a clear acrylic cover placed on the hoverboard. One important function of the acrylic cover is that it can protect the electronic parts from the rain since we’re operating Umbotella outdoors. Also, we can see through the cover to monitor the status of the electronic parts such as the ip address of the RPi and the power status of the power bank without removing anything.


Not only we as the bot controllers could see through the cover, but also users could notice that there are electronic devices inside the moving umbrella. We made all the electronic parts visible to people in order to observe how people would react to a robot-like object.

* Adjustable Umbrella


The height of the umbrella is also adjustable, which was installed on a tripod.
![unnamed](https://github.com/xuanyufang/Mobile_HRI_Lab_Hub/assets/42874337/1ad9d0a6-1902-4cc8-aec7-650374252c4b)

### 2.2 Modularized Parts

One of the most unique features of Umbotella is that all the parts on the bot are modularized which can be easily removed and replaced. All the parts are attached to the bot base with magic tape so they’re strongly adhesive while easily removable.

* Take off the cover

The acrylic cover could be taken off at any time to switch the electronic parts on the hoverboard. It would also be much easier to plug in the ODrive power and the RPi power with the cover removed.

![unnamed (1)](https://github.com/xuanyufang/Mobile_HRI_Lab_Hub/assets/42874337/e7ecddb3-9c5d-407d-a9bb-6520cfda0996)

* Replace the portable charger

The portable charger could also be taken off and switched to a new one if the original charger ran out of power.

![unnamed (2)](https://github.com/xuanyufang/Mobile_HRI_Lab_Hub/assets/42874337/eef9e0f1-5f20-494c-af62-6110287d3b10)

* Recharge the power bank

Similarly, the power bank could also be taken off anytime to be recharged.

![unnamed (3)](https://github.com/xuanyufang/Mobile_HRI_Lab_Hub/assets/42874337/ddd73e80-4319-4524-8ffb-40f29db411f4)

## 3. Intended Interactions and Settings

### 3.1 Possible Features

We first designed some features and use cases the umbrella bot could have:

1. Shelter people over different weather conditions

Since it’s an umbrella bot, its main purpose would be sheltering people during the rainy days. In this scenario, the Umbotella would follow people to their destination while staying close to them so that it could shelter them from the rain. In other scenarios like cloudless sunny days, it can also be used to shade the sunlight from people when they are using electronic devices or looking at screens outside.

2. Guide people to their destinations within a short distance

We have also designed the robot to be able to guide people to navigate to a certain place that is set by the users. It serves as navigation at the same time as sheltering people from weather conditions. Users are also allowed to lead the way and the robot will automatically follow them to wherever they are going for maximum flexibility. 

3. Bring people joy by being a fun robot around the neighborhood

As a robot that serves within a specific community area, it’s also carrying the responsibility to entertain people around the neighborhood and on the street. We designed it will be able to communicate with users, chat when them, and play music for them in a highly autonomous way.

### 3.2 Designed Interactions

Based on these possible features, we have designed some interaction scenes that might happen.

*Interaction Settings*

- Robot speed

The default settings of the speed of the robot are too fast in our interaction settings. We have modified the code to change its speed as well as moving directions.
[code]

- Voice

Since we need the robot to interact with people, we wanted it to be more human-like and autonomous. We have designed a few sentences for the bot and planned possible scenes that the bot could encounter. In particular, we chose a female voice with a British accent to make the robot sound less intimidating as well as more professional. We generated the voices using Murf.

Based on the intended use cases and voices, we have designed the following possible interactions:

1. Greeting to people when wandering around the neighborhood

The bot would say “Hello there! I'm umbrella bot. I’ll be around whenever you need me”. In this case, the bot intends to tell people that it’s constantly showing up around the neighborhood and to remind people that they could use this umbrella bot on rainy days.

2. Asking people if they need and umbrella

The bot would ask “Hi! Do you need an umbrella?” The answer depends on how people respond.

Positive answer: The bot would randomly give one of the two responses “No problem! Happy to do that!” and “Sure! I’ll follow you!” If people start to walk towards the destination, the bot would follow them. After the ride, the bot would say “Thanks for riding with me! Please give me a five-star on google review.”

Negative answer: The bot would respond “Bye bye! I’ll see you around!” and then move away.

3. Avoiding passers-by when moving

In this case, the bot would just stop and wait for people to pass by.

4. Entertaining people

The bot would just move to people and ask “Do you want some music?” With a positive answer, the bot would start to play music. After the music ends, the bot would say “Thank you so much! Bye bye! I’ll see you around!” and then move away.

[Interaction Storyboards]

## 4 Interaction Observations

After carefully planning out the possible interaction scenarios, we take out Umbotella to the field within the Cornell Tech campus and give it a test interaction publicly. Here’s a video capturing all the important interaction we designed and executed during the field trip, as well as important moment that was captured among the people interacting with it. 

[![Final Interaction](https://github.com/xuanyufang/Mobile_HRI_Lab_Hub/assets/42874337/d1a53bb0-c131-40f5-bea9-bc20afcbe9f8)]([https://www.youtube.com/watch?v=AvoLztTPKl8](https://www.youtube.com/watch?v=5NJEbth1VVE))

We have identified a number of things during the interaction in the wild. First of all, people have expressed different feelings and attitudes towards the umbrella bot as shown below. 
People have laughed at it, curious about it, ignored it, and frightened of it.

![unnamed (7)](https://github.com/xuanyufang/Mobile_HRI_Lab_Hub/assets/42874337/c62aab20-93d4-4dda-ac2d-fbdf2d972eea)
![unnamed (6)](https://github.com/xuanyufang/Mobile_HRI_Lab_Hub/assets/42874337/39200c6d-2d79-4c18-aae6-48d350bf4bed)
![unnamed (5)](https://github.com/xuanyufang/Mobile_HRI_Lab_Hub/assets/42874337/b4f57fd1-eef8-47f1-9145-6a8b7d50b511)
![unnamed (4)](https://github.com/xuanyufang/Mobile_HRI_Lab_Hub/assets/42874337/b1fd2e56-cdc5-4fe1-9d1b-e6a6b1a0410d)

We have mainly tested out the interaction with three groups of people who’s never seen the robot before. All users are sitting at the cafe area at Cornell Tech campus, and are all passengers who are not Cornell Tech affiliated. Aside from the technical problems we detected during the robot in the field like not large enough umbrella and not high enough base to avoid obstacles, we have also identified a number of problems in our interactions with people. 

First of all, most people showed confusion before the umbrella bot approached and don’t really know about its purpose. Only after it introduced itself that people would be able to correctly respond to it or treat it as its designed purpose. 
Another important interaction we have found is people are somewhat reluctant to get into the umbrella even if it’s sitting still on the ground. We have inquired a number of participants and they reported an unknown feeling upon entering the shaded area because they don’t know when it’s going to move around or where it’s going. This caused a rather far away distance most people kept from the umbrella, which was against its design at the beginning. 

One most interesting interaction we noticed was even if people answered yes when they were asked whether they’d need an umbrella, people rarely move on their own, but wait for the next cue given by the robot to do anything. This reflects the unfamiliarity of the users with the procedure of the robot, and in future designs might need more visual and voice cues to indicate what the users should do in order to better use the robot.


## 5 Reflections

### Hardware Improvements: 
Our testing phase has brought to light several areas for hardware improvement for our umbrella bot:

- Heat Management: During operation, the Raspberry Pi controlling the bot has shown tendencies to overheat, which can lead to decreased performance and elevated battery usage. A heat dissipation mechanism, such as heat sinks or fans, could be implemented to alleviate this issue, or the casing design could be improved for better thermal management.

- Wind Resistance and Stability: The bot has faced challenges in maintaining stability, especially when the umbrella was at its highest position during windy conditions. A lower center of gravity, a wider base, or a wind-resistant umbrella design could help improve stability in such situations.

- Umbrella Size and Positioning: The current size of the umbrella is inadequate to fully cover users during rainy conditions. Increasing the size of the umbrella or incorporating an adjustable design could enhance the bot's ability to provide shelter. Furthermore, the position and movement of the umbrella require improvements. The umbrella should adjust its position dynamically based on the user's movements and the wind's direction for optimal coverage.

- Mechanical Durability: Since our bot is intended for outdoor use in various weather conditions, enhancing the durability of mechanical parts like wheels and the umbrella lifting mechanism is crucial. Consideration of rust-resistant and wear-resistant materials could lead to a more robust design that can withstand different environments and prolonged use.


### User Interaction Improvements: 
Our interactions with users highlighted several areas for improvement:

- Intuitive Interaction: Users were often initially confused about the bot's purpose. Improving the bot's introduction or adding clear visual cues could make its purpose immediately clear to users.

- User Comfort: Some users were hesitant to enter the bot's shaded area due to uncertainty about its movements. To make users more comfortable, the bot's movements should be made smoother and more predictable.

- Guidance for Users: Users frequently waited for further cues from the bot after accepting its offer of assistance. More explicit visual or auditory cues could be designed to guide users through their interaction with the bot.

### Future Studies: 
Several directions for future research on the umbrella bot are apparent:
* User Study: A more extensive user study could help us better understand user needs and preferences, guiding improvements in design and interaction.
* AI Integration: Incorporating advanced AI algorithms could improve the bot's autonomous navigation and decision-making capabilities, including object detection and avoidance, route planning, and user behavior prediction.
* Weather Resistance: Research into materials and designs that offer greater resistance to various weather conditions could help improve the bot's durability and effectiveness.

### Learnings from Interactions 
Through our interactions, we've gained valuable insights into how people perceive and interact with our bot. People are generally amicable towards robots and willing to engage with them. They could intuit the bot's purpose without much instruction and often chose to respond to the bot using voice commands. However, we also learned that people are more comfortable interacting with the bot when its movements and intentions are clear and predictable. These insights will shape our future improvements in both hardware design and interaction design.


