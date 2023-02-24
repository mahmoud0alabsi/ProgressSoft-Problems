<h1> Problem-2_FaceMaskDetection </h1> 

<h2> About Project: </h2>
<p>
About Project:
In this project, I worked on detecting the face mask.
I build CNN (Convolutional Neural Network) from (Tensor-Flow & Keras) libraries, then train model using data sets from (kaggle).
</p>

<h2> CNN model: </h2>

![model_summary](https://user-images.githubusercontent.com/44245032/221187321-0d613bd5-f16c-4b1e-8134-36ca69b7c913.png)

![Training_metrics](https://user-images.githubusercontent.com/44245032/221187341-e83a4259-3b4f-43bc-8d2d-9604df2c3ccf.png)

![metrics_summary](https://user-images.githubusercontent.com/44245032/221187359-b3229135-7555-40be-aba5-18b985e7a53a.png)

![Confusion_matrix](https://user-images.githubusercontent.com/44245032/221187371-b576c7e0-0cc4-4c47-96e9-fa21581556c9.png)

<h3>
You can run this program from (Google Colab) or (Jupyter notebook).
</h3>

<h2> Run steps: </h2>
<p>
  
  * Download libraries from (requirements)
  * load model using ( model = tf.keras.models.load_model('/face_mask_model.h5')  )
  * use (predict_image) function and pass to it image path to test the model

</p>

<h2> Python version: </h2>
<p>
Python 3.8.10
</p>
