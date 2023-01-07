## Dataset Content
* The dataset is sourced from [Kaggle](https://www.kaggle.com/codeinstitute/cherry-leaves). We created then a fictitious user story where predictive analytics can be applied in a real project in the workplace.
* The dataset contains +4 thousand images taken from client's crop fields. The images show cherry leaves that are healthy and cherry leaves that contain powdery mildew, which is a fungal disease that affects a wide range of plants. The cherry plantation crop is one of their finest products in the portfolio and the company is concerned about supplying the market with a product of compromised quality.



## Business Requirements

Marianne McGuineys, a fictional individual, is the head of IT and Innovation at Farmy & Foods, a company in the agricultural sector that produces and harvests different types of food. Recently, she is facing a challenge where their cherry plantations have been presenting powdery mildew, which is a fungal disease that affects a wide range of plants.

The cherry plantation crop is one of their finest products in the portfolio and the company is concerned about supplying the market with a product of compromised quality.

Currently, the process is to manually verify if a given cherry tree contains powdery mildew. An employee spends around 30 minutes in each tree, taking a few samples of tree leaves and verifying visually if the leaf tree is healthy or has powdery mildew. If it has powdery mildew, the employee applies a specific compound to kill the fungus. The time spent applying this compound is 1 minute. The company has thousands of cherry trees located in multiple farms across the country. As a result, this manual process is not scalable due to time spent in the manual process inspection.

To save time in this process, the IT team suggested an ML system that is capable of detecting instantly, using a tree leaf image, if it is healthy or has powdery mildew. A similar manual process is in place for other crops for detecting pests, and if this initiative is successful, there is a realistic chance to replicate this project to all other crops. The dataset is a collection of cherry leaf images provided by Farmy & Foods, taken from their crops.

* 1 - The client is interested in conducting a study to visually differentiate a cherry leaf that is healthy and that contains powdery mildew.
* 2 - The client is interested to predict if a cherry leaf is healthy or contains powdery mildew.


## Hypothesis and validation
* We suspect mildew infected cherry leaves have unclear marks/signs, the mildew is light roughly-circular, powdery looking patches on young, susceptible leaves.

* An Image Montage, shows that typically mildew infected leaves has white marks across. Average Image, Variability Image and Difference between Averages studies didn't reveal any clear pattern to differentiate one to another.



## Business requirements map to the Data Visualizations and ML tasks
* Business understanding (
* Data understanding
* Data preparation
* Modelling
* Evaluation
* Deployment


## ML Business Case
* In the previous bullet, you potentially visualized a ML task to answer a business requirement. You should frame the business case using the method we covered in the course.


## Dashboard Design
Menu
* Quick Project Summary: 
  Powdery mildew of sweet and sour cherry is caused by Podosphaera clandestina, an obligate biotrophic fungus.
  Mid- and late-season sweet cherry (Prunus avium) cultivars are commonly affected, rendering them unmarketable due to the covering of white fungal growth   on the cherry surface.
  According to WSU, Season long disease control of both leaves and fruit is critical to minimize overall disease pressure in the orchardand consequently to   protect developing fruit from accumulating spores on their surfaces.

* Cherry leave Visualizer:
  The client is interested to have a study to visually differentiate a powdery mildew infected cherry leaf and healthy cherry leaf.
  Difference between average image and variability image.
  Differences between average powdery mildew infected and average healthy leaves.
  Image montage.
  
* Mildew detection:
  The client is interested to tell whether a given leaf contains mildew or not.
  The client can download the dataset of mildew infected cherry leaves and uninfected cherry leaves for live evaluation.
  
* Project Hypothesis:
  We suspect mildew infected cherry leaves have unclear marks/signs, the mildew is light roughly-circular, powdery looking patches on young, susceptible     leaves.
  
* ML Performance Metrics:
  Train, Validation and Test Set: Labels Frequencies


## Unfixed Bugs
* Difficulties to deploy the project on heroku but I found a solution on an alternative plateform Render. Bug fixed and deployment works.
## Deployment
### Render

* The App live link is: https://mildew-detector.onrender.com
* The project was deployed to Render using the following steps.

1. Log in to Render and create an App
2. At the Deploy tab, select GitHub as the deployment method.
3. Select your repository name and click Search. Once it is found, click Connect.
4. Select the branch you want to deploy, then click Create Web Service.
5. Watch the console for some activity, deployment can take up to 15 minutes to complete. Open the deployed site via the link below the WEB SERVICE name.
   

## Main Data Analysis and Machine Learning Libraries
* Here you should list the libraries you used in the project and provide example(s) on how you used these libraries.


## Credits 

* In this section you need to reference where you got your content, media and extra help from. It is common practice to use code from other repositories and tutorials, however, it is important to be very specific about these sources to avoid plagiarism. 
* You can break the credits section up into Content and Media, depending on what you have included in your project. 

### Content 

- The text for the Home page was taken from Wikipedia Article A
- Instructions on how to implement form validation on the Sign Up page was taken from [Specific YouTube Tutorial](https://www.youtube.com/)
- The icons in the footer were taken from [Font Awesome](https://fontawesome.com/)

### Media

- The photos used on the home and sign up page are from This Open Source site
- The images used for the gallery page were taken from this other open source site



## Acknowledgements (optional)
* In case you would like to thank the people that provided support through this project.
