# Cloud Computing Project: Sentiment Analysis of Melbourne's multi-area livability

This repository contains the source code for a project I completed at the University of Melbourne. In this project, I crawled and extracted Twitter data from the Melbourne area in real-time on the cloud server MRC, combined it with natural language processing sentiment analysis to achieve sentiment analysis of the livability of the Melbourne area, and finally presented the results on the website as heat map charts and other visualizations

The system can be accessed via the following URL: 

## YouTube Link
Demo video for cloud deployment of harvests on different instances

  * https://www.youtube.com/watch?v=GomoVtsVbfw
  
Demo video for the introduction of models, scenarios, and Demo on preprocessing and MapReduce
  
  * https://www.youtube.com/watch?v=yIrU9tkz45k

Demo video for the frontend
  * https://www.youtube.com/watch?v=REwNQ-jyZQ4

## Web page
  * http://172.26.129.131:8080/
  
## Repository Structure
```
| /AURIN 
      - AURIN data processing and geojson creation
  /Ansible_Deployment
      - ansible scripts
  /crawler
      - twitter harvest
  /MapReduce 
      - CouchDBMapReduce
  /frontend
      - frontend application
  /demo_harvest_for_video
      - demo twitter harvest for video
  
```
## The focus of this project
1. harvest tweets using the Unimelb Research Cloud which depends on the requirement of analysis 
2. use the twitter data and Aurin data to analyse scenarios which imply the liveability of Melbourne
3. visualize the scenarios' analysis and creat the user interface using the Unimelb Research Cloud

## System architecture

The system architecture designed for this project is deployed on the [University of Melbourne Research Cloud](https://dashboard.cloud.unimelb.edu.au/). It makes use of various technologies such as [Ansible](https://www.ansible.com), [Docker](https://www.docker.com) and [CouchDB](https://couchdb.apache.org). 

For further information, please refer to the project report attached to this submission.
