# INTRODUCTION
The role of the electricity demand side is undergoing a fundamental change. For the UK the potential annual system savings from demand response have been estimated to be in the billions of pounds [1]. The extent to which the 'technical potential' can be realised is not well understood. Here we seek to explore the status of demand models and identify conceptual shortcomings and data gaps that need to be addressed if we are to better understand demand side flexibility.

##	Changing needs for evidence in the residential sector
¬	From overall demand to flexibility
¬	Any definitions, scope of paper
¬	Literature review (though some of this will sit more neatly in following sections)


# REVIEW OF MODELS AND DATA USED FOR UNDERSTANDING RESIDENTIAL DEMAND
## Taxonomy of residential energy models
Energy models are generally used to explore and explain changes in energy consumption. There are generally two main approaches to modelling energy consumption in the residential sector:  top-down and bottom-up - the terminology referring to the hierarchical level of the data inputs. The use of each depends on the data available and the purpose of the analysis.  Top-down models generally make use of historic sector specific (e.g. residential) time series data of energy consumption and related sector-specific data.  Such top-down models are usually driven by econometric data (such as energy and appliance prices) and technological data (such as autonomous rates of efficiency improvement and ownership rates). On the other hand, bottom-up models require significantly more data at the sub-sector level, and so can account for energy consumption at the regional, individual household or equipment level. Figure 1 shows a simple classification of residential modelling.  [1] [2]

[!Figure1](Figure1)

Bottom up models are usually classified further into two main groups: engineering and statistical. The statistical ones can include regression methods when measured data are available [3], conditional demand analysis and neural networks [4].

However, it is the engineering style of bottom-up model that has, to date, presented the best opportunities to develop a greater understanding of how energy is being used at the sub-sector level, and how user behaviour influences consumption.  A selection of such models is now reviewed.

## Review of selected UK end-use models
We review the historical development of UK residential end-use demand models with the examples of BREHOMES, DECADE, DCM and CREST. This review shows how the demands on these models has changed and increased over time and how analysts have responded by developing new and improved modelling and data collection approaches.

### BREHOMES
The BREHOMES housing stock model was an early physically-based residential stock model, providing overall national energy consumption estimates by house type  [5].  Developed by the Building Research Establishment, it was based on the BREDEM calculation which requires detailed information on the building type, heating system, internal and external temperatures, etc. Different versions of the underlying BREDEM algorithm can be used to estimate energy consumption: BRDEM-12 for annual consumption, whilst BREDEM-8 for the monthly energy estimates. This model developed over a number of years allowed the exploration of technology and policy interventions, especially relating to heating aspects of the home. 

The largest draw back was that appliances and lighting were included at an aggregated level, so it was not possible to explore these in detail. The DECADE project developed these in a significant way for the UK.
2.2.2 DECADE
The Domestic equipment and carbon dioxide emissions (DECADE) model is a detailed end-use model of energy consumption, developed from 1994 onwards by the ECI at Oxford University.  The DECADE project was co-funded by the EC and the UK government during the early phase of product policy (mandatory energy labels and minimum energy performance standards). The model was further developed under the Lower Carbon Futures (LCF) project [6] with modelling approach listed in an annex [7]. The detailed end-uses include cooking, lighting, water heating, consumer electronics, refrigeration.  Monte Carlo simulations were also undertaken to provide confidence intervals around the point estimates of energy consumption.

The modelling approach was used to show annual energy consumption by end-use, with the primary use being the ex-ante impact assessments of technical potential, variation in usage patterns, and policy options [8, 9].   The modelling approach was used for the ex-ante impact assessment of multiple EU-wide studies for options for developing labelling/MEPS regulations. [refs?] 

The DECADE model itself was further developed by the UK Government’s Market Transformation Programme and used as the basis for ex-ante impact assessments of potential energy savings from more efficient products and later policy measures (e.g. Ecodesign regulations for energy using and related equipment). [refs?]

Similar modelling approaches are used elsewhere for product policy regulation, e.g. USA, Australia, and China, for ex ante assessments of their MEPS programmes. Such models can also be used for evaluations of past policy measures, for example a detailed long term ex-post assessment of label/MEPS policies for Australian refrigerators [10],

