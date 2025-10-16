# Traditional Malay Women Fashion Product Recommendation System
 Welcome to Traditional Malay Women Fashion Product Recommendation System Using CNN Deep Learning !

What is it?
<br>
Web-based Traditional Malay Women Fashion Product Recommendation System using CNN (ResNet-50) and Nearest Neighbors algorithm to suggest culturally relevant traditional Malay women’s fashion products (Baju Kurung,Baju Kebaya,Tudung).

Problem Statement
* Difficulty to find fashion products suggestion that fit user personality in online platform for Traditional Malay Women Fashion Product.
* Ineffective Traditional Text Based Search Method to provide good recommendation fashion products for user.

Objectives
* To identify a suitable machine learning algorithm for a traditional Malay women's fashion product recommendation system.
* To develop a system that can recommend traditional Malay women's fashion products for users.
* To test the accuracy result of the traditional Malay women's fashion product system.

Software & Tools
* CNN - (ResNet50) Model
* Python - Programming language
* TensorFlow - Deep learning library
* Keras - Neural networks API
* Jupyter Notebook - Interactive computing environment
* Scikit Learn - Machine learning library
* Streamlit - Web app framework
* Visual Studio Code - Code Editor

Methodology
* Agile Development Model - Enables revisions if business requirements change.
* Overall Design – Use Case Diagram
  <br>
  <img width="513" height="394" alt="image" src="https://github.com/user-attachments/assets/ceb98e75-f58e-4d5a-bf8c-fb661af06d30" />
* Flow Design - Flowchart
  <br>
  <img width="336" height="623" alt="image" src="https://github.com/user-attachments/assets/407471a9-076e-425a-8b99-f0e470d3c3ea" />
* Development
  <br>
  1) Features - Image Upload and Preprocessing,CNN Model Training,Recommendation Generation
     * Image Upload and Preprocessing
     * First iteration, the system will implement the functionality to upload and preprocess images.Once submitted, the photos will go through preprocessing stages to ensure they are standardized and optimized           for future processing by the system.
     * CNN Model Training
     * CNN model to train using the preprocessed images in the second iteration.TensorFlow and Keras libraries were used to create and train the model. The ResNet-50 architecture will be employed for its                 robustness in image recognition tasks.
     * Recommendation Generation
     * In the final iteration, the system will include the ability to produce recommendations based on an uploaded image. The trained CNN model will scan the uploaded image for similar things in the data. The            recommendation will be displayed to the user through the interface.
  3) Visualization Algorithm - Image Recognition Algorithm (Data Preprocessing,Model Training,Feature Extraction,Similarity Matching,Recommendation Generation)
     * Data Preprocessing
     * The sample size of the dataset is 600 images consisting of 3 different categories of the traditional Malay women's fashion products which are baju kurung, baju kebaya, and tudung used for the system.
     * Model Training
     * Import the required libraries and dependencies are critical to ensure a seamless and effective process to trained using the ResNet-50 model for preprocessed images.
     * Feature Extraction
     * The trained model extracts features from the uploaded image.Advance feature augmentation techniques use to enhance the robustness of a machine learning model's feature extraction s using random                    transformations such as rotations, shifts, shear,zoom, and flips to promote stability and generalization for improving its performance across a variety of tasks.
     * Similarity Matching
     * Compare the extracted features with features from the dataset to find similar items.This approach allows the recommendation engine to discover and retrieve objects that closely resemble the visual                 attributes of the user-uploaded image, improving the precision relevance of the recommendations using visual similarities.
     * Recommendation Generation
     * After identifying similar things through the similarity-matching process, the recommendation system suggests these items to the user. The recommendation algorithm improves the experience of the user by            provide image suggestion that is closely related for their interests and stylistic choices, resulting in increased user engagement and satisfaction in the website.
    
     Interface of Recommendation System
     * Welcome Page
       <br>
       <img width="689" height="340" alt="image" src="https://github.com/user-attachments/assets/895b6904-b86d-4118-a0ba-bd164bf5e60e" />
     * Main Page (Recommendation System)
       <br>
       <img width="689" height="334" alt="image" src="https://github.com/user-attachments/assets/49c56d2d-8137-4391-bdd7-b035da1505cf" />

       System Demo
       <br>
       <img width="689" height="318" alt="image" src="https://github.com/user-attachments/assets/1f2495c5-ef83-445f-a409-359b5cd78e30" />
       * Users need to upload their fashion product images by selecting the "browse file" option on this page to upload the file image to get recommendations images based on the image they have uploaded in the             system.
       <br>
       <img width="689" height="497" alt="image" src="https://github.com/user-attachments/assets/a4139f68-e0ce-4d71-9af5-3f292b08f5a3" />
       <br>
       * After the image has been uploaded, the system will suggest a few recommendations based on the image the user has submitted.This enables users to receive fashion product recommendations that are                   appropriate for their preferences,based on the image they have uploaded to the system.

       Final Result
       * Achieve more than 80% match accuracy result between recommended images and uploaded image for all 3 categories (baju kurung,baju kebaya and tudung) using similarity percentage formula using cnn deep               learning.
       * User be able to get good recommendation of fashion products using image based approach instantly in this system to avoid frustration finding fashion products using traditional text search based method.

       


      


     

