COMPUTER SCIENCE
| T exTbook |   for   C | lass  xI |
| --------- | --------- | -------- |
Reprint 2026-27
Prelims.indd   1 08-Apr-19   10:03:55 AM

11120 – Computer SCienCe
ISBN 978-93-5292-117-1
Textbook for Class XI
First Edition
ALL RIGHTS RESERVED
May 2019 Vaishakha 1941  No part of this publication may be reproduced, stored in a
retrieval system or transmitted, in any form or by any means,
Reprinted electronic, mechanical, photocopying, recording or otherwise
without the prior permission of the publisher.
June 2021 Jyeshtha 1943
 This book is sold subject to the condition that it shall not, by
November 2021 Agrahayana 1943 way of trade, be lent, re-sold, hired out or otherwise disposed
of without the publisher’s consent, in any form of binding or
October 2022 Kartika 1944
cover other than that in which it is published.
March 2024 Chaitra 1946  The correct price of this publication is the price printed on
this page, Any revised price indicated by a rubber stamp or
June 2024 Jyeshtha 1946 by a sticker or by any other means is incorrect and should
be unacceptable.
March 2025 Phalguna 1946
February 2026 Phalguna 1947
OFFICES OF THE PUBLICATION
DIVISION, NCERT
NCERT Campus
Sri Aurobindo Marg
New Delhi 110 016 Phone : 011-26562708
108, 100 Feet Road
Hosdakere Halli Extension
Banashankari III Stage
PD 20T SM Bengaluru 560 085 Phone : 080-26725740
Navjivan Trust Building
P.O.Navjivan
© National Council of Educational Ahmedabad 380 014 Phone : 079-27541446
Research and Training, 2019 CWC Campus
Opp. Dhankal Bus Stop
Panihati
Kolkata 700 114 Phone : 033-25530454
CWC Complex
Maligaon
Guwahati 781 021 Phone : 0361-2674869
Publication Team
Head, Publication : M.V. Srinivasan
` 190.00
Division
Printed on 80 GSM paper Chief Editor : Bijnan Sutar
Chief Business : Amitabh Kumar
Published at the Publication
Manager
Division by the Secretary, National
Chief Production : Deepak Jaiswal
Council of Educational Research
Officer (In charge)
and Training, Sri Aurobindo Marg,
New Delhi 110 016 and printed at Assistant Production : Sayuraj A.R.
Stallion Graphics Pvt. Ltd., D-165, Officer
Sector 63, Noida, Gautam Budh
Nagar, U.P.
Cover and Layout
DTP Cell
Reprint 2026-27
Prelims.indd 2 03-03-2026 10:04:15

Foreword
Computer science as a discipline has evolved over the years and has
emerged as a driving force for socio-economic activities. It has made
continuous inroads into diverse areas — be it business, commerce, science,
technology, sports, health, transportation or education. With the advent
of computer and communication technologies, there has been a paradigm
shift in teaching learning at the school level. The role and relevance of this
discipline is in focus because the expectations from the school pass-outs
have grown to be able to meet the challenges of the twenty-first century.
Today, we are living in an interconnected world where computer-based
applications influence the way we learn, communicate, commute or
even socialise!
There is a demand for software engineers in various fields like
manufacturing, services, etc. Today, there are a large number of successful
startups delivering different services through software applications. All
these have resulted in generating interest for this subject among students
as well as parents.
Development of logical thinking, reasoning and problem-solving skills
are fundamental building blocks for knowledge acquisition at the higher
level. Computer plays a key role in problem solving with focus on logical
representation or reasoning and analysis.
This book focuses on the fundamental concepts and problem-solving
skills while opening a window to the emerging and advanced areas of
computer science. The newly developed syllabus has dealt with the dual
challenge of reducing curricular load as well as introducing this ever
evolving discipline.
As an organisation committed to systemic reforms and continuous
improvement in the quality of its products, NCERT welcomes comments
and suggestions which will enable us to revise the content of the textbook.
HrusHikesH senapaty
Director
New Delhi National Council of Educational
8 August 2018 Research and Training
Reprint 2026-27
Prelims.indd 3 08-Apr-19 10:03:55 AM

Reprint 2026-27
Prelims.indd 4 08-Apr-19 10:03:55 AM

Preface
In the present education system of our country, specialised or discipline-
based courses are introduced at the higher secondary stage. This stage
is crucial as well as challenging because of the transition from general
to discipline-based curriculum. The syllabus at this stage needs to have
sufficient rigour and depth while remaining mindful of the comprehension
level of the learners. Further, the textbook should not be heavily loaded
with content.
Computers have permeated in every facet of life. Study of basic concepts
of computer science has been desirable in education. There are courses
offered in the name of Computer Science, Information and Communication
Technology (ICT), Information Technology (IT), etc., by various boards and
schools up to secondary stage, as optional. These mainly focus on using
computer for word processing, presentation tools and application software.
Computer Science (CS) at the higher secondary stage of school education
is also offered as an optional subject. At this stage, students usually opt
for CS with an aim of pursuing a career in software development or related
areas, after going through professional courses at higher levels. Therefore,
at higher secondary stage, the curriculum of CS introduces basics of
computing and sufficient conceptual background of Computer Science.
The primary focus is on fostering the development of computational
thinking and problem-solving skills. This book has 11 chapters covering
the following broader themes:
• Fundamentals: basic understanding of computer system, hardware
components and software, data representation, number system,
encoding as well as awareness of emerging trends in computer
science.
• Problem-solving: problem analysis, algorithm, flowchart, implementation,
testing and maintenance.
• Programming: basic constructs of a program using Python
programming language — program structure, identifiers, variables,
flow of control, advanced data types, functions.
• Societal impact: awareness of digital footprints, data privacy and
protection, cyber crime, etiquettes in a digital society and implications
on security, privacy, piracy, ethics, values and health concerns.
• Chapters 1, 2, 3, 4 and 11 have two additional components —
(i) activities and (ii) think and reflect for self assessment while learning
as well as to generate further interest in the learner.
Python programming language is introduced that is easy to learn in
interactive and script mode. A number of hands-on examples are given to
gradually explain methodology to solve different types of problems across
the Chapters 5 to 10. The programming examples as well as the exercises
in these chapters are required to be solved in a computer and verify with
the given outputs.
Reprint 2026-27
Prelims.indd 5 08-Apr-19 10:03:55 AM

vi
Group projects through case studies are proposed to solve complex
problems. Peer assessment of these projects will promote peer-learning,
team spirit and responsiveness. Some exercises have been made in case-
study format to promote problem-finding and problem-solving skills.
Box items (light green background) are pinned inside the chapters
either to explain related concepts or to provide additional information
related to the topic covered in that section. However, these box items are
not to be assessed through examinations.
Unicode encoding scheme for Indic scripts have also been introduced
to motivate students to solve problems in public services and the local
micro or small businesses in India.
These chapters have been written by involving practicing teachers as
well as subject experts. These have been iteratively peer-reviewed.
I would like to place on record appreciation for Professor Om Vikas for
leading the review activities of the book as well as for his guidance and
motivation to the development team throughout. Several iterations have
resulted into this book. Thanks are due to the authors and reviewers for
their valuable contribution.
Comments and suggestions are welcome to make this endeavour of par
excellence.
New Delhi rejaul karim BarBHuiya
9 August 2018 Assistant Professor
Department of Education
in Science and Mathematics, NCERT
Reprint 2026-27
Prelims.indd 6 08-Apr-19 10:03:55 AM

Textbook Development Committee
ChIef advIsor
Om Vikas, Professor (Retd.), Former Director, ABV-IIITM, Gwalior, M.P.
MeMbers
Anuradha Khattar, Assistant Professor, Miranda House, University of Delhi
Ashish Dhalwankar, PGT (Computer Science), Centre Point School, Nagpur,
Maharashtra
Chetna Khanna, Freelance Educationist, Delhi
Harita Ahuja, Assistant Professor, Acharya Narendra Dev College, University
of Delhi
Mudasir Wani, Assistant Professor, Government College for Women,
Nawakadal, Srinagar
Pratiksha Majumdar, PGT (Computer Science), School of Scholars, Nagpur,
Maharashtra
Priti Rai Jain, Assistant Professor, Miranda House, University of Delhi
Rinku Kumari, PGT (Computer Science), Kendriya Vidyalaya, Sainik Vihar,
Delhi
Sajid Yousuf Bhat, Assistant Professor, University of Kashmir, J&K
Sarnavi Mahesh, Research Scholar, Universita Del Salento, Italy
Sharanjit Kaur, Associate Professor, Acharya Narendra Dev College,
University of Delhi
Sonali Gogate, Software Consultant, Pune, Maharashtra
Tapasi Ray, Former Global IT Director, Huntsman Corporation, Singapore
Vandana Tyagi, PGT (Computer Science), Kendriya Vidyalaya, JNU, Delhi
MeMber-CoordInaTor
Rejaul Karim Barbhuiya, Assistant Professor, DESM, NCERT, Delhi
Reprint 2026-27
Prelims.indd 7 08-Apr-19 10:03:55 AM

Acknowledgements
The National Council of Educational Research and Training acknowledges
the valuable contributions of the individuals and organisations involved in
the development of Computer Science Textbook for Class XI.
The Council expresses its gratitude to the syllabus development team
including MPS Bhatia, Professor, Netaji Subhas Institute of Technology,
Delhi; T. V. Vijay Kumar, Professor, School of Computer and Systems
Sciences, Jawaharlal Nehru University, New Delhi; Zahid Raza, Associate
Professor, School of Computer and Systems Sciences, Jawaharlal Nehru
University, New Delhi; Vipul Shah, Principal Scientist, Tata Consultancy
Services, and the CSpathshala team; Aasim Zafar, Associate Professor,
Department of Computer Science, Aligarh Muslim University, Aligarh;
Faisal Anwer, Assistant Professor, Department of Computer Science, Aligarh
Muslim University, Aligarh; Smruti Ranjan Sarangi, Associate Professor,
Department of Computer Science and Engineering, Indian Institute of
Technology, Delhi; Vikram Goyal, Associate Professor, Indraprastha
Institute of Information Technology (IIIT), Delhi; Tabrez Nafis, Assistant
Professor, Jamia Hamdard, New Delhi and Mamur Ali, Assistant Professor,
Central Institute of Educational Technology, NCERT, New Delhi.
The Council is thankful to the following resource persons for editing,
reviewing and refining the manuscript of this book — Mukesh Kumar, DPS
RK Puram, Delhi; Gurpreet Kaur, G.D. Goenka Public School, Vasant Kunj,
Delhi; Gautam Sarkar, Modern School, Barakhamba Road, Delhi; Aswin
K. Dash, Mother’s International School, Delhi; Nancy Sehgal, Mata Jai
Kaur Public School, Delhi; Ashish Kumar Srivastava, Assistant Professor,
Department of Education in Science and Mathematics, NCERT, New Delhi;
Neelima Gupta, Professor, Department of Computer Science, University of
Delhi; Anamika Gupta, Assistant Professor, Shaheed Sukhdev College of
Business Studies, University of Delhi. The Council further acknowledges
the contributions of Anuja Krishn, Freelance Editor, for language editing.
The Council also gratefully acknowledges the contributions of Meetu
Sharma, Graphic Designer; Kanika Walecha, DTP Operator; and Pooja,
Junior Project Fellow, in shaping this book. The contributions of the office
of the APC, DESM and Publication division, NCERT, New Delhi, in bringing
out this book are also duly acknowledged.
The Council also acknowledges the contribution of Shilpa Mohan,
Assistant Editor (Contractual) Publication Division, NCERT for copy editing
this book. The efforts of Sadiq Saeed, DTP Operator (Contractual) and
Sachin Tanwar, DTP Operator (Contractual), Publication Division, NCERT,
are also acknowledged.
Reprint 2026-27
Prelims.indd 8 08-Apr-19 10:03:56 AM

Contents
| Foreword                                         |                                           | iii |
| ------------------------------------------------ | ----------------------------------------- | --- |
| PreFace                                          |                                           | v   |
| ChapTer 1 : CoMpuTer sysTeM                      |                                           | 1   |
|                                                  | 1.1 Introduction to Computer System       | 1   |
|                                                  | 1.2 Evolution of Computer                 | 3   |
|                                                  | 1.3 Computer Memory                       | 5   |
|                                                  | 1.4 Data Transfer between Memory and CPU  | 7   |
|                                                  | 1.5 Microprocessors                       | 8   |
|                                                  | 1.6 Data and Information                  | 10  |
|                                                  | 1.7 Software                              | 14  |
|                                                  | 1.8 Operating System                      | 20  |
| ChapTer 2 : enCodIng sCheMes and nuMber sysTeM   |                                           | 27  |
|                                                  | 2.1 Introduction                          | 27  |
|                                                  | 2.2 Number System                         | 30  |
|                                                  | 2.3 Conversion between Number Systems     | 34  |
| ChapTer 3 : eMergIng Trends                      |                                           | 45  |
|                                                  | 3.1 Introduction                          | 45  |
|                                                  | 3.2 Artificial Intelligence (AI)          | 45  |
|                                                  | 3.3 Big Data                              | 49  |
|                                                  | 3.4 Internet of Things (IoT)              | 51  |
|                                                  | 3.5 Cloud Computing                       | 53  |
|                                                  | 3.6 Grid Computing                        | 55  |
|                                                  | 3.7 Blockchains                           | 56  |
| ChapTer 4 : InTroduCTIon To probleM solvIng      |                                           | 61  |
|                                                  | 4.1 Introduction                          | 61  |
|                                                  | 4.2 Steps for Problem Solving             | 62  |
|                                                  | 4.3 Algorithm                             | 64  |
|                                                  | 4.4 Representation of Algorithms          | 65  |
|                                                  | 4.5 Flow of Control                       | 70  |
|                                                  | 4.6 Verifying Algorithms                  | 77  |
|                                                  | 4.7 Comparison of Algorithm               | 79  |
Reprint 2026-27
Prelims.indd   9 08-Apr-19   10:03:56 AM

x
4.8 Coding 80
4.9 Decomposition 81
ChapTer 5 : geTTIng sTarTed wITh pyThon 87
5.1 Introduction to Python 87
5.2 Python Keywords 90
5.3 Identifiers 91
5.4 Variables 91
5.5 Comments 92
5.6 Everything is an Object 93
5.7 Data Types 94
5.8 Operators 99
5.9 Expressions 104
5.10 Statement 106
5.11 Input and Output 107
5.12 Type Conversion 108
5.13 Debugging 112
ChapTer 6 : flow of ConTrol 121
6.1 Introduction 121
6.2 Selection 122
6.3 Indentation 126
6.4 Repetition 127
6.5 Break and Continue Statement 132
6.6 Nested Loops 136
ChapTer 7 : funCTIons 143
7.1 Introduction 143
7.2 Functions 145
7.3 User Defined Functions 146
7.4 Scope of a Variable 158
7.5 Python Standard Library 160
ChapTer 8 : sTrIngs 175
8.1 Introduction 175
8.2 Strings 175
8.3 String Operations 177
8.4 Traversing a String 180
8.5 String Methods and Built-in Functions 180
8.6 Handling Strings 184
Reprint 2026-27
Prelims.indd 10 08-Apr-19 10:03:56 AM

xi
ChapTer 9 : lIsTs 189
9.1 Introduction to List 189
9.2 List Operations 190
9.3 Traversing a List 192
9.4 List Methods and Built-in Functions 193
9.5 Nested Lists 195
9.6 Copying Lists 196
9.7 List as Arguments to Function 197
9.8 List Manipulation 199
ChapTer 10 : Tuples and dICTIonarIes 207
10.1 Introduction to Tuples 207
10.2 Tuple Operations 209
10.3 Tuple Methods and Built-in Functions 211
10.4 Tuple Assignment 212
10.5 Nested Tuples 213
10.6 Tuple Handling 213
10.7 Introduction to Dictionaries 215
10.8 Dictionaries are Mutable 216
10.9 Dictionary Operations 217
10.10 Traversing a Dictionary 217
10.11 Dictionary Methods and Built-in functions 218
10.12 Manipulating Dictionaries 219
ChapTer 11 : soCIeTal IMpaCT 229
11.1 Introduction 229
11.2 Digital Footprints 229
11.3 Digital Society and Netizen 231
11.4 Data Protection 235
11.5 Cyber Crime 239
11.6 Indian Information Technology Act (IT Act) 242
11.7 Impact on Health 242
Reprint 2026-27
Prelims.indd 11 08-Apr-19 10:03:56 AM

Reprint 2026-27
Prelims.indd 12 29-01-2025 2.30.45 PM