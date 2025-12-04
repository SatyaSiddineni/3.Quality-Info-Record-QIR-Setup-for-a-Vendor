🏷️ Quality Info Record (QIR) Setup for a Vendor – SAP QM Project


1. Project Overview

            This project demonstrates the complete setup and usage of Quality Info Records (QIR) in SAP QM for controlling vendor quality during the procurement cycle.
            As an SAP QM Functional Consultant, this project highlights your understanding of Quality Management integration with Materials Management (MM) — without any coding.
      
            A QIR ensures that only approved vendors can supply materials and defines quality-related controls such as inspection type, release status, certificate requirements, and skip logic.


2. Business Scenario

      A manufacturing company wants to ensure that procurement is executed only through quality-approved vendors. A Quality Info Record is created to manage:
          
          Vendor approval for specific materials
          Inspection requirements at Goods Receipt
          Blocking procurement for unapproved vendors
          Managing validity and quality system certifications

 
3. Process Flow
   
          Material Master (QM View Setup)
                  ↓
          Purchasing Info Record (Vendor + Material)
                  ↓
          Create Quality Info Record (QI01)
                  ↓
          Maintain Release/Block Status + Inspection Controls
                  ↓
          Test with Purchase Order (ME21N)
                  ↓
          Goods Receipt (MIGO)
                  ↓
          Inspection Lot Generated / Procurement Blocked


4. Key Learning Outcomes

            By completing this project, you demonstrate:
            SAP QM integration with Procurement
            Master data dependencies
            QIR release/blocked logic
            Inspection lot generation


5. SAP Transactions Used
   
            Purpose	                        Transaction
            Maintain Vendor Master	            XK02
            Maintain Material Master	          MM02
            Create QIR	                        QI01
            Change QIR	                        QI02
            Display QIR	                        QI03
            Goods Receipt for PO                MIGO
            Display Inspection Lot	            QA03

🙌 Author

Satyanarayana Siddineni 
SAP Functional Consultant