The DECADE modelling also included the ability to estimate load curves by end-use, however, the lack of information on the time of use, meant that these were not well developed or published. However, the impact on the load curve for MEPS has been done in various jurisdictions using this approach, e.g. recently in Vietnam [11] though with caveats on the representativeness and reliability of the use profile data.
2.2.3 UKDCM 
The DECADE Modelling was extended to create the UK Domestic Carbon Model (UKDCM) model – as part of the 40% House Project [12]. This was mainly to include space/water heating along with building types, using BREDEM-8 algorithm. This made it very similar to BREHOMES in scope, though extended with significantly more detail and realistic data for appliances and lighting. The model generated monthly estimates of energy consumption and carbon emissions by house type, region, and end-use.  This enabled long term technical and policy scenarios to be examined in more detail [13].

[A later UKDCM2 was also generated.  Russel can provide further information? Other similar models which use BREDEM as the underlying physical model (eg DeCARB, Johnson).]
2.2.4 CREST [This sub-section could be moved to the next section?]
The CREST model introduces the concept of intra-day demand variation as a function of household occupancy, such that load profiles can be generated with high temporal resolution, to support network constraints analysis.  [add Jose text as appropriate]

2.3 Typical data used by bottom up end-use models
This section summarises the types of data sources used for bottom-up energy-use models, mainly focussing on energy-using equipment.
2.3.1 Physical survey of homes
Physical surveys of households can provide insights into the ownership of end-use equipment along with physical characteristics of the buildings themselves. Such surveys can be through home visits, such as those used to generate SAP assessments or provide representative national statistics on the housing stock. Governments also collect and collate these through the use of national surveys. For England, the most significant for end-use models is the English Housing Survey (EHS), which is a continuous national survey, commissioned by the Department for Communities and Local Government (DCLG). It collects information about people’s housing circumstances and the condition and energy efficiency of housing in England. In addition to the household interview (next section) it undertakes a physical inspection of a sub-sample of the properties. [list earlier studies, EHCS, etc]. Similar studies are undertaken in other parts of the UK.
2.3.2 Interview survey of householders
In terms of understanding how and why people are using their energy-using equipment in the home, it is necessary to undertake interviews of the householders themselves. Such interviews can provide insights into ownership of equipment (without the need for a physical inspection), and more importantly insights into usage patterns and motivation for use.

Interviews with householders can take different forms. The Government undertakes regular surveys of householders. The English Housing Survey provides this function. [ref]. Previously, the Survey of English Housing (SHE) includes information from over 15,000 households. Housing in England reports were the annual reports based principally on the Survey of English Housing. They were published each year that the survey operated, from 1993-93 to 2007-08 inclusive [14], and contain detailed analyses, commentary, over 200 data tables and charts and a full technical description of the survey. Prior to 2008, The ONS interviewed householders for the English Household Conditions Survey (EHCS) [15]. These types of report, in addition to providing a snapshot in time, also provide longitudinal data. 

In addition to Government-collected statistics and information, market research companies also collect useful information from householders, by making use of questionnaires given to large panels (multiple thousands).  For example, the market research GfK has a home audit panel, which can be used to provide very reliable estimates of ownership figures for installed appliances, insulation, recent sales, etc.

Beyond simple questionnaires with large sample sizes, extended interviews with smaller sample sizes can be employed.  The targeted use of household diaries to log the use of equipment can be a useful low cost method, e.g. to obtain numerical information on the use of washing machines (number of loads and temperature selected). 

Within householder surveys, time use diaries can be included. These provide a rich insight into what people are actually doing (activity), though not necessarily why.  Other techniques to understand why consumers are acting in a particular way can be done through semi-structured interviews, and focus groups to explore reasons for particular actions and activity.  [gap - couple activity with consumption with explanation]
2.3.3 Product registration and sales
Registration databases are important data sources which provide technical information on products being sold and installed in homes. Various countries require energy-using products to be registered centrally before they can be placed in the market to comply with minimum energy performance or labelling requirements. The requirements vary, but will usually include technical information such as efficiency (tested using standard conditions).  The UK/EU does not yet have a formal registration database, though other countries around the world have these (e.g. Australia, U.S.A., and China) which makes it easier and cheaper for regulators and analysts to get robust data and at a low cost. In some jurisdictions sales volume data also required to be logged with a regulator. Such databases enables better understanding of the technology being installed.

