---
title       : Chapter 2 -- Quiz
subtitle    : Thomas Piketty, Capital in the 21st Century (Harvard University Press 2014)
author      : Patrick Toche
framework   : io2012  # minimal, io2012, html5slides, shower, dzslides, ...
mode        : selfcontained  # selfcontained, standalone, draft
highlighter : highlight.js  # highlight.js, prettify, highlight
hitheme     : tomorrow
widgets     : [mathjax, quiz, bootstrap]   # [mathjax, quiz, bootstrap]
url         : {lib: "../../libraries", assets: "../../assets"}
editlink    : "tests/01"

--- &radio

### Question 1

The period of higher world population growth is

1. 
0-1500
2. 
1500-1600
3. 
1600-1700
4. 
1700-1800
5. 
1800-1900
6. 
_1900-2000_


*** .hint
World population in the year 0 was about 300 million. In 1500, it was about 500 million. Current world population is about 7 billion. 

*** .explanation
See Table 2.1.

Based on United Nations estimates (Department of Economic and Social Affairs):
World population in 1500 was about 500 million; in 1600 about 550 million; in 1700 about 600 million; in 1800 about 1 billion; in 1900 about 1.5 billion; in 1925 about 2 billion; in 1950 about 2.5 billion; in 1960 about 3 billion; in 1975 about 4 billion; in 1990 about 5 billion; in 2000 about 6 billion; in 2010 about 7 billion; by 2025 probably about 8 billion; by 2040 probably about 9 billion; by 2060 about 10 billion; some time after 2100 about 11 billion.

--- &radio

### Question 2

The period of higher world output growth is

1. 
0-1500
2. 
1500-1600
3. 
1600-1700
4. 
1700-1800
5. 
1800-1900
6. 
_1900-2000_


*** .hint
The third industrial revolutions spurred larger growth rates than the first and second industrial revolutions.


*** .explanation
See Table 2.1.

--- &radio

### Question 3

An annual growth rate of 1% compounded over 100 years results in a total increase by a factor of

1. 
0.7
2. 
1.7
3. 
_2.7_
4. 
3.7
5. 
4.7
6. 
5.7

*** .hint
An annual growth rate of $g$ compounded $T$ times results in a total ('non-annual') **growth rate** of
$G = (1 + g)^{T} - 1$. 

*** .explanation
An annual growth rate of $0.01$ compounded $100$ times results in a total increase:
$$
1 + G = (1 + 0.01)^{100} \simeq 2.7
$$


--- &radio

### Question 4

An annual growth rate of 10% compounded over 10 years results in a total growth rate of

1. 
0.6
2. 
_1.6_
3. 
2.6
4. 
3.6
5. 
4.6
6. 
5.6

*** .hint
An annual growth rate of $g$ compounded $T$ times results in a total ('non-annual') **growth rate** of
$G = (1 + g)^{T} - 1$. 

*** .explanation
An annual growth rate of $0.10$ compounded $10$ times results in total growth:
$$
G = (1 + 0.1)^{10} - 1 \simeq 1.6\%
$$


--- &radio

### Question 5

Which gives the greater growth? (a) annual growth rate of 1% compounded over 100 years; (b) annual growth rate of 10% compounded over 10 years.

1. 
(a) and (b) give exactly the same growth.
2. 
_(a) and (b) give almost the same growth, but (a) is a little greater._
3. 
(a) and (b) give almost the same growth, but (b) is a little greater.
4. 
(a) and (b) give very different growth, with (a) much greater.
5. 
(a) and (b) give very different growth, with (b) much greater.
6. 
There is not enough information to answer the question.

*** .hint
Precision: 'much' means a more than 20% difference &mdash; 'little' means less than a 10% difference. 

*** .explanation
**Case (a).** 
An annual growth rate of $0.01$ compounded $100$ times gives:
$$
1 + G = (1 + 0.01)^{100} \simeq 2.7
$$
or $G \simeq 1.7\%$

