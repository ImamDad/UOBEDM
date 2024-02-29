# UOBEDM
Educational data for prediction from underdeveloped regions
Cleaned data of arround 23000 students of Bachelors Degree Program



S.No	Attributes	Ranks	Type
1	Districts	6	Nominal
2	Degree	2	Ordinal
3	Subjects	9	Nominal
4	Optional Subjects	8	Nominal
5	Previous Pass or Fail	0	Nominal
6	Age	0	Ordinal
7	Matric Intermediate Board	5	Nominal
8	Religion	1	Nominal
9	Gender	2	Nominal
10	Registration Type	2	Nominal
11	Matric_Annual_Supply	2	Nominal
12	Matric_Division	5	Ordinal
13	Matric_Major_Subjects	2	Nominal
14	Inter_Annual_Supply	2	Nominal
15	Inter_Division	5	Ordinal
16	Inter_Major_Subjects	2	Nominal
17	BA_Division		Class Value
Table 1 Rank Feature Scores

X1 Division: The province of Baluchistan is subdivided into five distinct divisions: Kalat, Kech, Quetta, Sibi, and Zhob, collectively comprising 33 districts. This study organizes these districts into their corresponding divisions. For example, the Kalat division comprises 7 districts—Mastung, Kalat, Surab, Khuzdar, Kharan, Awaran, and Lasbela. Each division encompasses all the districts falling within its jurisdiction.
X2 Degree: The Bachelor's programs encompass two primary degrees: B.A. (Arts) and B.Sc. (Science). The representation for B.A. is denoted by "A," while "S" represents B.Sc.
X3 Subjects: Students are required to select two elective subjects for B.A. (such as Political Science, Sociology, Economics, Islamiat) and three subjects for B.Sc. (such as Zoology, Chemistry, Botany, Math A, Math B, Geography, Statistics). It's noteworthy that compulsory subjects like English, Pakistan Studies, and Islamiat are common to both programs; hence, information regarding compulsory subjects is not included in this study.
X4 Optional Subjects: The optional subjects, represented by values (English, Urdu, Balochi, Brahvi, Pashto), encompass regional languages that play a significant role in promoting regional and international linguistic diversity within the province.
X5 Previous Pass or Fail: This feature indicates the number of attempts a student has made to pass the Intermediate examination in the past.
X6 Age: The study includes students aged between 18 and 26, considered the ideal range for pursuing a bachelor’s degree. Students are categorized into three age groups: A (18 to 20), B (21 to 23), and C (23 to 26). 
X7 Matric Intermediate Board: This feature denotes the examination board with which the student completed their matriculation and intermediate exams. The five examination boards are "Federal," "Baluchistan," "Punjab," "Khyber," and "Sindh," administration examination processes in Pakistan. 

X8 Religion: Although religion obtained a rank of 1 in the feature engineering matrix, it is acknowledged that religion likely has no direct impact on student's academic performance.
X9 Gender: A key feature with two possible values: ‘M’ for Male and ‘F’ for Female.
X10 Registration Type: This attribute distinguishes between two registration types: ‘R’ for regular students (on-campus) and ‘P’ for private students (off-campus).
X11 Matric Annual Supply: Indicates whether a student passed their matriculation exam on the first attempt ("A" for Annual) or required multiple attempts ("S" for Supplementary).
X12 Matric Divisions: This attribute comprises three possible values representing matriculation grades: A, B, and C.
X13 Matric_Major_Subjects: Major subjects are denoted by "S" for Science and "A" for Arts, reflecting the student's matriculation focus.
X14 Inter_Annual_Supply: Indicates if the student passed their intermediate examination on the first attempt ("A" for Annual) or after multiple attempts ("S" for Supplementary).
X15 Inter_Division: This feature reflects the Intermediate students' results with five different values ranging from "A" to "E."
X16 Inter_Major_Subjects: Identifies the student's area of study in Intermediate, with "S" for Science and "A" for Arts as potential values.
X17 Response Class (BA_Divisions): Serves as the dependent variable or class value, predicting one of three probable values between "A," "B," and "F" based on Distinction thresholds (>=60, >=45, and 45).


this dataset can be used for educational Purposes
