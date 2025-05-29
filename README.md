# Automated-Parking-Detection-CV

This project aims to solve the issue of unauthorized parking in reserved and disabled spots using a real-time computer vision system. Built as part of a final project at Arizona State University (CIS 515), it combines image classification and license plate recognition to automate violation detection.

🔍 Problem Statement
ASU’s current system for monitoring parking violations relies on manual checks, which are time-consuming and often inconsistent. This creates challenges for people with disabilities and exposes the university to potential legal risks.

💡 Our Solution
We built a dual-model solution:

Parking Spot Detection – Using OpenCV and ElementTree, we detect if a vehicle is in a reserved or disabled spot.

License Plate Recognition – Using YOLO and EasyOCR, we read the license plate and verify it against a dummy database.

If the vehicle is parked in the wrong spot and not registered, the system flags it for a fine.

⚙️ Tools Used
Python

OpenCV

YOLO

EasyOCR

Pandas, NumPy

Jupyter Notebook

📈 Impact

✅ Replaces manual checks with automated detection

✅ Improves accessibility and parking enforcement fairness

✅ Sets foundation for smart campus infrastructure
