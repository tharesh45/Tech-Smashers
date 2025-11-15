# Tech-Smashers
road quality index with safety(Squareroots.ai)

Problem Statement
One-liner

Build SafeJourney — a three-phase intelligent system to improve road and personal safety by:

automatically detecting and reporting road hazards,

providing an AI-assisted emergency monitoring service for women, and

recommending safe driving/walking routes instead of only the fastest routes.

Short Description

Phase 1: Automatically detects potholes, cracks, and missing lane markings using images captured from vehicles or crowdsourced users. The system analyzes each image through an AI model, assigns a priority level based on severity, and sends structured reports to authorities for faster road maintenance.

Phase 2: Implements a women-safety emergency flow. When a user feels unsafe, she can activate emergency monitoring. The system captures live location, short audio/video snippets, and initiates a real-time monitoring and escort process. Verified alerts are automatically shared with police or guardians until the user reaches safety.

Phase 3: Computes safety-aware routes by combining crime/incident data and road condition scores. Instead of only showing the quickest route, the system recommends paths that are objectively safer for driving or walking.

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
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
