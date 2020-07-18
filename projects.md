--- 
layout: page 
title: Projects 
---
## Projects Summary:

- [Locating Objects - Yr 3 Robotics](#robotics)
- [IoT Pillbox - Yr 3 Embedded Systems](#iot)
- [Interactive Class App - IC Hack 2020](#class)
- [Rash Identifier - Health Hack 2019](#rash)

---

<a name="robotics"></a>
### Locating Objects - Year 3 Robotics
<p>A group project to design and test a robot that must find a set number of objects. A map of the area is known but the robot does not know its starting position. Through the use of an ultrasound sensor and Monte Carlo Localisation, the robot probabilistically works out its location and navigates to make contact with the objects. The maximum distance to a wall was greater than the maximum distance the ultrasound sensor could read which was an interesting challenge to overcome.</p>
<div>
<img class="image" src="{{ site.url }}/{{ site.robotics }}" alt="Alt Text">
<figcaption class="caption">A perfectly engineered charging whilst testing solution!</figcaption>
</div>

---

<a name="iot"></a>
### IoT Pillbox  - Yr 3 Embedded Systems
<p>A smart pillbox designed to remind help the user take medication on time and request prescription refills when necessary. Built using time of flight and geomagnetic sensors. We hosted a database on Firebase and used an MQTT protocol to communicate with the device.</p>
<p>Link to <a href="https://ramon15749.wixsite.com/unodose">our website</a></p>

---

<a name="class"></a>
### Interactive Class App - IC Hack 2020
<p>Large classes can be stressful for students and teachers alike so we designed Class.io, an interactive teaching tool designed to enhance the classroom experience. The tool features live subtitles, average class sentiment and live simulations. We used a CISCO WebEx camera to do sentiment analysis and provide the teacher with feedback on the quality of their teaching. My main role was setting up the live transcript service which I did using Google's speech-to-tect API and TCP communication. </p>
<iframe width="560" height="310" src="https://youtu.be/BM4OZks_Q6E" frameborder="0" allowfullscreen></iframe>

<p>Link to <a href="https://devpost.com/software/class-io">Devpost</a></p>

---

<a name="rash"></a>
### Rash Identifier - Health Hack 2019
<p>We were inspired by the utility of non-invasive diagnostics to make this rash identifying app. It identifies if an input image is 1 of 4 skin conditions; Basal Cell Carcinoma, Dyshidrotic Eczema, Melanoma, Urticaria or normal skin. Due to the time and resource limited nature of a hackathon, we used transfer learning to train our model. This was my first experience with machine learning and I had a lot of fun learning how to use Tensorflow as well as create a frontend for the web app. </p>
<img class="image" src="{{ site.url }}/{{ site.rash }}" alt="Alt Text">
<figcaption class="caption">The result of a test input of Hives</figcaption>
<p>Link to <a href="https://devpost.com/software/rash-identifier">Devpost</a></p>