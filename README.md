Splunk Cybersecurity Portfolio

Introduction
Welcome to my Splunk cybersecurity portfolio! As an aspiring cybersecurity professional with a passion for technology and continuous learning, I've embarked on a journey to deepen my understanding of Splunk, a powerful tool for security information and event management (SIEM). Through the LetsDefend platform, I've completed the Splunk badge, gaining comprehensive knowledge in various aspects of Splunk administration and usage.

About This Repository
This repository serves as a showcase of my expertise in Splunk and cybersecurity. Here, you'll find detailed guides, tutorials, and resources covering essential topics such as installation, configuration, data management, searching, reporting, and user management within the Splunk ecosystem. Whether you're a fellow cybersecurity enthusiast, a hiring manager, or a recruiter, I invite you to explore the contents of this repository and witness my dedication to mastering Splunk and enhancing cybersecurity practices.

What's Included
Installation: Step-by-step instructions for installing Splunk on both Windows and Linux systems, accompanied by screenshots to guide you through the process.

Universal Forwarders: Insights into the role of universal forwarders in data forwarding and configuration guidance for setting up universal forwarders.

Adding Data: Techniques for adding various data sources to Splunk, with practical examples and visual aids.

Searching and Querying: Tips and tricks for conducting effective searches and queries in Splunk, including basic and advanced search syntax.

Reports, Alerts, and Dashboards: Strategies for creating insightful reports, alerts, and interactive dashboards to visualize and analyze data.

Health Check: Best practices for monitoring the health status of your Splunk deployment and ensuring optimal performance.

User Management: Guidelines for managing users, roles, and permissions within Splunk, emphasizing security and access control.

About Me
I am a passionate IT professional transitioning into cybersecurity, with a keen interest in leveraging technology to enhance security measures. Through my continuous learning journey, I aim to contribute to the ever-evolving landscape of cybersecurity and protect organizations from emerging threats.

Get in Touch
If you have any questions, suggestions, or collaboration opportunities, feel free to reach out to me. I'm always eager to connect with fellow cybersecurity enthusiasts and industry professionals.


Below are two of the key learning path that leads to Splunk on LetsDefend platform which I think is key to a depth SIEM understanding.


SIEM introduction:

![image](https://github.com/karothebenard/SIEM/assets/165713653/905c3afc-a78a-495d-bdf3-a61858e24b14)

     Log collection,

     Log aggregation and Parsing,

     Log Storage,

     Alerting,


INCIDENT MANAGEMENT 101:

![image](https://github.com/karothebenard/SIEM/assets/165713653/2ef049d3-ba0b-4214-831f-60908c1cd40d)

     Introduction to incident management,

     Basic definition about incident management,

     Incident management syatem(IMS),

     Case/Alert Naming,

     Playbook,

     What does the SOC analyst do when an alert occurs,


SPLUNK:


![image](https://github.com/karothebenard/SIEM/assets/165713653/0b2104a3-36be-4c87-b084-84b87dd02ec9)



INSTALLATION:

Visit splunk site,

Log in using you account or create one if you do not have one,

Download the MSI installation, Please go to Letsdefend for the detailed installation process,

![image](https://github.com/karothebenard/SIEM/assets/165713653/aafba881-1a7a-44eb-a35b-acd72de0ab4d)

Log in using the created username and password during the installation,

![image](https://github.com/karothebenard/SIEM/assets/165713653/eded87db-e59d-4480-904e-062df74197a1)

Universal forwarder,

Go to windows computer and download the setup file (Universal forwarder)
![image](https://github.com/karothebenard/SIEM/assets/165713653/aa2e08ba-8c86-415e-9f39-a4ada9d2869f)

Please visit letsDefend site for the detailed installation process.

Kindly note that I have used Letsdefend data file and lab for practice for the below processes.

Adding data file for the Lab

![image](https://github.com/karothebenard/SIEM/assets/165713653/e0406eca-9dae-432c-9506-ebb8abe4db19)

![image](https://github.com/karothebenard/SIEM/assets/165713653/f4f060ca-c622-47c4-a3ec-af2923b47bef)


![image](https://github.com/karothebenard/SIEM/assets/165713653/87f4906e-5d31-42fd-8a93-ae9e38556726)

Search data Lab exercise

Tips:

Field names are case sensitive,

Field values are not case sensitive,

The wild card is available(use *)

You can use operators such as AND,OR,NOT

Process:

Data selection: 

              :Range in terms of date presets(today,last week,last year,last 24 hours,etc.)
              
              :Relative(beginning of hour, x minutes ago , x weeks ago, etc.)
              
              :Real -time(Date range between 00:00 DD/MM/YYYY to DD/MM/YYYY 24:00)
              
Timeline:

        : When you perform search , splunk will display a timeline.
        
Search mode:

        :There are three modes (Fast mode,Smart mode,Verbose mode) you will use mostly the smart mode.
              

![image](https://github.com/karothebenard/SIEM/assets/165713653/add3e526-64ec-434d-85f4-e525f886431b)

Reports, alerts and dashboards:

          Reports: Reports are saved search results. They can be scheduled or can be executed when needed.

          Try search bar
          
![image](https://github.com/karothebenard/SIEM/assets/165713653/7530d071-620a-4108-9865-e72eb0448568)
          
          Go to save as menu and select reports
          
![image](https://github.com/karothebenard/SIEM/assets/165713653/2ef63c27-21cb-49a8-8122-935e4c207a39)
          
          Give a title and description of your report
          
![image](https://github.com/karothebenard/SIEM/assets/165713653/7eea5de8-984c-4a18-b041-7848681e06ce)
          
          Save and go to view
          
![image](https://github.com/karothebenard/SIEM/assets/165713653/ca3ba9d9-fb03-41eb-bd7a-f36b8352bda1)
          
          Edit or delete an existing report
          
![image](https://github.com/karothebenard/SIEM/assets/165713653/9d20e882-2ed2-4915-9fdc-b85329ba919f)
          
![image](https://github.com/karothebenard/SIEM/assets/165713653/94f7aef1-1be9-464c-9403-c50914840473)

          Shedule reportfrom edit button:

![image](https://github.com/karothebenard/SIEM/assets/165713653/44f631b8-279a-439a-a57a-fa517fbb6860)

![image](https://github.com/karothebenard/SIEM/assets/165713653/9c58e6f9-7b45-4bc7-b035-800e03ad6ca2)

          Scheduled report

![image](https://github.com/karothebenard/SIEM/assets/165713653/ac089482-2cf3-450c-9bdc-23d97390c2c3)

          Alerts:Use the same request as in the report section and save as an alert.

![image](https://github.com/karothebenard/SIEM/assets/165713653/415e4e81-cf8e-4375-bdd7-927d59c7d141)

          Dashboards:Dashboards are made for the purpose of having same request with same information.


          Health status:We have 4 different health status as described below

![image](https://github.com/karothebenard/SIEM/assets/165713653/d22342f6-273e-433d-97c5-e6e5d66647a7)


           User management:We have roles,user and Password management.

                 Roles:The default splunk give you some role and as only account it will give you admin role. You can find roles as below.

![image](https://github.com/karothebenard/SIEM/assets/165713653/00c01a2c-3fef-4c46-8d11-aad6e8695542)

![image](https://github.com/karothebenard/SIEM/assets/165713653/81118bac-1e31-4075-8420-d6732af3a9b5)

                  User: The default user is admin and every user must have a role.

![image](https://github.com/karothebenard/SIEM/assets/165713653/dd7f5505-3aaf-4ef2-86c1-02895e54ac2a)


You have reached the end of the Splunk thread.

Thank you.


                  

                 


          


          





          
          


          

          

          

          

          

          
          























