**This is a GRC assessment of the information systems at Blank Inc., a hypothetical organization.** It follows the NIST Risk Management Framework (RMF) and relevant NIST 800-series guidelines. As it progresses through the six RMF steps, it will incorporate business impact considerations and compliance recommendations.

Blank Inc. (BKI) is a mid-sized hospitality and entertainment company operating three luxury resorts and casinos across North America. The company provides lodging, dining, entertainment, and gaming services, processing thousands of transactions daily. With a loyalty program, high-profile guests, and an online reservation/payment system, cybersecurity is a growing concern. 


**The 6 step process:**
**Categorize, Select, Implement, Assess, Authorize, and Monitor**

---
 **CATEGORIZE**

In this section, we categorize the key information systems at Blank Inc. to assess their security posture and determine the potential impact a loss of Confidentiality, Integrity, or Availability could have on the company. This categorization forms the foundation for the subsequent steps in the Risk Management Framework (RMF). The following is the exhaustive list of critical information systems of Blank Inc.:
<br>
<br>
<br>
####
**1\. Reservation and Payment System**

**Platform: ResNexus (for reservations) and Stripe (for payment processing)**

**Description: The ResNexus system is used to manage online reservations, customer bookings, and loyalty program information. Stripe is integrated to process payment transactions, handling sensitive credit card and financial data.**

**CIA Impacts:**

**Confidentiality: High.** Sensitive financial data is processed daily, and any unauthorized access could lead to fraud or data theft.

**Integrity: High.** Tampering with reservation or payment data would cause significant operational disruption and financial loss.

**Availability: High.** A system outage would halt bookings and payments, severely disrupting resort operations.

---

**2\. Casino Management System**

**Platform: Micros 3700 (Point of Sale), IGT Advantage (gaming management system)**

**Description: The Micros 3700 system manages gaming floor point-of-sale transactions, while IGT Advantage oversees gaming operations, including player tracking, loyalty programs, and transaction records.**

**CIA Impacts:**

**Confidentiality: Moderate.** While customer gaming data and transaction records are sensitive, the system’s primary focus is on transaction integrity.

**Integrity: High.** Any compromise to gaming data or loyalty program records would result in immediate financial and reputational damage.

**Availability: High.** Casino operations would be paralyzed without the ability to process transactions or manage gaming activities.

---

**3\. Customer Data Management System**

**Platform: Salesforce (Customer Relationship Management)**

**Description: Salesforce is used to manage customer data, including guest profiles, preferences, and interactions. This system is integral to maintaining high-quality customer service and engagement.**

**CIA Impacts:**

**Confidentiality: High.** Personal information and preferences are stored, and unauthorized access could lead to identity theft or privacy violations.

**Integrity: Moderate.** Corruption of customer data would affect service, but operational consequences would not be as severe as with financial transactions.

**Availability: Moderate.** While useful for customer service, the system’s unavailability would not stop core business operations.

---

**4\. Internal Communication and Collaboration System**

**Platform: Microsoft Teams and SharePoint**

**Description: Microsoft Teams is used for internal communications, meetings, and messaging across departments. SharePoint is used for document management and collaboration.**

**CIA Impacts:**

**Confidentiality: Moderate.** While internal communications need protection, they are generally less sensitive than customer-facing data.

**Integrity: Moderate.** Disruptions or errors in internal communications would cause inefficiencies but would not directly affect revenue.

**Availability: Moderate.** While vital for internal operations, system downtime would not cause a direct financial impact.

---

**5\. Entertainment and Event Management System**

**Platform: Eventbrite (for event ticketing and management)**

**Description: Eventbrite is used to manage ticket sales, event scheduling, and promotional campaigns for entertainment activities at the resorts.**

**CIA Impacts:**

**Confidentiality: Low.** Event details and guest lists are private but not as sensitive as payment or employee data.

**Integrity: High.** Any errors or manipulation in event data could lead to logistical issues, financial loss, and customer dissatisfaction.

**Availability: High**. System downtime would impact event planning and ticket sales, directly affecting revenue.

---

**6\. HRIS and Payroll System**

**Platform: ADP Workforce Now**

**Description: ADP Workforce Now is used for employee payroll processing, benefits management, tax filing, and compliance with labor laws. It stores critical employee data including personal information, salaries, and tax documents.**

**CIA Impacts:**

**Confidentiality: High.** This system contains sensitive employee data such as PII, payroll, and benefits, which must be protected.

**Integrity: High.** Any corruption of payroll data could lead to incorrect payments and legal issues, along with employee dissatisfaction.

**Availability: High.** Payroll and HR services must remain operational to ensure timely compensation, benefits management, and compliance with tax laws.

---

#### **System Categorization by CIA Impact**

| **System** | **Confidentiality** | **Integrity** | **Availability** | **Impact Level** |
|------------|---------------------|---------------|------------------|------------------|
| **ResNexus / Stripe (Reservation and Payment System)** | High | High | High | High |
| **Micros 3700 / IGT Advantage (Casino Management System)** | Moderate | High | High | High |
| **Salesforce (Customer Data Management System)** | High | Moderate | Moderate | Moderate |
| **Microsoft Teams / SharePoint (Internal Communication Systems)** | Moderate | Moderate | Moderate | Moderate |
| **Eventbrite (Entertainment and Event Management System)** | Low | High | High | High |
| **ADP Workforce Now (HRIS and Payroll System)** | High | High | High | High |

<br>
<br>

#### **Conclusion**

The Categorize process at Blank Inc. identifies 6 critical information systems, all of which play integral roles in day-to-day operations. The systems handling reservation/payments, casino management, HR/payroll, and entertainment/event management all have high-impact levels due to the sensitivity of data and the essential nature of their operations. Salesforce and Microsoft Teams/SharePoint have moderate impact levels but still require appropriate security measures.

From a business impact perspective, any compromise of these high-impact systems could result in financial losses, legal risks, and reputational damage. The next steps in the RMF will build upon these categorizations to ensure effective security controls are applied where they are most needed.
