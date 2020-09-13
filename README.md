# suicides_in_india
Data analysis to provide insights in order to find solutions to the problem of depression and suicide especially in university students.
In a recent study published in Depression and Anxiety of more than 67,000 college students from more than 100 institutions, one in five students have had thoughts of suicide, with 9% making an attempt and nearly 20% reporting self-injury. One in four students reported being diagnosed with a mental illness. So it  can be directly inferred that sucide may be dependent on the depression.suicide is the second leading cause of death for young people ages 15 to 24.

The dataframe after merging all the datasets looks like this

![Alt text](screenshots/df.PNG?raw=true "DF")

After removing the missing values and outliers, the analysis was made based on different attributes.

There are number of gender differences this is known as gender paradox of suicide. Males are much more likely to take their lives while women have more suicide thoughts.

![Alt text](screenshots/gender.PNG?raw=true "gender")


When children start school, their parents begin to lose the influence they once had. By the teenage years, peers are the most influential group as teenagers navigate finding an identity and figuring out the roles that they play. Unfortunately, teenagers who choose the wrong peer groups can find themselves getting into a lot of trouble.

![Alt text](screenshots/peer.PNG?raw=true "peer")


Regular exercise significantly reduces both suicidal thoughts and attempts among students who are bullied as exercise is a  great way to help improve your overall mental health and ability to cope with mental illness.

![Alt text](screenshots/exercise.PNG?raw=true "exercise")

Highest chances of suicides can be found in teenagers as they have higher peer pressure which in turn leads to depression.

![Alt text](screenshots/age.PNG?raw=true "age")

According to the analysis, it can be seen that if a person is healthy i.e. has a good BMI , does not smoke and does enough exercise(moderate and heavy) then the person has a low  possibility of suicide.

![Alt text](screenshots/isHealthy.PNG?raw=true "isHealthy")

After scaling the data and splitting it into training and testing, the different classification models were applied out of which decision tree performs the best with an accuracy of 85.76%

![Alt text](screenshots/model.PNG?raw=true "model")



