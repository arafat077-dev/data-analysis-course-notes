# Semester Resource Plan: ধাপে ধাপে শেখার রোডম্যাপ

Course: Foundations of Data Thinking and Analysis  
আজকের Week 1 slides-এর semester roadmap থেকে তৈরি

## 1. Resource বাছাইয়ের নিয়ম

আপনি বলেছেন YouTube video পছন্দ করেন, কিন্তু পুরোনো video এবং Indian video সাধারণত skip করেন। তাই এই plan-এ আমি এগুলো follow করেছি:

- সম্ভব হলে 2024 বা তার পরের video আগে রাখা হয়েছে।
- English-language, U.S./Europe/global creator/channel আগে রাখা হয়েছে।
- Tool শেখার ক্ষেত্রে official documentation রাখা হয়েছে, কারণ video পুরোনো হয়ে গেলেও docs updated থাকে।
- কিছু পুরোনো resource শুধু তখনই রাখা হয়েছে যখন topic timeless এবং source খুব strong।

YouTube-এ search করার সময় যদি খুব পুরোনো Excel UI video বা obvious India-based mass tutorial channel আসে, আপনার preference অনুযায়ী skip করতে পারেন।

## 2. প্রতি সপ্তাহের study routine

প্রতি সপ্তাহে একই cycle রাখুন:

1. Lecture-এর আগে 15-20 মিনিট key terms preview করুন।
2. Lecture-এর সময় question, source, variables, evidence, limitation লিখুন।
3. Lab-এর আগে pre-lab note পড়ে planning table fill করুন।
4. Lab-এর সময় raw data আলাদা রাখুন, working copy-তে কাজ করুন, cleaning decision note করুন।
5. Lab attempt করার পর post-lab solution video দেখুন।
6. Weekend-এ “mistake log” update করুন: কী বুঝিনি, কীভাবে ঠিক করলাম।

## Week 1: Data thinking ও analysis lifecycle

লক্ষ্য:

- Data আর information আলাদা করা।
- Analysis flow বোঝা: Question -> Data -> Process -> Evidence -> Interpretation -> Communication।
- Broad topic থেকে measurable question বানানো।

করণীয়:

- 5টি raw data example লিখে information বানান।
- 3টি broad topic নিয়ে specific data question বানান।
- প্রতিটি question-এর জন্য one row, variables, source, possible bias লিখুন।

Resources:

