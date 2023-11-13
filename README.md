# AstroHachers
kaggle dataset used: https://www.kaggle.com/datasets/mostafaabla/garbage-classification (we used only 8 types)

1.How to use:
1.1 Download all of the source code included in the reposatory.

1.2 python3 with libraries Flask, Tensorflow, numpy, scikit-learn, cv2, flask, firebase_admin is required.

1.3 After installing the libraries, open cmd in Green Dream directory (the root directory) and type "flask run" without the quotes.

1.4 Open the link that will be displaye after clicking Enter.

2.How it works:
3.1 The user is introduced to our homepage

3.2 The user can log in or register (The accounts information is stored in firebase realtime database).

3.3 After logging in, the user can make an order by clicking on 'order' on the navbar.

3.4 The user now is asked to fill a form of the recyclable object they want to recycle.

3.5 The user can provide an image of the object they want to be recycled and the image is passed to our trained model, and the model returns the type of the object given.

3.6 The photo uploaded by the user (if any) will be uploaded to firebase storage and the order details will be stored in firebase realtime database.
