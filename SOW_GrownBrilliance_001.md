# STATEMENT OF WORK #001
**GROWN BRILLIANCE - DATA ASSET RECOVERY AND OPTIMIZATION ENGAGEMENT**

**Client:** AJS Creations / Grown Brilliance  
**Contact:** Ronny Wang, Director of Operations  
**Date:** [Date]  
**SOW Number:** GB-001-2024  

---

## 1. STATEMENT OF WORK

This Statement of Work ("SOW") is incorporated into and subject to the terms and conditions of the Master Services Agreement between Cloud Data Consulting LLC ("CDC") and AJS Creations/Grown Brilliance ("Client") dated [MSA Date] (the "Agreement"). In the event of any conflict between this SOW and the Agreement, the terms of the Agreement shall prevail.

## 2. SERVICES, DELIVERABLES, TIMELINE AND ESTIMATED COSTS

The services, deliverables, timeline and estimated costs for this project are set forth in the attached Exhibit A, which is incorporated herein by reference.

## 3. TERM

This SOW shall commence upon execution and shall continue until completion of the services described herein, unless earlier terminated in accordance with the Agreement.

## 4. ENTIRE AGREEMENT; MODIFICATIONS

This SOW, together with the Agreement, constitutes the entire agreement between the parties with respect to the subject matter hereof. This SOW may only be modified by written agreement signed by both parties.

## 5. PAYMENT AND BILLING INFORMATION

**Initial Retainer:** $15,000 due upon execution of this SOW  
**Payment Method:** ACH or Bill.com  
**Billing Frequency:** Upon completion of milestones  
**Payment Terms:** Due upon receipt  

Cloud Data Consulting LLC  
**Bank:** Chase Bank  
**Account:** [Account Details]  
**Bill.com:** accounting@clouddataconsulting.com  

---

**CLIENT SIGNATURE:**

_________________________________  
Ronny Wang, Director of Operations  
AJS Creations / Grown Brilliance  
Date: _______________

**CONTRACTOR SIGNATURE:**

_________________________________  
Bernie Pruss, Principal  
Cloud Data Consulting LLC  
Date: _______________

---

# EXHIBIT A: PROJECT SPECIFICATIONS

## EXECUTIVE SUMMARY

### Business Context
Grown Brilliance (AJS Creations) acquired the assets of Clean Origin in 2024, including a sophisticated data reporting system built on Snowflake that represented a $630,000 investment over 3-4 years. The system included Fivetran for data ingestion, dbt for transformations, and Looker for business intelligence, supporting daily operations and strategic decision-making.

**Total Investment Context:** The $630,000 paid to CDC represents only a portion of Clean Origin's total investment. Additional significant internal resources were dedicated to requirements gathering, testing, validation, and project management. The true value of the system likely exceeds $1 million when including internal labor and opportunity costs.

**Proven Business Impact:** According to Clean Origin's former CFO Jeb Beckwith, the data warehouse transformed their operations: *"We were drowning... we wouldn't have been able to do it without [CDC]."* The system enabled data-driven store openings that **doubled regional sales**, optimized marketing spend against 52,000 SKUs, and became something they *"used every single day"* for pricing and strategic decisions.

**Notable System Reliability:** The Clean Origin data infrastructure operated without intervention for over 7 months (February to September 2024), only stopping when payment processing was discontinued - a testament to the robust architecture and automated design. As Jeb noted: *"Maintenance on it was really low. The usefulness of it was very good."*

Following the asset acquisition, Grown Brilliance needs to:
- Extract valuable historical data from the Clean Origin Snowflake system
- Optimize AWS infrastructure costs while maintaining necessary services
- Integrate Clean Origin customer and sales data into their existing Power BI analytics framework
- Assess the value of the existing data infrastructure for potential future utilization

### Strategic Opportunity
This engagement represents an opportunity to protect and leverage the significant investment already made in Clean Origin's data infrastructure while addressing immediate operational needs. The project will provide Grown Brilliance with both tactical data extraction services and strategic insights into their data assets.