- YouTube: [How I Would Become a Data Analyst if I had to Start Over in 2024 | Alex The Analyst](https://youtu.be/K0-8G3DgjA4)
- YouTube/course listing: [Intro to Data Science - Crash Course for Beginners | freeCodeCamp](https://www.classcentral.com/course/freecodecamp-intro-to-data-science-crash-course-for-beginners-105054)
- Official: [Python For Beginners | Python.org](https://www.python.org/about/gettingstarted/)

সপ্তাহের output:

- Week 1-এর এক পৃষ্ঠার summary।
- Question, row meaning, variables, source, bias নিয়ে একটি table।

## Weeks 2-3: Data collection, quality, basic statistics

লক্ষ্য:

- Data source, sampling, bias, missing value, duplicate, inconsistent value বোঝা।
- Basic descriptive statistics শেখা: count, mean, median, min, max, range, standard deviation।

করণীয়:

- ছোট dataset নিয়ে missing/duplicate/suspicious values mark করুন।
- Summary statistics একবার manually, তারপর Excel-এ calculate করুন।
- Evidence-supported cautious interpretation লিখুন।

Resources:

- YouTube: [Stats You Need to Know as a Data Analyst w/ StatQuest | Avery Smith](https://youtu.be/nqtQUg4mZ9I)
- YouTube index: [StatQuest Statistics Fundamentals](https://statquest.org/video_index.html)
- Reading/practice: [Descriptive Statistics | Data Science Discovery, University of Illinois](https://www.dsdiscovery.web.illinois.edu/learn/Exploratory-Data-Analysis/Descriptive-Statistics/)

সপ্তাহের output:

- Data quality checklist।
- 5টি evidence statement এবং 5টি limitation statement।

## Weeks 4-5: Excel cleaning, transformation, summarization

লক্ষ্য:

- Excel দিয়ে tabular data inspect, clean, transform, summarize করা।
- Tables, filters, remove duplicates, text cleaning, number/date formatting, PivotTables শেখা।

করণীয়:

- Raw sheet এবং working sheet আলাদা করুন।
- Duplicate rows, blank cells, extra spaces, inconsistent categories clean করুন।
- PivotTable summary এবং একটি simple chart বানান।

Resources:

- YouTube: [Learn Excel in Under 3 Hours | Pivot Tables, Lookups, Data Cleaning | Alex The Analyst](https://youtu.be/zXnQNytHCPM)
- YouTube: [Stop Wasting Time! 3 Easy Ways to Remove Blank Rows in Excel | Leila Gharani](https://www.youtube.com/watch?v=3mkfF1pNw0U)
- Tutorial: [How to Clean Data in Excel | My Online Training Hub](https://www.myonlinetraininghub.com/how-to-clean-data-in-excel)
- Official: [Excel Help & Learning | Microsoft Support](https://support.microsoft.com/en-us/excel/)

সপ্তাহের output:

- Cleaned dataset।
- PivotTable summary।
- Cleaning decisions-এর short explanation।

## Weeks 6-7: Python, NumPy, Pandas

লক্ষ্য:

- Python data analysis workflow শেখা।
- NumPy array ও Pandas DataFrame বোঝা।
- File read, data inspect, filtering, grouping, new column create করা।

করণীয়:

- Python environment setup করুন, যদি আগে না থাকে।
- CSV file Pandas-এ read করুন।
- `head`, `info`, `describe`, `shape` ব্যবহার করুন।
- Row filter, column select, groupby, calculated column practice করুন।

Resources:

- YouTube: [Python for Data Analytics - Full Course for Beginners | Luke Barousse](https://youtu.be/wUSDVGivd-8)
- YouTube: [Learn Pandas in Under 3 Hours | Alex The Analyst](https://www.youtube.com/watch?v=cHdVR2UXdVM)
- Official: [The Python Tutorial](https://docs.python.org/3/tutorial/index.html)
- Official: [NumPy absolute basics for beginners](https://numpy.org/doc/stable/user/absolute_beginners.html)
- Official: [pandas Getting Started](https://pandas.pydata.org/docs/getting_started/index.html)

সপ্তাহের output:

- একটি notebook/script: data read, quality check, group summary, clean file export।

## Week 8: Midterm বা review checkpoint

Slides-এ Week 8 আলাদা করে লেখা নেই, কিন্তু evaluation-এ midterm আছে। তাই instructor অন্যভাবে না বললে এটিকে likely review/midterm checkpoint ধরে প্রস্তুতি নিন।

লক্ষ্য:

- Weeks 1-7 revise করা।
- Software ছাড়াও concepts explain করতে পারা।
- Excel বা Python দিয়ে basic cleaning এবং summary করতে পারা।

করণীয়:

- Lifecycle memory থেকে লিখুন।
- এক পৃষ্ঠার formula/command sheet বানান।
- একটি mini dataset Excel এবং Pandas দুইভাবেই practice করুন।

Resources:

- নিজের lecture notes ও lab mistake log।
- Excel, Python, NumPy, Pandas official docs।

সপ্তাহের output:

- Midterm revision sheet।
- 10টি practice question with answer।

## Week 9: Final project dataset ও plan

লক্ষ্য:

- Legal এবং responsible dataset choose করা।
- একটি clear analysis question define করা।
- Workflow এবং pseudocode লেখা।

করণীয়:

- 2-3টি possible dataset shortlist করুন।
- প্রতিটির source, license, variables, missingness, ethical risk check করুন।
- Final presentation-এর জন্য narrow question pick করুন।

Resources:

- Dataset source: [Kaggle Datasets](https://www.kaggle.com/datasets)
- Dataset source: [Our World in Data](https://ourworldindata.org/)
- Video orientation: [How I Would Become a Data Analyst if I had to Start Over in 2024 | Alex The Analyst](https://youtu.be/K0-8G3DgjA4)

সপ্তাহের output:

- One-line proposal।
- Research question।
- Needed variables।
- Workflow and pseudocode।

## Week 10: Visualization

লক্ষ্য:

- 2-3টি clear chart বানানো।
- Question অনুযায়ী chart type choose করা।
- Clutter remove করে audience attention guide করা।

করণীয়:

- Question অনুযায়ী bar, line, scatter, বা boxplot বানান।
- Title/caption-এ finding লিখুন।
- অপ্রয়োজনীয় gridline, label, decoration কমান।

Resources:

- YouTube: [How to Build Data Visualizations That Tell a Story | Lillian Chiu](https://youtu.be/SN8ZHFp_plw)
- Official: [Matplotlib Pyplot Tutorial](https://matplotlib.org/stable/tutorials/pyplot.html)
- Guide: [Storytelling with Data guide to charts and graphs](https://www.storytellingwithdata.com/chart-guide)

সপ্তাহের output:

- 2-3টি charts with finding-based captions।
- কেন ওই chart type বেছে নিয়েছেন তার short note।

## Week 11: Exploratory Data Analysis বা EDA

লক্ষ্য:

- Distribution, spread, pattern, missing value, unusual observation explore করা।
- Summary statistics এবং visual checks একসাথে ব্যবহার করা।

করণীয়:

- `info`, `describe`, missing value count, unique value count করুন।
- Distribution এবং grouped summary plot করুন।
- 3টি possible insight এবং 2টি limitation লিখুন।

Resources:

- YouTube: [Exploratory Data Analysis in Python Using Pandas | Alex The Analyst](https://youtu.be/Liv6eeb1VfE)
- Official: [pandas Getting Started](https://pandas.pydata.org/docs/getting_started/index.html)
- Official: [Seaborn introduction](https://seaborn.pydata.org/tutorial/introduction.html)

সপ্তাহের output:

- EDA notebook/report।
- Pattern এবং unusual values-এর visual summary।

## Week 12: Relationships এবং careful correlation

লক্ষ্য:

- Variables compare করা।
- Correlation carefully interpret করা।
- Unsupported causal claim avoid করা।

করণীয়:

- Numeric relationship-এর জন্য scatterplot বানান।
- Group means carefully compare করুন।
- দরকার হলে “association, not causation” limitation লিখুন।

Resources:

- YouTube: [Stats You Need to Know as a Data Analyst w/ StatQuest | Avery Smith](https://youtu.be/nqtQUg4mZ9I)
- YouTube index: [StatQuest correlation and statistics videos](https://statquest.org/video_index.html)
- Official: [Seaborn: visualizing statistical relationships](https://seaborn.pydata.org/tutorial/relational.html)

সপ্তাহের output:

- Relationship analysis section।
- Correlation/association paragraph with limitations।

## Week 13: Ethics, privacy, bias, citation

লক্ষ্য:

- Privacy risk, bias, unfair representation, weak citation, overclaiming চিনতে পারা।
- Conclusion-এর limit explain করা।

করণীয়:

- Dataset-এ personal/sensitive data আছে কি না check করুন।
- Source citation যোগ করুন।
- Bias এবং limitation section লিখুন।

Resources:

- YouTube/course listing: [Actionable Ethics for Data Scientists | Open Data Science](https://www.classcentral.com/course/youtube-actionable-ethics-for-datascientists-emily-miller-132312)
- Video replay: [Navigating ethical and technical challenges: privacy, bias, harm and accuracy | AI for Good](https://aiforgood.itu.int/event/replay-navigating-the-ethical-and-technical-challenges-of-ai-with-regards-to-data-privacy-bias-harm-and-accuracy/)

সপ্তাহের output:

- Ethics checklist।
- Privacy/bias/limitations paragraph।

## Week 14: Storytelling এবং report draft

লক্ষ্য:

- Analysis-কে one-page report draft-এ পরিণত করা।
- Non-technical audience যেন সহজে main finding বুঝতে পারে।

করণীয়:

- Question এবং context দিয়ে শুরু করুন।
- সবচেয়ে strong evidence দেখান।
- Method briefly explain করুন।
- Finding, limitation, possible next step দিয়ে শেষ করুন।

Resources:

- Guide: [Storytelling with Data chart guide](https://www.storytellingwithdata.com/chart-guide)
- YouTube: [How to Build Data Visualizations That Tell a Story | Lillian Chiu](https://youtu.be/SN8ZHFp_plw)
- Webinar: [Ask Me Anything About Data Storytelling | Yellowfin](https://systemsdigest.com/videos/ask-me-anything-about-data-storytelling)

সপ্তাহের output:

- One-page report draft।
- Slide/story outline।

## Week 15: Final presentation

লক্ষ্য:

- Methods, results, limitations, ethics, এবং key message clearly present করা।

করণীয়:

- Slides simple রাখুন।
- প্রতি chart-এ একটি main message রাখুন।
- 3-5 মিনিট spoken explanation practice করুন।
- Data source, cleaning decisions, limitations নিয়ে প্রশ্নের উত্তর প্রস্তুত করুন।

সপ্তাহের output:

- Final presentation।
- Final project report বা notebook।
- আপনার analysis কী prove করতে পারে এবং কী পারে না, তার clear statement।



