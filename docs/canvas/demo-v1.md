#Device Demo v1.x

> Contributor(s): Vik Babu

##Overview

###Goals
- Discover what information engages users in device level energy usage
- Design the UI for a dashboard that is intuitive and tells the device usage story

###Audiences
- Expo Attendants
- Facilities Managers
- Building Users
- Professional Engineers
- Investors

##Canvas

###Problems
- Device level energy isn't available to facilities leading to low energy awareness
- Num devices can reach into 100s making usability unclear
- Device usage data may be inaccurate or incomplete
- Energy feedback is non-intuitive leading to no behavioral change
- User expectations of real time differ between users and product capabilities

###Unique Value Proposition
- Building.ai gives users device level energy usage so they can make informed decisions about cutting back their energy usage
- ~~Device usage leading to circuit breaking~~

###Solutions
- BUD provides realtime device level data in addition to building data
- building.ai reduces the complexity of such large streams of data into an actionable dashboard
- building.ai clearly acknowledges the data discrepencies and unknowns
- building.ai provides intuitive feedback to influence user behavior and awareness
- Dashboard clearly shows historical data and duration

###Constraints
- Device level granularity would be monstrous to store
- RAW Data demos 24hrs to showcase capabilities
- How do we snapshot or represent the archival data at some level of granularity
- Capturing what device interests people have
- Device usage by area raises energy awareness locally at the user level
- Define all attributes & stack rank that gives a user sound proof

##Process
We surveyed the internal team to produce a list of information relevant to device screens

###Data Attributes
- Panel
- Circuit
- Location
- Last State Change
- State Change Count
- Instantaneous Real Power
- Average Real Power
- Estimated Device Count
- Peak Device Power
- Time at Peak Device Power
- Lowest Power Draw
- Time at Lowest Power Draw
- Energy (Power Use of Time) *Daily, Hourly, Weekly*
- Percent Time On of Time Specified
- On/Off
- Alternate State *Active, Standby, Peak*
- End Use Type
- Delta's of All of the above

###Aggregated Behavioral Attributes
- Long Term Recommendations
- Short Term Recommendations
- Analamous Usage
- Delta Energy Use Over Time
- Location
- Carbon Counting
- *Custom* Trends
- Device Alerts

###Assumptions
1. Proof of Realtime for User
2. Value of Energy Awareness for Client

##Usability Scenarios
- What are the most important features to develop to engender specific emotional responses from users?

##References
- [Zoom Sunburst](http://bl.ocks.org/mbostock/4348373)
- [USDE Device Categories](http://buildingsdatabook.eren.doe.gov/TableView.aspx?table=3.1.5)
- [US EIA](http://www.eia.gov/consumption/)
- [Ray Yun CMU Office Energy Dashboard Research](http://online.wsj.com/news/articles/SB10001424127887324886704579052883651889864)
- [Office Energy Consumption Dashboard](http://gcn.com/blogs/emerging-tech/2014/07/office-energy-consumption-dashboard.aspx)
- [Evaluating Energy Use Feedback Devices](http://www.ba-pirc.org/media/pdf/2008-HomeEnergy.pdf)
- [Power TakeOff](http://www.powertakeoff.com/solutions/direct-energy-management/real-time-monitoring/)
