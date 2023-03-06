# Final Project Planning
**Xy Fang (xf48)**

>   Collaborator: Yuxiang Chen (yc825) & Yutong Zou (yz2664)



# 0 Where the interaction is happening

Are you struggling with insufficient batteries while working or relaxing outdoors? Have you ever forgotten your umbrella when you went out? Holding too much stuff in your hands and leaving no ways of holding an umbrella? Here’s the Umbrella Bot for help! The umbrella bot will come right at you and hold the umbrella for you when it is raining heavily. What’s more, the umbrella bot can charge your devices and hold your stuff for you anytime and anywhere.



## 1 Interactions

## 1.1 Detecting Bad Weather and Share Umbrella

The Umbrella Bot can automatically sense the rain and the intensity of sunlight with sensors. When the sensors in the umbrella bot detect a strong intensity of sunlight or rain, the bot will open an umbrella automatically with a motor. The height of the umbrella would automatically adjust according to people’s heights.

*   **Technical Feasibility**

    A rain drop sensor could be used to detect rain and a UV light sensor could be used to detect the intensity of sunlight. Since we have the camera module, we could use some CV algorithms to calculate the height of a person detected on the camera, thus adjusting the height of the umbrella.

## 1.2 Wave to Stop the Bot

The Umbrella bot will be equipped with cameras that can detect the gesture of waving hands. Once people around the bot wave their hands towards the bot, the umbrella bot will move towards the people making the gestures.

*   **Technical Feasibility**

    We could use the camera with CV algorithms (such as motion detection) to detect a person waving. However, there could be many noises since the interaction is happening in an open workspace with a lot of people in the same camera frame.

## 1.3 Automatic Following People

When the umbrella bot detects the need for an umbrella, it would follow the people as they walk. People could use the umbrella and charge their equipment at the same time while they’re walking somewhere else.

*   **Technical Feasibility**

    With the object detection algorithm, the bot could follow the person detected in the first place. However, since the person could be standing beside the bot which is out of the camera’s frame, we could either set multiple cameras at different positions of the bot, or we could use radar to assist with detecting people.

## 1.4 Charging Station

The umbrella bot could also charge people’s laptops, phones and watches in either wired or wireless way. Charging pad/station will be mounted on top of the wooden surface of the umbrella bot. When the umbrella bot is in need and follows along with the person requesting it, the person requesting it can put their electronic devices on the surface and have them charged.

*   **Technical Feasibility**

    We need a [portable power station](https://www.jackery.com/products/explorer-1000-portable-power-station?variant=31523358769239&currency=USD&utm_medium=product_sync&utm_source=google&utm_content=sag_organic&utm_campaign=sag_organic&gclid=CjwKCAiAu5agBhBzEiwAdiR5tOgm-jd9oz-Or3E19tRvG_rwVIMuRCaW15amcff2xt85saiZtrQ_0RoC58IQAvD_BwE) with enough capacity of power (say 1000Wh which could charge 100 phones) which supplies different types of output. Ideally, the portable power station could be recharged using solar panels.

## 1.5 A Stationary Platform

When the umbrella bot detects the need from people, a working station will be automatically expanded when the bot comes close to the people requesting it. The working station will consist of charging stations and an extensible flat surface that allows people to put their stuff on.

## 1.6 **[Optional] - Voice Interaction & Navigation**

An AI voice assistant (speaker) will be mounted on the umbrella bot. People can talk to the voice assistant for a variety of purposes such as getting voice navigation, getting latest weather updates, and etc. 



## 2 Prototyping

We plan to make a wooden (desktop-like) platform on top of the hoverboard. Besides the two main wheels of the hoverboard, we need extra auxiliary wheels to make the bot more stable. An umbrella with adjustable height would be placed at the center of the bot.



## 3 Interaction Sketches

![Page1.png](https://s2.loli.net/2023/03/07/zWwLTEF5m2HYJNQ.png)

![Page2.png](https://s2.loli.net/2023/03/07/PHGU7pKcEwCgYnJ.png)

![Page3.png](https://s2.loli.net/2023/03/07/HDQ9XP5eg1wvNGS.png)

![Page4.png](https://s2.loli.net/2023/03/07/ZRXo3KCDW7MOTkp.png)