**Case (b).** 
An annual growth rate of $0.10$ compounded $10$ times gives:
$$
1 + G = (1 + 0.1)^{10} \simeq 2.6
$$
or $G \simeq 1.6\%$

The compounding effect is a little larger in case (a).


--- &radio

### Question 6

Which gives the greater average growth rate? (a) annual growth of 1% followed by 2%;  (b) annual growth of 2% followed by 1%.

1. 
_(a) and (b) always give exactly the same average growth rate._
2. 
(a) always gives greater average growth rate than (b).
3. 
(b) always gives greater average growth rate than (a).
4. 
(a) gives a greater rate than (b) if the starting value is greater.
5. 
(b) gives a greater rate than (a) if the starting value is greater.
6. 
There is not enough information to answer the question.

*** .hint
Experiment with a starting value of \\$100. 

*** .explanation
The starting value is irrelevant. The order of the growth episodes is irrelevant. Let $A_{t}$ denote the value at date $t$. Let $g_{t}$ denote the growth rate between date $t$ and date $t+1$. After 1 year, the value has grown to
$$
A_{t+1} = A_{t} (1+g_{t})
$$
After another year,
$$
A_{t+2} = A_{t+1} (1+g_{t+1})
$$
Taken together,
$$
A_{t+2} = A_{t} (1+g_{t}) (1+g_{t+1})
$$
It is clear from the above that the order of the growth rates is irrelevant. 

The overall growth rate is
$$
\frac{A_{t+2} - A_{t}}{A_{t}} = \frac{A_{t+2}}{A_{t}} - 1 =  (1+g_{t}) (1+g_{t+1}) - 1
$$
It is now clear that the starting value is also irrelevant.



--- &radio

### Question 7

An asset initially worth \\$100 (a) rises by 10%, then falls by 10%; (b) falls by 10%, then rises by 10%. What is the final value of the asset?

1. 
\\$101 in both cases.
2. 
\\$100 in both cases.
3. 
_\\$99 in both cases._
4. 
\\$101 in case (a), \\$99 in case (b).
5. 
\\$101 in case (b), \\$99 in case (a).
6. 
There is not enough information to answer the question.

*** .hint
The question assumes the starting value is used as a base &mdash; do not use the mid-point method!

*** .explanation
The order of the growth rates is irrelevant. In both cases, the final value of the asset is
$$
\$100 \times (1 + 0.1) \times (1 - 0.1) = \$100 \times 1.1 \times 0.9 = \$100 \times 0.99 = \$99
$$


--- &radio 

### Question 8

United Nations estimates suggest that world population growth

1. 
averaged 1.8% during 1970-1990, and 1.8% again during 1990-2010.
2. 
averaged 1.3% during 1970-1990, and 1.3% again during 1990-2010.
3. 
rose to 1.3% during 1970-1990, and again to 1.8% during 1990-2010. 
4. 
fell to 1.3% during 1970-1990, and rose to 1.8% during 1990-2010. 
5. 
rose to 1.8% during 1970-1990, and fell to 1.3% during 1990-2010. 
6. 
_fell to 1.8% during 1970-1990, and again to 1.3% during 1990-2010._ 


*** .hint
See Chapter 2.

*** .explanation
See Chapter 2 and Table 2.3.


--- &radio .shrink30

### Question 9

The current structure of employment in the rich countries (U.S., Germany, Japan):  

1. 
Manufacturing accounts for more than 50% of total employment. Services account for less than 30%. Agriculture accounts for less than 5%. 
2. 
Manufacturing accounts for more than 50% of total employment. Services account for more than 30%. Agriculture accounts for less than 5%. 
3. 
Manufacturing accounts for more than 50% of total employment. Services account for more than 30%. Agriculture accounts for more than 5%. 
4. 
_Services account for more than 50% of total employment. Manufacturing accounts for less than 30%. Agriculture accounts for less than 5%._
5. 
Services account for more than 50% of total employment. Manufacturing accounts for more than 30%. Agriculture accounts for less than 5%.
6.  
Services account for more than 50% of total employment. Manufacturing accounts for more than 30%. Agriculture accounts for more than 5%.

