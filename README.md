# Kata-Container

Team:
=====
 
* * *
 
  
 
 
1\. Tingzhou Yuan (tzyuan15@bu.edu)  
2\. Alex Lee (alee23@bu.edu)  
3\. Dabin Jang (djang12@bu.edu)  
4\. Junyi Tang (jytang2@bu.edu)  
5\. Zhenhuan Wu (zhenhuan@bu.edu)
 
  
 
Mentors:
========
 
* * *
 
  
 
1\. James Hunt (james.o.hunt@intel.com)  
2\. Chao Wu (chaowu@linux.alibaba.com)  
3\. Zhongtao Hu (zhongtaohu.tim@linux.alibaba.com)
## Background: 
The Kata container project is gradually migrating from go to rust as v3 rolls out as rust performs better and is safer in multi-threaded environments. V3 has both go and rust runtime. Potential work can focus on the kata container tool chain: kata-runtime (go), or katactl (rust).  

## Vision
This project needs to align students’ needs with the community: students expect experience in building actual features while the community expects entry level contributors to carry out entry-level tasks (e.g. write unit tests). Despite the fact that there’s not many new features needed in Go, and the team is generally not ready to code in rust, we believe that there’s more we can do than just unit tests. The anticipated impact of this project is to create contributions to the kata containers community through feature testing and development in a 3-step setting.  

## Solution
Due to the migration from Go to Rust, there’s a lot more opportunities if the team chooses to work on the Rust part. This would mean starting with unit tests to get familiar with the language, container and codebase, and then move on to features on CLI/core components. For go it would mainly be bug tracing (there’s not even many go issues), there would be little to no new go features, and possibly some backports to maintain.
 (Context: mentors from Alibaba mainly work on the rust codebase, and James from Intel has a strong preference for rust as well.)

For those who choose to stick with go, opportunities are limited; for rust, the team would split to 1-2 ppl and work on minor issues/ unit tests, then possibly working together on a larger project with larger scope if the team ever gets one (This is also where we might get an actual user story going).  

## User Story
In accordance to the feature delivery plan, user stories would be ready in week4 when the team’s more familiar with Rust as well as the kata containers project codebase.  

## Incremental feature delivery
Week1 (week 4 in teaching calendar, this week) (Step1)
- Familiarize with kata-container core concepts
- Learn rust, get rust-runtime to build?
- Get kata-containers to run
- Walk through the codebase
Week2 (Step2)
- Familiarize with code base
- Learn rust through unit tests
Week3
- Learn rust through unit tests
Week4
- Learn rust through unit tests
- Assessment on project: 
  - CLI improvements?
  - features?
Week5 (Step3)
- Project design & impl
Week6
- Project impl
Week7
- Project impl
- Project testing
- Project mid term report
Week8
- Project impl
- Project testing
Week9
- Project assessment
- Final Project amendments
Week10
- Final presentation:
   - Kata intro
   = Actual project  

## Acceptance Criteria
The core evaluation would be subjective to each person,  depending on how much one’s learned or a team’s learned across 10 weeks. In the final presentation, the team is expected to share knowledge on both kata containers in an architecture level as well as detailed features, which should be confirmed by week4. It is reasonable for evaluations to be not based on actual output as spending time to learn a new & trending high performance language is considered justifiable. Also considered is the fact that learning how a large scale open source community works is valuable, especially how such a project is managed across orgs, therefore it doesn’t really matter if things really got merged.
   - (To-be negotiated, should be able to do better than just KPI, should NOT be superficial as learned xxx)
   - Evaluation by project mentors