**Unique Advantage:** As the original architects and builders of the Clean Origin system, CDC possesses unmatched knowledge of the data structures, business logic, and system capabilities - eliminating the learning curve and risk associated with third-party vendors. This is particularly valuable given the complex Magento data structures that, as Jeb Beckwith noted, *"took a lot of work"* to map correctly across 52,000 SKUs with individual pricing and margin calculations.

**Business Value at Risk:** The Clean Origin system contains proven business intelligence that enabled:
- Store location decisions that doubled regional sales (using geographic heat maps showing sales by ZIP code)
- Daily pricing optimization across tens of thousands of products
- Marketing ROI improvements through margin-based targeting
- Customer lifetime value tracking that reduced acquisition costs to "almost nothing"

### Retainer Structure Rationale
Given the exploratory nature of this work and the need for flexible resource allocation, a retainer-based engagement provides optimal cash flow management and allows for responsive support as requirements are clarified during data exploration.

**Time-Sensitive Note:** Snowflake data retention policies and AWS resource lifecycles may impact data availability. Prompt project initiation is recommended to ensure complete data recovery.

## PROJECT SCOPE DEFINITION

### Phase 1: Data Extraction and Infrastructure Assessment

#### Core Data Extraction Services
• **Sales History Extraction**
  - Complete sales transaction history from Kwi and Square payment systems
  - Customer purchase data including products, pricing, and transaction details
  - Payment method and transaction metadata
  - Service plans and additional product details where available
  - **Critical Business Intelligence:** Gross margin by SKU, customer attribution data, and geographic performance metrics that Clean Origin used for daily decision-making

• **Customer Database Export**  
  - Complete customer records including contact information
  - Purchase history and customer lifetime value data
  - Geographic and demographic data for marketing analysis (including ZIP code intelligence used for store placement)
  - Customer relationship mapping between payment systems

• **Product and Inventory Data**
  - Product catalog with pricing and cost information
  - Margin calculation data and vendor information  
  - Product categorization and metadata
  - Historical pricing and cost changes

#### AWS Infrastructure Optimization
• **Cost Analysis and Optimization**
  - Comprehensive review of current AWS account usage and costs
  - Identification of unused or underutilized resources (EC2, RDS instances)
  - Recommendations for service consolidation and termination
  - S3 storage optimization and lifecycle management review

• **Infrastructure Cleanup Planning**
  - Safe termination procedures for unused resources
  - Data backup and archival strategies before resource elimination
  - Migration planning for essential services
  - Cost projection and savings analysis

#### System Assessment and Documentation
• **Clean Origin System Value Analysis**
  - Documentation of existing Snowflake data warehouse architecture
  - Assessment of data transformation logic and business rules
  - Evaluation of data quality and completeness
  - Analysis of potential value for ongoing operations
  - **Magento Complexity Documentation:** Detailed mapping of how complex Magento structures were transformed into business-friendly reporting formats

• **Integration Planning Support**
  - Power BI integration recommendations and documentation
  - Data export formats optimized for Power BI consumption
  - OneDrive file organization and automation recommendations
  - Data refresh and synchronization strategy development

### Materials and Support to be Provided by Client

• Access credentials to Snowflake, AWS, and related systems
• Business context and priorities for data extraction
• Current Power BI reporting requirements and preferences  
• Internal stakeholder availability for requirements clarification
• Designated technical contact (Chris) for coordination
• Support for outreach to Brian Walker regarding historical documentation access

## DELIVERABLES

### Data Extraction Deliverables
• **Exported Data Files**
  - Sales history in CSV/Excel format optimized for Power BI
  - Customer database with complete relationship mapping
  - Product and pricing data with margin calculations
  - Documentation of data fields and business logic

• **Data Integration Package**
  - Power BI connection documentation and examples
  - Automated data refresh procedures where feasible
  - Data quality assessment and cleansing recommendations

