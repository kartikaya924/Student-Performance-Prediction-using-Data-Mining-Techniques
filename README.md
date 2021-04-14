# Student-Performance-Prediction-using-Data-Mining-Techniques
## Introduction
In this project i tried to identify and evaluate the impact of the Covid-19 pandemic and its subsequent fallout in predicting student’s academic performance using the Eduction Data Mining (EDM).
As a result of the lockdown announced after the spread of the virus, many colleges were forced to adapt to online learning tools. For this, a data set of various undergraduate students was
compiled from March 2021. A Likert-type questionnaire was
administered and large number of responses were gathered from
various primary and secondary resources. This was subsequently
used to validate the proposed methodology. Furthermore, different
classification algorithms were applied and compared with
one another based on their performance concerning the said
methodology. The results show that the excessive use of elearning
tools including smartphones, laptops and tablets have
a significant impact on student performance as well as on their
psychological health.
## Dataset 
Similar to the one used in https://www.sciencedirect.com/science/article/pii/S2352340920309987, a Likert-type questionnaire
was made in the template of a google form (https://docs.google.com/forms/d/e/1FAIpQLSdWs_oPDMZyt4LVbXkCQVMJ-3Q31n1cRp5_cJDW0DKlDK98cw/viewform)
and distributed to undergraduate students through social
media, starting from March 2021. The form
was composed of 5 sections, where each section asked students
questions related to their use of e-learning tools and its impact
on their education. The first section aimed at gathering the student’s
demographic information such as gender, level/year, age
and CGPA (+90%:’4’, 80-89%:’3’, 70-79%:’2’, 60-69%:’1’),
which was used to judge the academic performance of the
student. The second section asked students about the time
they spent using online learning tools (mobiles, tablets and
computers) before and after the pandemic along with its effect
on their concentration level. The third and fourth section aimed
to elicit a response from the students about their sleeping
habits and the effect of the excessive use of digital tools
on their social behaviour. Finally, the form asked students to
respond to questions about the impact of the lockdown on
their psychological state and the effects on their academic
performance. This was later added to our primary dataset.


## Data Mining Techniques used 
1.Decision Tree and Random Forests -
Due to its lesser complexity and simple architecture, decision
trees are widely used in EDM. It consists
of nodes and leaves where data is continuously split in accordance
with certain parameters. Another advantage of decision
tree is that it requires lesser time for data preparation and is
easy to interpret.
Random Forests on the other hand perform classification
by constructing a number of decision trees at training time
using bootstrapping, random subsets of features and average
voting. It is more robust than decision trees and lesser prone
to overfitting.

2. K-nearest neighbors -
It determines the class of the data point through a majority
voting principle. It means that a class label can assigned to
a data point based on it’s distance to it’s nearest neighbors.
Its relatively lesser computation time compared to other classification
techniques and clarity makes it very useful in EDM.

3. Support Vector Machine
It is generally used for smaller datasets and hence perform
relatively faster. In this technique a hyper plane is drawn
which helps to separate two or more different classes. The
decision boundary or Hyperplane is estimated by maximizing
the distance between different groups. The dimension of
the hyperplane depends upon the number of features of the
class. Due to it’s shorter computation time it’s often used to
predict student performance and in other EDM
techniques.




