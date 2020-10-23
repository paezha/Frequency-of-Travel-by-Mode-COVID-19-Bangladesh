
<!-- README.md is generated from README.Rmd. Please edit that file -->

# Changes in trip-making frequency by mode during the COVID-19 emergency: evidence from an online survey in Bangladesh

<!-- badges: start -->

<!-- badges: end -->

Shaila Jamal (<jamals16@mcmaster.ca>)  
Antonio Paez (<paezha@mcmaster.ca>)  
School of Geography and Earth Science  
McMaster University  
1280 Main Street West, Hamilton, ON L8S 4K1  
Canada

Paper submitted for peer review to Transport Findings

## Abstract

The COVID-19 pandemic has had a profound impact on mobility in every
country and region around the world. Recent studies help to illuminate
some of the dimensions of change - however, the evidence is still scant
in developing countries. The objective of this paper is to present an
exploratory analysis of the changes in the frequency of trip-making by
mode during the COVID-19 emergency in Bangladesh. The analysis is based
on an online sample conducted during the pandemic, and the results
confirm an overall loss of mobility, especially among younger people, in
the form of reduced trip-making frequency by all modes. In addition, the
results suggest that changes are not uniform across modes, and in
particular the loss of mobility was more pronounced for bus, rickshaw,
and CNG auto-rickshaw. In contrast, there was some adoption of walking
during the pandemic.

## Keywords

  - COVID-19
  - Mobility
  - Trip-making frequency
  - Modes of transportation
  - Transition probabilities
  - Circular plots

# Research Questions and Hypotheses

The spread of the COVID-19 pandemic has led to limitations to movement
in many countries and regions, either because of lock-down policies or
self-censoring by segments of the public. The magnitude of changes in
mobility has been studied by recent research, including DeWeese et al.
(2020) and Molloy et al. (2020). While the evidence available indicates
that although the overall mobility has reduced in much of the world, the
changes were uneven depending on the mode of transportation or the
purpose of the trip (see Lock 2020; Paez 2020). Unfortunately, with few
exceptions, evidence remains more spotty for developing countries, most
of which have large population segments that are less able to absorb
losses in mobility (e.g., Astroza et al. 2020; Huynh 2020; Saha, Barman,
and Chouhan 2020).

The objective of this paper is to investigate changes in the trip-making
frequency by different modes of transportation during the COVID-19
emergency in Bangladesh. Using data from a recent online survey that
asked respondents to report mobility levels before and during the
pandemic, we pose the following questions:

  - Was there a reduction of mobility in Bangladesh during COVID-19?
  - And if so, what forms of transportation were more affected?

This paper is a reproducible research document (see Brunsdon and Comber
2020); the code and data necessary to reproduce the tables and figures
are available in a public repository

# Methods and Data

Data used for this paper come from an online survey, “Exploring the
potential of travel mode change behavior in the post-lock-down and
post-pandemic (COVID-19) period”, conducted during July - August 2020 in
Bangladesh (\(n=800\)). The survey was disseminated through various
electronic means along with a widespread social media campaign and
promotion in various social media sites and groups. In addition to the
respondents’ socio-demographic information, the survey covered different
aspects of travel such as travel behavior before and during COVID-19,
knowledge related to COVID-19, and opinions and perceptions regarding
travel behavior after lock-down and post-pandemic situation.

Like other surveys conducted during COVID-19 (e.g., Astroza et al.
2020), this is a convenience sample. Convenience samples have the
advantage of being quick and cost-efficient and, despite their lower
generalizability, when they are homogeneous they are useful to address
rapidly emerging questions (Fricker and Schonlau 2002; Jager, Putnick,
and Bornstein 2017). This particular data set has an over-representation
of the 16-30 years age group, whereas 37% of the country’s population
belongs to this group (Bangladesh Bureau of Statistics 2015). Also, 66%
of the respondents are male and 32% are females compared to country’s
49:51 male-female ratio (Bangladesh Bureau of Statistics 2015). These
characteristics of the sample are expected in terms of online surveys as
young adults are more familiar with online platforms, especially in the
context of a developing country context. Also, in the case of
Bangladesh, collecting a representative sample remains difficult because
of overall public reluctance to participate, with women’s strong
unwillingness to share their information to unknown parties in
particular in face-to-face interviews (see Jamal, Mohiuddin, and Paez
2020). In fact, compared to Jamal et al. \[(2020); Table 1\], who had
only 15% of responses from females, the online survey used in the
present research achieved greater penetration among women.

In terms of geography, respondents were asked to identify the name of
the district they reside. The resulting sample has 48% of respondents
who live in Dhaka. Although, there are some differences in availability
of transportation services between cities, especially between Dhaka and
cities outside Dhaka, the mode use frequency indicates that only 15%
never used buses and 32% never used ride-hailing services before
COVID-19, which means these modes were available to most of the
respondents and a vast majority has used them to some extent before the
lock-down.

Given the above characteristics, the sample cannot be said to be a
probabilistic random sample, but is rather homogeneous for urban,
younger respondents, and has greater representation from females than
comparable samples obtained from face-to-face interviews in Bangladesh.

