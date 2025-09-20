# <p align="center"> St.Galler Kantonalbank and IBM</p>
<p align="center"> Personal Financial Management (PFM): Categorisation & enrichment of expenses using GenAI </p>

# <p align="center"> Who are we? </p>

St.Galler Kantonalbank (SGKB) is a Swiss universal bank based in the canton of St. Gallen, founded in 1868 to promote the regional economy. 

Our focus is on retail, corporate, and private banking solutions, with expertise in mortgages, SME financing, and wealth management.
We offer a full range of financial services and focuses on the core markets of Eastern and German-speaking Switzerland, as well as Germany.

Together with IBM, we aim to explore how GenAI can enhance the financial well-being of our clients.

A new AI-driven expenses analysis and advice service - based on your protoype - is planned to be integrated into our mobile app. 
A Demo of our current app is available here: https://www.sgkb.ch/static/demo-app

## <p align="center"> Case Introduction </p>
__What is the current problem?__
- Users have limited insight into their spending and no tools to detect patterns in their spending history.

__What is the expected final product?__

Development of a prototype UI for an AI Finance Manager
- Automatically categorizes bank transactions (e.g. “groceries”, “transport”, “leisure”). 
- Automatically recognizes retailer logos and assigns them to transactions – even without a provided logo database; the use of external APIs/services (ideally free of charge) is explicitly permitted. 
- Provides conversational interface or pre-defined question & answer buttons
- Possibly: Provides visuals on the spending patterns and derives insights and develops proposals
- Possibly: Exports the results as a file (CSV/Excel) and provides an inference output point (API/endpoint) that can be integrated into the banking architecture.

## <p align="center"> Data </p>
[20250918_Transaktionsdaten_Start-Global-Hackathon_v2.xlsx](https://github.com/user-attachments/files/22426867/20250918_Transaktionsdaten_Start-Global-Hackathon_v2.xlsx)


## <p align="center"> Technology </p>

IBM ID erstellen: https://www.ibm.com/docs/en/controller/11.1.1?topic=authentication-ibmid-registration

Orchestrate Documentation: https://www.ibm.com/docs/en/watsonx/watson-orchestrate/base?topic=getting-started-watsonx-orchestrate

Cloud Pack for Data: https://developer.ibm.com/learningpaths/get-started-watson-studio/

## <p align="center"> Corporate Colors </p>
The corporate colors of St.Galler Kantonalbank are based on the colors of the canton's coat of arms, thus creating a direct sense of affiliation with the region.
<table border="1">
  <tr>
    <td><img width="312" height="387" alt="image" src="https://github.com/user-attachments/assets/f0c3a21f-6323-4ec7-8e73-6c8c0df95842" /></td>
    <td><img width="1200" height="436" alt="SGKB-corporate colors" src="https://github.com/user-attachments/assets/95e9a159-5a22-4409-9618-4384d8bbdd5f" /></td>
  </tr>
</table>

## <p align="center"> Use Case </p>


__(1)   Recurring transactions:__

a. Show me all invoices from [e.g. Swisscom].
    
b. Search for all transactions with [recipient X] and the amount [XY] and calculate the total.

    

__(2)   Spending analysis & insights:__

a. How much did my summer holidays cost -> What was the total expenditure for my summer holidays (based on timestamps or geodata)?

b. What was my most expensive month?

c. Show me my expenditure sorted by country.

d. How many ATM withdrawals did I make last year?

e. What are my monthly fixed costs?

f. What recurring costs can I expect at the turn of the year?

g. What is the total monthly cost of my subscriptions?
    
h. How much money did I receive from XY via TWINT?
        


__(3)   Comparisons & optimisation:__

a. What savings tips can you suggest based on my expenses?

b. How much do I spend on transport, broken down by car and public transport?

c. Are there any unusual or anomalous items in my expenses?

d. Can you suggest a new category for me?

e. Can I please export the data via CSV?


## <p align="center"> Deep Dive Slides </p>

Protoype Mockup: https://github.com/START-Hack/SGKBxIBM_START_Hack_Tour25/blob/main/2025_Finance_Manager_Prototype.pdf

## <p align="center"> Presentation & Deliverables </p>

__Format:__
- Demo of prototype
- Minimal pitch deck (background, approach, architectural building blocks)

__Key elements:__
- Enrichment and categorization of data
- Main visual artefacts
- Chat functions
- Icing: Insights and recommendations
  
__Requirements:__
- Web-browser


## <p align="center"> Judging Criteria </p>

__1. Functional fulfillment (25 %)__
- Coverage of requirements in chapter 6
- Inclusion of GenAI solutions, best with using APIs / inference endpoints of existing platforms

__2. Creativity (20 %)__
- Can include gamification or other aspects
- Increase in client stickiness to bank/wealth advisor

__3. Visual design (20 %)__
- Style and layout can be adapted to the target group (retail customers of age 18-35)

__4. Business Case (20 %)__
- Cross-Selling to other products
- Up-selling into portfolio resp. wealth management


__5. User Experience (15 %)__
- Financial well-being
- Customer engagement and retention

    
## <p align="center"> Point of Contact </p>

- Nils Reimelt, Head of Digital Banking
- Norman Stürtz, Head of Data & Analytics


## <p align="center"> Prize</p>
- Nice watsonx Books for the winning teams
- An invite to our Swiss Regional Club Oktoberfest Edition on Oct 14th at our Office
- More Goodies at the event (Travelbag, Umbrella, a Thermo-Bottle)
