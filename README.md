# Flight Delays in the USA

Anyone that has ever flown before knows the pain of a flight delay.
It's annoying and it can have major consequences for other flights if it's part of a connection.
There's also a chance that you might have needed to get another form of public transport such as a bus or train and having a delayed flight might complicate things.  
  
Therefore it would be interesting to be able to predict wether a given flight is delayed or not.  
It would be even better if we could then give for how long that delay would be, but with the dataset provided that wasn't possible.
Perhaps on a future project.  
For information regarding the dataset, [click here](#Data-Info)

## Sources

https://www.kaggle.com/datasets/jimschacko/airlines-dataset-to-predict-a-delay

## Business Questions  

Let's imagine we work for the Department of Transportation (DOT) and they'd like to answer some questions regarding flights and delays:

  1- Does the airline have an impact on number of flights and percentage of delays?  
  2- Does the deperture hour affect the number of flights and percentage of delays?  
  3- What is the impact of the day of the week on the amount of flights and percentage of delays?  
  4- How does a flight length impact number of flights and percentage of delays?  
  5- Do the airports (origin and destination) affect the amount of flights and percentage of delays?  

There is a notebook file exploring the amount of flights part of the buisness questions
<a href='https://github.com/lukwies/mid-bootcamp-project/blob/main/notebooks/hypothesis_test.ipynb'>
here</a> with the plots stored
<a href='https://github.com/GuiMacc/final_bootcamp_project/tree/main/Plots/EDA'> 
here</a>.

## Prediction  

We're now being hypothetically asked by the DOT to create a model capable of predicting if a given flight is delayed or not
so they can work on a new feature that would display this information to the public.

There is a notebook file conaining the code for the prediction models
<a href='https://github.com/GuiMacc/final_bootcamp_project/blob/main/Notebooks/prediction.ipynb'>
here</a> and images of the resulting confusion matrixes for each plot
<a href='https://github.com/GuiMacc/final_bootcamp_project/tree/main/Plots/ConfusionMatrix'>
here</a>.

## Data-Info

<pre>  
  airline - code of the airline  
  flight_id - numeric flight id  
  airport_from - code of the origin airport  
  airport_to - code of the destination airport  
  departure_hour - hour at which a flight departed  
  part_of_day - above column simply categorized into "morning", "afternoon" or "night"
  flight_length - length of the flight in minutes
  delay - the target column which indicates if a flight was delayed(1) or not(0)
</pre>

<a href='https://github.com/GuiMacc/final_bootcamp_project/blob/main/Notebooks/exploration.ipynb'>
Here</a> is the notebook where the
<a href='https://github.com/GuiMacc/final_bootcamp_project/blob/main/Data/raw/Airlines.csv'>
raw data</a> was transformed into
<a href='https://github.com/GuiMacc/final_bootcamp_project/blob/main/Data/clean/cleaned_airlines.csv'>
cleaned data</a> which containes the information above.

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------

As a final note I want to say this project was made as the final bootcamp project at Ironhack for the Data Analytics course
for which there was a presentation made in tableu which can be found
<a href='https://public.tableau.com/app/profile/guilherme.macedo/viz/f_proj/Dashboard2'>
here </a>.


A massive thank you to all the staff and my classmates for all the happy memories we had in these 2 short months
