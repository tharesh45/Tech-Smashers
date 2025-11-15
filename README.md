# Tech-Smashers
road quality index with safety(Squareroots.ai)

Problem Statement
The Safe Journey System is an integrated AI solution designed to ensure safer travel using real-time monitoring, road-quality insights, women safety features, safe route navigation, and deepfake-based driver verification. Built for hackathons and real-world deployment, this project combines computer vision, geospatial analysis, and AI-driven decision-making.

Phase 1 – Road Quality Intelligence (RQI)

This module analyzes road conditions to detect potholes, cracks, faded lane markings, and hazards using YOLO-based computer vision. Detected issues are automatically mapped to their GPS location and reported to authorities through a cloud dashboard. This ensures meaningful civic action and improves overall transportation safety.

Phase 2 – Women Safety & SOS Monitoring

Women can trigger SOS Mode through a button or voice command. The app sends the user’s live location every 10 seconds to police/guardian dashboards via API. An AI-assisted call monitors the user until she reaches a safe location. Tracking can only be stopped by identity verification to prevent misuse. Emergency SMS alerts are sent to registered contacts through Twilio/Firebase.

Phase 3 – Safe Route Recommendation

Traditional navigation systems focus on shortest or fastest routes, but not safety. Our system calculates a Safety Score for every road based on potholes, lighting, hazards, and crime-zone data. Using OpenStreetMap + Leaflet.js, the application displays two routes:

Fastest Route (Red)

Safest Route (Green)
This helps users make safer travel decisions.

Phase 4 – Deepfake Driver & Vehicle Verification

Before entering a cab or ride, users can scan the driver’s face or ID card. A deepfake detection model analyzes facial patterns to verify authenticity and detect manipulated images. This prevents fake driver identity fraud and enhances passenger safety.



--------------------------------------------------------------------------------------------------------------------------------------------------------------------
Phase 1 – Automatic Road Damage Detection(Squareroots.ai)

Phase 1 focuses on developing an AI system that automatically detects potholes, cracks, and missing lane markings from images submitted by vehicles or crowdsourced users. The aim is to speed up road inspection, reduce manual work, and help authorities fix damages faster. Using a trained YOLOv11s model, each uploaded road image is analyzed and labeled with the type of defect found. The system highlights the damage with bounding boxes and confidence scores, making it easy to understand what issues are present.

After detection, the system assigns a priority level based on the severity and size of the damage. High-priority issues—such as deep potholes or completely faded lane markings—are flagged immediately because they pose more risk. Medium and low priorities represent moderate or minor issues. These results are automatically converted into structured reports that include the image, defect type, and priority score. Authorities can then view these reports and decide which areas to repair first.

Benefits

Helps authorities identify dangerous road defects quickly

Reduces manual inspection time and field surveys

Minimizes accidents by highlighting high-risk areas early

Encourages public participation through crowdsourced reporting

Improves overall road quality and maintenance planning

Creates a reliable and continuous monitoring system
