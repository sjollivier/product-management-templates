# Project Brief for Planning and Scoping
## Project Name
Provide a short phrase that captures the essence of the effort in the language of the beneficiary of this effort. This name will be used in many ways and at many levels once the project is underway. All stakeholders wonder what we're working on. A bad name signals a possibly ill conceived effort and then requires a lot of effort to reduce the entropy caused by a vague or narrow name.  
*Example:* Mobile Device Usage Report

## Project Type (Delivery or Discovery)
Define the type of project. Delivery projects are the standard feature delivery for production deployment with hard requirements. Discovery projects involve a smaller team and usually result in  a throwaway prototype, but are vital in terms of validating a future winning feature or product and establishing its requirements so it can be delivered efficiently with low risk.  
***Example:*** Delivery

## Working Backwards - Example Press Release Quote or Sales Pitch
Provide a quote from a hypothetical customer or stakeholder that describes how they experienced the benefit. This is what we are aiming for with the effort.  
***Example:*** With the new ESP XYZ Mobile device usage reports, I was able to make a business case for investing in mobile-optimized email templates, complete the project, and see a 30% lift in engagement and conversions from my email programs. These reports gave me absolute transparency on what percentage of my audience was viewing my emails on a mobile device and how that varied over the week. All in all, I saw huge ROI with very little extra work once I revamped my templates to be mobile-optimized.

## Summary of Problem/Opportunity
Give a summary of the product and the benefit. Assume the reader will not read anything else so make this paragraph good. Describe the problem your product solves. Enumerate in bulleted points the problem or challenges or opportunity that will be addressed.    
***Example:*** One of the primary themes and business questions in the email marketing business this year is “To what extent is my audience interacting with my email via mobile devices?” This is often followed up by the question “And what should I do about it?”

Currently, ESP XYZ has no readily available way to answer this business question outside of directing customers to third party offerings such as IBM PV’s Mailbox IQ or LitmusApp. The downside of these approaches is setup friction, cost, and pushing users outside of native ESP XYZ product and services.

Further, there is a downstream strategy and creative services opportunity to exposing and documenting the magnitude of mobile usage in a customer’s audience. Specifically, if the answer to the question about mobile consumption of a brand’s email is greater than 20%, which is quite likely given industry benchmarks, then the ESP XYZ response is to offer strategy and creative services to revamp a brand’s email templates to be more mobile friendly.

As a result, it is believed that offering a simple tool that assesses mobile consumption of a brand’s email can drive business on the following levels:

- Customers will likely pay a nominal fee for this report, much like any custom report (org rollups) or report delivery by email.
- Once the reality of mobile consumption is apparent, it will be easier to persuade customers to engage our services teams on creative design projects.

## Essential Elements of the Solution
Describe from the user’s/stakeholder’s perspectives how the solution will improve upon their problem..

Example:

The CEO says to the VP of Marketing “Did you know that your emails look like crap on my iPhone? How many of our customers are using iPhones to read your email in the last 3 months? If they are having the same experience I’m having, then I think we need to something about it and pronto.” Then, since stuff flows downhill, the VP of Marketing then says to the users of the email marketing application “what’s our engagement via mobile devices, and they say hey no problem, ESP XYZ just told me that they have a cool little tool that will help me provide you with the following types of answers:”
In the last month, 30% of our opens occurred on a mobile device and 70% on the desktop.
In the last quarter, only 2% clicks occurred via a mobile device.
In the last month, iPhones represented 80% of the mobile devices used by our audience.
In the last two months, Outlook represented our biggest desktop email client in terms of opens and clicks.
The marketing user then visits the report to answer business questions around mobile and email client usage for a given period of time. The report is expected to have the following basic behavior and requirements:
Parse web access logs to generate a daily count for mobile vs desktop user agents: For a granularity of day-level (not mailing or any deeper segmentation), summary counts shall be generated for the number of opens and clicks attributable to mobile or desktop user agents for a trailing number of weeks. Open and click interaction counts shall be available for reporting individually.
Weekly or Daily Aggregation: The frequency of count aggregation shall be weekly at a minimum, but ideally would be performed daily, meaning specifically the counts are as recent as the previous day at all times.
Ability to Report on a User Defined Start and End Date: Users should be able to specify their own start and end date for their report.
Ability to view counts for device types within the mobile device category: Users should be able to look at counts for a given time period for each mobile device type (iPhone, iPad, Android, Windows phone, Blackberry, Other).
Ability to view counts for device types within the mobile device category: Users should be able to look at counts for a given time period for each desktop client (Outlook, Gmail, Yahoo, Hotmail, Windows Live, AOL, Other).
Day of Week Report: A day of week mobile vs desktop open proportion would be nice to have. Specifically, users would be able to see to what extent (by percent of total opens for the day) users are viewing through a mobile or desktop device. For example, users would be able to see that on Saturdays on average mobile devices account for 60% of opens but on Mondays they account for 20% of opens. 

## Low Fidelity Wireframe / Conceptual Diagram
Provide some visual description because often times “a picture is worth a thousand words” in terms of communicating to people that need to deliver on the desired project outcome. 

Show a wireframe that helps readers understand what might be delivered in the UI to solve the problem. This should not be considered a design and should instead be considered a conversation starter, an input to the design team.

## Early Adopter/Customer References
List of 2-3 customers that we will engage to validate requirements, designs, prototypes, early access, and first production use

## Estimated Financial Impact
Some basis for how the enhancement drives revenue. For example, a feature gap that will allow us to onboard $2MM in ARR. Or a feature that is key to 20 customers representing $20MM in ARR. Or a feature that has cost us $10MM in ARR in lost deals. Or some COGS reduction.

## Measure of Success
Some trackable measure of what success for the enhancement such as a desired level of adoption over a year, usage by customers representing some aggregate ARR, average lift associated with a recommendation model, COGS saving over a year, etc.
