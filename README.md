# NLP_Lab_Group7 

# FIFA 19 PLAYER ROLE PREDICTION
We start with an unsupervised model (K-Means Clustering) and then move to a supervised one (Random Forest Classifier) to compare their performance and improve prediction accuracy.


# Project Objectives
- To determine/ poredict whether the player is a defender, outfielder or defender
- To compare and contrast and see which model predicts the dataset better
-Apply Feature scaling and clustering to automatically classify players by their play style using K-Means
- Analyze FIFA 19 player statistics to uncover performance patterns


# Projet Member Names
💫 Project Leader

Adesola Enobong Adegoke — VUG/CSC/23/9079

🧠 K-Means Team

Obiwumma Chukwumeka Pascal — VUG/CSC/24/12422

Hamisu Emmanuella Gambo — VUG/CSC/23/10034

Haruna Success Ojonugwa — VUG/CSC/23/9613

Samuel Dajilak — VUG/CSC/23/9035

⚙️ Data Engineering Squad

Ikechukwu Marvellous Jidechi — VUG/CSC/24/12013

Ogbutu-Hillary Ebube Donald — VUG/CSC/23/10142

Linus Ebube John — VUG/CSC/23/10480

Isioro Oghenekome — VUG/CSC/24/13067

Onyebuchi Victor — VUG/CSC/23/9423

🌲 Random Forest Team

Nneka Maduike — VUG/CSC/24/12708

Lori Scofield Tosan — VUG/CSC/23/9420

Edeh Divine Onyedikachukwu — VUG/CSC/23/10610

Negedu Emmanuel Ojodomo — VUG/CSC/23/10588

Marcelo Anavhe — VUG/CSC/23/8952

🎨 Visualization Team

Jijingi Victor Avadoo — VUG/CSC/23/10385

Umeh Desmond Chukwubunna — VUG/CSC/23/9949

Famolu Ayotomiwa — VUG/CSC/23/9673

Lucky Covenant — VUG/CSC/23/9672

Joseph Daniel Kyubeh — VUG/CSC/23/10408

🧾 Documentation Team

Caleb Charles — VUG/CSC/23/9896

Oluehi Delight — VUG/CSC/23/9564

Joshua Olusola — VUG/CSC/23/9682

Christian Chukwuemeka Ejiasi — VUG/CSC/23/9074

💡 Explainability Team

Okeke Destiny Ifechukwu — VUG/CSC/23/10115

Ogunkuade Olasunkanmi — VUG/CSC/24/12403

Panan Peter Ezekiel — VUG/CSC/23/9680

Isaac Paul — VUG/CSC/23/9619



# Summary of Apporach
The essence of the two model is to predict positions of sport players using the FIFA'19 dataset. The 



# Instructions on how to run the code
    1. Open Jupyter Notebook
 - Launch Anaconda Navigator or run the following command in your terminal:
 "jupyter notebook"

 -Then navigate to where you saved the notebook file.
    2. Open the Project Notebook 
 Load the file named fifa19_role_prediction.ipynb.
    3. Check the Dataset Path 
 Make sure your FIFA 19 dataset path matches the one in the code.

    "data = pd.read_csv('path_to_your/FIFA19.csv')"


-If your dataset is in a different folder, just change the path accordingly.

    4. Install the Required Packages
Run this command in a new cell or in your terminal:

pip install pandas numpy scikit-learn matplotlib seaborn shap


    5. Run the Notebook
Click on the "Kernel" tab, then select "Restart & Run All" to execute all cells.
Sit back and let the notebook train both models and generate the visualizations.

    6. View the Results
You’ll get:

📊 Performance Metrics (Accuracy, F1 Score, etc.)

    7. K-Means vs Random Forest Comparison

🔍 Visualizations including:

Confusion Matrix

Feature Importance Plot

SHAP Value Plot

Actual vs Predicted Role Chart