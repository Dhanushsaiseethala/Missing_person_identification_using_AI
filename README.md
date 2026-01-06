# Missing_person_identification_using_AI
This project implements a face recognition system using InsightFace and OpenCV. It detects faces, extracts embeddings, and uses a trained machine learning model to identify individuals. The system supports efficient face matching and can be extended for real-time or image-based recognition tasks.
Rising Kidnapping and Missing Person CasesKidnapping incidents, especially involving children, often occur near routine locations like schools, playgrounds, or bus stops. Delayed identification and response during the early hours significantly reduce the chances of safely locating the missing person.

Inefficient Use of CCTV Camera FootageAlthough CCTV cameras are widely installed in public and private spaces, their footage is not centrally analyzed during missing person investigations. Manual collection and review of footage from multiple cameras leads to time loss and incomplete coverage.

Lack of Location-Based CCTV MappingThere is no automated system that links a missing person’s past known locations with nearby CCTV cameras using latitude and longitude data. This prevents investigators from quickly identifying the most relevant cameras along probable movement routes.

Absence of Real-Time Monitoring and VisualizationCurrent investigation methods lack real-time map-based visualization of missing person data and surrounding CCTV coverage. This limits situational awareness, slows coordination, and reduces the effectiveness of rescue operations.

Solution for this problem

Location-Based CCTV MappingPast known locations of the missing person are analyzed using latitude and longitude to automatically identify and prioritize nearby CCTV cameras.
AI-Powered Face Detection and RecognitionModels such as MTCNN for face detection and InsightFace for face recognition are used to identify the missing person from CCTV footage efficiently.
Centralized Real-Time VisualizationAn interactive map dashboard displays missing person locations and surrounding CCTV cameras in real time, improving situational awareness for investigators.
Automated and Scalable Investigation ProcessThe system reduces manual effort by automating camera selection, footage analysis, and alerts, enabling faster response during critical rescue operations.


we had used these technologies in this project

Python (Backend & AI Integration)Python is used as the core programming language for backend development, data processing, and integration of AI-based face recognition models.
Geospatial Processing (Geopy / Haversine Formula)Used to calculate real-world distances between missing person locations and nearby CCTV cameras using latitude and longitude data.
MTCNN (Face Detection Model)Used to detect human faces in CCTV video frames with high accuracy, even under varying lighting conditions and different face orientations.
InsightFace (Face Recognition Model)Used to extract facial embeddings and match detected faces against the missing person’s reference images for identity verification.
Deep Learning Frameworks (TensorFlow / PyTorch)Used to train, fine-tune, and deploy deep learning models for face detection and recognition tasks.
OpenCV (Computer Vision Processing)Used for real-time video frame extraction, image preprocessing, face cropping, and integration with AI models.
Leaflet.js with OpenStreetMap (Map Visualization)Used to display missing person locations and surrounding CCTV cameras on an interactive map interface.



