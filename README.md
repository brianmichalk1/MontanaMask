# MontanaMask
Development supporting the N95 Montana mask

For rigid masks, the current solutions don't scale.  I am not a medical professional, but I'm told that the prototypes I have provided do not fit all users properly.

Objective:
Create an app that will design an N95 mask tailored to an individual.  That STL file goes to a central server where volunteers sign up to provide that mask.  Volunteer prints the mask and ships it to the mailing address indicated for that mask.

Use case:
End user (health care professional) installs app on phone.
The app collects information such as name, phone number, email and shipping address.  
The app 3D scans a face.
From that scan, the app creates the mask/face intersection line.
A surface is lofted from that intersecion line to a standard filter boss.
An STL file is created from the loft, and is transmitted to a central server.
The central server lists masks that have been requested, and tracks these.
A volunteer with a printer downloads the mask project.  The project contains the mask STL files, as well as a PDF packing slip, and perhaps a USPS shipping label.
Volunteer prints the mask, places it in a box and mails it to the location on the label.
Volunteer then marks the project as complete.
