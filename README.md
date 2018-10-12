# Rescue_and_relief

**Natural disasters** can be utterly devastating to human lives and the environment they live in. Although humans have progressed far in the field of science and technology, still they stand vulnerable in the face of nature's fury. 

We aim to provide relief and management support during any natural calamity through our web application. Our application will bring better connectivity to a calamity hit area providing volunteer help and updating about any impending danger.

**Web App** --- `Framework used :  Django, Google Maps APIs, Twitter APIs, Other APIs as req.`

**Prediction** : We will scrape `Twitter` (use a predictive classification model) and other social platforms (Facebook "Marked as safe") to spread awareness about any natural disaster that has recently occured. We would use meteorological datas and some weather APIs, for predicting events which are likely to occur.

**Management** : Our application will run on two modes : `Victim` and `Volunteer` mode. One can get an account in either of them. 

- For the `victim` mode. he has to specify his location, contact details, requirements, scale of the damage caused. They can then send SMS's to the authority. This SMS stream will be monitored and keyword clustering will be carried out to initiate a response.

- Based on the his data, he would recieve the details of the nearest Volunteers registered to help. Volunteers can be individual or some organization. Both the locations of the victim and the volunteer will be protrayed on Google Maps using the `Google Maps API`. 

- Automated suggestions of healthcare centres/police stations to triage relief from, will be lent to the victims. 

- Hospitals will be monitored in real-time (current capacity vs full capacity) so that victims can select their hospital. Also, hospitals can update patient information merely by sending a simple SMS in case of communications loss.

- For the `Volunteer` mode, an account has to be created to volunteer for rescue and relief operation of the natural disaster. He would be notified about any victim located in the proximity and their scale of devastation, status of relief operation. He can volunteer to contact the victim. He can send SMS alerts to victims in the area with directions to the nearest relief centre.

- Heatmap generation with the location of victims in the region to direct response.

- There will be options in the application for donation of money, via some payment gateway, to some governnment organisations (in th main menu).
