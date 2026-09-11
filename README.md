# European space technology manufacturers database
## General information
This research aims to investigate the dependency of the EU’s space capabilities on foreign
actors along the following three dimensions, non-EU ownership of EU spacecraft
manufacturing firms, non-EU success in EU space technology tenders and non-EU
participation in the supply chain of EU space programmes.

The share of investment deals that European space firms receive from foreign actors has
steadily increased over the past years. (ESPI, 2023) While data on the yearly amount of
foreign investments is easily findable, an in-depth analysis of the resulting degree of non-EU
ownership of EU space firms has not yet been conducted. Since industrial autonomy is
paramount to strategic autonomy, the degree of non-EU control over EU spacecraft
manufacturing firms should be determined.

The dependency of the public sector on foreign actors is another area in which strategic
dependencies within the EU’s space capabilities can be revealed. Supply robustness in the
public procurement of space technology is crucial for the resilience of the EU’s space
capabilities and its correlated strategic aims. When public sector needs are then supplied by
foreign companies, the EU’s space capabilities become vulnerable to potential trade
restrictions and export bans. In order to determine this dependency, the share of tenders
awarded by the EU and its member states to non-EU companies for the procurement of space
technology will be analysed over a sufficient period.

The argument is that an autonomous EU space capacity hinges on the foreign dependence of
its supply chains. Therefore, it is crucial to also do a case study on the involvement of foreign
actors in the main EU space programmes, as these represent the majority of the EU’s space
capabilities.

## Methodological information
This research aims to answer the following questions:
How dependent is the EU’s space capacity on the involvement of foreign actors?

- What is the level of non-EU ownership of the EU space industry, and to which degree
do foreign actors control EU spacecraft manufacturing firms?
- How dependent are EU27 public institutions on foreign companies for the
procurement of their space technology needs?
- To which degree was the establishment of the EU’s Copernicus programme dependent
on foreign suppliers?

## Data-specific information
The first dimension of non-EU ownership of the EU space industry is measured based on the
following two variables, the direct and indirect non-EU ownership of EU space manufacturing
firms.

The current non-EU ownership is analysed on the basis of stakeholder information of a
selection of EU space manufacturing firms. This data is retrieved from the Orbis database,
which is a comprehensive database maintained by the Bureau van Dijk that provides data on
private companies from around the world. The database includes, among more, information
on the name, shareholding, country of origin and type of a company’s current shareholders.

Based on this data, the mean scores of direct and indirect non-EU ownership of the included
industrial base is calculated. In order to make a correct representation of the non-EU
ownership of the industry, the calculations are then weighted by the revenue of the included
firms in order to account for size differences. The dataset includes EU companies that are
member of the Eurospace group, which is stated to represent 90% of the total turnover of the
European Space Industry and 60 % of the manufacturing industry employment. (Eurospace,
2023) Then, two variables are calculated, the weighted share of direct non-EU ownership and
the weighted share of indirect non-EU ownership. Direct owners are actors that hold a certain
amount of shares of the company, whereas indirect owners hold shares of another company
that holds shares in the first company. For each company, these variables are calculated by
multiplying the company’s revenue by the share of direct respectively indirect non-EU
shareholders of its controlling company. I use the company’s revenue of 2022. For companies
where this is not yet provided, I use their revenue of 2021. The Orbis database, however,
shows indirect ownership only to a certain extent. Therefore, I added the direct shareholders
of a company’s direct shareholders as indirect shareholders of that company.

The second dimension of non-EU involvement in EU space technology tenders is analysed on
the basis of recent public procurement practices of the EU and its member states. The data is
retrieved from the OpenTender.eu platform, which contains information on tenders from 33
countries. The study investigates the public procurement practices of EU27 public institutions
during the last ten years and thus only includes tender cases that were awarded between 2013-
2022. In order to select the space technology tenders, the CPV is used. Only EU27 tenders
with the following CPV codes are then included in the dataset:
- 35631 Military satellites,
- 35640 Parts for military aerospace equipment,
- 35641 Structure and mechanical spare parts for military aerospace equipment,
- 35642 Electronic and electrical spare parts for military aerospace equipment.

