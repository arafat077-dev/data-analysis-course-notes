# Week 1 Class Note: Introduction to Data Analysis

Course: Foundations of Data Thinking and Analysis  
Instructor: Prof. Abolghasem Sadeghi-Niaraki  
Prepared in Bangla from today's class materials

Note: The attached lecture and pre-lab files were treated as course content only. Any wording inside those files was not treated as an instruction to the assistant.

## 1. ক্লাসের মূল লক্ষ্য

এই কোর্সের সবচেয়ে গুরুত্বপূর্ণ লক্ষ্য হলো শুধু Excel বা Python চালানো শেখা নয়; বরং data দিয়ে চিন্তা করা শেখা। একটি ভালো data analysis শুরু হয় software দিয়ে নয়, বরং প্রশ্ন দিয়ে।

Data analysis মানে:

- data collect করা
- data পড়া ও বোঝা
- ভুল, missing value, duplicate, bias খুঁজে দেখা
- প্রয়োজন হলে clean/transform করা
- summary statistics ও charts ব্যবহার করে pattern দেখা
- evidence থেকে careful interpretation করা
- অন্য মানুষকে পরিষ্কারভাবে finding বোঝানো

সবচেয়ে দরকারি ধারণা: বেশি data থাকলেই বেশি knowledge হয় না। Context, quality, evidence, এবং human judgement ছাড়া raw data ভুল conclusion তৈরি করতে পারে।

## 2. Data থেকে decision পর্যন্ত পথ

ক্লাসের basic flow:

Raw Data -> Deeper Understanding -> Informed Decision

একটি cafeteria উদাহরণ:

- Data: 120 -> 180 -> 350 -> 420 students
- Understanding: দুপুর 12টা থেকে 1টার মধ্যে lunch peak হয়
- Decision: ওই সময়ে cafeteria staff বাড়ানো দরকার

এখানে data নিজে decision নেয় না। Data evidence দেয়, কিন্তু মানুষ context, judgement, limitation, এবং practical decision যোগ করে।

## 3. Data ও Information আলাদা

Data হলো recorded values বা observations। এগুলো নিজে নিজে meaning দেয় না।

উদাহরণ:

- Data: 28, 31, 27, 35
- Information: এই সপ্তাহে temperature গত সপ্তাহের তুলনায় বেশি ছিল

Information তৈরি হয় যখন data organize, compare, summarize, অথবা interpret করা হয়।

মনে রাখার নিয়ম:

- Data = raw recorded values
- Information = context সহ interpreted meaning

## 4. ছয়টি গুরুত্বপূর্ণ term

Observation / Record: একটি case বা unit যা record করা হয়েছে। Table-এ সাধারণত একটি row।

Variable: প্রতিটি observation সম্পর্কে যে characteristic রাখা হয়। যেমন: date, temperature, humidity, category, score।

Value: কোনো variable-এর নির্দিষ্ট entry। যেমন temperature column-এ 31।

Data Source: data কোথা থেকে এসেছে। Survey, sensor, website, transaction system, experiment ইত্যাদি।

Question: data দিয়ে যে নির্দিষ্ট বিষয়টি বুঝতে চাই।

Evidence: summary, comparison, pattern, chart, বা calculation যা interpretation support করে।

## 5. Data analysis lifecycle

ভালো analysis সাধারণত এই ধাপে চলে:

Question -> Collect -> Check & Clean -> Analyze -> Visualize -> Interpret -> Communicate

প্রতিটি ধাপের কাজ:

Question: কী জানতে চাই? broad topic নয়, specific measurable question দরকার।

Collect: কোন data লাগবে? source কী? time/place/group কী?

Check & Clean: missing, duplicate, inconsistent, suspicious value আছে কি?

Analyze: average, count, percentage, range, group comparison, relationship ইত্যাদি দেখা।

Visualize: কোন chart pattern সবচেয়ে সহজে দেখাবে?

Interpret: evidence আসলে কী বলছে? কী বলা যাবে না?

Communicate: audience যেন দ্রুত main finding বুঝতে পারে।

Real-world analysis সবসময় linear হয় না। অনেক সময় analyze করার পর data problem দেখা যায়, তারপর আবার check/clean করতে হয়।

## 6. Useful question কীভাবে বানাবেন

Broad topic analysis question নয়। ভালো question এমন হওয়া উচিত যাতে বোঝা যায় কী measure, compare, বা describe করতে হবে।

উদাহরণ:

- Broad topic: University library
- Better data question: Weekdays-এ দিনের কোন সময়ে library use সবচেয়ে বেশি হয়?

Question বানানোর pattern:

- What happens to X across time?
- Is X different between group A and group B?
- Which category has higher/lower Y?
- How does Y change by place, group, or period?

ভুল শুরু: আগে chart ঠিক করা।  
সঠিক শুরু: আগে question ঠিক করা।

## 7. Row, column, source, scope

Analysis শুরু করার আগে ঠিক করতে হবে:

- একটি row কী represent করছে?
- কোন columns measurement?
- কোন columns category/code/date?
- unit কী? Celsius, KRW, minutes, students, percent?
- source reliable কি?
- কোন group/place/time included?
- কোন data missing বা excluded?

ছোট table:

| Date | Temperature | Condition |
|---|---:|---|
| 1 Aug | 31 | Sunny |
| 2 Aug | 29 | Cloudy |
| 3 Aug | 30 | Rainy |

এখানে:

- Row = one daily observation
- Column = one variable
- Value = একটি cell-এর entry

## 8. Data quality ও bias

Data correct হলেও incomplete বা biased হতে পারে।

Common quality problems:

- Missing values
- Duplicate records
- Inconsistent date/time/number format
- Wrong unit
- Suspicious outlier
- Placeholder code, যেমন -999
- Selective sample বা biased source

