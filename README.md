# Face Recognition

## Getting Started

Prepare at least two class with images in folder 'raw'. After that, use

      python load_model.py --mode crop
      python load_model.py --mode train  
to train these images with FaceNet. Use

      python load_model.py --mode stream
to check result. If you want to test with API, use

      python app.py
and access to localhost to try some functionality of website.