The context for the study was the country-wide emergency situation
during COVID-19, with required physical distancing recommendations and
relevant health regulations in place. Bangladesh was under partial
lock-down during the survey period, with only essential services open,
offices running on a rotation basis, all educational institutes closed,
and public transport services running at 50% capacity. For the purpose
of this paper, we use two questions that provide information about
trip-making frequency by eight modes of transportation. The modes are
**car**, **ride-hailing** (e.g., Uber, Pathao), **rickshaw**, **CNG
auto-rickshaw** (a rickshaw-like vehicle powered by compressed natural
gas), **bus**, motorcycle/scooter (hereafter just **motorcycle**),
**walking**, and **bicycle** (there was an additional catch-all category
**other** which we ignore here). Participants in the survey used the
following levels to report their frequency of traveling by each mode
both before and during COVID-19: *Never*, *Rarely*, *Once a week*, *2-3
trips per week*, *4-5 trips per week*, *Almost daily*.

To describe changes in travel frequency by mode in the transition to the
pandemic, we use well-established exploratory data analysis (EDA)
techniques.

# Findings

Figure  shows the number of responses (out of 800) in each trip-making
frequency class by mode of transportation. The white bars and gray bars
are for travel before and during the pandemic, respectively. Considering
travel before the pandemic, travel by rickshaw, and bus were relatively
common for many respondents (few respondents reported *never* using
these modes). The mode most commonly used on a quotidian basis was walk.
In contrast, respondents reported less frequent travel by car,
ride-hailing services, CNG auto-rickshaw, motorcycle, and bicycle.
During the pandemic, we see that while there were reductions in mobility
by car, motorcycle, and bicycle (with more respondents reporting never
traveling by these modes), the changes were relatively minor.

![Number of responses by trip-making frequency class and mode, before
and during
COVID-19](README_files/figure-gfm/column-plot-cases-before-after-1.png)

<table class="table" style="margin-left: auto; margin-right: auto;">

<caption>

Cross-tabulation of counts of travel frequency by mode, before and
during COVID-19

</caption>

<thead>

<tr>

<th style="empty-cells: hide;border-bottom:hidden;" colspan="1">

</th>

<th style="border-bottom:hidden;padding-bottom:0; padding-left:3px;padding-right:3px;text-align: center; " colspan="6">

<div style="border-bottom: 1px solid #ddd; padding-bottom: 5px; ">

During

</div>

</th>

</tr>

<tr>

<th style="text-align:left;">

Before

</th>

<th style="text-align:left;">

Never

</th>

<th style="text-align:left;">

Rarely

</th>

<th style="text-align:left;">

Once a week

</th>

<th style="text-align:left;">

2-3 times per week

</th>

<th style="text-align:left;">

4-5 times per week

</th>

<th style="text-align:left;">

Almost daily

</th>

</tr>

</thead>

<tbody>

<tr grouplength="6">

<td colspan="7" style="border-bottom: 1px solid;">

<strong>car</strong>

</td>

</tr>

<tr>

<td style="text-align:left; padding-left:  2em;" indentlevel="1">

Never

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(0, 0, 4, 0.3) !important;">267</span>

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(251, 132, 95, 0.3) !important;">20</span>

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(253, 154, 106, 0.3) !important;">5</span>

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(254, 159, 109, 0.3) !important;">1</span>

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(254, 159, 109, 0.3) !important;">1</span>

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(254, 157, 108, 0.3) !important;">2</span>

</td>

</tr>

<tr>

<td style="text-align:left; padding-left:  2em;" indentlevel="1">

Rarely

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(0, 0, 4, 0.3) !important;">142</span>

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(79, 18, 123, 0.3) !important;">99</span>

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(246, 109, 92, 0.3) !important;">21</span>

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(251, 134, 97, 0.3) !important;">12</span>

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(252, 142, 100, 0.3) !important;">9</span>

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(254, 159, 109, 0.3) !important;">3</span>

</td>

</tr>

<tr>

<td style="text-align:left; padding-left:  2em;" indentlevel="1">

Once a week

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(165, 49, 126, 0.3) !important;">11</span>

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(0, 0, 4, 0.3) !important;">23</span>

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(39, 18, 89, 0.3) !important;">19</span>

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(224, 76, 103, 0.3) !important;">7</span>

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(254, 159, 109, 0.3) !important;">2</span>

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(252, 141, 99, 0.3) !important;">3</span>

</td>

</tr>

<tr>

<td style="text-align:left; padding-left:  2em;" indentlevel="1">

2-3 times per week

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(180, 54, 122, 0.3) !important;">10</span>

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(0, 0, 4, 0.3) !important;">23</span>

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(224, 76, 103, 0.3) !important;">7</span>

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(236, 88, 96, 0.3) !important;">6</span>

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(211, 67, 110, 0.3) !important;">8</span>

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(254, 159, 109, 0.3) !important;">2</span>

</td>

</tr>

<tr>

<td style="text-align:left; padding-left:  2em;" indentlevel="1">

4-5 times per week

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(254, 159, 109, 0.3) !important;">4</span>

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(101, 26, 128, 0.3) !important;">9</span>

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(246, 111, 92, 0.3) !important;">5</span>

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(222, 73, 104, 0.3) !important;">6</span>

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(0, 0, 4, 0.3) !important;">12</span>

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(254, 159, 109, 0.3) !important;">4</span>