After applying this selection, the dataset included 1 055 tender cases. Then, the tender cases
that were neither awarded nor preawarded, as indicated in the column lot_status, were deleted
from the dataset. The cases that have no value for bidder_country were manually completed
by searching the company nationality in the Orbis database on the basis of bidder_name.
Afterwards, there still remained 13 cases that had no value in neither bidder_country and
bidder_name. These cases were also deleted from the dataset. For each tender there are three
possible price indications of the public procurement, the bid price, the final price and the
estimated price. If there is no indication of the bid price, the case was included with its final
price and if there is no indication of the final price, it was included with its estimated price.
The final dataset consists of 911 valid tender cases. However, there are 319 cases that have no
price indication at all. These cases are included in the calculation of the results in table 2 but
excluded from the calculation of the results shown in table 3.

The third dimension of non-EU involvement in the supply chain of the main EU space
programmes is analysed by doing a case study on the industrial consortium of the Copernicus
programme. The choice for this space programme as the topic of the case study lies in the
strategic significance of EO data in the realisation of many other EU policies. Additionally,
there is much more available data on the Copernicus programme than is the case for the other
EU space programmes. Based on a document analysis, I aim to determine the degree of
dependency on foreign actors in the establishment of its space technology systems. This is
both done in general for all Copernicus technology by analysing the foreign supply within its
public procurement and specifically for the Sentinel satellites by analysing foreign
involvement in their industrial consortium. The data used for the analysis of the public
procurement practices is retrieved from the official website of the ESA, where all contracts
awarded under the Copernicus programme are listed by year from 2014 until 2022. (ESA,
n.d.) The data on the industrial consortium used to manufacture the Sentinel satellites is
retrieved from their respective special publication, where the appendixes include information
on the supplier of each individual component. These special publications are also accessible
on the official website of the ESA. 

## Findings
This section provides the empirical results of the research along the three analysed dimension,
the foreign ownership of the EU space industry, the foreign success in EU27 space technology
tenders and foreign involvement in the Copernicus programme.

### Dimension 1: foreign ownership of the EU space industry
The first dimension investigates the degree of non-EU ownership of the EU space industry.
The results in table 1 show that the direct non-EU ownership of the EU space industry,
through shareholding, is over 8 %. However, industry ownership by non-EU actors increases
to over 27 % when indirect ownership is also considered.

Non-EU ownership is mainly distributed among owners from the USA, Canada or European
countries that are not EU member states such as Switzerland, the UK and Norway.
Geopolitical rivals to the EU such as Russia and China have almost no ownership of EU space
firms.

#### Table 1: Non-EU ownership of the EU space industry

| Nationality of non-EU owners | % Direct | % Indirect |
|---|---:|---:|
| USA | 5,94 | 16,43 |
| Canada | 0,45 | 2,06 |
| UK | 1,13 | 2,72 |
| Switzerland | 0,07 | 1,05 |
| Norway | 0,37 | 1,52 |
| China | 0 | 0,03 |
| **Total non-EU ownership of industry** | **8,22** | **27,26** |
| **Average shareholding of non-EU owners** | **5,27** | **2,61** |

*Source: Own analysis based on the Orbis database, Bureau van Dijk, 2023.*

The results further show that foreign ownership is strongly related to the firm type. All public
traded firms in the dataset show some degree of non-EU ownership, while most state- or
family-owned firms are fully owned by EU actors.

### Dimension 2: foreign success in EU27 space technology tenders
The second dimension investigates the dependency of the EU27 public institutions on non-EU
suppliers in the public procurement of its space technology needs.

The results in table 2 show that over 18 % of the EU27 tenders for procurement of space
technology in the period 2013-2022 were won by external suppliers. USA companies won
over 13 % of the tenders, which makes them the most successful foreign supplier inside the
EU’s public procurement practices. The success rate of foreign companies from other
countries is significantly lower, with 3 % of the tenders won by companies from the UK and
just over 1 % awarded to companies from Canada, Israel and Switzerland. Except for three the
tender cases won by Israeli companies, EU27 countries are have only been depending on
members of common alliances such as the EEA and NATO for the foreign supply of their
space technology. There were further no tenders awarded to companies from geopolitical
rivals of the EU such as China or Russia.

#### Table 2: Non-EU success in EU space technology tenders

| Nationality non-EU tender supplier | #tenders won | Share of total #tenders (in %) |
| :--- | :---: | :---: |
| USA | 129 | 14,16 |
| UK | 31 | 3,4 |
| Canada | 6 | 0,66 |
| Israel | 3 | 0,33 |
| Switzerland | 1 | 0,11 |
| **Total** | **170** | **18,66** |

*Source: Own analysis based on data retrieved from OpenTender.eu, 2023.*

