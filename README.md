# project-blue-moon
This educational article provides a description of what a face recognition software does, how deployment of such systems are misused or abused by policing agencies and what can we as ordinary persons do to guard ourselves from the rampant abuse of face recognition systems.

## Identification vs. Recognition
In computer science, automated identification of an object using signal detection techniques typically means that the generic category of that object can be unambiguously recorded *across* a finite number of well defined categories. 

For example, the Not Hotdog app identifies (distinguishes) an image of a hotdog from a given set of images. 

<p align="center">
  <img width="69%" src="https://cdn.vox-cdn.com/thumbor/YhNlzjfQltWz_h1qZZMGQFARyZ0=/0x0:846x730/1400x933/filters:focal(356x298:490x432):no_upscale()/cdn.vox-cdn.com/uploads/chorus_image/image/55453471/not_hot_dog_app.0.png"></img>
</p>
<p align="center">
  Identifying presence of a hotdog in a given image using machine learning
</p>

However, the term "recognition" typically means that a unique instance of an object *within* a category can be unambiguously recorded and distinguished from other similar objects in the given category. From an information theoretic perspective, recognition can be thought of as identification followed by indexed tracking of a particular signal against a plethora of background signals. 

If we consider the object or signal to be the face of a person we can first try to identify various features in an image that constitute a human face. And then record that identified face in a database along with a unique name or ID so that it can be tracked in a room or even outdoors on the street among various other faces.

<p align="center">
  <img width="69%" src="https://www.pymnts.com/wp-content/uploads/2019/10/facial-recognition.jpg"></img>
</p>
<p align="center">
  Recognizing a face in a given image using machine learning
</p>

Comparing an identified face with a database of faces in order to recognize its unique ID or assigning it a new one is a computational challenge that is prone to many sources of errors. But more important than the technical errors are the issues of using surveillance systems where an agency can sabotage the economic and social opportunities of a person or a group of persons in a very targeted and covert way.