</td>

</tr>

<tr>

<td style="text-align:left; padding-left:  2em;" indentlevel="1">

Almost daily

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(206, 64, 113, 0.3) !important;">6</span>

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(59, 15, 112, 0.3) !important;">15</span>

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(206, 64, 113, 0.3) !important;">6</span>

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(141, 41, 129, 0.3) !important;">10</span>

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(254, 159, 109, 0.3) !important;">0</span>

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(0, 0, 4, 0.3) !important;">20</span>

</td>

</tr>

<tr grouplength="6">

<td colspan="7" style="border-bottom: 1px solid;">

<strong>ride-hailing</strong>

</td>

</tr>

<tr>

<td style="text-align:left; padding-left:  2em;" indentlevel="1">

Never

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(0, 0, 4, 0.3) !important;">254</span>

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(252, 139, 99, 0.3) !important;">13</span>

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(253, 150, 104, 0.3) !important;">6</span>

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(253, 154, 106, 0.3) !important;">4</span>

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(254, 159, 109, 0.3) !important;">0</span>

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(254, 159, 109, 0.3) !important;">0</span>

</td>

</tr>

<tr>

<td style="text-align:left; padding-left:  2em;" indentlevel="1">

Rarely

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(0, 0, 4, 0.3) !important;">192</span>

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(228, 79, 100, 0.3) !important;">44</span>

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(252, 137, 97, 0.3) !important;">12</span>

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(254, 159, 109, 0.3) !important;">1</span>

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(254, 159, 109, 0.3) !important;">1</span>

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(254, 159, 109, 0.3) !important;">1</span>

</td>

</tr>

<tr>

<td style="text-align:left; padding-left:  2em;" indentlevel="1">

Once a week

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(0, 0, 4, 0.3) !important;">60</span>

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(196, 60, 117, 0.3) !important;">20</span>

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(135, 39, 129, 0.3) !important;">31</span>

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(252, 139, 99, 0.3) !important;">3</span>

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(253, 154, 106, 0.3) !important;">1</span>

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(254, 159, 109, 0.3) !important;">0</span>

</td>

</tr>

<tr>

<td style="text-align:left; padding-left:  2em;" indentlevel="1">

2-3 times per week

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(0, 0, 4, 0.3) !important;">49</span>

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(223, 75, 104, 0.3) !important;">12</span>

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(237, 90, 95, 0.3) !important;">9</span>

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(244, 105, 92, 0.3) !important;">7</span>

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(252, 144, 101, 0.3) !important;">2</span>

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(254, 159, 109, 0.3) !important;">0</span>

</td>

</tr>

<tr>

<td style="text-align:left; padding-left:  2em;" indentlevel="1">

4-5 times per week

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(0, 0, 4, 0.3) !important;">28</span>

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(205, 64, 113, 0.3) !important;">10</span>

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(252, 144, 101, 0.3) !important;">3</span>

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(248, 116, 92, 0.3) !important;">5</span>

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(243, 101, 92, 0.3) !important;">6</span>

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(254, 159, 109, 0.3) !important;">2</span>

</td>

</tr>

<tr>

<td style="text-align:left; padding-left:  2em;" indentlevel="1">

Almost daily

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(0, 0, 4, 0.3) !important;">14</span>

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(231, 82, 99, 0.3) !important;">3</span>

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(211, 67, 110, 0.3) !important;">4</span>

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(251, 132, 95, 0.3) !important;">1</span>

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(254, 159, 109, 0.3) !important;">0</span>

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(244, 105, 92, 0.3) !important;">2</span>

</td>

</tr>

<tr grouplength="6">

<td colspan="7" style="border-bottom: 1px solid;">

<strong>rickshaw</strong>

</td>

</tr>

<tr>

<td style="text-align:left; padding-left:  2em;" indentlevel="1">

Never

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(0, 0, 4, 0.3) !important;">51</span>

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(239, 93, 94, 0.3) !important;">9</span>

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(247, 114, 92, 0.3) !important;">6</span>

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(254, 159, 109, 0.3) !important;">0</span>

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(253, 152, 105, 0.3) !important;">1</span>

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(254, 159, 109, 0.3) !important;">0</span>

</td>

</tr>

<tr>

<td style="text-align:left; padding-left:  2em;" indentlevel="1">

Rarely

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(12, 9, 37, 0.3) !important;">64</span>

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(0, 0, 4, 0.3) !important;">70</span>

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(223, 73, 104, 0.3) !important;">18</span>

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(252, 142, 100, 0.3) !important;">4</span>

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(253, 149, 103, 0.3) !important;">3</span>

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(254, 159, 109, 0.3) !important;">1</span>

</td>

</tr>

<tr>

<td style="text-align:left; padding-left:  2em;" indentlevel="1">

Once a week

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(47, 17, 99, 0.3) !important;">36</span>

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(31, 17, 74, 0.3) !important;">38</span>

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(0, 0, 4, 0.3) !important;">45</span>

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(244, 105, 92, 0.3) !important;">9</span>

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(254, 159, 109, 0.3) !important;">3</span>

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(254, 159, 109, 0.3) !important;">3</span>

</td>

</tr>

<tr>

