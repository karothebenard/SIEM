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

INSTALLATION:

Visit splunk site

Log in using you account or create one if you do not have one

Download the MSI installation, Please go to Letsdefend for the detailed installation process

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























