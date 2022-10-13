# IBM-Project-51619-1660981043
Classification of Arrhythmia by Using Deep Learning with 2-D ECG Spectral Image Representation
What is Heart Arrhythmia?
A heart arrhythmia is an irregular heartbeat. Heart rhythm problems (heart arrhythmias) occur when the electrical signals that coordinate the heart's beats do not work properly. The faulty signalling causes the heart to beat too fast (tachycardia), too slow (bradycardia) or irregularly. 
Heart arrhythmias may feel like a fluttering or racing heart and may be harmless. However, some heart arrhythmias may cause bothersome — sometimes even life-threatening — signs and symptoms.
However, sometimes it is normal for a person to have a fast or slow heart rate. For example, the heart rate may increase with exercise or slow down during sleep.
Heart arrhythmia treatment may include medications, catheter procedures, implanted devices, or surgery to control or eliminate fast, slow, or irregular heartbeats. A heart-healthy lifestyle can help prevent heart damage that can trigger certain heart arrhythmias.

What are its types?
Fast heartbeat (tachycardia)
Types of tachycardias include:
•	Atrial fibrillation (A-fib). Chaotic heart signalling causes a rapid, uncoordinated heart rate. The condition may be temporary, but some A-fib episodes may not stop unless treated. A-fib is associated with serious complications such as stroke.
•	Atrial flutter. Atrial flutter is like A-fib, but heartbeats are more organized. Atrial flutter is also linked to stroke.
•	Supraventricular tachycardia. Supraventricular tachycardia is a broad term that includes arrhythmias that start above the lower heart chambers (ventricles). Supraventricular tachycardia causes episodes of a pounding heartbeat (palpitations) that begin and end abruptly.
•	Ventricular fibrillation. This type of arrhythmia occurs when rapid, chaotic electrical signals cause the lower heart chambers (ventricles) to quiver instead of contacting in a coordinated way that pumps blood to the rest of the body. This serious problem can lead to death if a normal heart rhythm isn't restored within minutes. Most people who have ventricular fibrillation have an underlying heart disease or have experienced serious trauma.
•	Ventricular tachycardia. This rapid, regular heart rate starts with faulty electrical signals in the lower heart chambers (ventricles). The rapid heart rate does not allow the ventricles to properly fill with blood. As a result, the heart cannot pump enough blood to the body. Ventricular tachycardia may not cause serious problems in people with an otherwise healthy heart. In those with heart disease, ventricular tachycardia can be a medical emergency that requires immediate medical treatment.
Slow heartbeat (bradycardia)
Although a heart rate below 60 beats a minute while at rest is considered bradycardia, a low resting heart rate does not always signal a problem. If you are physically fit, your heart may still be able to pump enough blood to the body with fewer than 60 beats a minute at rest.
If you have a slow heart rate and your heart is not pumping enough blood, you may have a type of bradycardia. 


Types of bradycardias include:

•	Sick sinus syndrome. The sinus node is responsible for setting the pace of the heart. If it doesn't work properly, the heart rate may alternate between too slow (bradycardia) and too fast (tachycardia). Sick sinus syndrome can be caused by scarring near the sinus node that's slowing, disrupting or blocking the travel of impulses. Sick sinus syndrome is most common among older adults.
•	Conduction block. A block of the heart's electrical pathways can cause the signals that trigger the heartbeats to slow down or stop. Some blocks may cause no signs or symptoms, and others may cause skipped beats or bradycardia.
How is it diagnosed?
Electrocardiography (ECG) is examined to determine heart arrhythmia.
 
An electrocardiogram (ECG) is a simple test that can be used to check your heart's rhythm and electrical activity. Sensors attached to the skin are used to detect the electrical signals produced by your heart each time it beats. These signals are recorded by a machine and are looked at by a doctor to see if they're unusual. An ECG may be requested by a heart specialist (cardiologist) or any doctor who thinks you might have a problem with your heart, including your GP. The test can be carried out by a specially trained healthcare professional at a hospital, a clinic or at your GP surgery. Despite having a similar name, an ECG isn't the same as an echocardiogram, which is a scan of the heart
When is an ECG is used?
An ECG is often used alongside other tests to help diagnose and monitor conditions affecting the heart. It can be used to investigate symptoms of a possible heart problem, such as chest pain, palpitations (suddenly noticeable heartbeats), dizziness and shortness of breath. An ECG can help detect:
•	Arrhythmias - Where the heart beats too slowly, too quickly, or irregularly.
•	Coronary Heart Disease - Where the heart's blood supply is blocked or interrupted by a build-up of fatty substances.
•	Heart Attacks - Where the supply of blood to the heart is suddenly blocked.
•	Cardiomyopathy - Where the heart walls become thickened or enlarged.
A series of ECGs can also be taken over time to monitor a person already diagnosed with a heart condition or taking medication known to potentially affect the heart.







Normal ECG
 
A normal ECG is illustrated above. Note that the heart is beating in a regular sinus rhythm between 60 - 100 beats per minute (specifically 82 bpm). All the important intervals on this recording are within normal ranges.
Abnormal ECG
 				 
Electrocardiographic abnormalities include first-degree heart block, right and left bundle branch block, premature atrial and ventricular contractions.
Currently available market solutions
Though several proposed solutions are present as a means of predicting the types of arrhythmias, none have been implemented as an end-to-end solution. Current solutions lie in the form of research papers. This is where our product would come in. 

In this project, we propose to build an effective electrocardiogram (ECG) arrhythmia classification method using a Convolutional Neural Network (CNN), in which we classify ECG into six different categories namely:
•	Left Bundle Branch Block
•	Normal
•	Premature Atrial Contraction
•	Premature Ventricular Contractions
•	Right Bundle Branch Block
•	Ventricular Fibrillation

We intend on creating a web application where the user selects the image which is to be classified. The image is fed into the model that is trained on publicly available datasets of ECG and is accordingly classified into one of the above-mentioned classes which will be displayed on the webpage.
Technologies needed for development
Upon research it was found that we need require a sound knowledge of the following software technologies for the systematic completion of the project:
•	HTML/CSS/JavaScript/Bootstrap – Front End Development
•	Python
•	TensorFlow
•	Image Processing Basics
•	Flask – Backend Development
•	Git & GitHub – Project Management
•	IBM Cloud – Hosting
•	IBM Watson – Training the Deep Learning Model