<td style="text-align:left; padding-left:  2em;" indentlevel="1">

2-3 times per week

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(7, 6, 28, 0.3) !important;">34</span>

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(0, 0, 4, 0.3) !important;">36</span>

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(160, 47, 127, 0.3) !important;">18</span>

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(49, 17, 101, 0.3) !important;">29</span>

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(251, 135, 97, 0.3) !important;">6</span>

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(254, 159, 109, 0.3) !important;">4</span>

</td>

</tr>

<tr>

<td style="text-align:left; padding-left:  2em;" indentlevel="1">

4-5 times per week

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(106, 28, 129, 0.3) !important;">21</span>

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(0, 0, 4, 0.3) !important;">30</span>

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(254, 159, 109, 0.3) !important;">7</span>

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(176, 53, 123, 0.3) !important;">16</span>

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(191, 58, 119, 0.3) !important;">15</span>

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(252, 142, 100, 0.3) !important;">8</span>

</td>

</tr>

<tr>

<td style="text-align:left; padding-left:  2em;" indentlevel="1">

Almost daily

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(110, 30, 129, 0.3) !important;">45</span>

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(0, 0, 4, 0.3) !important;">65</span>

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(211, 67, 110, 0.3) !important;">30</span>

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(252, 144, 101, 0.3) !important;">18</span>

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(254, 159, 109, 0.3) !important;">16</span>

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(137, 40, 129, 0.3) !important;">41</span>

</td>

</tr>

<tr grouplength="6">

<td colspan="7" style="border-bottom: 1px solid;">

<strong>CNG auto-rickshaw</strong>

</td>

</tr>

<tr>

<td style="text-align:left; padding-left:  2em;" indentlevel="1">

Never

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(0, 0, 4, 0.3) !important;">176</span>

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(250, 129, 95, 0.3) !important;">14</span>

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(253, 154, 106, 0.3) !important;">3</span>

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(254, 157, 108, 0.3) !important;">1</span>

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(254, 159, 109, 0.3) !important;">0</span>

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(254, 159, 109, 0.3) !important;">0</span>

</td>

</tr>

<tr>

<td style="text-align:left; padding-left:  2em;" indentlevel="1">

Rarely

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(0, 0, 4, 0.3) !important;">213</span>

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(159, 47, 127, 0.3) !important;">95</span>

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(251, 135, 97, 0.3) !important;">14</span>

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(253, 154, 106, 0.3) !important;">4</span>

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(254, 159, 109, 0.3) !important;">1</span>

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(253, 156, 107, 0.3) !important;">3</span>

</td>

</tr>

<tr>

<td style="text-align:left; padding-left:  2em;" indentlevel="1">

Once a week

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(6, 5, 24, 0.3) !important;">36</span>

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(41, 17, 90, 0.3) !important;">31</span>

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(0, 0, 4, 0.3) !important;">38</span>

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(235, 87, 96, 0.3) !important;">9</span>

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(254, 159, 109, 0.3) !important;">2</span>

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(253, 149, 103, 0.3) !important;">3</span>

</td>

</tr>

<tr>

<td style="text-align:left; padding-left:  2em;" indentlevel="1">

2-3 times per week

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(0, 0, 4, 0.3) !important;">29</span>

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(116, 33, 129, 0.3) !important;">18</span>

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(141, 41, 129, 0.3) !important;">16</span>

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(166, 49, 125, 0.3) !important;">14</span>

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(236, 88, 96, 0.3) !important;">8</span>

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(254, 159, 109, 0.3) !important;">3</span>

</td>

</tr>

<tr>

<td style="text-align:left; padding-left:  2em;" indentlevel="1">

4-5 times per week

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(10, 8, 34, 0.3) !important;">13</span>

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(179, 54, 122, 0.3) !important;">6</span>

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(205, 64, 113, 0.3) !important;">5</span>

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(103, 28, 128, 0.3) !important;">9</span>

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(0, 0, 4, 0.3) !important;">14</span>

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(254, 159, 109, 0.3) !important;">1</span>

</td>

</tr>

<tr>

<td style="text-align:left; padding-left:  2em;" indentlevel="1">

Almost daily

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(0, 0, 4, 0.3) !important;">8</span>

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(21, 14, 55, 0.3) !important;">7</span>

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(222, 73, 104, 0.3) !important;">2</span>

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(254, 159, 109, 0.3) !important;">0</span>

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(254, 159, 109, 0.3) !important;">0</span>

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(141, 41, 129, 0.3) !important;">4</span>

</td>

</tr>

<tr grouplength="6">

<td colspan="7" style="border-bottom: 1px solid;">

<strong>bus</strong>

</td>

</tr>

<tr>

<td style="text-align:left; padding-left:  2em;" indentlevel="1">

Never

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(0, 0, 4, 0.3) !important;">116</span>

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(250, 129, 95, 0.3) !important;">9</span>

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(253, 149, 103, 0.3) !important;">3</span>

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(254, 159, 109, 0.3) !important;">0</span>

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(254, 159, 109, 0.3) !important;">0</span>

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(254, 159, 109, 0.3) !important;">0</span>

</td>

</tr>

<tr>

<td style="text-align:left; padding-left:  2em;" indentlevel="1">

