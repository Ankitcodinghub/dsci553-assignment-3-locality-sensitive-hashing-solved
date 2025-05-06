# dsci553-assignment-3-locality-sensitive-hashing-solved
**TO GET THIS SOLUTION VISIT:** [DSCI553 Assignment 3-Locality Sensitive Hashing Solved](https://www.ankitcodinghub.com/product/dsci553-assignment-3-locality-sensitive-hashing-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;96083&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;3&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (3 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;DSCI553 Assignment 3-Locality Sensitive Hashing Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (3 votes)    </div>
    </div>
<div class="page" title="Page 1">
<div class="section">
<div class="layoutArea">
<div class="column">
1. Overview of the Assignment

In Assignment 3, you will complete two tasks. The goal is to familiarize you with Locality Sensitive Hashing (LSH), and different types of collaborative-filtering recommendation systems. The dataset you are going to use is a subset from the Yelp dataset used in the previous assignments.

2. Assignment Requirements

2.1 Programming Language and Library Requirements

a. There will be a ​10% bonus for each task (or case) if you also submit a Scala implementation and both your Python and Scala implementations are correct.

b. ​You are required to only use the Spark RDD ​to understand Spark operations. You will not receive any points if you use Spark DataFrame or DataSet.

2.2 Programming Environment

Python 3.6.4, Scala 2.11, JDK 1.8 and Spark 2.4.4

We will use these library versions to compile and test your code. There will be a 20% penalty if we cannot run your code due to the library version inconsistency.

2.3 Write your own code

Do not share your code with other students!!

We will combine all the code we can find from the Web (e.g., GitHub) as well as other students’ code from this and other (previous) sections for plagiarism detection. We will report all the detected plagiarism.

3. Yelp Data

In this assignment, the datasets you are going to use are from:

https://drive.google.com/drive/folders/1SufecRrgj1yWMOVdERmBBUnqz0EX7ARQ?usp=shar ing

We generated the following two datasets from the original Yelp review dataset with some filters. We randomly took 60% of the data as the training dataset, 20% of the data as the validation dataset, and 20% of the data as the testing dataset.

</div>
</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="section">
<div class="layoutArea">
<div class="column">
a. yelp_train.csv: the training data, which only include the columns: user_id, business_id, and stars. b. yelp_val.csv: the validation data, which are in the same format as training data.

c. We are not sharing the test dataset.

d. other datasets: providing additional information (like the average star or location of a business)

4. Tasks

4.1 Task1: Jaccard based LSH (2 points)

In this task, you will implement the Locality Sensitive Hashing algorithm with Jaccard similarity using yelp_train.csv​.

In this task, we focus on the ​“0 or 1” ratings rather than the actual ratings/stars from the users. Specifically, if a user has rated a business, the user’s contribution in the characteristic matrix is 1. If the user hasn’t rated the business, the contribution is 0. ​You need to identify similar businesses whose similarity &gt;= 0.5.

You can define any collection of hash functions that you think would result in a consistent permutation of the row entries of the characteristic matrix. Some potential hash functions are:

f(x)=(ax+b)%m​ or ​f(x)=((ax+b)%p)%m

where p is any prime number and m is the number of bins.​ Please carefully design your hash functions.

After you have defined all the hashing functions, you will build the signature matrix. Then you will divide the matrix into ​b bands with ​r rows each, where ​b x r = n (n is the number of hash functions).​ ​You should carefully select a good combination of ​b and ​r ​in your implementation (b&gt;1 and r&gt;1)​. Remember that two items are a candidate pair if their signatures are identical in at least one band.

Your final results will be the candidate pairs whose original Jaccard similarity is ​&gt;= 0.5​. You need to write the final results into a CSV file according to the output format below.

</div>
</div>
<div class="layoutArea">
<div class="column">
Example of Jaccard Similarity:

user1 user2 user3

</div>
<div class="column">
user4

</div>
</div>
<div class="layoutArea">
<div class="column">
business1 0 1 1 1

business2 0 1 0 0

Jaccard Similarity (business1, business2) = #intersection / #union = 1/3

Input format: (we will use the following command to execute your code)

./spark-submit task1.py &lt;input_file_name&gt; &lt;output_file_name&gt;

Param: input_file_name: the name of the input file (yelp_train.csv), including the file path. Param: output_file_name: the name of the output CSV file, including the file path.

Output format:

IMPORTANT: Please strictly follow the output format since your code will be graded automatically. We will not regrade because of formatting issues.

</div>
</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="section">
<div class="layoutArea">
<div class="column">
a. The output file is a CSV file, containing all business pairs you have found. The header is “business_id_1, business_id_2, similarity”. Each pair itself must be in the alphabetical order. The entire file also needs to be in the alphabetical order. There is no requirement for the number of decimals for the similarity value. Please refer to the format in Figure 2.

Figure 2: a CSV output example for task1

Grading:

We will compare your output file against the ground truth file using ​precision and recall metrics​.

Precision = true positives / (true positives + false positives) Recall = true positives / (true positives + false negatives)

The ground truth file has been provided in the Google drive, named as “pure_jaccard_similarity.csv”. You can use this file to compare your results to the ground truth as well.

The ground truth dataset only contains the business pairs (from the yelp_train.csv) whose Jaccard similarity ​&gt;=0.5​. The business pair itself is sorted in the alphabetical order, so each pair only appears once in the file (i.e., if pair (a, b) is in the dataset, (b, a) will not be there).

In order to get full credit for this task you should have ​precision &gt;= 0.99 and recall &gt;= 0.97​. If not, then you will get only partial credit based on the formula:

(Precision / 0.99) * 0.4 + (Recall / 0.97) * 0.4

Your runtime should be ​less than 100 seconds​. If your runtime is more than or equal to 100 seconds, you will not receive any point for this task.

4.2 Task2: Recommendation System (5 points)

In task 2, you are going to build different types of recommendation systems using the ​yelp_train.csv to predict the ratings/stars for given user ids and business ids. You can make any improvement to your recommendation system in terms of the ​speed and ​accuracy​. You can use the validation dataset (yelp_val.csv) to evaluate the accuracy of your recommendation systems, but please don’t include it as your training data.

There are two options to evaluate your recommendation systems. You can compare your results to the corresponding ground truth and compute the absolute differences. You can divide the absolute differences into 5 levels and count the number for each level as following:

&gt;=0 and &lt;1: 12345 &gt;=1 and &lt;2: 123 &gt;=2 and &lt;3: 1234 &gt;=3 and &lt;4: 1234 &gt;=4: 12

</div>
</div>
</div>
</div>
<div class="page" title="Page 4">
<div class="section">
<div class="layoutArea">
<div class="column">
This means that there are 12345 predictions with &lt; 1 difference from the ground truth. This way you will be able to know the error distribution of your predictions and to improve the performance of your recommendation systems.

Additionally, you can compute the RMSE (Root Mean Squared Error) by using following formula:

Where ​Predi​ is the prediction for business ​i and ​Rate​i is the true rating for business ​i​. n is the total number of the business you are predicting.

In this task, you are required to implement:

Case 1: Item-based CF recommendation system with Pearson similarity (2 points) Case 2: Model-based recommendation system (1 point)

Case 3: Hybrid recommendation system (2 point)

4.2.1. Item-based CF recommendation system

Please strictly follow the slides to implement an item-based recommendation system with Pearson similarity.

4.2.2. Model-based recommendation system

You need to use XGBregressor(a regressor based on the decision tree) to train a model. You need to use

this API ​https://xgboost.readthedocs.io/en/latest/python/python_api.html​, the XGBRegressor inside package xgboost.

Please choose your own features from the provided extra datasets and you can think about it with customer thinking. For example, the average stars rated by a user and the number of reviews most likely influence the prediction result. You need to select other features and train a model based on that. Use the validation dataset to validate your result and remember don’t include it into your training data.

4.2.3. Hybrid recommendation system.

Now that you have the results from previous models, you will need to choose a way from the slides to combine them together and design a better hybrid recommendation system.

Here are two examples of hybrid systems:

Example1:

You can combine them together as a weighted average, which means:

final score = α×scoreitem_based + (1 − α)×scoremodel_based

The key idea is: the CF focuses on the neighbors of the item and the model-based RS focuses on the user

and items themselves. Specifically, if the item has a smaller number of neighbors, then the weight of the CF should be smaller. Meanwhile, if two restaurants both are 4 stars and while the first one has 10 reviews, the second one has 1000 reviews, the average star of the second one is more trustworthy, so

</div>
</div>
</div>
</div>
<div class="page" title="Page 5">
<div class="section">
<div class="layoutArea">
<div class="column">
the model-based RS score should weigh more. You may need to find other features to generate your own weight function to combine them together.

Example2:

You can combine them together as a classification problem:

Again, the key idea is: the CF focuses on the neighbors of the item and the model-based RS focuses on the user and items themselves. As a result, in our dataset, some item-user pairs are more suitable for the CF while the others are not. You need to choose some features to classify which model you should choose for each item-user pair.

If you train a classifier, you are allowed to upload the pre-trained classifier model named “model.md” to save running time on Vocareum. You can use pickle library, joblib library or others if you want. Here is an example: ​https://scikit-learn.org/stable/modules/model_persistence.html​.

You also need to upload the training script named “train.py” to let us verify your model.

Some possible features (other features may also work):

-Average stars of a user, average stars of business, the variance of history review of a user or a business. -Number of reviews of a user or a business.

-Yelp account starting date, number of fans.

-The number of people think a users’ review is useful/funny/cool. Number of compliments (Be careful with these features. For example, sometimes when I visit a horrible restaurant, I will give full stars because I hope I am not the only one who wasted money and time here. Sometimes people are satirical. :-))

