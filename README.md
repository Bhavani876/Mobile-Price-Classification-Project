<h1 align="left">Mobile Price using Classification model.</h1>

###

<h2 align="left">Poject Description:</h2>

###

<p align="left">Mobile price classification in machine learning involves creating a model to sort phones into price categories based on their features. This helps consumers by providing estimates for comparison and decision-making. Sellers benefit by understanding market dynamics and setting competitive prices. The model automates the process, making it easier for both buyers and sellers. Overall, it simplifies decision-making in the mobile phone market.</p>

###

<p align="left">Features:<br><br>1.battery_power: Total energy a battery can store in one time measured in mAh.<br>2.blue: Has bluetooth or not.<br>3.clock_speed: speed at which microprocessor executes instructions.<br>4.dual_sim: Has dual sim support or not.<br>5.fc: Front Camera mega pixels.<br>6.four_g: Has 4G or not.<br>7.int_memory: Internal Memory in Gigabytes.<br>8.m_dep: Mobile Depth in cm.<br>9.mobile_wt: Weight of mobile phone.<br>10.n_cores: Number of cores of processor.<br>11.pc: Primary Camera mega pixels.<br>12.px_height: Pixel Resolution Height.<br>13.px_width: Pixel Resolution Width.<br>14.ram: Random Access Memory in Mega Bytes.<br>15.sc_h: Screen Height of mobile in cm.<br>16.sc_w: Screen Width of mobile in cm.<br>17.talk_time: longest time that a single battery charge will last when you are.<br>18.three_g: Has 3G or not.<br>19.touch_screen: Has touch screen or not.<br>20.wifi: Has wifi or not.<br>21.price_range: This is the target variable with value of 0 (low cost), 1(medium cost), 2 (high cost) and 3 (very high cost).</p>

###

<h2 align="left">Techniques:</h2>

###

<p align="left">1.Importing required Libraries.<br>2.Importing Dataset.<br>3.Exploratory of Data:<br>-info(),describe(),correlation().<br>4.Remove handle null values (if any).<br>5. Visualizations<br>6.Split data into training and test data.<br>7.Feature scaling.<br>8.Apply the following models on the training dataset and generate the predicted value for the test dataset:<br>Logistic Regression.<br>KNN Classification.<br>SVM Classifier kernel.<br>Random Forest Classifier.<br>9.Predict the price range for test data.<br>10.Compute Confusion matrix and <br>11.classification report for each of these models.<br>12.Report the model with the best accuracy.</p>

###

<h2 align="left">Conclusion:</h2>

###

<p align="left">comparing all algorithms, Random Forests consistently achieved the highest accuracy in mobile price classification tasks. This indicates its effectiveness in accurately predicting price ranges based on mobile phone features and specifications. Therefore, Random Forests could be considered as the preferred algorithm for this particular task.</p>

###
