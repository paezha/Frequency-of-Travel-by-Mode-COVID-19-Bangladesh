
<!-- README.md is generated from README.Rmd. Please edit that file -->

# Changes in trip-making frequency by mode during the COVID-19 emergency in Bangladesh

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
country and region around the world. Recent helps to illuminate some of
the dimensions of change - however, the evidence is still scant in
developing countries. The objective of this paper is to present an
exploratory analysis of the changes in the frequency of trip-making by
mode during the COVID-19 emergency in Bangladesh. The results confirm an
overall loss of mobility in the form of reduced trip-making frequency by
all modes, but the changes are not uniform across modes. In particular,
there was a greater loss of mobility for bus, rickshaw, and CNG
auto-rickshaw, and some adoption of walking during the pandemic.

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
emergency in Bangladesh. Using data from a recent survey that asked
respondents to report mobility levels before and during the pandemic, we
pose the following questions:

  - Was there a reduction of mobility in Bangladesh during COVID-19?
  - And if so, what forms of transportation were more affected?

This paper is a reproducible research document (see Brunsdon and Comber
2020); the code and data necessary to reproduce the tables and figures
are available in a public repository

# Methods and Data

Data used for this paper come from an online survey, “Exploring the
potential of travel mode change behavior in the post-lock-down and
post-pandemic (COVID-19) period” conducted during July - August 2020 in
Bangladesh. The survey was available both in Bengali and English and
disseminated through various electronic means along with a widespread
social media campaign and promotion in various social media sites and
groups. In addition to socio-economic and demographic information of the
respondents, the survey covered different aspects of travel such as
travel behavior before and during COVID-19, knowledge related to
COVID-19, and opinions and perceptions regarding travel behavior after
lock-down and post-pandemic situation.

For the purpose of this paper, we use two questions that provide
information about trip-making frequency by eight modes of
transportation. The modes are **car**, **ridesharing** (e.g., Uber,
Pathao), **rickshaw**, **CNG auto-rickshaw** (a rickshaw-like vehicle
powered by compressed natural gas), **bus**, motorcycle/scooter
(hereafter just **motorcycle**), **walking**, and **bicycle** (there was
an additional catch-all category **other** which we ignore here).
Participants in the survey used the following levels to report their
frequency of traveling by each mode both before and during COVID-19:
*Never*, *Rarely*, *Once a week*, *2-3 trips per week*, *4-5 trips per
week*, *Almost daily*. There are \(n=800\) responses in the data set.

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
ridesharing services, CNG auto-rickshaw, motorcycle, and bicycle. During
the pandemic, we see that while there were reductions in mobility by
car, motorcycle, and bicycle (with more respondents reporting never
traveling by these modes), the changes were relatively minor.

![Number of responses by trip-making frequency class and mode, before
and during
COVID-19](README_files/figure-gfm/column-plot-cases-before-after-1.png)

The frequency of trip-making by other modes changed more noticeably: the
frequency of travel by ridesharing services, rickshaw, CNG
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
respondents who cycled almost daily before the pandemic stopped doing
so, but 4.88% who never cycled before started doing so during the
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
never ridesharing during the pandemic are high irrespective of the
initial level of use of this mode of transportation, and the probability
of using this mode more are fairly small.

![Transition probabilities in trip frequency from before to during
COVID-19: car and
rideshare](README_files/figure-gfm/circular-plots-transition-probabilities-1-1.png)

The probabilities of change in trip frequency by rickshaw and CNG
auto-rickshaw are similar (see Figure ), although the probabilities of
being less mobile by CNG auto-rickshaw are greater: between 1/3 and 2/3
of respondents who used this mode almost daily, stopped using it during
the pandemic. Very rarely there were increases in mobility by these
modes.

![Transition probabilities in trip frequency from before to during
COVID-19: rickshaw and cng
auto-rickshaw](README_files/figure-gfm/circular-plots-transition-probabilities-2-1.png)

After rideshare, the use of bus had the largest probabilities of
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

The findings reported here provide important changes in mobility in a
developing country during COVID-19. In general there was a loss of
mobility across-the-board, but modes that require interaction with
strangers (rideshare, bus, rickshaw, and CNG auto-rickshaw) were more
affected. Travel by car, motorcycle, and bicycle were somewhat less
affected, and there is evidence of some adoption of walking during the
pandemic.

# References

<div id="refs" class="references">

<div id="ref-Astroza2020mobility">

Astroza, Sebastian, Alejandro Tirachini, Ricardo Hurtubia, Juan Antonio
Carrasco, Angelo Guevara, Marcela Munizaga, Macarena Figueroa, and
Valentina Torres. 2020. “Mobility Changes, Teleworking, and Remote
Communication During the Covid-19 Pandemic in Chile.” *Transport
Findings*, July. <https://doi.org/10.32866/001c.13489>.

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

<div id="ref-Huynh2020culture">

Huynh, T. L. D. 2020. “Does Culture Matter Social Distancing Under the
Covid-19 Pandemic?” Journal Article. *Safety Science* 130: 7.
<https://doi.org/10.1016/j.ssci.2020.104872>.

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
