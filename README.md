# Dermatology EMR

### Work In Progress

## About
Dermatologists rely a lot on images for diagnosis and assessing improvement. Openmrs-suite-dermatology is an OpenMRS extension that tries to address this unique need. It comprises openmrs-module-dermatology and openmrs-owa-dermatology. The module adds some custom APIs to OpenMRS backend along with a link to the dermatology chart from the patient dashboard. The OWA is the dermatology patient chart. 

The patient chart supports the upload of images and webcam (https site required). The images can be viewed and manipulated using the viewer. The LesionMapper allows semantic mapping of dermatological lesions on a body map (publication pending). This provides a  privacy-preserving method for annotating dermatological lesions for sharing and machine-learning applications. The chart integrates SkinHelpDesk.com services - asynchronous web services that provide machine learning and artificial intelligence applications in general and cosmetic dermatology.

The OWA is written in Vue using my openmrs-owa-vue-template. All images are stored as OpenMRS complex observations. This incorporates the functionalities of my old modules - clinical images and skinhelpdesk will be officially deprecated soon.

## Demonstration Video

[Watch this!](https://www.youtube.com/watch?v=EigPbnvxR34)

## Contact
* [Bell Eapen](https://nuchange.ca)  |  [Contact](https://nuchange.ca/contact)
