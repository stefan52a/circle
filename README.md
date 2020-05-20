# circle

![alt text](https://github.com/stefan52a/circle/blob/master/header.png)

VThe Circle App: no data will be shared with (government) agencies, but within a small trust group (Circle). The people in the group help each other creating a protecting Circle around the Covid-19 virus. Without any tracking, taking part in the Circle app ensures, together with the people you trust, that within the group when there is a chance that somebody is infected with Corona, this can be shared anonymously with the outside world, when the Circle consents. So, the app does not work automatically, and the Circle has control.
If somebody gets a notification there was contact with the anonymous notifier, then his risk for infection can be shown and the app, at certain level of probability, gives pointers to advice what to do.
This way the Circle app will be a responsible example how privacy and inclusive care for each other, can go together.

The secure app gives advice and it helps people to support each other in a Circle (social care). The app conforms to the Dutch expectations around Corona security, privacy and care for each other.
We like to keep it simple, as minimal features can deliver maximal robustness

![alt text](https://github.com/stefan52a/circle/blob/master/circle.gif)

We propose this app because we share the concerns of ref 0, in a realistic way:
We need (ref 1) "A decentralized protocol which does not require the exchange of data with a central authority (such as the DP3T protocol) should be examined".
And (ref 2) "without invading privacy... For example, the use of Bluetooth instead of GPS, ... identification numbers that are only stored on the phone, and therefore not on a central server".


The basics:
Every individual has a circle of family/acquaintances/neighbors/colleagues/ etc. around them. 
People you trust, especially in the context of the common enemy Corona. People you dare to tell that you are infected with COVID-19, and whom you trust to take the responsibility to share that information e.g. with the health authority.
Suppose you can grow to a maximum of 50 people who all want to fight Covid-19. Such a group has the right size to improve on protection of everyone, inside and outside the circle, against COVID-19 infection, through the app. 
It is a threat that affects all of us and that will be the motivation to work together in this limited circle. There is a relationship of trust in this responsibility for each other: the key against a global enemy. No other information can be shared with this app. The circle is not too big for privacy and not too small for the responsibility that will actually be carried out.

How it works:
The operation of the app in practice:

Your own phone number/ID will be encrypted with a key of your own for the circle. This key can only be decrypted by the circle's key.

Every individual within the circle has a secret number of everyone else. Outside the circle, nobody can link a name or person to that number.

The mobile phone will measure where everyone meets: at what time and at what distance. On everyone's app is registered which secret numbers are encountered (time/distance). These registrations will be shared within your own circle via the app. 
You won't notice anything unless the following happens:

Suppose someone from the group shows symptoms of COVID-19 infection and goes (if possible anonymously) to the doctor or hospital, then, in case of a positive test, the appointment is that he/she or another member of the group presses a test (joint appointment for the fight against corona). This test will inform each app user by means of a push message that this number is infected. And also everyone within the circle can see if he/she or another member of the circle has been in contact with the infected person (where/when and without knowing who the infected person is). If an encounter has taken place then, taking into account the incubation period, etc., it could be calculated how likely infection could have occurred.  
The circle members then receive this information from the app, and can then see what the best measures are. For example: paying extra attention to symptoms, self-isolation, contacting a GP, etc.

In addition, the circle in which you participate has the responsibility to pass on the secret number of the corona-infected person in question to all circles via a button. The local GGD or any other authority authorized to do so could request information from an individual if he or she so permits.
Only the circle knows the combination of name and secret number. Someone outside that circle who has been in contact (place/time/distance) with the infected person receives the information that this took place and can, therefore, take measures for himself/herself and his/her own environment.
This person(s) cannot trace the connection between the notification and the infected person in question. Only the circle knows the connection, but that circle is a maximum of 50.

The principle closely resembles that of a solidarity system such as a bread fund or mutual health insurance, where you share the responsibility to support each other in case of illness, and where the degree of fraud is very low because of the mutual involvement. Given the impact this crisis has had on solidarity and helpfulness with each other so far, we believe that this principle can also work for the app, and then hopefully be implemented in other crises.

In this way, trust in - and a sense of responsibility towards - one another, while maintaining privacy, is guaranteed as far as possible, among other things.
Technically:

Then every (person from a) circle receiving that push message would be able to see if and who within his own circle has been in contact with infected person X (without knowing who that is), where, and when and at what distance. 

Our voluntarily usable open source app and consensus backend ensure privacy at a minimum according to AVG standard.

Data on contacts, locations, and time remain on the user's smartphone. The anonymous identifiers of third parties are stored on users' phones. From this identifier, the identity of third parties cannot be traced.
In case of contamination, only the anonymous identifier of the user is published with the consent of the user. This will alert third parties without revealing the identity of the source.
Outside the limited circle and the frequent random identification, the processed data cannot be traced back to individuals or deanonymized. Data within the app/circuit are stored for as long as they are relevant for source and contact detection.

Optionally, a user can mitigate privacy and spread responsibility through a self-composed circle (Circle) of people; a Circle of people who support each other in case infection occurs within the Circle and thereby bear and increase solidarity.
Each Circle can never be larger than 50 people, maintained by consensus (the blockchain). Every individual can always withdraw completely (including his data) from the Circle.

For privacy and information security, we use cryptographic common and open standards, such as elliptic curve private/public keys, blockchain immutability, secure transfer protocols, and confidential range proofs.
Our app is based on apps researched for usability, privacy, information security, technology, content, and operation.

Via opt-in, data can be shared outside the app/ circle with for example GGD and with HMAC salts can be destroyed by the individual remotely. The GGD's can potentially with differential privacy (Hashing, Subsampling, and Noise Injection) still have (also statistical) information.
False positives due to accidental reporting are partly reduced by the Circle of Confidants of the users who have insight into the state of the users in their Circle.
False positives, by the Covid-19 test itself, will be minimized by a probability check with - of course - limited historical contact history. 

The app is explicitly not limited to country or EU borders. The small Circle can extend all over the world.

The multilingual, BLE energy efficient, app can be made available and marketed at very short notice from the Google Play Store and Apple Store, with the associated update and crash recovery environment (frontend crashlytics). Crashlytics is also available in the backends.

It remains imperative to explain to the public that voluntary self-isolation can protect other people's health and lives.

The app and backend do not include central controllers such as an administrator, nor Zoof-It , no university, no government, no company, nobody, just all Dutch people.

Covid-19 infection is a social disease and as such, just like STD’s should be countered with social remedies.
----
Hypothesis: By giving up just a minimum of privacy to your trusted Circle of 1 to 50 people we can ensure a better working Covid-19 tracing app.
Hypothesis: The number of Dunbar (e.g.ref 3), the average number of people we know, 148, often rounded to 150, is the maximum number of people within a Circle. 
Objective: Make an informed decision on which concept is best, e.g. privacy wise. (see ref 4, 5 & 6)
Hypothesis: The maximum number of people within a Circle should be 50. A non-hierarchical Circle can consist of max. 50 people.
Hypothesis: Objective: The software should be correct, robust, maintainable, have a permissive Open Source license; should have Privacy by Design; should be Inclusive or Optional; not be based upon only Android or only iOS, see ref 7 & 8;
Hypotheses: /People trust their doctor to look after their data. /People do not necessary trust the government to look after their data. /People do not trust private companies to look after their data.  (see ref 8)
Hypothesis: A non-governed, immutable blockchain is the only way that cooperation between Circles can exist. (see ref 9). 
Objective: The ecosystem cannot be gamed (see ref 10) in a way that is counterproductive. E.g. Bitcoin cannot be gamed; one is unable to get more out of a transaction than actually given by another person.
Hypothesis: Robust app usage: False positives and false negatives will be prevented by a social voting system within a Circle. See ref 11.
Objective: How can we protect people's privacy and sense of privacy as much as possible in the social fight against the coronavirus? Help us recovery, but which protect fundamental rights See also ref 17. 
Objective: Take into account Ethical, Social, Fundamental Rights, Legal & Governance issues; Objective: make an informed decision on the right basis for our social app, see ref 18
Hypothesis Technology is limited: based solely upon DP3T (PEPP-PT), although can implement it pretty fast, conceptually has its limits, i.e. the social support is missing, maybe good for a first phase;
Objective: make design inclusive, understandable, scalable, see ref 21

https://www.veiligtegencorona.nl/ by various authors
http://allai.nl/wp-content/uploads/2020/04/Brief-Minister-President-Rutte-Ministers-De-Jonge-Van-Rijn-Grapperhaus-de-heer-Sijbesma-inzake-COVID-19-tracking-en-tracing-en-gezondheidsapps.pdf  by various authors
https://3e011b6e-db6c-4135-98e3-678feeac2463.usrfiles.com/ugd/3e011b_451e8a809e53459ca2a46206c2ba7115.pdf by  Stijn van Gils
https://www.nicovanstraalen.nl/columns/holland-media-combinatie/hoeveel-mensen-kun-kennen/ 
https://www.pepp-pt.org/
https://github.com/DP-3T/documents   
A DP3T alternative: TCN:  https://github.com/TCNCoalition/TCN
https://www.apple.com/covid19/contacttracing/
https://medium.com/asecuritysite-when-bob-met-alice/the-flawed-world-of-contact-tracing-wheres-carol-the-tester-3939ac92488a by Prof Bill Buchanan OBE
https://medium.com/@stefjan_67880/permissionless-blockchain-by-design-d5d0b90255ca by Drs. SPRM Verhagen MBA
https://library.princeton.edu/special-collections/sites/default/files/Non-Cooperative_Games_Nash.pdf and https://www.ncbi.nlm.nih.gov/pmc/articles/PMC1063129/by John Nash and https://en.wikipedia.org/wiki/Nash_equilibrium
https://pdfs.semanticscholar.org/7e8d/c5b93a2ff6fcb4a986e89d23add04f9ac27e.pdf by Ahmed Ben Ayed
Plaatjes uit
https://covid19-static.cdn-apple.com/applications/covid19/current/static/contact-tracing/pdf/ExposureNotification-FAQv1.1.pdf
Figma van ito-org
https://www.dropbox.com/s/m0f2d433krhqffv/3PersonTest%20van%20ITO-ORG.mp4?dl=0
https://www.dropbox.com/s/b0zjavmsz6v83uq/Peek%202020-05-10%2018-03Figma3.mp4?dl=0
Artikelen en plaatjes van https://medium.com/asecuritysite-when-bob-met-alice/the-core-of-contact-tracing-app-design-who-owns-your-identity-df971e794d09 etc.
https://medium.com/asecuritysite-when-bob-met-alice/contact-tracing-the-most-amazing-and-scariest-technology-of-the-21st-century-9fb86d7869e5 by Prof Bill Buchanan OBE
https://github.com/shankari/covid-19-tracing-projects by https://github.com/shankari
https://medium.com/@stefjan_67880/the-case-for-a-slim-blockchain-and-where-to-store-personal-data-under-gdpr-37b1a7891717 by Drs. SPRM Verhagen MBA
https://ec.europa.eu/health/sites/health/files/ehealth/docs/covid-19_apps_en.pdf by the European Union
https://docs.google.com/document/d/1uQSPfUnPSJVDse4_mYrjsQdIi83bUZorVJardBPOuo0/edit?usp=sharing by various authors
Social innovation:  ……




There is a **problem** that technology is limited:

Technology based solely upon [DP3T](https://github.com/DP-3T) (PEPP-PT) , although we can [implement](https://gitlab.com/PrivateTracer) it pretty fast, conceptually has its limits, i.e. the social support is missing, maybe good for a first phase;


Most software known has other limits, either
    
..* is not Open Source;
        
..* does not have Privacy by Design;
        
..* does not have highly Decentralized Storage;
        
..* is not Inclusive or Optional
        
Technology based upon only Android or only iOS has its limits;
    
Ethical, Social, Fundamental Rights, Legal, Governance etc. limits;
    
Technology based upon Apple/Google only, has its limits:
    
..* Contact Tracing is The Most [Amazing And Scariest Technology](https://medium.com/asecuritysite-when-bob-met-alice/contact-tracing-the-most-amazing-and-scariest-technology-of-the-21st-century-9fb86d7869e5) of The 21st Century! We get this wrong, we are in big trouble for our health, our economy, and for our privacy! Please support and build things that help us recovery, but which protect fundamental rights.
        
..* I state [three things](https://medium.com/asecuritysite-when-bob-met-alice/the-flawed-world-of-contact-tracing-wheres-carol-the-tester-3939ac92488a) I’ve learnt from working in health care:
        
    ..* People trust their doctor to look after their data.
        
    ..* People do not nescessary trust the government to look after their data.
        
    ..* People do not trust private companies to look after their data.




So trust your Circle:


Privacy and Take Care & 
                    Give Care



https://ncase.me/contact-tracing/