Rarely

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(0, 0, 4, 0.3) !important;">155</span>

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(207, 64, 112, 0.3) !important;">46</span>

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(252, 137, 97, 0.3) !important;">9</span>

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(254, 159, 109, 0.3) !important;">0</span>

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(254, 159, 109, 0.3) !important;">0</span>

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(253, 156, 107, 0.3) !important;">1</span>

</td>

</tr>

<tr>

<td style="text-align:left; padding-left:  2em;" indentlevel="1">

Once a week

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(0, 0, 4, 0.3) !important;">73</span>

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(160, 47, 127, 0.3) !important;">32</span>

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(206, 64, 113, 0.3) !important;">22</span>

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(252, 138, 98, 0.3) !important;">4</span>

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(254, 159, 109, 0.3) !important;">0</span>

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(254, 159, 109, 0.3) !important;">0</span>

</td>

</tr>

<tr>

<td style="text-align:left; padding-left:  2em;" indentlevel="1">

2-3 times per week

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(0, 0, 4, 0.3) !important;">43</span>

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(159, 47, 127, 0.3) !important;">19</span>

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(220, 72, 105, 0.3) !important;">11</span>

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(241, 97, 93, 0.3) !important;">7</span>

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(247, 114, 92, 0.3) !important;">5</span>

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(254, 159, 109, 0.3) !important;">0</span>

</td>

</tr>

<tr>

<td style="text-align:left; padding-left:  2em;" indentlevel="1">

4-5 times per week

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(0, 0, 4, 0.3) !important;">60</span>

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(250, 126, 94, 0.3) !important;">6</span>

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(251, 134, 97, 0.3) !important;">5</span>

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(252, 139, 99, 0.3) !important;">4</span>

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(237, 89, 96, 0.3) !important;">12</span>

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(254, 159, 109, 0.3) !important;">1</span>

</td>

</tr>

<tr>

<td style="text-align:left; padding-left:  2em;" indentlevel="1">

Almost daily

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(0, 0, 4, 0.3) !important;">103</span>

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(237, 89, 96, 0.3) !important;">21</span>

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(250, 129, 95, 0.3) !important;">10</span>

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(250, 124, 94, 0.3) !important;">11</span>

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(254, 159, 109, 0.3) !important;">2</span>

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(250, 129, 95, 0.3) !important;">10</span>

</td>

</tr>

<tr grouplength="6">

<td colspan="7" style="border-bottom: 1px solid;">

<strong>motorcycle</strong>

</td>

</tr>

<tr>

<td style="text-align:left; padding-left:  2em;" indentlevel="1">

Never

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(0, 0, 4, 0.3) !important;">467</span>

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(252, 142, 100, 0.3) !important;">22</span>

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(253, 150, 104, 0.3) !important;">12</span>

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(254, 157, 108, 0.3) !important;">3</span>

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(254, 159, 109, 0.3) !important;">1</span>

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(253, 154, 106, 0.3) !important;">8</span>

</td>

</tr>

<tr>

<td style="text-align:left; padding-left:  2em;" indentlevel="1">

Rarely

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(0, 0, 4, 0.3) !important;">44</span>

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(24, 15, 61, 0.3) !important;">38</span>

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(208, 65, 111, 0.3) !important;">13</span>

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(228, 79, 100, 0.3) !important;">10</span>

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(254, 159, 109, 0.3) !important;">0</span>

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(250, 124, 94, 0.3) !important;">4</span>

</td>

</tr>

<tr>

<td style="text-align:left; padding-left:  2em;" indentlevel="1">

Once a week

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(219, 71, 106, 0.3) !important;">11</span>

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(219, 71, 106, 0.3) !important;">11</span>

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(0, 0, 4, 0.3) !important;">34</span>

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(254, 159, 109, 0.3) !important;">3</span>

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(254, 159, 109, 0.3) !important;">3</span>

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(254, 159, 109, 0.3) !important;">3</span>

</td>

</tr>

<tr>

<td style="text-align:left; padding-left:  2em;" indentlevel="1">

2-3 times per week

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(28, 16, 69, 0.3) !important;">13</span>

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(205, 64, 113, 0.3) !important;">6</span>

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(205, 64, 113, 0.3) !important;">6</span>

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(0, 0, 4, 0.3) !important;">15</span>

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(243, 101, 92, 0.3) !important;">4</span>

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(254, 159, 109, 0.3) !important;">2</span>

</td>

</tr>

<tr>

<td style="text-align:left; padding-left:  2em;" indentlevel="1">

4-5 times per week

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(165, 49, 126, 0.3) !important;">6</span>

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(211, 67, 110, 0.3) !important;">4</span>

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(254, 159, 109, 0.3) !important;">0</span>

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(211, 67, 110, 0.3) !important;">4</span>

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(0, 0, 4, 0.3) !important;">14</span>

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(231, 82, 99, 0.3) !important;">3</span>

</td>

</tr>

<tr>

<td style="text-align:left; padding-left:  2em;" indentlevel="1">

Almost daily

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(254, 159, 109, 0.3) !important;">1</span>

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(250, 124, 94, 0.3) !important;">3</span>

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(252, 141, 99, 0.3) !important;">2</span>

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(245, 107, 92, 0.3) !important;">4</span>

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(250, 124, 94, 0.3) !important;">3</span>

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(0, 0, 4, 0.3) !important;">23</span>

