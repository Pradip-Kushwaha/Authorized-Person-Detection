# Authorized-Person-Detection

DESCRIPTION:
This project is an advanced security application that integrates real-time 
Facial Recognition with Liveness Detection (Anti-Spoofing). It is designed 
to distinguish between a real human presence and a static image/photo.

CORE TECHNOLOGIES:
- Python 3
- OpenCV (Computer Vision)
- Face_Recognition (Dlib-based encodings)
- SciPy (Euclidean distance for EAR calculation)

KEY LOGIC:
1. Facial Recognition: Matches live face encodings against a local dataset.
2. EAR (Eye Aspect Ratio): Monitors the vertical distance of eyelids to 
   detect natural blinks.
3. State Tracking: Maintains individual "Blink Counters" for multiple 
   people simultaneously using a dictionary-based tracking system.

SECURITY STATUSES:
- RED: Unknown / Unauthorized
- ORANGE: Authorized but static (Liveness verification pending)
- GREEN: Authorized and Live (Verified via blink)

SYSTEM REQUIREMENTS:
- Standard Webcam
- Authorized_da