Technical information on products can also be obtained directly from manufactures, to include information such as U-values, power ratings, and efficiency values. These data are from data fiches and information labels. With such data increasingly being available on online, automatic web ‘scrapers’ are being used to obtain such technical information. [ref]

Market research companies also log sales going through retailer establishment. For example, GfK will collect data (on the number of individual appliances sold) directly from retail stores. 
2.3.4	Metering of homes and end-uses
The most robust and accurate way of measuring use of equipment by householders, especially by time of day is through the use of metering equipment. 
Historically, these have been quite intrusive and relatively expensive to undertake. As such, there have been few metering studies focused at the end-use, and even fewer including time of day. The first few end-use studies were more interested in understanding the total consumption (kWh) rather than kWh every few seconds or minutes.  The paucity of such types of metering was primarily due to metering technology availability and the cost of such equipment.  
The time of day use studies to date have been small scale (so not necessarily representative, and prone to bias, etc). This is a universal issue, and there has have been a few international metered studies. Examples of international end-use metering campaigns include:
•	New Zealand - BRANZ Household Energy End-Use Project (HEEP) metered 400 homes over the period 1997 to 2007 [16]
•	Sweden – STEM metered 300-400 homes in 2007-08 [17]
•	Europe – EC EIE funded project REMODECE, covered over 100 homes in 12 European countries. [18]
The Household Electricity Survey (HES) was the first ‘large’ scale survey in the UK to meter end-use electricity consumption. [Insert summary information. 250 homes, electric, etc.]  [19]
The role of out ‘smart’ metering is providing the real time logging of actual consumption through the day (every few minutes). However, this is only measured at the meter, so a combined consumption figure for all appliances and lighting consumption. There is, however, research underway to attempt to disaggregage these whole house measurements to allocate the total consumption to specific end-uses. If successful, this will provide a valuable stream of new data. However, to date the level of success is still limited. [insert refs]
Data from electricity meters can be used, to track how consumers respond to different signals.  For example, the CER, electricity smart metering customer behaviour trials. [insert information here. Check if should be moved to next section. . More experiment, over 5,000 recruits.]
Similarly, CLNR- British Gas trials, consisting over 13,000 electricity customers, is generating useful information that can be used in end-use models. However, it worth nothing that it is slightly biased towards customers with low carbon technologies, and is also examined load (and generation) profiles from meter data. [insert more, and check if we should move]
2.3.5 Other ad hoc sources
End-use models require other information. For example, sector data, such as household numbers and carbon emission factors, are all obtained from national statistics, based on various surveys (census). The models are usually calibrated or checked using residential sector energy from DUKES.
2.4 Gaps in modelling and data
To understand how energy is being used within homes, analysts usually generate bottom-up style models, such as end-use stock models.  To develop such models usually requires large amounts of data. 

The information on the stock or installed base of equipment is relatively well understood, and current data collection methods are mostly sufficient. The largest gaps, or the largest uncertainties in models, usually come from the householders’ use of appliances and equipment. The amount of times (or duration) a piece of equipment is used per annum is usually better understood than how the equipment is used over different time periods (day, week, month, season). It is this lack of data which is compromising the robustness of current models and also hampering the development of models which will better explain dynamic properties of consumption.

Dynamic properties, such as flexibility, call for new modelling approaches and new forms of data to support them. Inferring flexibility from existing static data is challenging [9].

Data from CER [20], HES[21] and CLNR [22] afford new opportunities to gain insights, to validate existing household models, and also allow us to generate new models.   In addition, new data such as CLNR also gain insights into flexibility [23].

Existing modelling approaches can be extended or new ones developed. The next section will focus more explicitly on how to better represent and understand temporality (or time of use) in energy models.

3.	REPRESENTING TEMPORALITY