### Infrastructure Optimization Deliverables  
• **AWS Cost Optimization Report**
  - Current usage and cost analysis
  - Specific recommendations for resource optimization
  - Projected monthly savings from recommended changes
  - Step-by-step implementation guide for changes

• **Infrastructure Cleanup Plan**
  - Prioritized list of resources for review/termination
  - Data backup and migration procedures
  - Risk assessment and mitigation strategies

### Strategic Assessment Deliverables
• **Clean Origin System Assessment**
  - Technology stack evaluation and capabilities overview
  - Data asset inventory and value analysis
  - Integration potential with existing Grown Brilliance infrastructure
  - Recommendations for future data strategy development

• **Documentation Recovery and Knowledge Transfer**
  - Outreach to Brian Walker to recover valuable Jira and Confluence documentation from Clean Origin project
  - System architecture documentation (recovered and/or reconstructed)
  - Business rule and transformation logic documentation
  - **Magento Transformation Logic:** Years of complex mapping rules that convert Magento's intricate data model into actionable business insights
  - Operational procedures and maintenance requirements
  - Historical project documentation and implementation notes representing thousands of hours of analysis and refinement

## ADDITIONAL SERVICES: CONSULTING AND ADVISORY

Beyond the core deliverables, CDC will provide:

• **Collaboration with Internal Resources**
  - Knowledge transfer sessions with Anik to ensure internal capability building
  - Joint assessment of data warehouse options to leverage internal expertise
  - Documentation specifically designed for internal team utilization
  - Positioning CDC as strategic advisor supporting internal initiatives

• **Strategic Data Consulting**
  - Business requirements clarification sessions
  - Data strategy recommendations based on current state analysis
  - Technology decision support for future data infrastructure needs

• **Technical Advisory Services**
  - Power BI optimization recommendations
  - Data integration best practices guidance  
  - Future data warehouse planning consultation (if requested)

## PROVEN RESULTS FROM CLEAN ORIGIN IMPLEMENTATION

Based on testimonial from Jeb Beckwith, Former CFO of Clean Origin:

### Operational Transformation
• **Before CDC:** *"We were drowning"* with 52,000 SKUs and no visibility into margins or marketing effectiveness
• **After CDC:** Daily pricing decisions, marketing optimization, and strategic planning based on real-time data

### Measurable Business Impact
• **100% Sales Increase:** First omnichannel store doubled regional sales
• **Marketing ROI:** Reduced customer acquisition costs to "almost nothing" for repeat customers
• **Daily Operations:** System became essential for daily pricing and repricing decisions
• **Low Maintenance:** *"Maintenance on it was really low. The usefulness of it was very good"*
• **Strategic Expansion:** Data-driven insights enabled successful expansion from online-only to 6 physical stores
• **Location Intelligence:** Looker dashboards visualized sales by ZIP code on US maps, enabling data-driven store placement decisions that maximized ROI

### Client Testimonial
*"Cloud Data Consulting was tremendous... we wouldn't have been able to do it without you."* - Jeb Beckwith, Former CFO, Clean Origin

## INVESTMENT AND TIMELINE

### Billing Structure
**Initial Retainer:** $15,000  
- Credited against project fees and expenses
- Provides immediate resource allocation flexibility
- Covers initial data exploration and requirements refinement

**Total Project Investment:** $35,000  
- Includes all data extraction, AWS optimization, and documentation deliverables
- Covers up to 140 hours at blended rate of $250/hour
- Additional consulting beyond scope available at current rates:
  - Principal/Data Architect: $275/hour
  - Senior Data Engineers: $200/hour
  - Blended project rate: $250/hour

### Timeline and Milestones

**Week 1-2: Discovery and Access Setup**
- System access verification and credential setup
- Initial data exploration and requirements validation
- AWS account review and cost analysis initiation
- Outreach to Brian Walker for Jira/Confluence documentation recovery
- Stakeholder alignment and project planning finalization