*** .hint
See Table 2.4.

*** .explanation
See Chapter 2 and Table 2.4.


--- &radio .shrink10

### Question 10

1. 
_1700-1800 and 1800-1900 were periods of low inflation, while 1913-1950 and 1970-1990 of relatively high inflation (sometimes very high)._ 
2. 
1700-1800 and 1800-1900 were periods of relatively high inflation (sometimes very high), while 1913-1950 and 1970-1990 of low inflation. 
3. 
1700-1800 and 1913-1950 were periods of low inflation, while 1800-1900 and 1970-1990 of relatively high inflation (sometimes very high). 
4. 
1970-1990 and 1990-2010 were periods of low inflation, while 1700-1900 and 1913-1950 of relatively high inflation (sometimes very high). 
5. 
1700-1900 and 1913-1950 were periods of low inflation, while 1970-1990 and 1990-2010 of relatively high inflation (sometimes very high). 

*** .hint
See Figure 2.6.

*** .explanation
See Chapter 2 and Figure 2.6.


--- &radio
### Question 11

Explain the 'law of cumulated growth.' Illustrate with numerical examples.

*** .hint
Carefully distinguish the 'time effect' and the 'compounding effect.'

*** .explanation
A simple explanation of compounding goes like this. Suppose \\$100 grows at an annual rate of 10%. At the end of the year, the sum has grown by \\$10 to \\$110:
$$
100 + 10 = 110
$$
where $ \$10 = 0.01 \times \$100 $

After another year, the sum has grown by \\$11 to \\$121:
$$
110 + 11 = 121
$$
where $ \$11 = 0.01 \times \$110 $

In the second year, the sum grows by \\$11 instead of \\$10, that is an extra dollar. That extra dollar arises because the 'gain' is reinvested. That is 'compounding.'

If you ignored compounding, you would predict a growth of \\$20 only. That prediction is equivalent to:
$$
2 \times 0.01 \times 100 = 20
$$

More generally, ignoring compounding over a period $T$:
$$
T \times 0.01 \times 100 = T
$$
The 'time effect' measures the impact of the passing of time on growth. It is a simple linear effect in that it is proportional to $T$.  

The 'compounding effect' measures the remaining part of the total growth. Table 1.1 gives various numerical examples. By comparing the 'compounding effect' for different values of the growth rate, it becomes apparent that compounding is increasing in the growth rate (it increases more than proportionally as the growth rate is increased). 

Thus, there are 2 ways in which small growth rates lead to large effects: the passing of time and compounding. The compounding effect is larger the larger the growth rate is, and it is larger the longer the time horizon is.


--- &radio
### Question 12

What is the 'demographic transition'? Illustrate with examples based on real-world data.

*** .hint
See Chapter 2.

*** .explanation
See Chapter 2.


--- &radio
### Question 13

The annual growth rate of real income per person in Western Europe, Canada, and the United States over the period 1700-1950 was below 2%. Yet that is a time of industrial revolutions, of unprecedented population growth, of electricity, of trains, of cars, of planes. The annual growth rate of real income per person in the United Kingdom, Germany, and France over the period 1950-1970 was above 4% (more than twice as large). Yet that is the end of the British empire, of the French empire, a time of military defeats and loss of international influence. Explain this 'paradox.'

*** .hint
See Chapter 2.

*** .explanation
The economies of Western Europe had been greatly disturbed by the war. Entire industries disappeared to give way to the war industry. Bombing destroyed factories, bridges, and much of the infrastructure, especially in Germany and France. The high growth rates of 1950-1970 are a consequence of the reconstruction boom (capital accumulation together with a reorganization of labor and education) and, with a delay, the baby boom (population growth). Unlike in the 19th century, technological progress did not play the main part.

