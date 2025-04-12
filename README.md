Student Face Recognition & Attendance System using FaceNet

This project is a face recognition-based attendance system built using a combination of machine learning models and techniques. It works through the following pipeline:

Face Detection: Detects faces in an input image using FaceNet MTCNN — supports images with single or multiple faces, with or without masks or accessories.

Face Embedding: Converts each detected face into a numerical vector (embedding) for easy comparison.

Face Recognition: Matches the new face embeddings against a pre-saved dataset of student embeddings and names.

Attendance Marking: Identifies recognized students and generates an Excel sheet marking them as "Present" or "Absent" based on their appearance in the image.

🔍 Features
Works on group photos or single face images

Robust to masks, glasses, and face angles

Stores student data (name + face embeddings) for easy matching

Generates a clean attendance report in Excel for a specific class
