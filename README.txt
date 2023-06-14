# Facial Recognition Attendance System

The Facial Recognition Attendance System is a Python-based project that utilizes computer vision and facial recognition techniques to automate attendance tracking. It detects and recognizes faces in real-time using a webcam or video input, matches them with a pre-defined dataset of known faces, and marks the attendance of recognized individuals.

## Features

- Real-time face detection and recognition using OpenCV and face_recognition library
- Automatic attendance marking for recognized faces
- Easy integration with existing attendance systems
- Simple and intuitive user interface
- Flexibility to add or remove faces from the dataset

## Setup and Usage

1. Clone or download the project repository to your local machine.
2. Install the required dependencies by running `pip install -r requirements.txt`.
3. Prepare the image dataset by placing the images of individuals in the `ImagesAttendance` folder.
4. Run the `facial_recognition_attendance.py` script to start the Facial Recognition Attendance System.
5. Ensure that your webcam is connected and positioned properly for face detection.
6. The system will detect faces in the webcam feed, compare them with the dataset, and mark the attendance accordingly.
7. Press 'q' to exit the application.

## Dependencies

- Python
- OpenCV
- NumPy
- face_recognition

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, feel free to open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).

## Acknowledgments

- The project utilizes the face_recognition library, developed by Adam Geitgey. (Link: [face_recognition](https://github.com/ageitgey/face_recognition))

Please customize the ReadMe file as per your project structure, additional details, and any specific instructions you want to provide.