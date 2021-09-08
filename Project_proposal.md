### Project Proposal Template

#### Question/need:
* What is the framing question of your analysis, or the purpose of the model/system you plan to build?
  * For my analysis, the framing question would be: How could we maximize the number of people submitting their signatures, providing their emails and also assisting to the gala and making contribuitions to the cause?
* Who benefits from exploring this question or building this model/system?
  * The most basic answer to this question would be the WTWY organization, due to the possibility of throwing a successful event; in a more general sense, by helping WTWY acomplish their mission and advance towards the pursue of their vision, we will be using Data Science to try to reduce the gender gap, increase the representation of women in the tech sector and providing the future generation of girls with role models that could influence the path they follow in life. 




#### Data Description:
* What dataset(s) do you plan to use, and how will you obtain the data?
  * Initially we will be using the dataset from the MTA in order to determine for example, the top 10 busiest subway stations. Starting from that point, we will at least find out where to find the biggest flow of people and where the canvassers team would have the higher chances to at least get the signatures. Now, in my opinion, in order to actually gather signatures from people that could assist to the gala, make contributions and even spread the word about the mission of WTWY, we will have to gather socieconomic data or gender base information of the city neighborhoods in order to make more informed decisions, for example, if we focus in maximizing the contributions people make, we could target subway stations close to affluent neighborhoods. 
* What is an individual sample/unit of analysis in this project? What characteristics/features do you expect to work with? 
  * For the MTA data, we will have the number of accumulated entries and exits for an specific turnstile of a determined subway station. I would focus on working with the features related to the location of a turnstile, the number of entries and exits and the date and time of the day. 
* If modeling, what will you predict as your target?
  * For this project and with the MTA data, we will determining which subway stations have the higher foot traffic as a base point of analysis. 

#### Tools:
* How do you intend to meet the tools requirement of the project? 
  * I will be using SQL (and then perform exploration with DB Browser) and SQLAlchemy on Jupyter Notebooks for data ingestion, then, woud be using Pandas to do some deeper exploration of the data, as well, as cleaning the data and making the mofifications needed in order to present results based on curated and trustworthy data. For visualization and presentation of results, I'll rely on matplotlib and seaborn.
* Are you planning in advance to need or use additional tools beyond those required?

#### MVP Goal:
* What would a [minimum viable product (MVP)](./mvp.md) look like for this project?
  * The MVP will be centered on providing visualizations of the subway stations with the higher flow of people and the times where we could consider will be more pertinent to place the canvassers. 
  * If we manage to analyze socieconomic and demographic data for this project, we could create visualizations of the busiest times in the subway stations that are surrounded by the most affluent neighborhoods in the city. 
