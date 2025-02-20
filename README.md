This Jupyter Notebook project uses machine learning linear regression from Sklearn to predict the price to rent out a hotel room, being required some features.

The file has multiple boxes, which should be run in order in Jupyter Notebook. Here you can find a tutorial on how to run a Jupyter Notebook project https://youtu.be/r8BXJdE9ChE?si=lSu5zIOUttVggt0r, but there are plenty other tutorials on Youtube. Note that you should first clone the repository on your machine and install all necessary libraries.
There are 25 input data examples(hotels) in hotel_data.csv and 50 in hotel_data2.csv, each with their own features (input) and their price (output) given. The user can input some personal features and run the model to predict the price which could be used to rent out this personal hotel room.
All the other details of the structure and the algorithms are explained next to the code in every box.


The project is inspired by algorithms and ideas presented in the "Machine Learning Specialization" course, by Andrew Ng, from the Coursera official website.
THIS PROJECT IS JUST EXPERIMENTAL, DO NOT RELY ON ITS RESULTS IN THE REAL WORLD.
Formulas used in the code:

StandardScaler (computes z-score normalization):


![11](https://github.com/user-attachments/assets/8e3748d4-77fc-49b8-8643-b1bfce6b890a)



MSE train:


![12](https://github.com/user-attachments/assets/955be34c-adc2-4734-9898-78a034024bfd)


MSE cross-validation:


![13](https://github.com/user-attachments/assets/2cd0e4ee-78d2-4ce6-86c1-ebe9edcad92f)
