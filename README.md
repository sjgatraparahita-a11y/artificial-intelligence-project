# artificial-intelligence-project
Face Recognition Project for Artificial Intelligence Final Project
## Introduction
This project was originally conceived as a method for recording attendance in class. The idea being that each student will stand in front of a small piece of hardware equipped with a small camera placed by the door. The camera will activate, recognize the student, and record attendance. The use case is only a hypothetical to apply knowledge of artificial intelligence and not in any way a real implementation. The project itself is only concerned with the actual facial recognition portion and not any of the supporting software and hardware.

## Method
Photos of each student were taken from various angles from the front. The faces were encoded using Histogram of Oriented Gradients via the face-recognition library (https://pypi.org/project/face-recognition/). The generated encodings were fed into an SVM for multi-class classification with the names of students.

## Additional Notes
The original image dataset contains identifiable names and faces and are omitted for privacy reasons.