**Week 3-4: Data Extraction and Analysis**  
- Complete data extraction from Snowflake systems
- Data quality assessment and cleansing procedures
- AWS infrastructure optimization analysis
- Initial documentation and recommendations development

**Week 5-6: Delivery and Integration Support**
- Final data packages and documentation delivery
- Power BI integration support and testing
- AWS optimization implementation guidance
- Project completion and knowledge transfer sessions

### Payment Schedule
- **Initial Retainer:** $15,000 upon SOW execution
- **Milestone 1:** $10,000 upon completion of data extraction (Week 3)
- **Final Payment:** $10,000 upon project completion and delivery (Week 6)

## ASSUMPTIONS AND REQUIREMENTS

### Technical Assumptions
• Existing Snowflake and AWS access credentials remain valid and functional
• Data extraction can be completed through standard SQL and database export procedures
• Current AWS infrastructure allows for safe resource modification and termination
• Power BI integration requirements align with standard data import capabilities

### Business Assumptions  
• Client stakeholders will be available for timely requirements clarification
• Project scope remains focused on extraction and optimization rather than new development
• Clean Origin data systems contain the historical information required for business operations
• Future data warehouse discussions remain separate from this immediate tactical engagement

### Success Criteria
• Complete extraction of specified sales, customer, and product data
• AWS cost reduction of at least 20% through optimization recommendations
• Successful integration of extracted data into Power BI workflows
• Client stakeholder satisfaction with documentation and knowledge transfer
• Clear understanding of Clean Origin system value and integration potential

## RISK MITIGATION AND SUCCESS FACTORS

### Technical Risks and Mitigation
• **Data Accessibility Risk:** Early credential verification and system access testing
• **Data Quality Risk:** Comprehensive data profiling and quality assessment procedures  
• **AWS Modification Risk:** Careful analysis and backup procedures before any infrastructure changes
• **Integration Complexity:** Phased approach with testing and validation at each step

### Business Risks and Mitigation
• **Scope Creep Risk:** Clear definition of included services with change order procedures for additional work
• **Stakeholder Alignment Risk:** Regular communication and milestone reviews with key decision makers
• **Timeline Risk:** Realistic milestone planning with buffer time for unexpected discoveries

## FUTURE OPPORTUNITIES (POSITIONING ONLY)

While this engagement focuses on immediate tactical needs, the project will provide valuable insights into potential future opportunities:

### Data Warehouse Modernization Potential
• Assessment of ROI for maintaining vs. rebuilding Clean Origin's Snowflake infrastructure
• Integration possibilities with existing Grown Brilliance data systems
• Evaluation of Power BI vs. Looker capabilities for unified reporting across all brands

### Long-term Partnership Structure  
• Ongoing data consulting and advisory services
• Incremental data infrastructure development and optimization
• Strategic data initiatives supporting business growth and operational efficiency

### Future Engagement Options
• **2024 Market Rate Lock-In:** Client may secure current 2024 professional services rates for future projects initiated within 12 months:
  - Principal/Data Architect: $275/hour (market rate: $300-350)
  - Senior Data Engineers: $200/hour (market rate: $225-275)
  - Represents 15-20% discount from projected 2025 market rates
• **Retainer Option:** Monthly retainer arrangements available starting at $10,000/month for ongoing support and development

### Investment Protection Strategy
• Maximizing value from the $1+ million total Clean Origin system investment (including internal resources)
• Preserving years of Magento data mapping expertise that would be costly and time-consuming to recreate
• Integration planning for unified customer experience across all AJS Creations brands
• Technology roadmap development for scalable data operations

---

*This Statement of Work protects your existing data investments while addressing immediate operational needs. As Clean Origin discovered, the right data infrastructure can transform a business - doubling sales, optimizing margins across 52,000 SKUs, and enabling strategic decisions that drive growth. This engagement ensures you capture the full value of the proven system you've acquired.*