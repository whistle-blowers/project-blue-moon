# project-blue-moon
This article provides a description of how a generic face recognition software works, how some implementations of such software are misused or abused by certain organizations and what can we as ordinary persons do to guard ourselves from the reampant abuse of face recognition software by policing agencies and other organizations.

## Identification vs Recognition
In computer science, automated identification of an object using signal detection techniques typically means that the generic category of that object can be unambiguously recorded *across* a finite number of well defined categories. 

For example, the "not hotdog app" distinguishes an image of a hotdog from a given set of images. 

<p align="center">
  <img width="69%" src="https://cdn.vox-cdn.com/thumbor/YhNlzjfQltWz_h1qZZMGQFARyZ0=/0x0:846x730/1400x933/filters:focal(356x298:490x432):no_upscale()/cdn.vox-cdn.com/uploads/chorus_image/image/55453471/not_hot_dog_app.0.png"></img>
</p>
<p align="center">
  Identifying presence of a hotdog in a given image using machine learning
</p>

However, the term "recognition" typically means that a unique instance of an object *within* a category can be unambiguously recorded and distinguished from other similar objects in the given category. From an information theoretic perspective, recognition can be thought of as identification followed by indexed tracking of a particular signal against a plathora of background signals. 

If we consider the object or signal to be the face of a person we can first try to identify various features in an image that constitute a human face. And then record that identified face in a database along with a unique name or ID so that it can be tracked in a room or even outdoors on the street among various other faces.

<p align="center">
  <img width="69%" src="https://www.pymnts.com/wp-content/uploads/2019/10/facial-recognition.jpg"></img>
</p>
<p align="center">
  Recognizing a face in a given image using machine learning
</p>

Comparing an identfied face with a database of faces in order to recognize its unique ID or assigning it a new one is an interesting computational challenge that is prone to many sources of technical errors. But more important than the technical errors are the issues that come up with serveillance systems where an agency can sabotage the economic and social opportunities of a person or a group of persons in a very targetted and covert manner.

## Systematized prejudice and surveillance systems
Let us look at the political dynamics and power play between an enforcement agency that hordes tax-payer money and resource-poor private individuals, coincidentally paying thoses taxes, who get surveilled. 

There is usually no human being acting as "Big Brother" who is actually viewing any of the footage from the countless surveillance equipment deployed in a city. The task of singling out a trouble maker is programmed into a software. The software program is deliberately trained and biased towards judging people of colour as more likely to be "troublesome." The simple causal factor in this industrial arrangement of surveillance equipment throughout a city is that the people who build it or buy it in the first place are never the poorer and oppressed sections of society. Instead, they were always the more affluent and dominating imperialists and colonialists within seats of authority among municipalities, state or provincial governments and federal governments.  

The interests and motivations of such imperialists and colonialists are simple: track and thwart any discent or uprizing that would expose or otherwise diminish their userped control of natural resources. Doing so necessarilky requires that any human individual who has a discenting view is swiftly tracked and "put into place of their lowly station."

Continuously tracking every individual "possession" within the monarch's "dominion" in real-time so that credence from that subject can be extracted by forced persuassion, magician's choice, threat or guile is the standard promise made by companies that prop up the despot or monarch for their personal greed.

Which one of the richest companies or corporations currently existent in the world is actually intersted in **not** exploiting human and natural resources to the anhialating **maximum extent**? None of them, absolutely none of them!

## Implementing Project Blue Moon
So how can resource poor serfs and slaves rescue their dignity and basic human rights from being pillaged and plundered by cronies of a monarchy that seemingly has unlimited zeal, opportunity and resources to oppress world citizens? 

Here is how we simply make sure that the technical faults within opto-electronic systems are utilized to protect the cultural heritage and innosence of all peoples along with our fundamental human rights: 

1. Faults in the business model of survaillance companies: Companies like FLIR and MioVision supply opto-electronic equipment to munispalities and states. Such companies often push the incentive that the cost of such equipment can be paid off at a future period of time from the earnings generated by "tickets" or "penalities" issued against trouble makers caught using systems supplied by them. This buisiness model front-loads or primes authorities and enforcement agencies to fill up monthly quotas by fishing or snaring as many people as possible using as miniscule a reason as possible to reach a financial breakeven point as soon as possible. And then following that, to start generating "profits" for the city or state from such penalty fees and tickets. This is a very bad and pradatory business model that has been culturally normalized among industrialized nations and city-states over the past decade.

    - Having appropriate legislative action to prevent such systemic misuse and abuse of survaillance equipment for profiteering is necessary but quite the long shot. The more immediate method is to notify the employees and investors of such companies that their methods of "creative destruction" in disrupting the survaillance market is also unapolagetically destroying basic legal tenants like *public accountability and transperancy* within business dealings of government bodies. 
    
    - Black-boxed and close-sourced artificial intelligence (AI) algorithms destroy human rights like the right of information to the mechanisms and procedures that issue a warrant, ticket or penalty against a survailled person. Bringing this issue directly to promoters and propegators of survaillance based businesses like Google and Amazon is essential. To appropriately regulate such corporations with fairness, framing and administering ISO standards for business and technical practices involving any machine learning (ML) or AI components is paramount! Corporations not adhearing to such standards would undoubtedly risk the health and safety of human beings and our ecology.
    
1. Challenges in the training algorithms of survaillance equipment: Practically every image processing algorithm takes cues from or directly uses the findings from cascade boosting algorithm described by [Viola Jones Detection Framework](https://en.wikipedia.org/wiki/Viola%E2%80%93Jones_object_detection_framework)
