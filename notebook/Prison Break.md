# Helicopter Escapes!

In this project, we'll aim to do a simple data analysis project which will include a proses of:
- Obtaining data from internet
- Cleaning data
- Analyzing data
- Visualizing data

We'll work with a [dataset of helicopter prison escapes](https://en.wikipedia.org/wiki/List_of_helicopter_prison_escapes#Actual_attempts). Here's a data sample:

| Date | Prison name | Country | Succeeded | Escapee(s) | Details |
| --- | --- | --- | --- | --- | --- |
| August 19, 1971 | Santa Martha Acatitla |  ![](//upload.wikimedia.org/wikipedia/commons/thumb/f/fc/Flag_of_Mexico.svg/23px-Flag_of_Mexico.svg.png) [Mexico](https://en.wikipedia.org/wiki/Mexico "Mexico") | Yes | Joel David Kaplan Carlos Antonio Contreras Castro | Joel David Kaplan was a [New York](https://en.wikipedia.org/wiki/New_York_City "New York City") businessman who had been arrested for murder in 1962 in [Mexico City](https://en.wikipedia.org/wiki/Mexico_City "Mexico City") and was incarcerated at the Santa Martha Acatitla prison in the [Iztapalapa](https://en.wikipedia.org/wiki/Iztapalapa "Iztapalapa") borough of Mexico City. Joel's sister, Judy Kaplan, arranged the means to help Kaplan escape, and on August 19, 1971, a helicopter landed in the prison yard. The guards mistakenly thought this was an official visit. In two minutes, Kaplan and his cellmate Carlos Antonio Contreras, a [Venezuelan](https://en.wikipedia.org/wiki/Venezuela "Venezuela") counterfeiter, were able to board the craft and were piloted away, before any shots were fired.<sup id="cite_ref-TimeMexico_9-0" class="reference"><a href="https://en.wikipedia.org/wiki/List_of_helicopter_prison_escapes#cite_note-TimeMexico-9">[9]</a></sup> Both men were flown to [Texas](https://en.wikipedia.org/wiki/Texas "Texas") and then different planes flew Kaplan to [California](https://en.wikipedia.org/wiki/California "California") and Contreras to [Guatemala](https://en.wikipedia.org/wiki/Guatemala "Guatemala").<sup id="cite_ref-Kaplan_3-1" class="reference"><a href="https://en.wikipedia.org/wiki/List_of_helicopter_prison_escapes#cite_note-Kaplan-3">[3]</a></sup> The Mexican government never initiated extradition proceedings against Kaplan.<sup id="cite_ref-TimeMexico_9-1" class="reference"><a href="https://en.wikipedia.org/wiki/List_of_helicopter_prison_escapes#cite_note-TimeMexico-9">[9]</a></sup> The escape is told in a book, _The 10-Second Jailbreak: The Helicopter Escape of Joel David Kaplan_.<sup id="cite_ref-Kaplan_book_4-1" class="reference"><a href="https://en.wikipedia.org/wiki/List_of_helicopter_prison_escapes#cite_note-Kaplan_book-4">[4]</a></sup> It also inspired the 1975 [action movie](https://en.wikipedia.org/wiki/Action_film "Action film") _[Breakout](https://en.wikipedia.org/wiki/Breakout_(1975_film) "Breakout (1975 film)")_, which starred [Charles Bronson](https://en.wikipedia.org/wiki/Charles_Bronson "Charles Bronson") and [Robert Duvall](https://en.wikipedia.org/wiki/Robert_Duvall "Robert Duvall").<sup id="cite_ref-TimeMexico_9-2" class="reference"><a href="https://en.wikipedia.org/wiki/List_of_helicopter_prison_escapes#cite_note-TimeMexico-9">[9]</a></sup> |
| October 31, 1973 | [Mountjoy Jail](https://en.wikipedia.org/wiki/Mountjoy_Jail "Mountjoy Jail") |  ![](//upload.wikimedia.org/wikipedia/commons/thumb/4/45/Flag_of_Ireland.svg/23px-Flag_of_Ireland.svg.png) [Ireland](https://en.wikipedia.org/wiki/Republic_of_Ireland "Republic of Ireland") | Yes | JB O'Hagan [Seamus Twomey](https://en.wikipedia.org/wiki/Seamus_Twomey "Seamus Twomey") Kevin Mallon | On October 31, 1973, an [IRA](https://en.wikipedia.org/wiki/Provisional_Irish_Republican_Army "Provisional Irish Republican Army") member hijacked a helicopter and forced the pilot to land in the exercise yard of Dublin's [Mountjoy Jail](https://en.wikipedia.org/wiki/Mountjoy_Jail "Mountjoy Jail")'s D Wing at 3:40 p.m., October 31, 1973. Three members of the IRA were [able to escape](https://en.wikipedia.org/wiki/1973_Mountjoy_Prison_helicopter_escape "1973 Mountjoy Prison helicopter escape"): [JB O'Hagan](https://en.wikipedia.org/wiki/JB_O%27Hagan "JB O'Hagan"), [Seamus Twomey](https://en.wikipedia.org/wiki/Seamus_Twomey "Seamus Twomey") and [Kevin Mallon](https://en.wikipedia.org/wiki/Kevin_Mallon_(Irish_republican) "Kevin Mallon (Irish republican)"). Another prisoner who also was in the prison was quoted as saying, "One shamefaced screw apologised to the governor and said he thought it was the new Minister for Defence ([Paddy Donegan](https://en.wikipedia.org/wiki/Paddy_Donegan "Paddy Donegan")) arriving. I told him it was our Minister of Defence leaving." The Mountjoy helicopter escape became [Republican lore](https://en.wikipedia.org/wiki/Republican_Movement_(Ireland) "Republican Movement (Ireland)") and was immortalized by "[The Helicopter Song](https://en.wikipedia.org/wiki/The_Helicopter_Song "The Helicopter Song")", which contains the lines "It's up like a bird and over the city. There's three men a'missing I heard the warder say".<sup id="cite_ref-mountjoy_1-1" class="reference"><a href="https://en.wikipedia.org/wiki/List_of_helicopter_prison_escapes#cite_note-mountjoy-1">[1]</a></sup> |
| May 24, 1978 | [United States Penitentiary, Marion](https://en.wikipedia.org/wiki/United_States_Penitentiary,_Marion "United States Penitentiary, Marion") |  ![](//upload.wikimedia.org/wikipedia/en/thumb/a/a4/Flag_of_the_United_States.svg/23px-Flag_of_the_United_States.svg.png) [United States](https://en.wikipedia.org/wiki/United_States "United States") | No | [Garrett Brock Trapnell](https://en.wikipedia.org/wiki/Garrett_Brock_Trapnell "Garrett Brock Trapnell") Martin Joseph McNally James Kenneth Johnson | 43-year-old Barbara Ann Oswald hijacked a [Saint Louis](https://en.wikipedia.org/wiki/St._Louis,_Missouri "St. Louis, Missouri")\-based charter helicopter and forced the pilot to land in the yard at USP Marion. While landing the aircraft, the pilot, Allen Barklage, who was a [Vietnam War](https://en.wikipedia.org/wiki/Vietnam_War "Vietnam War") veteran, struggled with Oswald and managed to wrestle the gun away from her. Barklage then shot and killed Oswald, thwarting the escape.<sup id="cite_ref-St._Joseph_News-Press_10-0" class="reference"><a href="https://en.wikipedia.org/wiki/List_of_helicopter_prison_escapes#cite_note-St._Joseph_News-Press-10">[10]</a></sup> A few months later Oswald's daughter [hijacked TWA Flight 541](https://en.wikipedia.org/wiki/TWA_Flight_541 "TWA Flight 541") in an effort to free Trapnell. |

We'll analyze the data about helicopter prison escapes to answer the following questions:
- Which year did the most helicopter prison break attempts occur?
- Which countries do the most attempted helicopter prison escapes occur?
- Which countries do the helicopter prison breaks have a higher chance of success?
- How does the number of escapees affect the success?
- Which escapees have done it more than once?

### Summary



After analyzing the data, we know that the number of escapees is the most important factor in the success of a helicopter prison break. The more escapees, the higher the chance of success. Given that, the United States and Canada are the country that has highest chance of success in a helicopter prison break, is actually because of most of the attempts are attempted by more than one escapees.


## Obtaining the Data

As mentioned before, the data that we'll be using are available in this [Wikipedia article](https://en.wikipedia.org/wiki/List_of_helicopter_prison_escapes). So, we'll use the `requests` to get the HTML content of the page and the `pandas.read_html()` to parse the HTML content.


```python
# import libraries
import pandas as pd
import numpy as np
import requests

# Get the HTML content from the Wikipedia page
url = "https://en.wikipedia.org/wiki/List_of_helicopter_prison_escapes"
page = requests.get(url) 
```

Now, the HTML content of the page is available in the `page` variable. We'll use the `pandas.read_html()` to parse the HTML content and get the data in a `list` of `DataFrame` objects. We'll store the data in the `attempt_record` variable. We'll also take a look at the first 5 rows of the data and the data types of the columns to get a better understanding of the data.


```python
# Extract the table from the HTML content
attempt_record = pd.read_html(page.text.replace('<br />', ';'))[1] # <br /> is replaced by ; to later split the escapees names
attempt_record.head()
```




<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>Date</th>
      <th>Prison name</th>
      <th>Country</th>
      <th>Succeeded</th>
      <th>Escapee(s)</th>
      <th>Details</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>August 19, 1971</td>
      <td>Santa Martha Acatitla</td>
      <td>Mexico</td>
      <td>Yes</td>
      <td>Joel David Kaplan Carlos Antonio Contreras Castro</td>
      <td>Joel David Kaplan was a New York businessman w...</td>
    </tr>
    <tr>
      <th>1</th>
      <td>October 31, 1973</td>
      <td>Mountjoy Jail</td>
      <td>Ireland</td>
      <td>Yes</td>
      <td>JB O'Hagan; Seamus Twomey;Kevin Mallon</td>
      <td>On October 31, 1973, an IRA member hijacked a ...</td>
    </tr>
    <tr>
      <th>2</th>
      <td>May 24, 1978</td>
      <td>United States Penitentiary, Marion</td>
      <td>United States</td>
      <td>No</td>
      <td>Garrett Brock Trapnell;Martin Joseph McNally;J...</td>
      <td>43-year-old Barbara Ann Oswald hijacked a Sain...</td>
    </tr>
    <tr>
      <th>3</th>
      <td>February 27, 1981</td>
      <td>Fleury-Mérogis, Essonne, Ile de France</td>
      <td>France</td>
      <td>Yes</td>
      <td>Gérard Dupré;Daniel Beaumont</td>
      <td>With the help of Serge Coutel, Gérard Dupré an...</td>
    </tr>
    <tr>
      <th>4</th>
      <td>May 7, 1981</td>
      <td>Orsainville Prison, Quebec City</td>
      <td>Canada</td>
      <td>No</td>
      <td>Marina Paquet (hijacker);Giles Arseneault (pri...</td>
      <td>Marina Paquet held a sawed off shotgun against...</td>
    </tr>
  </tbody>
</table>
</div>




```python
attempt_record.info()
```

    <class 'pandas.core.frame.DataFrame'>
    RangeIndex: 48 entries, 0 to 47
    Data columns (total 6 columns):
     #   Column       Non-Null Count  Dtype 
    ---  ------       --------------  ----- 
     0   Date         48 non-null     object
     1   Prison name  48 non-null     object
     2   Country      48 non-null     object
     3   Succeeded    48 non-null     object
     4   Escapee(s)   48 non-null     object
     5   Details      48 non-null     object
    dtypes: object(6)
    memory usage: 2.4+ KB


## Cleaning the Data for Analysis

Now, we get a better understanding of the data. We can see that the data is in a good shape. The problem is that both `Date` and `Succeeded` column is in the `str` data type. We'll need to convert the `Date` column data type from `str` into `datetime` and the `Succeeded` columns data type from `str` into `bool`.


```python
# Convert the Date column to datetime
attempt_record["Date"] = pd.to_datetime(attempt_record["Date"])

# Convert the Succeeded column to boolean
attempt_record["Succeeded"] = attempt_record["Succeeded"].map({"Yes": True, "No": False})
```

We don't need the `Details` column. So, we'll drop it. We'll also rename the `Escapee(s)` column to `Escappees` and rename all column into lowercase.


```python
# Remove the Details column
attempt_record.drop(columns=["Details"], inplace=True)

# Rename the columns
attempt_record.rename(columns={"Escapee(s)": "Escappees"}, inplace=True)
attempt_record.columns = [col.lower() for col in attempt_record.columns]
```

Since we want to analyze the escapees who have done it more than once, we'll need to extract the names of the escapees from the `escapees` column. We'll use the `str.split()` to split the names of the escapees and the `explode()` to split the names of the escapees into multiple rows. We'll store the result in the `escapees_attempt` variable.


```python
# Copy the dataframe into a new one
escapees_attempt = attempt_record.copy()

# Split the escapees names
escapees_attempt.replace('—', np.nan, inplace=True) # replace the — with NaN
escapees_attempt["escappees"] = escapees_attempt["escappees"].str.replace("\(hijacker\)|\(prisoner\)", '', regex=True) # remove the (hijacker) and (prisoner) from the names
escapees_attempt["escappees"] = escapees_attempt["escappees"].str.split(";")

# Explode the dataframe
escapees_attempt = escapees_attempt.explode("escappees")
escapees_attempt["escappees"] = escapees_attempt["escappees"].str.strip() # remove the leading and trailing spaces
escapees_attempt = escapees_attempt[escapees_attempt["escappees"].str.len() > 0] # remove the empty rows
```

Now, let's take a look at the data before proceeding to the analysis.


```python
attempt_record.head()
```




<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>date</th>
      <th>prison name</th>
      <th>country</th>
      <th>succeeded</th>
      <th>escappees</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>1971-08-19</td>
      <td>Santa Martha Acatitla</td>
      <td>Mexico</td>
      <td>True</td>
      <td>Joel David Kaplan Carlos Antonio Contreras Castro</td>
    </tr>
    <tr>
      <th>1</th>
      <td>1973-10-31</td>
      <td>Mountjoy Jail</td>
      <td>Ireland</td>
      <td>True</td>
      <td>JB O'Hagan; Seamus Twomey;Kevin Mallon</td>
    </tr>
    <tr>
      <th>2</th>
      <td>1978-05-24</td>
      <td>United States Penitentiary, Marion</td>
      <td>United States</td>
      <td>False</td>
      <td>Garrett Brock Trapnell;Martin Joseph McNally;J...</td>
    </tr>
    <tr>
      <th>3</th>
      <td>1981-02-27</td>
      <td>Fleury-Mérogis, Essonne, Ile de France</td>
      <td>France</td>
      <td>True</td>
      <td>Gérard Dupré;Daniel Beaumont</td>
    </tr>
    <tr>
      <th>4</th>
      <td>1981-05-07</td>
      <td>Orsainville Prison, Quebec City</td>
      <td>Canada</td>
      <td>False</td>
      <td>Marina Paquet (hijacker);Giles Arseneault (pri...</td>
    </tr>
  </tbody>
</table>
</div>




```python
attempt_record.info()
```

    <class 'pandas.core.frame.DataFrame'>
    RangeIndex: 48 entries, 0 to 47
    Data columns (total 5 columns):
     #   Column       Non-Null Count  Dtype         
    ---  ------       --------------  -----         
     0   date         48 non-null     datetime64[ns]
     1   prison name  48 non-null     object        
     2   country      48 non-null     object        
     3   succeeded    48 non-null     bool          
     4   escappees    48 non-null     object        
    dtypes: bool(1), datetime64[ns](1), object(3)
    memory usage: 1.7+ KB



```python
escapees_attempt.head()
```




<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>date</th>
      <th>prison name</th>
      <th>country</th>
      <th>succeeded</th>
      <th>escappees</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>1971-08-19</td>
      <td>Santa Martha Acatitla</td>
      <td>Mexico</td>
      <td>True</td>
      <td>Joel David Kaplan Carlos Antonio Contreras Castro</td>
    </tr>
    <tr>
      <th>1</th>
      <td>1973-10-31</td>
      <td>Mountjoy Jail</td>
      <td>Ireland</td>
      <td>True</td>
      <td>JB O'Hagan</td>
    </tr>
    <tr>
      <th>1</th>
      <td>1973-10-31</td>
      <td>Mountjoy Jail</td>
      <td>Ireland</td>
      <td>True</td>
      <td>Seamus Twomey</td>
    </tr>
    <tr>
      <th>1</th>
      <td>1973-10-31</td>
      <td>Mountjoy Jail</td>
      <td>Ireland</td>
      <td>True</td>
      <td>Kevin Mallon</td>
    </tr>
    <tr>
      <th>2</th>
      <td>1978-05-24</td>
      <td>United States Penitentiary, Marion</td>
      <td>United States</td>
      <td>False</td>
      <td>Garrett Brock Trapnell</td>
    </tr>
  </tbody>
</table>
</div>




```python
escapees_attempt.info()
```

    <class 'pandas.core.frame.DataFrame'>
    Int64Index: 72 entries, 0 to 47
    Data columns (total 5 columns):
     #   Column       Non-Null Count  Dtype         
    ---  ------       --------------  -----         
     0   date         72 non-null     datetime64[ns]
     1   prison name  72 non-null     object        
     2   country      72 non-null     object        
     3   succeeded    72 non-null     bool          
     4   escappees    72 non-null     object        
    dtypes: bool(1), datetime64[ns](1), object(3)
    memory usage: 2.9+ KB


Great! Now, we have the data in a good shape for analysis.

## Analyzing the Data

Before we start analyzing the data, we'll need import visualization libraries. We'll use the `matplotlib` and `seaborn` for visualization.


```python
# import libraries
from matplotlib import pyplot as plt
import seaborn as sns

# Set the style
sns.set_style("whitegrid")
```

## First Question: Which Year Did the Most Helicopter Prison Break Attempts Occur?


```python
# Number of attempts by year
attempt_by_year = (attempt_record.groupby(["date", "succeeded"])
                                    .size() # count the number of rows
                                    .unstack() # create a new column for each value of the succeeded column
                                    .resample("A").sum()) # group data by year and sum the values

# Plot the bar chart
plt.figure(figsize=(15, 5))

sns.barplot(x=attempt_by_year.index.year, 
            y=attempt_by_year[True], 
            color="red", 
            bottom=attempt_by_year[False], # bottom is used to stack the bars
            label="Succeeded")

sns.barplot(x=attempt_by_year.index.year, 
            y=attempt_by_year[False], 
            color="green",
            label="Failed")

plt.title("Helicopter Prison Escapes Success Rate by Year")

plt.legend()

plt.xticks(rotation=45)
plt.xlabel("Year")

plt.ylabel("Number of Attempts")

plt.show()
```


    
![png](Prison%20Break_files/Prison%20Break_28_0.png)
    


As we can see, the most helicopter prison break attempts occurred 4 times in 1986, 2001, 2007, and 2009 while in 2001 and 2007 only one attempt was failed. Surprisingly, most of the attempts were successful which 34 successful attempts out of 48 attempts.

## Second & Third Questions: Which Countries Do the Most Attempted Helicopter Prison Escapes Occur & Which Have a Higher Chance of Success?


```python
# Number of attempts by country
attempts_by_country = (attempt_record.groupby(["country", "succeeded"])
                                        .size() # count the number of rows
                                        .unstack() # create a new column for each value of the succeeded column
                                        .fillna(0)) # replace the NaN with 0

# Total number of attempts by country to sort the dataframe
attempts_by_country["total"] = attempts_by_country.sum(axis=1)
attempts_by_country = attempts_by_country.sort_values(by="total", ascending=False)

# plot the bar chart
sns.barplot(x=attempts_by_country[True], y=attempts_by_country.index, color="red")
sns.barplot(x=attempts_by_country[False], y=attempts_by_country.index, color="green", left=attempts_by_country[True])

plt.show()
```


    
![png](Prison%20Break_files/Prison%20Break_31_0.png)
    


France have the most attempted helicopter prison escapes with 15 attempts followed by the United States with 7 attempts. Even though France have the most attempted helicopter prison escapes, the United States & Canada have the highest chance of success with 6 successful attempts out of 8 attempts for the United States and 3 successful attempts out of 4 attempts for Canada while France 11 successful attempt out of 14 attempts which consideribly high.

This leaves a question does the attempts happen in the same prison? Let's take a look at the data.


```python
# Number of prisons by country
(attempt_record.groupby("country")
                .agg({"country": "count", "prison name": "nunique"})
                .rename(columns={"country": "number of attempts", "prison name": "number of prisons"})
                .sort_values("number of prisons", ascending=False)
)
```




<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>number of attempts</th>
      <th>number of prisons</th>
    </tr>
    <tr>
      <th>country</th>
      <th></th>
      <th></th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>France</th>
      <td>15</td>
      <td>13</td>
    </tr>
    <tr>
      <th>United States</th>
      <td>8</td>
      <td>8</td>
    </tr>
    <tr>
      <th>Belgium</th>
      <td>4</td>
      <td>4</td>
    </tr>
    <tr>
      <th>Canada</th>
      <td>4</td>
      <td>4</td>
    </tr>
    <tr>
      <th>Greece</th>
      <td>4</td>
      <td>3</td>
    </tr>
    <tr>
      <th>Australia</th>
      <td>2</td>
      <td>2</td>
    </tr>
    <tr>
      <th>Brazil</th>
      <td>2</td>
      <td>2</td>
    </tr>
    <tr>
      <th>United Kingdom</th>
      <td>2</td>
      <td>2</td>
    </tr>
    <tr>
      <th>Chile</th>
      <td>1</td>
      <td>1</td>
    </tr>
    <tr>
      <th>Ireland</th>
      <td>1</td>
      <td>1</td>
    </tr>
    <tr>
      <th>Italy</th>
      <td>1</td>
      <td>1</td>
    </tr>
    <tr>
      <th>Mexico</th>
      <td>1</td>
      <td>1</td>
    </tr>
    <tr>
      <th>Netherlands</th>
      <td>1</td>
      <td>1</td>
    </tr>
    <tr>
      <th>Puerto Rico</th>
      <td>1</td>
      <td>1</td>
    </tr>
    <tr>
      <th>Russia</th>
      <td>1</td>
      <td>1</td>
    </tr>
  </tbody>
</table>
</div>



So, almost every single attempts is actually from different prisons. This means that the number of attempts is not the only factor that affects the success of the escape. We'll need to take a look at the number of escapees.

## Question Four: How Does the Number of Escapees Affect the Success?

First we need to extract the number of escapees from the `escapees` column to determine in one attempt(one row) how many escapees are there. We'll use the `str.split()` to split the names of the escapees into a `list` and use the `apply()` function to apply the `len()` function to the `list` to get the number of escapees. We'll store the result in the `number_of_escapees` column.


```python
# Number of escapees
attempt_record["number_of_escapees"] = attempt_record["escappees"].str.split(";").apply(len)
attempt_record.head()
```




<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>date</th>
      <th>prison name</th>
      <th>country</th>
      <th>succeeded</th>
      <th>escappees</th>
      <th>number_of_escapees</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>1971-08-19</td>
      <td>Santa Martha Acatitla</td>
      <td>Mexico</td>
      <td>True</td>
      <td>Joel David Kaplan Carlos Antonio Contreras Castro</td>
      <td>1</td>
    </tr>
    <tr>
      <th>1</th>
      <td>1973-10-31</td>
      <td>Mountjoy Jail</td>
      <td>Ireland</td>
      <td>True</td>
      <td>JB O'Hagan; Seamus Twomey;Kevin Mallon</td>
      <td>3</td>
    </tr>
    <tr>
      <th>2</th>
      <td>1978-05-24</td>
      <td>United States Penitentiary, Marion</td>
      <td>United States</td>
      <td>False</td>
      <td>Garrett Brock Trapnell;Martin Joseph McNally;J...</td>
      <td>3</td>
    </tr>
    <tr>
      <th>3</th>
      <td>1981-02-27</td>
      <td>Fleury-Mérogis, Essonne, Ile de France</td>
      <td>France</td>
      <td>True</td>
      <td>Gérard Dupré;Daniel Beaumont</td>
      <td>2</td>
    </tr>
    <tr>
      <th>4</th>
      <td>1981-05-07</td>
      <td>Orsainville Prison, Quebec City</td>
      <td>Canada</td>
      <td>False</td>
      <td>Marina Paquet (hijacker);Giles Arseneault (pri...</td>
      <td>2</td>
    </tr>
  </tbody>
</table>
</div>




```python
# attempts success rate by the number of escapees
success_rate_by_escapees = attempt_record.groupby("number_of_escapees")["succeeded"].mean()

sns.barplot(x=success_rate_by_escapees.index, y=success_rate_by_escapees.values)
plt.show()
```


    
![png](Prison%20Break_files/Prison%20Break_38_0.png)
    


Wow! We can see that the more escapees, the higher the chance of success. Let's take a closer look at the number of attempt before jumping into a conclusion.


```python
# number of attempts by the number of escapees
attempts_by_number_escapees = attempt_record.groupby(["number_of_escapees", "succeeded"]).size().unstack().fillna(0)

sns.barplot(x=attempts_by_number_escapees.index, y=attempts_by_number_escapees[True], color="red", bottom=attempts_by_number_escapees[False])
sns.barplot(x=attempts_by_number_escapees.index, y=attempts_by_number_escapees[False], color="green")

plt.show()
```


    
![png](Prison%20Break_files/Prison%20Break_40_0.png)
    


Now, we can say for sure that the more escapees, the higher the chance of success. Even though we need more data to make the conclusion more accurate.

Given by our last statement from previous question that the United States & Canada have the highest chance of success. Is it because the United States & Canada have the most escapees in one attempt? Let's take a look at the data.


```python
attempt_record[attempt_record["country"].str.contains("Canada|United States", case=False, regex=True)].sort_values("number_of_escapees", ascending=False)
```




<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>date</th>
      <th>prison name</th>
      <th>country</th>
      <th>succeeded</th>
      <th>escappees</th>
      <th>number_of_escapees</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>29</th>
      <td>2002-12-30</td>
      <td>Las Cucharas prison, Puerto Rico</td>
      <td>United States</td>
      <td>True</td>
      <td>Orlando Cartagena; Jose Rodriguez; Victor Diaz...</td>
      <td>6</td>
    </tr>
    <tr>
      <th>2</th>
      <td>1978-05-24</td>
      <td>United States Penitentiary, Marion</td>
      <td>United States</td>
      <td>False</td>
      <td>Garrett Brock Trapnell;Martin Joseph McNally;J...</td>
      <td>3</td>
    </tr>
    <tr>
      <th>6</th>
      <td>1985-12-19</td>
      <td>Perry Correctional Institution, Pelzer, South ...</td>
      <td>United States</td>
      <td>True</td>
      <td>James Rodney Leonard;William Douglas Ballew;Je...</td>
      <td>3</td>
    </tr>
    <tr>
      <th>12</th>
      <td>1988-07-11</td>
      <td>Santa Fe prison</td>
      <td>United States</td>
      <td>True</td>
      <td>Mahoney Danny ;Francis Mitchell;Randy Lackey</td>
      <td>3</td>
    </tr>
    <tr>
      <th>44</th>
      <td>2014-06-07</td>
      <td>Orsainville Detention Facility, Quebec</td>
      <td>Canada</td>
      <td>True</td>
      <td>Yves Denis;Denis Lefebvre;Serge Pomerleau</td>
      <td>3</td>
    </tr>
    <tr>
      <th>4</th>
      <td>1981-05-07</td>
      <td>Orsainville Prison, Quebec City</td>
      <td>Canada</td>
      <td>False</td>
      <td>Marina Paquet (hijacker);Giles Arseneault (pri...</td>
      <td>2</td>
    </tr>
    <tr>
      <th>14</th>
      <td>1989-08-19</td>
      <td>Arkansas Valley Correctional Facility</td>
      <td>United States</td>
      <td>True</td>
      <td>Ralph Brown;Freddie Gonzales</td>
      <td>2</td>
    </tr>
    <tr>
      <th>15</th>
      <td>1990-06-19</td>
      <td>Kent Penitentiary, British Columbia</td>
      <td>Canada</td>
      <td>True</td>
      <td>Robert Ford;David Thomas</td>
      <td>2</td>
    </tr>
    <tr>
      <th>43</th>
      <td>2013-03-17</td>
      <td>Saint-Jérôme Detention Facility, Quebec</td>
      <td>Canada</td>
      <td>True</td>
      <td>Benjamin Hudon-Barbeau;Danny Provençal</td>
      <td>2</td>
    </tr>
    <tr>
      <th>9</th>
      <td>1986-11-05</td>
      <td>Federal Correctional Institution, Dublin</td>
      <td>United States</td>
      <td>True</td>
      <td>Samantha Lopez</td>
      <td>1</td>
    </tr>
    <tr>
      <th>13</th>
      <td>1989-04-17</td>
      <td>Federal Holding Facility, Miami, FL</td>
      <td>United States</td>
      <td>False</td>
      <td>Ben Kramer</td>
      <td>1</td>
    </tr>
    <tr>
      <th>23</th>
      <td>2000-06-05</td>
      <td>Martin Treatment Center for Sexually Violent P...</td>
      <td>United States</td>
      <td>True</td>
      <td>Steven Whitsett</td>
      <td>1</td>
    </tr>
  </tbody>
</table>
</div>



## Question Five: Which Escapees Have Done It More Than Once?


```python
# top 5 escapees by number of attempts
escapees_attempt.groupby("escappees").size().sort_values(ascending=False).head()
```




    escappees
    Pascal Payet       2
    Michel Vaujour     2
    Marina Paquet      1
    Nordin Benallal    1
    Nikos Maziotis     1
    dtype: int64



So, there is two people who have done it more than once which are Michel Vaujour and Pascal Payet. Let's take a closer look.


```python
attempt_record[attempt_record["escappees"].str.contains("Pascal Payet|Michel Vaujour", case=False, regex=True)]
```




<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>date</th>
      <th>prison name</th>
      <th>country</th>
      <th>succeeded</th>
      <th>escappees</th>
      <th>number_of_escapees</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>8</th>
      <td>1986-05-26</td>
      <td>Prison de la Santé</td>
      <td>France</td>
      <td>True</td>
      <td>Michel Vaujour</td>
      <td>1</td>
    </tr>
    <tr>
      <th>19</th>
      <td>1993-06-17</td>
      <td>Touraine Central Prison, Tours</td>
      <td>France</td>
      <td>False</td>
      <td>Michel Vaujour</td>
      <td>1</td>
    </tr>
    <tr>
      <th>25</th>
      <td>2001-01-19</td>
      <td>Luynes prison</td>
      <td>France</td>
      <td>True</td>
      <td>Pascal Payet</td>
      <td>1</td>
    </tr>
    <tr>
      <th>35</th>
      <td>2007-07-15</td>
      <td>Grasse prison</td>
      <td>France</td>
      <td>True</td>
      <td>Pascal Payet</td>
      <td>1</td>
    </tr>
  </tbody>
</table>
</div>



We see that both Michel Vaujour and Pascal Payet are Frencs escapees. Michel Vaujour is the first one to attempt to escape more than once while the first one is a success the last one is a failure. Then Pascal Payet with all of his attempts are successful.

# Conclusion

In this project, we analyzed the data about helicopter prison escapes. To my surprise, most of the attempts were successful which 34 successful attempts out of 48 attempts. We also found out that the more escapees, the higher the chance of success. Even though we need more data to make the conclusion more accurate. We also found out that there is two people who have done it more than once surprisingly **alone** which are Michel Vaujour and Pascal Payet.