</td>

</tr>

<tr grouplength="6">

<td colspan="7" style="border-bottom: 1px solid;">

<strong>walk</strong>

</td>

</tr>

<tr>

<td style="text-align:left; padding-left:  2em;" indentlevel="1">

Never

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(0, 0, 4, 0.3) !important;">17</span>

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(170, 51, 125, 0.3) !important;">7</span>

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(239, 93, 94, 0.3) !important;">3</span>

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(226, 77, 102, 0.3) !important;">4</span>

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(254, 159, 109, 0.3) !important;">0</span>

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(247, 114, 92, 0.3) !important;">2</span>

</td>

</tr>

<tr>

<td style="text-align:left; padding-left:  2em;" indentlevel="1">

Rarely

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(150, 44, 128, 0.3) !important;">26</span>

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(0, 0, 4, 0.3) !important;">53</span>

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(231, 82, 99, 0.3) !important;">13</span>

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(250, 129, 95, 0.3) !important;">6</span>

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(254, 159, 109, 0.3) !important;">2</span>

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(252, 144, 101, 0.3) !important;">4</span>

</td>

</tr>

<tr>

<td style="text-align:left; padding-left:  2em;" indentlevel="1">

Once a week

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(236, 88, 96, 0.3) !important;">12</span>

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(198, 60, 115, 0.3) !important;">19</span>

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(0, 0, 4, 0.3) !important;">54</span>

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(246, 108, 92, 0.3) !important;">9</span>

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(252, 144, 101, 0.3) !important;">4</span>

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(254, 159, 109, 0.3) !important;">2</span>

</td>

</tr>

<tr>

<td style="text-align:left; padding-left:  2em;" indentlevel="1">

2-3 times per week

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(214, 69, 108, 0.3) !important;">10</span>

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(155, 46, 127, 0.3) !important;">14</span>

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(185, 55, 120, 0.3) !important;">12</span>

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(0, 0, 4, 0.3) !important;">26</span>

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(171, 51, 124, 0.3) !important;">13</span>

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(254, 159, 109, 0.3) !important;">4</span>

</td>

</tr>

<tr>

<td style="text-align:left; padding-left:  2em;" indentlevel="1">

4-5 times per week

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(205, 64, 113, 0.3) !important;">7</span>

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(254, 159, 109, 0.3) !important;">3</span>

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(205, 64, 113, 0.3) !important;">7</span>

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(103, 28, 128, 0.3) !important;">11</span>

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(0, 0, 4, 0.3) !important;">16</span>

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(179, 54, 122, 0.3) !important;">8</span>

</td>

</tr>

<tr>

<td style="text-align:left; padding-left:  2em;" indentlevel="1">

Almost daily

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(248, 116, 92, 0.3) !important;">46</span>

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(216, 69, 108, 0.3) !important;">73</span>

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(251, 131, 95, 0.3) !important;">40</span>

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(246, 109, 92, 0.3) !important;">49</span>

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(254, 159, 109, 0.3) !important;">27</span>

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(0, 0, 4, 0.3) !important;">197</span>

</td>

</tr>

<tr grouplength="6">

<td colspan="7" style="border-bottom: 1px solid;">

<strong>bicycle</strong>

</td>

</tr>

<tr>

<td style="text-align:left; padding-left:  2em;" indentlevel="1">

Never

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(0, 0, 4, 0.3) !important;">504</span>

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(252, 144, 101, 0.3) !important;">22</span>

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(253, 155, 107, 0.3) !important;">7</span>

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(254, 157, 108, 0.3) !important;">4</span>

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(254, 159, 109, 0.3) !important;">2</span>

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(254, 157, 108, 0.3) !important;">4</span>

</td>

</tr>

<tr>

<td style="text-align:left; padding-left:  2em;" indentlevel="1">

Rarely

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(0, 0, 4, 0.3) !important;">59</span>

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(70, 16, 120, 0.3) !important;">43</span>

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(200, 62, 115, 0.3) !important;">20</span>

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(253, 146, 102, 0.3) !important;">4</span>

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(254, 159, 109, 0.3) !important;">2</span>

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(253, 146, 102, 0.3) !important;">4</span>

</td>

</tr>

<tr>

<td style="text-align:left; padding-left:  2em;" indentlevel="1">

Once a week

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(92, 22, 127, 0.3) !important;">14</span>

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(108, 29, 129, 0.3) !important;">13</span>

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(0, 0, 4, 0.3) !important;">21</span>

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(249, 121, 93, 0.3) !important;">3</span>

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(252, 139, 99, 0.3) !important;">2</span>

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(254, 159, 109, 0.3) !important;">1</span>

</td>

</tr>

<tr>

<td style="text-align:left; padding-left:  2em;" indentlevel="1">

2-3 times per week

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(165, 49, 126, 0.3) !important;">3</span>

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(117, 33, 129, 0.3) !important;">4</span>

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(72, 16, 120, 0.3) !important;">5</span>

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(0, 0, 4, 0.3) !important;">7</span>

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(211, 67, 110, 0.3) !important;">2</span>

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(254, 159, 109, 0.3) !important;">0</span>

