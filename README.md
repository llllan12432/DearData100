# Dear Data 100 – Daily Calorie Intake

This Processing sketch visualises 49 observations of my daily calorie intake over time.

The data was collected using the iOS Notes app and later formatted into a CSV file.

## What the sketch shows
- A red line representing total calories per day  
- Coloured points indicating calorie ranges  
  - Green = low (<500)  
  - Blue = medium (500–1500)  
  - Black = high (>1500)

The axes, spacing, and labels are kept simple so the overall pattern of fluctuation is easy to see.

## How to run
1. Download this repository  
2. Open the folder in **Processing**  
3. Make sure the CSV file is inside the sketch folder  
4. Run `sketch.pde`

---

## AI Assistance Note
I used ChatGPT as a support tool while working on this project.  
It helped me with:
- clarifying Processing syntax  
- suggesting example code for loading my CSV file  
- giving advice on colours and layout based on my own design choices  

All data collection, topic choice, visual decisions, and the final sketch output are my own.  
I tested, modified, and adapted the code myself to fit my dataset.

---

## Topic Statement and Context

My chosen topic for Dear Data 100 is **Daily Calorie Intake**. I have been tracking my food intake for several months, and collecting this data has become a meaningful personal habit. This dataset shows my relationship with food, energy balance, and daily eating patterns, especially during stressful periods at university.

This data is highly individual but completely anonymous, since numbers for calories don’t reveal sensitive personal information. Although I also keep track of my body weight privately, I decided not to include it in the visualisation. Weight is a sensitive type of data, and because my focus is on calories, it isn’t necessary or appropriate to display it.

## Method (Data Collection & Processing)

I recorded the food I ate each day in free-text form, noting:
* The names of foods,
* Their estimated calories,
* Sometimes protein values,
* And occasionally markers like my period.

Some days I logged only total calories, while other days included multiple food items. Because the level of detail of individual food entries was uneven, I focused the visualisation on **daily total calorie intake**, which is consistent across all the data. The data was then formatted into a CSV file and imported into Processing to create a simple and clear line chart.

## Reflection

Recording this data wasn’t troublesome for me. In fact, tracking calories helps me stay aware of my eating habits, so the process feels natural and even useful.

### Ambiguities and Challenges:

1.  **Estimating Calories:** Accurately estimating calories is hard. Many foods don’t match portion sizes on packaging, and calorie tables can vary. To avoid underestimating, I often intentionally over-estimated my intake, which affects precision.
2.  **Uneven Data Detail:** Some days include detailed breakdowns of multiple foods; others have only one total value. A few days also include exercise calories or markers for my period. While the dataset isn’t messy, it is uneven, and this affected what could be visualised clearly.
3.  **Incomplete Protein Data:** I recorded protein only occasionally and eventually stopped tracking it, so it wasn’t suitable for the visualisation.
4.  **Fluctuating Patterns:** My logging habit is stable, but calorie intake naturally fluctuates—especially around my period—which creates sudden peaks or dips that strongly affect the graph scale.
5.  **Privacy:** Even though I also keep weight records, I chose not to show them. This shows the tension between personal relevance and privacy, which is a key idea in the Dear Data project.

Overall, this process showed me that even simple personal data can have ambiguities, missing values, uneven formats, and subjective judgment, which only become clear when you try to visualise it.