Input format: (we will use the following commands to execute your code)

Case1:

./spark-submit task2_1.py &lt;train_file_name&gt; &lt;test_file_name&gt; &lt;output_file_name&gt;

Param: train_file_name: the name of the training file (e.g., yelp_train.csv), including the file path Param: test_file_name: the name of the testing file (e.g., yelp_val.csv), including the file path

Param: output_file_name: the name of the prediction result file, including the file path

Case2:

./spark-submit task2_2.py &lt;folder_path&gt; &lt;test_file_name&gt; &lt;output_file_name&gt;

Param: folder_path: the path of dataset folder, which contains exactly the same file as the google drive. Param: test_file_name: the name of the testing file (e.g., yelp_val.csv), including the file path

Param: output_file_name: the name of the prediction result file, including the file path

Case3:

./spark-submit task2_3.py &lt;folder_path&gt; &lt;test_file_name&gt; &lt;output_file_name&gt;

Param: folder_path: the path of dataset folder, which contains exactly the same file as the google drive. Param: test_file_name: the name of the testing file (e.g., yelp_val.csv), including the file path

</div>
</div>
</div>
</div>
<div class="page" title="Page 6">
<div class="section">
<div class="layoutArea">
<div class="column">
Param: output_file_name: the name of the prediction result file, including the file path

Output format:

a. The output file is a CSV file, containing all the prediction results for ​each user and business pair in the validation/testing data. The header is “user_id, business_id, prediction”. There is no requirement for the order in this task. There is no requirement for the number of decimals for the similarity values. Please refer to the format in Figure 3.

Figure 3: Output example in CSV for task2

</div>
</div>
</div>
</div>
