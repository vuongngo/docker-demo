# Hypothesis Website parent project

## Overview
1. Demo is composed by 9 containers   
+ Frontend (universal React/Redux) (TBC)   
+ Backend (Golang)   
+ Admin (keystone.js)   
+ Matching (python) (TBC)   
+ Mongo   
+ nsqlookupd   
+ nsqd   
+ nsqadmin   
+ Proxy (TBC)   

## Project setup
1. Directory contains sub-modules of frontend (TBC), backend, admin and matching (TBC)  
2. To sync three project into sub modules, run   
'''
git submodule update --recursive
'''

## Development
1. Build docker image with docker-compose   
'''
docker-compose build
'''

2. Run all components with docker compose as    
'''
docker-compose up
'''

## Test
1. Build docker image with docker-compose   
'''
docker-compose -f docker-compose-test.yml build
'''

2. Run all tests with docker compose as    
'''
docker-compose -f docker-compose-test.yml up
'''

## Production (TBC)



