# Mediculus
Mediculus is a automated ambulance service which analysses video form security cameras to find health emergencies and alert the ambulance drivers the location of the accident and guides the to the location using a flutter application installed in thier mobiles. An Express Backend is used to find the nearest ambulance driver from the location of the health emergency. 

CONTENTS OF THIS REPOSITORY
---------------------

- Mediculus Fall and Pain Detection Model
- Mediculus Express Server Backend
- Mediculus Flutter Application

# Mediculus Fall and Pain Detection Model:

* Machine Learning models to analyse video feeds in surveillance systems and detect fall, accidents or pain expressions in people and notify authorities. A LSTM model was used to predict fall provided Keypoints of Human. A CNN Model was used to detect pain from a person's face. cv2 harr cascade was used to detect faces.

<i> DEMO </i>

<p align="center">
<img src="https://user-images.githubusercontent.com/54630055/152993370-3f22422a-b603-4b34-89f4-c001fba762e9.gif" width="800" height="400" />
</p>
# Mediculus Express Server Backend:

* An express framework based backend server to get data from the ML model and send the incident location to the closest authority.

# Mediculus Flutter Application:

* A flutter based android application for people, hospitals and ambulance drivers to get notified of the incident location processed by the server in case if they're found to be close to the incident.


ADDITIONAL CONTENT
------------------

* Trained ML model for pain detection

# Trained ML model for pain detection:

* The following model has been trained to detect facial expressions to detect distress in a person.
* [Pain Detection Model](https://amritavishwavidyapeetham-my.sharepoint.com/:u:/g/personal/cb_en_u4cse19302_cb_students_amrita_edu/EQ6fdiQduZ9AncJTRkrFK_kBbyeUNvZg_hXBfJZ8o-LFcQ?e=ZFnEVD)

