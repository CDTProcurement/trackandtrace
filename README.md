# California Track and Trace System Procurement

In partnership with the California Department of Food and Agriculture and other state agency partners, the California Department of Technology will be conducting a procurement to acquire a system to "Track and Trace" cannabis products within California. 

If you have comments or questions please [submit a Github Issue](https://github.com/CDTProcurement/trackandtrace/issues) by noon on 12/23/2016. 

# Administrative Requirements
* [Standard Contract Terms & Conditions - Information Technology General Provisions](http://www.documents.dgs.ca.gov/pd/poliproc/GSPD401IT14_0905.pdf)
* [Cloud Computing Special Provisions for Software-as-a-Service (SaaS)](http://www.documents.dgs.ca.gov/pd/poliproc/CLOUDCOMPUTINGSERVICESSPECIALPROVISIONS_14_0903.docx)
* [Payee Data Record](http://www.documents.dgs.ca.gov/dgs/fmc/pdf/std204.pdf)
* [Bidder Declaration](http://www.documents.dgs.ca.gov/pd/delegations/GSPD105.pdf)
* [SB/DVBE Certifications](https://caleprocure.ca.gov/pages/PublicSearch/supplier-search.aspx) - you only need to submit an SB or DVBE certification if you are a State of California certified Small Business (SB) or Disabled Veteran Business Enterprise (DVBE) or will be utilizing an SB or DVBE as a subcontractor.
* [DVBE Declaration](https://www.documents.dgs.ca.gov/pd/poliproc/STD-843FillPrintFields.pdf) - you only needs to submit a DVBE Declaration if you are a certified DVBE or is utilizing a DVBE as a subcontractor.
* [Security of State Registration](https://businesssearch.sos.ca.gov) - Proof of current registration with California Secretary of State.
* Compliance with the Iran Contracting Act of 2010.

____

## Business Needs and User Stories for Cannabis Track and Trace System

The State defined the following preliminary business needs and user stories for the Cannabis Track and Trace System.

### As a Licensee
1.	I would like to be notified of recalls.
2.	I would like to obtain / create unique Identifier & Tags (Tag ID)
3.	I would like to document these events;
    * Tagging, labeling, processing, manufacturing, packaging and repackaging events
2.	I would like to ship product.
3.	I would like to label shipments of products.
4.	I would like to create, update, print & receive shipping manifest.
5.	I would like to report cultivation details (plant and batch)
6.	I would like to report product information
7.	I would like to report cannabis plants by type, strain and name.
8.	I would like to track and report cloned, germinating and mother cannabis plants by count, type, strain
9.	I would like to enter lab test report
10.	I would like to report losses and product changes
11.	I would like to report irregularities
12.	I would like to grandfather plants through lifecycle stages
13.	I would like to track and report on cloned and germinating plants sold to licensed dispensaries
14.	I would like to handle multiple drivers on transport
15.	I would like to track and report inventory, purchases, sales and ending inventory on a real-time or daily basis
16.	I would like to track and report inventory loss from plant death, failure to grow, theft, etc.)
17.	I would like to track and report all disposal of cannabis and cannabis products.
18.	I would like to track cannabis plants through the entire cultivation lifecycle.
19.	I would like to track all materials and ingredients used during the cultivation lifecycle (e.g., soil, growth regulators, pesticides, etc.)
20.	I would like to track accountability for all aspects of the cannabis plant including trim, leaves, flowers, stems, stalks, etc.
21.	I would like record transfers of small amounts of cannabis and cannabis products to a laboratory for testing.
22.	I would like a secure web service API for integrating my 3rd party information system.
23.	I would like to upload data into the system from my 3rd party information system
24.	I would like the ability to verify and correct uploaded data before it is posted to the system.
25.	I would like the correct/amend/supplement posted data and information.
26.	I would like a training and testing program to ensure I / my staff know how to correctly use the system.
27.	I would like to document receipt of a shipment from another licensee.
28. I would like to integrate, in real-time, with hardware / equipment used to weigh cannabis and cannabis products, scanners, printers.

### As a Law Enforcement Officer
1.	I would like to retrieve shipping manifest.
2.	I would like to verify shipment and associated licensee information.
3.	I would like to notify Licensor of infraction
4.	I would like to search Track & Trace data.
5.	I would like to handle destruction of products and tags/ids upon arrests / confiscations.
6.	I would like to verify transporter has:
    * Manifest, cannabis license, company security badge identifying the employee works for the licensee, driver’s license Cannabis License Expiration Date, Cannabis License Issue Date.

### As a Regulator
1.	I would like unique identifiers to be created and issued for each cannabis plant.
2.	I would like unique identifiers that can be attached to the base of each cannabis plant.
3.	I would like unique identifiers to be created and issued for lots of cannabis plants
4.	I would like to perform analytics, program & management reporting.
5.	I would like ad-hoc reporting capabilities for all tables and all data within the system.
6.	I would like to export/display any report in multiple formats (MS Excel, PDF, CSV, HTML, text files, etc.)
7.	I would like to download datasets and reports.
8.	I would like the ability to configure the system in response to any address any changes to regulations or statutes or to address enforcement needs that arise.
9.	I would like to have to the information necessary to assess, levy, collect and track cultivation and excise taxes:
    *  In a way that minimizes manual labor.
    *  Tag or mark to identify when/if, by licensee taxes paid.
    *  Identify when tagged or marked product changes possession (i.e., sale from cultivator to distributor, or sale from distributor to manufacturer)
    *  Subsequently tag or mark previously tagged or marked product when it changes composition, i.e. leaves turned into extract, or extract turned into edible.
    *  Subsequently tag or mark previously tagged or marked product when it changes packaging or size, i.e. 1 lb bag broken down into 16 one ounce bags.
    *  Traceable back to origin of harvest.
10.	I would like track if product is returned, and be able to show the adjustment in the track and trace system.
11.	I would like to easily verify (i.e. via physical inspection; perhaps via visual inspection) that taxes have been paid/levied on a product.
12.	I would like an audit log for historical purposes, data analysis and/or data restoration.
13.	I would like the system to track all changes in the system including adds, updates, and deletes by any registered system user and the associated date/time stamps.
14.	I would like to suspend access to the system for a licensee and all associated users when the applicable license status is not active.
15.	I would like the ability to configure system user access to functions, data and reports appropriate to the individual and their user group.
16.	I would like to prevent the creation of a shipping manifest when a destination address is outside of California.
17.	I would like a means to determine the validity of a hardcopy shipping manifest produced by the system.
18.	I would like to send specified data elements on demand or as a scheduled job in a specified timeframe, to an external system in a defined format(s).
19.	I would like the capability to grant security access to the system / data elements in a granular manner.
20.	I would like to track and monitor inventory discrepancies for any transfer of inventory between licensees.
21.	I would like to maintain a record of all electronic shipping manifests.
22.	I would like to access to all electronic shipping manifests.

### As an Inspector/Investigator
1.	I would like to differentiate function and purpose for an inspection versus an investigation
2.	I would like to enter data associated with a site inspection while in the field/working remotely.
3.	I would like a secure, web-based application which inspectors may use to access and record data.
4.	I would like to retrieve data for site inspection.
5.	I would like to receive automated alerts on track and trace irregularities (reuse of unique identifiers, identifiers don’t match product/packaging, product designated as recalled, destroyed or stolen).
6.	I would like to perform site inspection.
7.	I would like to record data and information associated with a site inspection
8.	I would like to track, monitor and report irregularities in reported data based upon defined business rules
9.	I would like to be notified of irregularities or violated thresholds (business rules).
    * I.e. “smart inspections”
10.	I would like to be able to configure the tax events in the supply chain – track and trace system.
11.	I would like to track and monitor all movement/transfer of cannabis and cannabis products on a licensed cultivator’s premises during the cultivation lifecycle (e.g., germination, vegetative growth, and flowering) and during the harvesting process (e.g., drying, trimming, storage) for each harvest batch of cannabis.
12.	I would like to track unique identifiers issued to a licensee.
13.	I would like to track the agent receiving unique identifiers issued to a licensee.
14.	I would like a unique identifier that provides safeguards against creation of fraudulent identifiers and helps to limit diversion of unique identifiers to unlicensed individuals.
15.	I would like to conduct a periodic inventory reconciliation of a licensee.
16.	I would like to inspect and input information regarding outbound and inbound shipments of cannabis and cannabis products for any licensee.

### As a Government Stakeholder
1.	I would like to access activity records
2.	I would like to search Track & Trace data.
3.	I would like to track lot and batch information through the entire supply chain and cross-reference and analyze data between and across all licensees.
4.	I would like to ensure that my interests, goals, and objectives are represented in operations.
5.	I would like to run reports; e.g.
    * “Total” summary by license:
        * Manufactured, grown, moving through the system; i.e. what the system is producing.
    *	How much is grown and moved through the system.
    * Number Of cultivators.
        * In a way that allows to divide by license type.
    * Ad hoc (various); per field (location); per global (location); per plant; per batch, etc.
    * How much water used per crop.
    * Site visits.
    * Defined relationship between tags & license types and cross reference reports by license type. #Tying #associating license number to unique id.
    * #Tying #associating transporter license number to manifest to driver license number .
    * Number of plants by cultivator.
    * What is moving through the system?
    * Reports by Licensee.
    * How much is being manufactured?
    * How much is being grown?
    * Cultivators using ground water, surface water, etc.

### As a Tester or Licensor
1.	I would like to document a product recall.

### As a Licensor
1.	I would like to verify product quality.
2.	I would like to do a product recall.
3.	I would like to be notified of irregularities or violated thresholds (business rules).
4.	I would like to handle cultivator nurseries. (Final place for flowering);
    * Aka. I would like to handle hybridizing Research and Development (R&D)
5.	I would like to grandfather plants through lifecycle stages
6.	I would like to handle returns.
7.	I would like to administer the concept of  - >> sell by/expiration date.
8.	I would like to integrate with existing industry systems / processes.
6.	I would like the ability to create, update delete data as needed
9.	I would like to audit licensees and their products;
    * E.g. Distributor
        * Product’s Cultivator’s name
        * Transporter(s) and license number(s)
        * Type of goods received
        * Type by weight and count
        * Date of receipt
        * Details of dispensary
        * Transportation to Dispensary details including vehicle and license number
        * Samples given to Dispensary
    * E.g. Dispensary
        * Distributor and Transporter details
        * Delivery details

### As a Tester
1.	I would like to document test results.

### As a Tester, Distributor, Manufacture, Transporter, or Dispenser
1.	I would like to receive and verify receipt of product.

# Bureau of Medical Cannabis Regulation (BMCR) Track and Trace Requirements

## Distributor Requirements
A distributor shall enter the following events into the track-and-trace database:

**Receipt of goods from cultivator or manufacturer:**

1.  Enter the following information:
    * Cultivator’s or manufacturer’s name and license number;
    * Name of licensee who transported the goods and license number;
    * Type of goods received;
    * Amount received, by weight or count;
    * Best-by, sell-by, or expiration date of the batch;
    * Party who holds title to the goods;
    * The date of receipt of goods;
    * The unique identifiers associated with the goods; and
    * Other information required elsewhere by the Bureau.

**Sample taken by testing laboratory:**

1. Enter the following information:
    * The testing laboratory’s name and license number;
    * The name of the lab agent who obtained the sample;
    * Total weight of the sample obtained;
    * The date the sample was obtained; and
    * Other information required by the Bureau.

**Sale to dispensary:**

1. If a distributor purchases medical cannabis, the distributor shall enter the following information:
    * Name of dispensary licensee with whom the distributor contracted for sale and dispensary’s license number;
    * The date of the contract for sale;
    * The type of goods contracted for sale;
    * The amount of goods contracted for sale, by weight or count;
    * The date title passed to the dispensary; and
    * Other information required by the Bureau.

**Transportation to dispensary:**

1. If the distributor uses his or her transporter license to transport the medical cannabis to a dispensary, the distributor shall enter the following information: * Transportation license number;
    * Amount of goods transported, by weight or count;
    * Vehicle license plate number used for transportation;
    * Date of transport; and
    * Other information required by the Bureau.

**Provision of a sample given to a dispensary or manufacturer for business purposes under section [11].**

1. Enter the following information:
    * Licensee to whom the sample was provided and license number;
    * Type of sample provided;
    * Weight of sample provided;
    * Date sample was provided; and
    * Other information required by the Bureau.

## Dispensary Requirements
A dispensary shall enter the following events into the track-and-trace database:

**Receipt of goods from a distributor:**

1. Enter the following information:
    * Distributor’s name and license number;
    * Name of licensee who transported the goods and license number;
    * Type of goods received;
    * Amount received, by weight or count;
    * Best-by, sell-by, or expiration date of each product received;
    * The date of receipt of goods;
    * The unique identifiers associated with the goods received; and
    * Other information required by the Bureau.

**Sale of goods to a qualified patient or primary caregiver:**

1. Enter the following information:* The name of the licensed dispensary employee who processed the sale;
    * The name or patient identification number of the qualified patient or primary caregiver who made the purchase
    * The date and time of the transaction;
    * A list of all of the medical cannabis or medical-cannabis product purchased, including a description of the quantity purchased;
    * The unique identifiers associated with the goods sold; and
    * Other information required by the Bureau.

**Return of goods from a qualified patient or primary caregiver**

1. If a dispensary accepts a return of medical cannabis from a qualified patient or a primary caregiver, the dispensary shall enter the following information:  * The name of the licensed dispensary employee who processed the return;
    * The name or patient identification number of the qualified patient or primary caregiver who made the purchase
    * The date and time of the transaction;
    * A list of all of the medical cannabis or medical-cannabis product returned, including a description of the quantity purchased;
    * The unique identifiers associated with the goods; and
    * Other information required elsewhere by law.

**Return of goods to a distributor:**

1. Enter the following information: * Distributor’s name and license number;
    * Name of licensee who transported the goods and license number;
    * Type of goods returned;
    * Amount received, by weight or count;
    * Best-by, sell-by, or expiration date of each product returned;
    * The date of the return of goods;
    * The unique identifiers associated with the goods returned; and
    * Other information required by the Bureau.

**Destruction of goods:**

1. Enter the following information:
    * The name of the licensed dispensary employee who performed the destruction;
    * The date and time of the destruction;
    * A list of all of the medical cannabis or medical-cannabis product destroyed, including a description of the quantity destroyed;
    * The unique identifiers associated with the goods destroyed; and
    * Other information required by the Bureau.

**Transfer of goods to a distributor for destruction:**

1. Enter the following information:
    * Distributor’s name and license number;
    * Name of licensee who transported the goods and license number;
    * Type of goods transferred;
    * Amount transferred, by weight or count;
    * The date of the transfer of goods;
    * The unique identifiers associated with the goods transferred; and
    * Other information required by the Bureau.

## Transporter Requirements

A transporter shall enter the following events into the track-and-trace database:

1. Enter the following information:
    * Name and license number of transporter;
    * Date transporter receives goods from licensee for transport;
    * Amount transported, by weight or count;
    * Date transporter delivers product to licensee;
    * The unique identifiers associated with the goods transferred;
    * Spoilage or accidental fouling of product;
    * Any event resulting in exposure or compromise of the product and
    * Other information required by the Bureau.