To get a more tangible idea of which type of surveillance techniques are currently deployed in the US with little to no concern for their ethical use, please see: [EFF Atlas of Surveillance](https://atlasofsurveillance.org/)

## Systematized prejudice and surveillance systems
Let us look at the political dynamics and power play between an enforcement agency that hordes tax-payer money and resource-poor private individuals who get surveilled. Coincidentally, the ones getting spied on are the ones paying taxes.

There is usually no human being acting as "Big Brother" who is actually viewing any of the footage from the countless surveillance equipment deployed in a city. The task of singling out a trouble maker is programmed into a software. The software program is deliberately trained and biased towards judging people of colour as more likely to be "troublesome." The simple causal factor in this industrial arrangement of surveillance equipment throughout a city is that the people who build it or buy it are never the poorer and oppressed sections of society. Instead, they are always the more affluent and dominating imperialists and colonialists within seats of authority among municipalities, state or provincial governments and federal governments.  

The interests and motivations of such imperialists and colonialists are simple: track and thwart any dissent or uprising that would expose or otherwise diminish their control over usurped natural resources. Doing so necessarily requires that any human individual who has a dissenting view is swiftly tracked and "put back into their place as an obedient slave or serf."

The standard promise made by companies that prop up a despot or monarch for their personal greed is to continuously track every individual "possession" within a monarch's "dominion" in real-time so that credence from that subject can be extracted by forced assimilation, destruction of alternative free choices, threats and by guile.

If the above statement seems too broad and generalized with a negatively charged premise, just ask yourself, "Which of the richest companies or corporations in the world are actually **not** interested in exploiting human and natural resources to the **maximum extent** of annihilation?" None of them, absolutely none of them!

This is why, as private individuals we must act in accordance to our necessity for self-preservation and exercise our right to protection from exploitation!

## Implementation
So how can resource poor serfs and slaves rescue their dignity and basic human rights from being pillaged and plundered by cronies of a monarchy? Especially from an imperialist regime that seemingly has unlimited zeal, opportunity and resources to oppress world citizens? 

We start with a declaration of freedom from the very concepts of imperialism and colonialism!

Next, we make sure that the faults of acoustic and opto-electronic surveillance systems are addressed in order to protect the fundamental human rights, cultural heritage and innocence of all peoples: 

1. Faults in the business model of surveillance companies: Companies like FLIR and MioVision supply opto-electronic equipment to municipalities and states. Such companies often push the incentive that the cost of such equipment can be paid off at a future period of time from the earnings generated by "tickets" or "penalties" issued against trouble makers caught using the systems supplied by their company. This business model front-loads or primes authorities and enforcement agencies to fill up monthly quotas by fishing or snaring as many people as possible using as minuscule a reason as possible to reach a financial break-even point as soon as possible. And then following that, to start generating "profits" for the city or state from such penalty fees and tickets. This is a very bad and predatory business model that has been culturally normalized among industrialized nations and city-states over the past decade.

    - Having appropriate legislative action to prevent such systemic misuse and abuse of surveillance equipment for profiteering is necessary but quite the long shot. The more immediate method is to notify the employees and investors of such companies that their methods of "creative destruction" in disrupting the surveillance market is also unapologetically destroying basic legal tenants like *public accountability and transparency* within business dealings of government entities. 
    
    - Black-boxed and close-sourced artificial intelligence (AI) algorithms destroy human rights like the right of information to the mechanisms and procedures that issue a warrant, ticket or penalty against a surveilled person. Bringing this issue directly to promoters, proprietors and propagators of surveillance based businesses like Google and Amazon is essential. To appropriately regulate such corporations with fairness, framing and administering ISO standards for business and technical practices involving any machine learning (ML) or AI components is paramount. Corporations not adhering to such standards would undoubtedly risk the health and safety of human beings and our ecology.
    
1. Bias in training algorithms of surveillance equipment: Practically every image processing algorithm takes cues from or directly uses the cascade boosting algorithm described in [Viola Jones Detection Framework](https://en.wikipedia.org/wiki/Viola%E2%80%93Jones_object_detection_framework). Such a boosted algorithm and even other advanced generative techniques require labeled sample data as a starting step in image processing pipelines. Any labeling method naturally introduces the social and psychological biases of the persons preparing the sample data. Features of culturally diverse groups of people with wider range of demographics were not used in the earliest training algorithms of IBM, Google, Amazon, Microsoft and private vendors, especially not the ones contracted by [DARPA](https://www.darpa.mil/work-with-us/ai-next-campaign). Billions of dollars have been spent on creating manecured data sets for training and testing such algorithms. Interestingly, these algorithms can be defeated with a face covering or mask worth just a few dollars. 

    - Even andvanced learning algorithms cannot find a face to track once the face is covered with a mask and sun glasses. So surveillance companies have moved onto aggregate techniques. These techniques involve improving the probability of recognizing and tracking an individual based on the statistical overlap between snooped data about the person's: 
      - home or business address
      - body and gait (2D images, video and 3D point cloud from LiDAR and other moving equipment capable of producing a "sythetic aperture")
      - associates, friends and family
      - MAC address of routers, modems, computers, laptops, tablets, phones, etc. 
      - browser user agent profile
      - typical movement between physical locations within a geography
      - behavioral patterns while browsing online websites
      - voice and background sounds obtained from acoustic surveillance
      - passive or active electronic tags on clothing articles, artifacts, etc. 
      - financial details of bank accounts, credit and debit cards, online wallets, etc.
      - medical history and healtcare details 
      
  - Use of such statistically aggregated methods violate every legal statute concerning personal privacy, security and secracy. Particularly the combination of acustic and electromagnetic methods produces a spying tool that is as invasive as a secret service agent being physically attached to your hip at all times! Protection from such combined methods of surveillance to prevent business, industrial and military espionage requires stronger legislative action. Too bad most people incharge of making legislature aren't awere of the nuances, implications and ramifications of such things. 

  So, let's port all legislative statutes and procedures onto github or gitlab in order to improve their efficiency using crowd-sourced, continuous improvement and continuous deployment of legal frameworks ;)     

<p align="center">
  <img width="69%" src="https://sidlaurea.files.wordpress.com/2014/01/multi-cultural-face-blog.jpg"></img>
</p>
<p align="center">
  Types of facial features that are usually absent in free and commercial face recognition training sets
</p>

### Note 
Imagine a sythetic aperture based surveillance technique that uses a botnet of mesh networked mobile phones! For an inspiring seed to such a system checkout: M. C. Hemmsen et al., "Implementation of synthetic aperture imaging on a hand-held device," 2014 IEEE International Ultrasonics Symposium, Chicago, IL, 2014, pp. 2177-2180, doi: 10.1109/ULTSYM.2014.0542. https://ieeexplore.ieee.org/document/6931958 

A counter surveillance method interfering with such a synthetic aperture based system would also, most probably, require a botnet of mesh networked mobile devices. 

<p align="center">
  <img width="69%" src="hi.gif"></img>
</p>

<br><br>

## Do consider supporting this author
* * *
<p align="center">
<b>Please support my cause towards justice for ethnic minorities, migrants and refugees through your kind donations</b>
</p>

<p align="center">
<a href="https://liberapay.com/sameer-khan/donate"><img alt="Donate using Liberapay" src="https://liberapay.com/assets/widgets/donate.svg"></a>
</p>

* * *
