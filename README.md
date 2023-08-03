# Facial Recognition Application

This is a facial recognition application that uses the `face_recognition` and `cv2` libraries to perform face recognition on an input image. The application allows you to load an image, find faces in the image, and compare them with pre-encoded faces stored in the 'people/' folder. If a matching face is found, it draws a rectangle around the face and displays the name associated with that face.

## How to Use

1. Clone the repository to your local machine using the following command:
```
git clone https://github.com/PdRajan/SIH2022_Facial-Recoginition-Application.git
```

2. Install the required libraries: The application relies on `face_recognition` and `cv2` (OpenCV). You can install them using `pip`:
```
pip install face_recognition opencv-python
```
3. Prepare your 'people/' folder: Inside the 'people/' folder, place images of people you want to recognize. The filenames should correspond to the names of the individuals in those images. For example, if you have a person named "John Doe," you should have an image named "John_Doe.jpg" inside the 'people/' folder.

4. Run the application: Execute the Python script using the following command:
```
python face.py
```


5. The application will prompt you to select an input image using a dialog box. Select the image you want to perform facial recognition on.

6. The application will process the image, recognize the faces, and compare them with the images in the 'people/' folder. If a match is found, it will draw rectangles around the matching faces and display the associated names.

7. Close the displayed image to exit the application.

## Important Notes

- Facial recognition applications can have privacy implications. Ensure you have the necessary permissions and consents from individuals whose images you are using in the 'people/' folder.

- For the best results, ensure that the images in the 'people/' folder are clear and well-lit, containing only one face per image.

- You can adjust the recognition tolerance level in the script (default: 0.55) to fine-tune the recognition sensitivity.

## License

This project is licensed under the [MIT License](LICENSE).