Approaches based on available data
¬	Occupancy, Markov chain…
Limitations and gaps in data
¬	Mismatch in profiles CREST wrt HES
¬	
4. New data on temporality and flexibility [Phil]
Measuring flexibility
¬	Principles
¬	Methods
Applying new data to models

5. Conclusions and discussion [all]
¬	Summarise
¬	Recommendations for future research
¬	Any implications for policy?

6. References


1.	Swan, L.G. and V.I. Ugursal, Modeling of end-use energy consumption in the residential sector: A review of modeling techniques. Renewable and Sustainable Energy Reviews, 2009. 13(8): p. 1819-1835.
2.	Kavgic, M., et al., A review of bottom-up building stock models for energy consumption in the residential sector. Building and Environment, 2010. 45(7): p. 1683-1697.
3.	Fumo, N. and M.A. Rafe Biswas, Regression analysis for prediction of residential energy consumption. Renewable and Sustainable Energy Reviews, 2015. 47: p. 332-343.
4.	Aydinalp, M., V. Ismet Ugursal, and A.S. Fung, Modeling of the appliance, lighting, and space-cooling energy consumptions in the residential sector using neural networks. Applied Energy, 2002. 71(2): p. 87-110.
5.	Shorrock, L.D. and J.E. Dunster, The physically-based model BREHOMES and its use in deriving scenarios for the energy use and carbon dioxide emissions of the UK housing stock. Energy Policy, 1997. 25(12): p. 1027-1037.
6.	Fawcett, T., K. Lane, and B. Boardman, Lower Carbon Futures for European households, 2000, http://www.eci.ox.ac.uk/research/energy/downloads/lowercarbonfuturereport.pdf: Oxford.
7.	Lane, K., Modelling Approach. Appendix O to Lower Carbon Futures, 2000: Environmental Change Institute, University of Oxford.
8.	Boardman, B., et al., DECADE: Transforming the UK Cold Market, 1997, Environmental Change Unit, University of Oxford: Oxford.
9.	DECADE, DECADE (Domestic Equipment and Carbon Dioxide Emissions): 2 MtC, 1997, Environmental Change Institute, University of Oxford.
10.	Lane, K. and L. Harrington, Long Term Evaluation of Energy Efficiency Policy Measures for Household Refrigeration in Australia: An assessment of energy savings since 1986., 2010.
11.	Michaelis, C., et al. Lifting the label: evaluating the real impact of energy labelling in Vietnam. in IEPEC. 2014. Berlin, Germany: IEPEC.
12.	ECI, 40% House, 2005, Environment Change Institute, University of Oxford.
13.	Lane, K., et al., Foresight scenarios for the UK domestic sector, 2005, Environmental Change Institute, University of Oxford.
14.	CLG, Housing in England 2007-08, C.a.L. Government, Editor 2009: London.
15.	CLG, English House Condition Survey: Interview Survey Documentation 2007-08, C.a.L. Government, Editor 2010: London.
16.	Isaacs, N., et al., Energy use in New Zealand Household: Report on the Year 10 Analysis for the Household Energy End-use Project (HEEP), 2006.
17.	Zimmermann, J.P., End-use metering campaign in 400 households in Sweden: Assessment of the Potential Electricity Savings Enertech, Editor 2009.
18.	Aníbal de Almeida, et al. Residential Monitoring to Decrease Energy Use and Carbon Emissions in Europe in EEDAL. 2006. London.
19.	Fell, D. and G. King, Domestic energy use study: to understand why comparable households use different amounts of energy, D.f.E.a.C.C. (DECC), Editor 2012, Brook Lyndhurst: London.
20.	CER, Electricity Smart Metering Customer Behaviour Trials (CBT) Findings Report, 2011, The Commission for Energy Regulation,: Dublin.
21.	Zimmermann, J.-P., et al., Household Electricity Survey:  A study of domestic electrical product usage, 2012.
22.	Sidebotham, L., Customer-Led Network Revolution: Progress Report 7, 2014.
23.	Powells, G., et al., Peak electricity demand and the flexibility of everyday life. Geoforum, 2014. 55: p. 43-52.