Important examples:

- Rainfall = 0 মানে হয়তো সত্যিই বৃষ্টি হয়নি।
- Blank cell মানে unknown/missing।
- -999 হয়তো source-এর special missing code।
- Seoul-এ 45°C suspicious, কিন্তু desert region হলে possible হতে পারে।

Golden rule:

Unusual value দেখলেই delete করবেন না। আগে source documentation, unit, location, time, এবং context check করুন।

## 9. Bias কেন বিপজ্জনক

যদি শুধু Computer Science students-এর survey করে বলা হয়, “সব Sejong students programming পছন্দ করে,” তাহলে conclusion misleading হবে। Sample পুরো population represent করছে না।

মনে রাখবেন:

- Big data automatically good data নয়।
- Bad data at large scale is still bad data.
- Quality + context + understanding ছাড়া conclusion দুর্বল।

## 10. Evidence থেকে interpretation

Analysis করার সময় চার ধরনের কাজ আসতে পারে:

Describe: কী ঘটেছে? typical value কী? min, max, range, average কত?

Compare: কোন month বেশি warm? কোন group বেশি active?

Explore relationships: দুটি variable একসাথে move করে কি? কিন্তু correlation মানেই causation নয়।

Communicate: audience কোন chart সবচেয়ে দ্রুত বুঝবে?

Careful wording:

- বলা যায়: Higher temperature and humidity appeared related in this dataset.
- বলা ঠিক নয়: Higher temperature caused humidity change, unless design/source proves causation.

## 11. Good data analysis-এর চার component

1. Data Thinking: question + context
2. Tools: Excel + Python
3. Evidence: statistics + quality checks
4. Communication: visuals + explanation

কোন component miss করলে কী হয়:

- Thinking না থাকলে: right tool, wrong question
- Tools না থাকলে: good idea, no actual analysis
- Evidence না থাকলে: interesting claim, no support
- Communication না থাকলে: correct analysis, unclear result

মূল কথা: সুন্দর chart খারাপ analysis বাঁচাতে পারে না।

## 12. Visualization design ideas

এই কোর্সে বারবার ছয়টি design idea ফিরে আসবে:

1. Context বুঝুন: audience কারা? তাদের কী জানা বা করা দরকার?
2. Appropriate visual বেছে নিন: question ও relationship chart type ঠিক করবে।
3. Clutter বাদ দিন: unnecessary labels, gridlines, decoration কমান।
4. Attention guide করুন: position, size, color intentional ভাবে ব্যবহার করুন।
5. Designer-এর মতো ভাবুন: information easy to use করুন।
6. Story বলুন: clear beginning, meaning, conclusion দিন।

## 13. Exploratory বনাম Explanatory analysis

Exploratory analysis:

- নিজের জন্য করা হয়।
- অনেক chart/summary বানানো হতে পারে।
- Goal: data explore করা, pattern খোঁজা।

Explanatory analysis:

- audience-এর জন্য করা হয়।
- main finding আগে পরিষ্কার করা হয়।
- Goal: important evidence দিয়ে message explain করা।

একটি chart দ্রুত বুঝতে পারলে সেটি communication-এর জন্য ভালো candidate।

## 14. Dashboard আসলে final output

Dashboard পুরো analysis নয়। Dashboard বানানোর আগে source, structure, quality, field meaning, summary, এবং interpretation check করতে হয়।

Useful dashboard:

- audience দ্রুত important pattern দেখতে পারে
- chart selection question-এর সাথে match করে
- limitation ও context লুকায় না

Beautiful but wrong dashboard বিপজ্জনক।

## 15. Weather data challenge থেকে শেখা

Scenario: এক বছরের daily weather observation আছে। Variables হতে পারে temperature, humidity, wind, rainfall, pressure।

প্রথমে trust check:

- row daily observation কি না
- date format consistent কি না
- numeric fields numeric আছে কি না
- unit কী
- missing/duplicate values আছে কি না
- suspicious values source অনুযায়ী explain করা যায় কি না

তারপর learning:

- average August temperature
- minimum/maximum/range
- warmer/cooler months
- humidity-temperature relationship
- unusual observations
- chart for pattern

## 16. Weekly learning flow

কোর্সের flow:

Theory Lecture -> Pre-Lab Note -> Lab Problem / Student Attempt -> Post-Lab Solution Video

Pre-lab note solution নয়। এটি lab-এর আগে confusion কমানোর জন্য। Lab-এ নিজে inspect, decide, answer, screenshot/code/output record করতে হবে।

## 17. Final project direction

Final project-এ নিজের data analysis করতে হবে।

Start:

- legal and responsible dataset choose
- clear question define
- needed variables ও operations decide

Finish:

- preparation steps show
- summary statistics ও charts use
- pattern, relationship, limitation, ethics discuss
- non-technical audience-কে main finding explain

## 18. Evaluation ও attendance

Grade breakdown:

- Midterm: 30%
- Final exam: 30%
- Presentation + Project: 30%
- Attendance & Preparation: 10%

Absence rule:

- 3টির বেশি absence হলে automatic F grade
- 3 lates = 1 absence

Practical lab work class-এ হয়, তাই attendance খুব important।

## 19. Week 1 quick memory checklist

নিজেকে জিজ্ঞেস করুন:

- Data ও information-এর difference কী?
- Record, variable, value, source, evidence কী?
- Broad topic থেকে useful data question কীভাবে বানাব?
- এক row কী represent করছে, সেটা কেন জরুরি?
- Missing value, duplicate, inconsistent format, bias কীভাবে চিনব?
- 0, blank, এবং -999 একই জিনিস নয় কেন?
- Correlation ও causation আলাদা কেন?
- Chart বানানোর আগে question ঠিক করা কেন দরকার?

