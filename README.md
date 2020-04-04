# AI-Consult-Doctor
We're trying to understand how we can use Neural Net on specific Subject (understading), where users can consult A Doctor on daily basis. 

## IDEA:
1. user select multiple choice Quations/Answers about symptoms.
2. analyze health condition based on answers
3. repeat that process for more special consultation(e.g heart, lungs, kidney).
4. give output about 5 diffferent probublities about what could be the case.
5. Maybe suggest any solution and suggest to see a specalist doctor.

## Algorithm Workflow:
1. Take selected topic .(Choose by User)
2. select model or set model Parameters or Run model.
3. Give user another multiple-choice based on model output. AND . show couple of medical condition with probablity
ratings.
4. Repeat.

### Resources:
-------------------
* https://en.wikipedia.org/wiki/Electrocardiography
* https://en.wikipedia.org/wiki/Sphygmomanometer
* https://www.spicytricks.com/apps/top-apps-measure-heart-rate-android-smartphone
* http://www.ignaciomellado.es/blog/Measuring-heart-rate-with-a-smartphone-camera(Heart Rate) {HR}
* https://scholar.uwindsor.ca/cgi/viewcontent.cgi?article=8997&context=etd
* FingerPrint Termometer for mesuring Body Tempareture.{BT} + NN
* Get respiratory rate from User (Calculate for about 30 sec and mesure the bearthhs per minute)
* Read Blood Pressure using Smart Band with accurecy (and machine learning Algo to predict the BT data with along side)
