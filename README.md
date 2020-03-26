# MontanaMask
Development supporting the N95 Montana mask

For rigid masks, the current solutions don't scale.  I am not a medical professional, but I'm told that the prototypes I have provided do not fit all users properly.

Objective:
Create an app that will design an N95 mask tailored to an individual.  That STL file goes to a central server where volunteers sign up to provide that mask.  Volunteer prints the mask and ships it to the mailing address indicated for that mask.

Use case:
* End user (health care professional) installs app on phone.
* The app collects information such as name, phone number, email and shipping address.  
* The app 3D scans a face.
* The app creates the mask/face intersection line from the 3D scan.
* The app processes the scan, a surface is lofted from that intersecion line to one of several standard filter bosses.
* The app creates an STL file from the loft, and transmits the information to a central server.
* The app alternately emails the STL file to any email address, suitable for printing.
* The central server lists masks that have been requested, and tracks these.
* A volunteer with a printer downloads the mask project.  The project contains the mask STL files, as well as a PDF packing slip, and perhaps a USPS shipping label.
* Volunteer prints the mask, places it in a box and mails it to the location on the label.
* Volunteer then marks the project as complete.
* End user receives physical mask.  End user installs the filter and elastic band.

I need experts in the following areas:
* App development
* 3D scanning
* STL editing
* Back end services
