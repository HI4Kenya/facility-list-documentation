Chapter 1
===============
Introduction
--------------
DHIS2 is a tool for collection, validation, analysis, and presentation of aggregate and 
patient-based statistical data, tailored (but not limited) to integrated health information 
management activities.One of its feature is through use of the DHIS2 Web-API 
it allow for integration with external software and extension of the core platform 
through the use of custom apps.AFYA 360 will be one of the custom application in the DHIS2 
that will allow user to search for facilities inside DHIS2.Furthermore,the user will be able 
to compare Organization Units(DHIS2) and facilities(KHMFL).

1.0 Background
------------
Over the years, use of  applications to solve problems had gained a lot of support and popularity all
over the world.Health sector has not been left behind in employing applications to solve problems.
With the development of DHIS2 in 1998-1999 ,the Ministry of Health is a able to aggregate data and 
those Data needs to be made useful thought development of applications.Besides DHIS2 the 
Ministry of Health has Kenya Master Health Facility List (KMHFL), is an application with all 
health facilities and community units in Kenya. Each health facility and community unit is identified
with unique code and their details describing the geographical location, administrative location, 
ownership, type and the services offered.
Afya 360 is an application that will integrate this two systems.it will enable DHIS2 users to to see 
conflicts between facilities in DHIS2 and KMFL. 

1.1 Problem statement
------------
Kenya Master Health Facility List (KMHFL) is an application with all health facilities and community 
units in Kenya. Each health facility and community unit is identified with unique code and their 
details describing the geographical location, administrative location, ownership, type and the 
services offered.KMHFL is the official Registry of all the facilities in the country.For its the official
registry their was need to integrate it to DHIS2 beacause there are facilities that exists in DHIS2 
and are not recognised and licensed by the Ministry of Health.Besisdes that it will enable DHIS2 users 
search for facilities in DHIS2 and also able to compare facilities in both systems and resolve confict 
in both systems.

MHL is a system that exists as a Facility Registry system. It has the official list of facilities 
registered as health service institutions. Being able to integrate it in DHIS2 will help DHIS2 users 
know if their facility or facilities they are in charge of are registered in this system. 
Those who have their facilities registered may have different information in the systems and therefore 
a need to compare the data in the two systems arises.

1.2 Research Objective
------------------------
To investigate the effects of Dhis2 user adding facilities in Dhis2.

To find out if facilities in KMFL and DHIS2 match(name,code,services they offer and type)

To investigate why health HROs add new facilities in DHIS2

To find out if they is an existing facility registry in DHIS2 their features and how 
they operate and to improve them to increase its acceptability and usability.

1.3 System-Objective
---------------------
Create a facility registry application to be deployed and used  in DHIS2.
The application should be able to search through facility information available in KMHFL inside DHIS2.
A further ability is that it should be able to show conflicts in information about the two facilities 
and give an option for resolving.A report is derived and it can be used to resolve the issue in DHIS2.
Our application focused o the name and code of the facilities.

1.4 Justification
---------------------
Present systems are not intuitive and do not present a live search that allows a user who is not be 
sure about the name of a facility and its location in terms of county, sub-county to the ward.
Afya 360 will provide a smart search for the user who has a little  knowledge about the facility they 
want to search.Afya 360 will enable the users to know the  conflicts present in the two systems. 
a further functionality of the app will be to allow for rectification by a relevant authority.

1.4 Scope
----------------
The scope of the project includes:
    i. Parties/shareholders

These are the individuals that will use the system. They include;

        a.National health managers
        b.Province health managers
        c.National health information system division officers (HISO)
        d.District health records and information officers (DHRIO)
        e.Facility health records and information officers (HRIO)
        f.Data entry clecks.
    ii. Technologies
These are the technology platforms that the system will be built on. They include;

        a.react.js
        b.boostrap
        c.react route

    iii. Operations
These are the functions that can be performed in the system. They include;

a.The application should be able to be deployed in the DHIS2 system and be used my DHIS2 users.
b.It should be able to search through facilities present in KHMFL in DHIS2.
c.It should be easy to use and intuitive.
d.It should be able to show conflict in information from DHIS2 and KHMFL and update DHIS2.

