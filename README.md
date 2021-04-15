# ihealth
To monitor patient health remotely and collect data for better understanding & early detection
To connect the Doctors with Patients in remote areas

**Hardware:**
Raspberry Pi, Libelium Sensor Kit, ECG Sensor to measure Heart Rate

**Use Case:**
1. I think health industry has lot of potential and is not yet disrupted
2. It can be used to connect People in remote areas with doctors
3. This generic platform can be used to connect different health sensor devices and do the alerts & analytic based on input data
4. Machine Learning can be used further for Cognitive analysis and detecting the patterns for early detection of diseases
5. Mobile App will display Ads or suggest the medicines based on Symptoms or nearby hospitals. It will be beneficial for Pharmaceuticals and Hospitals
6. In near future there will highly advanced sensors connected to people


**Design Workflow:** Mobile App to connect Patients and Doctors
1. Sensor like iWatch/fitbit or any small IoT sensors will be connected with Patients
2. Sensor will monitor the parameter like Heart Rate of User
3. Mobile App will capture the data for user and send to Central Server
4. Central Server will monitor the rate..If threshold for hear rate increases
5. Send Notification/ Email / Message to Doctor
    Patient Name:  xyz
    Date: dd//mm/yyyy
    Parameter: Heart Rate %
    Patient History record:
6. Doctor will have app where they can view all Patient data /history / records and   
    monitor remotely and Send notification to patient to visit
    
7. Any Cloud Provider can act as intermediate medium connect the remote devices and get the stream of sensors data into Cloud which will be processed.
8. Machine Learning can be used for analysis or pattern recognition for early detection & diagnosis.     

**Technology Used:**
1. Mobile App Development: Flutter + Backend Firebase
2. Cloud IoT Core
3. Cloud Big Table
4. Cloud Pub/Sub
5. Google Kubernetes Engine
6. Cloud Dataproc
7. Cloud DataLab 
8. Cloud Datastudio