</td>

</tr>

<tr>

<td style="text-align:left; padding-left:  2em;" indentlevel="1">

4-5 times per week

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(246, 111, 92, 0.3) !important;">2</span>

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(246, 111, 92, 0.3) !important;">2</span>

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(181, 54, 122, 0.3) !important;">4</span>

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(254, 159, 109, 0.3) !important;">1</span>

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(0, 0, 4, 0.3) !important;">9</span>

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(222, 73, 104, 0.3) !important;">3</span>

</td>

</tr>

<tr>

<td style="text-align:left; padding-left:  2em;" indentlevel="1">

Almost daily

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(173, 52, 124, 0.3) !important;">7</span>

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(254, 159, 109, 0.3) !important;">1</span>

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(254, 159, 109, 0.3) !important;">1</span>

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(254, 159, 109, 0.3) !important;">1</span>

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(246, 108, 92, 0.3) !important;">3</span>

</td>

<td style="text-align:left;">

<span style=" font-weight: bold;    color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: rgba(0, 0, 4, 0.3) !important;">16</span>

</td>

</tr>

</tbody>

<tfoot>

<tr>

<td style="padding: 0; border: 0;" colspan="100%">

<span style="font-style: italic;">Note: </span>

</td>

</tr>

<tr>

<td style="padding: 0; border: 0;" colspan="100%">

<sup></sup> Darker cell colors indicate higher cell values in a row.

</td>

</tr>

</tfoot>

</table>

The frequency of trip-making by other modes changed more noticeably: the
frequency of travel by ride-hailing services, rickshaw, CNG
auto-rickshaw, and bus collapsed, with vastly more respondents reporting
never using these modes during the pandemic than before. The frequency
of walking trips also decreased (fewer respondents report walking almost
daily), but the reductions in mobility were not so heavily concentrated
at the bottom of the scale.

Table  is a cross-tabulation of the number of cases in each trip-making
frequency class before and during the pandemic. If no changes had
occurred, all values would be concentrated on the main diagonal of the
matrices. Values in the lower triangular matrix represent a *loss* of
mobility (lower travel frequency), whereas values in the upper
triangular matrix are *gains* (higher travel frequency). The further
away a value is from the main diagonal, the greater the loss or gain.

Despite across-the-board losses of mobility, there appears to have been
some adaptation that varied by mode of transportation. To illustrate,
103 respondents, or 65.61% of those who traveled by bus almost daily
before, reported never using it during the pandemic. In contrast, only
12 respondents, or 1.5% of those who never used buses before started
doing so during the pandemic. By way of comparison, 24.14% of
respondents who cycled almost daily before the pandemic stopped doing so
- but 4.88% who never cycled before started doing so during the
pandemic.

To more clearly understand the transitions towards different trip-making
frequencies, including possible adaptations, we convert the
cross-tabulations to probability transition matrices, which we then
visualize using circular plots.

Figures  to  present these plots. Each of the trip-making frequency
sectors on the left hemisphere of the circle represents 100% of
responses *before* the pandemic. The links’ size is proportional to the
probability \(p_{ij}\) of transitioning from frequency class \(i\)
before to the right hemisphere are proportional to the transition
probabilities to each frequency *during* the pandemic. There are three
transparency levels for the links: solid colors are for \(p_{ij}>2/3\),
intermediate transparency is for \(1/3 < p_{ij} \le 2/3\), and the more
transparent links are for \(p_{ij}\le 1/3\).

From Figure , we see that the probability of traveling less by car for
those who initially used this mode frequently is high, but their
probability of not using this mode at all during the pandemic is quite
small. In other words, there was a decline in use, but not complete
discontinuation of this mode. The probability of traveling more
frequently by car for those who originally never or rarely used this
mode remained is low. In contrast, we see that the probabilities of
never ride-hailing during the pandemic are high irrespective of the
initial level of use of this mode of transportation, and the probability
of using this mode more are fairly small.

![Transition probabilities in trip frequency from before to during
COVID-19: car and
ride-hailing](README_files/figure-gfm/circular-plots-transition-probabilities-1-1.png)

The probabilities of change in trip frequency by rickshaw and CNG
auto-rickshaw are similar (see Figure ), although the probabilities of
being less mobile by CNG auto-rickshaw are greater: between 1/3 and 2/3
of respondents who used this mode almost daily, stopped using it during
the pandemic. Very rarely there were increases in mobility by these
modes.

![Transition probabilities in trip frequency from before to during
COVID-19: rickshaw and cng
auto-rickshaw](README_files/figure-gfm/circular-plots-transition-probabilities-2-1.png)

After ride-hailing, the use of bus had the largest probabilities of
discontinuation (Figure ). We see that even respondents who used this
mode almost daily before the pandemic had close to 66% chances of never
using it during the contingency. Similarly large losses of mobility by
bus were observed for travelers who used this mode less frequently
before the pandemic. These losses were not offset to any appreciable
degree by the probability of some users turning to this mode during the
pandemic.

![Transition probabilities in trip frequency from before to during
COVID-19: motorcycle and
bus](README_files/figure-gfm/circular-plots-transition-probabilities-3-1.png)

