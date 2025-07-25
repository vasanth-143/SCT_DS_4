# SCT_DS_4
=>UK Road Casualty Data (2023) – A Quick Dive into Road Safety
This little project is all about exploring real-world road casualty data from the **UK Department for Transport (2023)**.

->Using Python and a bit of data viz magic, I tried to find out:
* How severe the road accidents were
* Who got hurt (age and gender)
* What kind of people were most involved (like pedestrians, drivers, passengers)

 ->Dataset
The dataset is called:
**`dft-road-casualty-statistics-casualty-2023.csv`**
It has over **130,000** rows — each one is a person involved in a road accident. Here's what it tells us:
* How bad the injury was (slight, serious, or fatal)
* Age and gender of the person
* What role they had (e.g., pedestrian, driver, passenger)
* A few more details about the type of casualty

-> What Did I Visualize?
With Python (pandas + seaborn + matplotlib), I made a few simple plots:
1. **Casualty Severity** – How many were fatal, serious, or slight?
2. **Casualties by Sex** – More men or women involved?
3. **Age Bands** – Which age groups got hit the hardest?
4. **Top 10 Casualty Types** – Who’s most affected on the road?

 ->How to Run This Yourself
You’ll need:
* Python
* Jupyter Notebook (or Google Colab)
* These libraries:
*pip install pandas matplotlib seaborn*

Then:
* 1. Download the dataset: dft-road-casualty-statistics-casualty-2023.csv
2. Place it in the same folder as your notebook
3. Open the "Road.ipynb" file using Jupyter Notebook
4. Run the cells one by one (Shift + Enter)
