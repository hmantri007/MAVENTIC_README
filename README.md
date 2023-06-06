## WHAT IS SAP HANA ??
SAP HANA  (High-performance ANalytic Appliance) is a multi-model database that stores data in its memory instead of keeping it on a disk. The column-oriented in-memory database design allows you to run advanced analytics alongside high-speed transactions – in a single system. Why is this so important? Because it lets companies process massive amounts of data with near-zero latency, query data in an instant, and become truly data-driven. By storing data in column-based tables in main memory and bringing online analytical processing (OLAP) and online transactional processing (OLTP) together, SAP HANA is unique – and significantly faster than other database management systems (DBMS) on the market today.

Reference: [HANA Overview]

## History of Native Hana Development ??
On 3rd February 2015, SAP announced its new business suite fully built on SAP HANA called SAP S/4HANA meaning SAP Business Suite 4 SAP HANA. This is considered to be the new product and biggest innovation of SAP since R/3 System.

1. SAP R/1 System:
SAP R/1 is the first ever product of the Software Giant — SAP (Systems, Applications and Products in Data Processing). As the name suggests, SAP R/1 is the system with one tier architecture. ‘R’ stands for real time data processing. A Software mainly consists of three layers — Presentation Layer, Application Layer and Database Layer. In one-tier architecture (SAP R/1), all these three layers were installed in one server. The first module developed was Financial Accounting System. It was introduced in the year 1972.

2. SAP R/2 System
SAP R/2 is the SAP’s mainframe product and also the first ever compact software package for the end-to-end business applications. It was introduced in the year 1979. SAP R/2 runs on mainframes such as IBM, Siemens, Amdahl etc.R/2 System is two-tier architecture based product. Presentation layer is on one server while the application and database layers are present in another server. The mainframe solution is not open. But with the help of ALE (Application Link Enabled) Technology, R/2 can be linked to system and share online data.

3. SAP R/3 System
SAP R/3 is SAP’s integrated software solution for client/server and distributed open systems. SAP’s R/3 is the world’s most-used standard business software for client/server computing. R/3 meets the needs of a customer from the small companies to multi-billion dollar companies. The software is highly customizable using SAP’s proprietary programming language, ABAP/4.The SAP R/3 System working process is described as follows:

    1. All requests that come in from presentation server are directed first to the dispatcher.
    2. The dispatcher writes them first to the dispatcher queue.
    3. The dispatcher pulls the requests from the queue on a first-in, first-out basis.
    4. Each request is then allocated to the first available work process. A work process handles one process at a time.


Reference: [History of S/4Hana]


## TASKS THAT ARE COMPLETED:

1]Business Technology Platform Setup 
Reference :[https://developers.sap.com/group.btp-setup.html]

2] SAP HANA Cloud Setup
Reference: [https://developers.sap.com/tutorials/hana-cloud-deploying.html]

3] Business Application Studio Setup
Reference : [https://developers.sap.com/tutorials/appstudio-onboarding.html]

4] a]Creation of HANA Project using template
   b]Explore the project structure and HANA Connections
   c]Create a table and load data into it
   d]Have your objects pushed to your existing git repository and also document the references in readme file

Reference: [https://developers.sap.com/tutorials/hana-cloud-create-db-project.html]




[History of S/4Hana]: https://medium.com/@ktern/history-of-sap-s-4hana-ad6b0d938bbc#id_token=eyJhbGciOiJSUzI1NiIsImtpZCI6IjgyMjgzOGMxYzhiZjllZGNmMWY1MDUwNjYyZTU0YmNiMWFkYjViNWYiLCJ0eXAiOiJKV1QifQ.eyJpc3MiOiJodHRwczovL2FjY291bnRzLmdvb2dsZS5jb20iLCJuYmYiOjE2ODQzODYyNzcsImF1ZCI6IjIxNjI5NjAzNTgzNC1rMWs2cWUwNjBzMnRwMmEyamFtNGxqZGNtczAwc3R0Zy5hcHBzLmdvb2dsZXVzZXJjb250ZW50LmNvbSIsInN1YiI6IjEwMTE2NDE2MTk4MDQ5ODExMjUzNSIsImVtYWlsIjoiaG1hbnRyaTIwMDFAZ21haWwuY29tIiwiZW1haWxfdmVyaWZpZWQiOnRydWUsImF6cCI6IjIxNjI5NjAzNTgzNC1rMWs2cWUwNjBzMnRwMmEyamFtNGxqZGNtczAwc3R0Zy5hcHBzLmdvb2dsZXVzZXJjb250ZW50LmNvbSIsIm5hbWUiOiJIYXJzaCBNYW50cmkiLCJwaWN0dXJlIjoiaHR0cHM6Ly9saDMuZ29vZ2xldXNlcmNvbnRlbnQuY29tL2EvQUdObXl4WnJNdjVZZU9PeFlCQVN5SUQ3bGx4NTZEX3FYdWdRT0Nfdnp5aHI9czk2LWMiLCJnaXZlbl9uYW1lIjoiSGFyc2giLCJmYW1pbHlfbmFtZSI6Ik1hbnRyaSIsImlhdCI6MTY4NDM4NjU3NywiZXhwIjoxNjg0MzkwMTc3LCJqdGkiOiIxNTU0NmYwZTI1MzlmMmFhMDI5NDliMDlhYjM5MTAzMzFiMmM2ZGZlIn0.dUNKu6f1M1uxk40XIMuktcODJl22wGQBfTLwmbwNuzzmLJr1iHByY3MkTgE9GHjYXIQHCVeYqynMFU5BgnbEAMTrskYI-v0pZOmx6_r5eFkZ8IrZqfeOSIwWXJTwNh2WAyWIA6nbsHAbATlqAJTmFXuiReep6m58brXXiZwVs1erORiWNfV7BoFpfKzsxZvmu2EXMZhi1HzNqqx-PGQbm_7_M5iwoZnrbidkrhi-kucDWyjac5UKhV3s-mbJmo5p4E-yqvfL4jttVHY407Lsf3B7mEMvTNJ6y9hiRcFNAPvTlex9HPDy8CamyXBvMpenp-xE1jqIjPcMpcpzx0BGHw
[HANA Overview]: https://www.sap.com/products/technology-platform/hana/what-is-sap-hana.html