Trip-making by motorcycle (Figure ) also declined for all but the most
frequent users pre-COVID-19, and the probability of adopting this mode
during COVID-19 was almost null. Contrast this to the case of walking
(Figure ), where a sizable number of respondents started walking during
the pandemic, even if only rarely. Close to 50% of respondents who
report walking almost daily during the pandemic walked less frequently
before the contingency. Bicycle (Figure ), like motorcycle, saw
relatively fewer respondents adopting it during the pandemic, and many
travelers who did use the mode rarely, once a week, or even 2-3 times
per week stopped cycling during the pandemic.

![Transition probabilities in trip frequency from before to during
COVID-19: bicycle and
walk](README_files/figure-gfm/circular-plots-transition-probabilities-4-1.png)

The findings reported here suggest important changes in mobility in a
developing country during COVID-19, which (given the characteristics of
the convenience sample) may be more representative of younger, urban
residents in Bangladesh. In general there was a loss of mobility
across-the-board, but modes that require interaction with strangers
(ride-hailing, bus, rickshaw, and CNG auto-rickshaw) were more affected.
Travel by car, motorcycle, and bicycle were somewhat less affected, and
there is evidence of some adoption of walking during the pandemic.

# References

<div id="refs" class="references">

<div id="ref-Astroza2020mobility">

Astroza, Sebastian, Alejandro Tirachini, Ricardo Hurtubia, Juan Antonio
Carrasco, Angelo Guevara, Marcela Munizaga, Macarena Figueroa, and
Valentina Torres. 2020. “Mobility Changes, Teleworking, and Remote
Communication During the Covid-19 Pandemic in Chile.” *Transport
Findings*, July. <https://doi.org/10.32866/001c.13489>.

</div>

<div id="ref-Bangladesh2015">

Bangladesh Bureau of Statistics. 2015. “Population Monograph of
Bangladesh. Age-Sex Composition of Bangladesh Population.” Statistics
and Information Division, Ministry of Planning. Government of the
People’s Republic of Bangladesh.

</div>

<div id="ref-Brunsdon2020opening">

Brunsdon, Chris, and Alexis Comber. 2020. “Opening Practice: Supporting
Reproducibility and Critical Spatial Data Science.” *Journal of
Geographical Systems*, 1–20.

</div>

<div id="ref-DeWeese2020tale">

DeWeese, James, Leila Hawa, Hanna Demyk, Zane Davey, Anastasia Belikow,
and Ahmed El-geneidy. 2020. “A Tale of 40 Cities: A Preliminary Analysis
of Equity Impacts of Covid-19 Service Adjustments Across North America.”
*Tansport Findings*, June. <https://doi.org/10.32866/001c.13395>.

</div>

<div id="ref-Fricker2002advantages">

Fricker, Ronald D, and Matthias Schonlau. 2002. “Advantages and
Disadvantages of Internet Research Surveys: Evidence from the
Literature.” *Field Methods* 14 (4): 347–67.

</div>

<div id="ref-Huynh2020culture">

Huynh, T. L. D. 2020. “Does Culture Matter Social Distancing Under the
Covid-19 Pandemic?” Journal Article. *Safety Science* 130: 7.
<https://doi.org/10.1016/j.ssci.2020.104872>.

</div>

<div id="ref-Jager2017convenience">

Jager, Justin, Diane L. Putnick, and Marc H. Bornstein. 2017. “II. MORE
Than Just Convenient: THE Scientific Merits of Homogeneous Convenience
Samples.” Journal Article. *Monographs of the Society for Research in
Child Development* 82 (2): 13–30. <https://doi.org/10.1111/mono.12296>.

</div>

<div id="ref-Jamal2020perceptions">

Jamal, Shaila, Hossain Mohiuddin, and Antonio Paez. 2020. “How Do the
Perceptions of Neighborhood Conditions Impact Active Transportation? A
Study in Rajshahi, Bangladesh.” *Transportation Research Part D:
Transport and Environment* 87: 102525.

</div>

<div id="ref-Lock2020cycling">

Lock, Oliver. 2020. “Cycling Behaviour Changes as a Result of Covid-19:
A Survey of Users in Sydney, Australia.” *Transport Findings*, June.
<https://doi.org/10.32866/001c.13405>.

</div>

<div id="ref-Molloy2020tracing">

Molloy, Joseph, Christopher Tchervenkov, Beat Hintermann, and Kay W.
Axhausen. 2020. “Tracing the Sars-Cov-2 Impact: The First Month in
Switzerland.” *Transport Findings*, May.
<https://doi.org/10.32866/001c.12903>.

</div>

<div id="ref-Paez2020using">

Paez, Antonio. 2020. “Using Google Community Mobility Reports to
Investigate the Incidence of Covid-19 in the United States.” *Transport
Findings*, May. <https://doi.org/10.32866/001c.12976>.

</div>

<div id="ref-Saha2020lockdown">

Saha, J., B. Barman, and P. Chouhan. 2020. “Lockdown for Covid-19 and
Its Impact on Community Mobility in India: An Analysis of the Covid-19
Community Mobility Reports, 2020.” Journal Article. *Children and Youth
Services Review* 116: 14.
<https://doi.org/10.1016/j.childyouth.2020.105160>.

</div>

</div>