In the graph below, we can see that the share of tenders awarded to non-EU bidders
significantly increased from 2017 onwards. As the yearly share of space technology tenders
won by non-EU members has consistently been higher than 30 % since 2017, with a peak of
over 60 % in 2021.

#### Graph 1: The share of EU27 space technology tenders awarded to non-EU bidders by year in period 2013-2022

![Graph 1: Share of EU27 space technology tenders](https://quickchart.io/chart?c={type:%27bar%27,data:{labels:[%272013%27,%272014%27,%272015%27,%272016%27,%272017%27,%272018%27,%272019%27,%272020%27,%272021%27,%272022%27],datasets:[{label:%27Share%20(in%20%25)%27,data:[3.08,11.38,4.12,1.41,37.04,42.39,32.14,33.33,60.32,32],backgroundColor:%27%2371717a%27}]},options:{plugins:{datalabels:{anchor:%27end%27,align:%27top%27,color:%27%23333333%27,font:{weight:%27bold%27}}},scales:{y:{max:70}}}})

When we look at the average bid price of the tender suppliers, shown in table 3, we can see
that the average bid price of tenders awarded to non-EU suppliers was much smaller than the
average bid price of tenders won by EU27 companies. This result is contradictive to the
assumption that EU27 public institutions have to rely on USA suppliers out of a lacking
production capacity within the EU space industry, certainly considering that the average bid
price for tenders won by USA suppliers was even lower. Although we cannot be sure whether
this is true or not based on the average bid price, it may indicate that EU27 public institutions
rather award their tenders to foreign suppliers because of price differences or an inability of
the EU industry to supply certain highly innovative technologies.

#### Table 3 : Average bid price by tender suppliers

| Nationality of EU tender supplier | Average tender price (in euro) |
| :--- | :---: |
| EU27 | 4 079 860,943 |
| Non-EU | 1 428 091,58 |
| USA | 585 596,46 |

*Source: Own analysis based on data retrieved from OpenTender.eu, 2023*

However, the assumption that EU public institutions have to rely on external suppliers out of
an inability of the EU industry to supply certain technologies might be incorrect given that
tenders won by non-EU suppliers received significantly more bids from companies than
tenders awarded to EU27 companies. This might indicate that there were more companies
able to supply the demanded space technology of tenders won by non-EU companies than of
those won by EU companies. Again, it is not possible to completely falsify this assumption
based on the data provided by the OpenTender.eu platform, as it only includes information on
the tender winner and not on the other bidders.

#### Table 4: The average and median amount of bids for tenders won by non-EU and EU27 suppliers

| Bids per tender | Average | Median |
| :--- | :---: | :---: |
| Non-EU won | 5,94230769 | 5 |
| EU27 won | 2,02953586 | 1 |

*Source: Own analysis based on data retrieved from OpenTender.eu, 2023*

### Dimension 3: foreign involvement in the Copernicus programme
The third dimension of this research investigates the involvement of foreign actors in the
establishment of the EU’s Copernicus programme on the basis of its public procurement
contracts and the industrial consortium used to manufacture the Sentinel satellites.
The results in table 5 show that almost 6 % of all Copernicus procurement contracts between
2014 and 2022 were awarded to non-EU companies.

#### Table 5: Copernicus contracts awarded to non-EU companies

| Country | 2014 | 2015 | 2016 | 2017 | 2018 | 2019 | 2020 | 2021 | 2022 | #contracts | % contracts |
| :--- | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| UK | - | - | - | - | - | - | 4 | 6 | 5 | 15 | 1,17 |
| Norway | 1 | 6 | 2 | 1 | 0 | 2 | 1 | 5 | 4 | 22 | 1,72 |
| Switzerland | 0 | 10 | 4 | 3 | 1 | 2 | 0 | 2 | 0 | 22 | 1,72 |
| USA | 0 | 1 | 0 | 0 | 0 | 0 | 0 | 0 | 1 | 2 | 0,16 |
| Canada | 0 | 2 | 1 | 1 | 0 | 2 | 1 | 4 | 1 | 12 | 0,94 |
| **#contracts** | **1** | **19** | **7** | **5** | **1** | **6** | **6** | **17** | **11** | **73** | **5,70** |
| **% contracts** | **16,67** | **10,05** | **6,09** | **5,81** | **1,23** | **6,38** | **3,90** | **7,62** | **3,30** | | |

*Source: Own analysis based on Copernicus space component tenders and contracts, ESA, n.d.*

Companies from Switzerland and Norway were awarded the most contracts, followed by
companies from the UK. These contracts were awarded for the procurement of all
technologies and services used in the establishment of the Copernicus programme and range
from spacecraft components and ground station equipment to research and launch services.
The EO capabilities of the Copernicus programme are the result of many spacecraft systems
and in situ sensors. The systems within the programme’s space component are divided into
two categories, the Sentinels that function as the main fleet of EO satellites and the
Contributing Missions. If we then look at the industrial consortium of the Sentinel satellites,
we can see that 11 % of the satellite components used to build the them were supplied by
companies outside the EU. The higher involvement of foreign companies in the industrial
consortium of the satellites of the Sentinel 1, 2 and 3 constellations are in particular
concerning as they function as the dedicated EO satellites.

#### Table 6: Supply of Sentinel components by non-EU companies

| Country | Sentinel 1 | Sentinel 2 | Sentinel 3 | Sentinel 4 | Sentinel 5P | #components | % components |
| :--- | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| Norway | 1 | 0 | 2 | 2 | 0 | 5 | 1,38 |
| Switzerland | 9 | 2 | 7 | 3 | 3 | 24 | 6,63 |
| USA | 1 | 2 | 0 | 0 | 0 | 3 | 0,83 |
| Canada | 1 | 1 | 2 | 0 | 0 | 4 | 1,10 |
| Israel | 3 | 0 | 1 | 0 | 0 | 4 | 1,10 |
| **#components** | **15** | **5** | **12** | **5** | **3** | **40** | **11,05** |
| **% components** | **18,52** | **13,16** | **8,82** | **8,77** | **6** | | |

*Source: Own analysis based on data retrieved from the special ESA publications on the Sentinel satellites, ESA, 2012<sup>[1][2][3]</sup>, 2016, 2017*

## CONCLUSION
From the results shown above, we can conclude that the foreign ownership of the EU space
industry is quite substantial, especially by companies from the USA. However, foreign
shareholding belongs mainly to companies from the USA, Canada or other European
countries, which are all members of international alliances such as the EEA and NATO.

Ownership by geopolitical adversaries is virtually non-existent. Moreover, foreign
shareholding of EU space firms is dispersed over many companies, investment funds and
financial services firms. There is some governmental ownership of EU space firms by public
institutions from the USA and Norway, although this remains very minimal.

We can also observe a big increase in the dependence of EU27 public institutions on external
suppliers in the procurement of its space technology needs, as the share of tenders awarded to
non-EU companies has majorly increased since 2017. On the other hand, the involvement of
foreign companies within the public procurement for the Copernicus programme remained
quite minimal over the investigated period. The non-EU involvement in the industrial
consortium of the Sentinel satellites was higher and in particular substantial for the dedicated
EO satellites of the Sentinel 1, 2 and 3 constellations. Again, except for minimal supply from
Israeli companies, foreign supply came solely from countries that are closely tied to the EU
through defence cooperation or as members of the EEA or NATO. Since the discontinuation
of the ESA’s Soyuz at CSG programme, there is little to no involvement of geopolitical
adversaries in the realisation of the EU space capacity. The substantial ownership and
involvement of foreign actors within the EU space capabilities is therefore less critical from a
strategic perspective.

The above analysis paints a mixed picture concerning the pursuit of the public procurement
objectives stated within the Strategic Compass. While only a limited share of tenders was won
by non-EU bidders, the dependency on foreign supply has been growing. If the EU seeks to
strengthen its autonomy in defence matters, as stated in the Strategic Compass, it must
reinvest into its own industrial base instead of awarding more public procurement contracts to
foreign companies. (EEAS, 2022)

Although full autonomy is, in many cases, unachievable and not necessarily desirable,
progress can be achieved to make the EU more self-reliant in pursuing its interests and values.
Recent events such as the Covid-19 pandemic and the increased threats from Russia have
highlighted the risks of strategic dependencies and the resulting costs of supply chain
disruptions. Space services in EO and geospatial navigation are crucial elements in many
other EU policies. Attaining an autonomous space capacity is therefore also of strategic
importance for the EU to achieve its interests in other fields, such as its climate policy and the
digital transition.

Progress towards more strategic autonomy is inevitably a long-term process. In the current
global context, the EU is met with growing tensions from Russia, trade wars between the
USA and China and the growing protectionism within the USA. Therefore, it would be a
mistake to believe that strategic dependence is still a sustainable condition, as was the case
before, when the EU could rely on the hegemonic role of the USA and the military support of
the NATO alliance.

# Foreign Dependency in EU Space Technology Capabilities

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Data Source](https://img.shields.io/badge/Data-OpenTender.eu%20%7C%20Orbis%20%7C%20ESA-blue)](#data-sources)

A quantitative Master's thesis analyzing the extent to which the European Union's space capabilities rely on non-EU actors across three critical strategic dimensions: corporate ownership, public procurement, and program supply chains.

---

## Executive Summary & Findings

* **Dimension 1: Corporate Ownership (EU Space Industry)**
  * **Direct vs. Indirect Ownership:** Direct non-EU ownership of Eurospace member firms stands at **8.22%**, but jumps to **27.26%** when incorporating indirect ownership structures.
  * **Geopolitical Profile:** Foreign ownership is heavily concentrated in allied nations (USA, Canada, UK, Switzerland, Norway). Ownership by geopolitical rivals (e.g., Russia, China) is **<0.03%**.
  * **Firm Type Variations:** Publicly traded space manufacturers exhibit significant foreign ownership, whereas state- or family-owned firms remain predominantly EU-owned.

* **Dimension 2: Public Procurement Tenders (2013–2022)**
  * **Foreign Success Rate:** Non-EU companies won **18.66%** of all EU space technology tenders (170 of 911 valid cases), with US firms taking the primary share (**14.16%**).
  * **Temporal Trend:** Foreign tender success surged from **2017 onward**, consistently exceeding **30% annually** and peaking at **60.32% in 2021**.
  * **Price & Competition Dynamics:** Tenders awarded to non-EU suppliers received **more bids per tender (5.94 average)** and lower average bid prices (€1.4M vs. €4.07M for EU firms), indicating price competition rather than purely an EU capacity deficit.

* **Dimension 3: Copernicus Programme Supply Chain**
  * **Public Procurement:** Foreign entities secured **5.70%** (73 of 1,281) of Copernicus contracts between 2014 and 2022, led by Switzerland (1.72%), Norway (1.72%), and the UK (1.17%).
  * **Sentinel Satellite Hardware:** Non-EU involvement in the Sentinel industrial consortium reaches **11.05%** of all components, with the highest foreign reliance in **Sentinel-1 (18.52%)** and **Sentinel-2 (13.16%)**.

---

## Empirical Data & Visualizations

<details>
<summary><b>Table 1: Non-EU Ownership of the EU Space Industry</b></summary>

| Nationality of Non-EU Owners | Direct Ownership (%) | Indirect Ownership (%) |
| :--- | :---: | :---: |
| **USA** | 5.94 | 16.43 |
| **UK** | 1.13 | 2.72 |
| **Canada** | 0.45 | 2.06 |
| **Norway** | 0.37 | 1.52 |
| **Switzerland** | 0.07 | 1.05 |
| **China** | 0.00 | 0.03 |
| **Total Non-EU Ownership** | **8.22** | **27.26** |
| **Average Shareholding** | **5.27** | **2.61** |

*Source: Own analysis based on Orbis database (Bureau van Dijk, 2023). Weighted by 2021/2022 revenue.*
</details>

<details>
<summary><b>Table 2: Non-EU Success in EU Space Tenders (2013–2022)</b></summary>

| Nationality Non-EU Supplier | # Tenders Won | Share of Total Tenders (%) |
| :--- | :---: | :---: |
| **USA** | 129 | 14.16 |
| **UK** | 31 | 3.40 |
| **Canada** | 6 | 0.66 |
| **Israel** | 3 | 0.33 |
| **Switzerland** | 1 | 0.11 |
| **Total Non-EU** | **170** | **18.66** |

*Source: Own analysis based on OpenTender.eu (2023). Total dataset = 911 valid tender cases.*
</details>

<details>
<summary><b>Graph 1: Yearly Share of EU Space Tenders Awarded to Non-EU Bidders (%)</b></summary>

```mermaid
xychart-beta
    title "Share of EU27 Space Tenders Awarded to Non-EU Bidders (2013-2022)"
    x-axis ["2013", "2014", "2015", "2016", "2017", "2018", "2019", "2020", "2021", "2022"]
    y-axis "Share (%)" 0 --> 70
    bar [3.08, 11.38, 4.12, 1.41, 37.04, 42.39, 32.14, 33.33, 60.32, 32.00]
