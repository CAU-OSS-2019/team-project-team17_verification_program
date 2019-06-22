# GameHaeDuo Verification Program
A program that verifies Gamehaeduo's **Matching Algorithm**.

## About GameHaeDuo Verification Program
* We crawl data we need from [op.gg](https://www.op.gg/). op.gg is a website that has real-time stats for League of Legend.
* We crawl real-time data and use that data to find how duos are playing League of Legend. We use the data we crawled to compare it with our original program. Comparing the data is also included in the verification program. 

### Necessity
* Our original project is [here](https://github.com/CAU-OSS-2019/team-project-team17). 
* We needed to verify if our project is working correctly. So we made our very own verification program. 

### Support Websites
* [op.gg](https://www.op.gg/)  
* [leagueofgraphs](https://www.leagueofgraphs.com/ko/champions/counters)  


## Getting Started with GameHaeDuo Verification
* You will need Python, C++ running environment to use our program. 
1. Run Makelist.py.Once you run the program the program will require the number of users you want to crawl. 
(The more data the more accurate the verifying process will be. )
2. Run verificationUserInfoCrawling.py. This will read the excel files and relocate user info to db server.
3. Run verification.cpp. Runs our actual matching algorithm
4. Check the excel file. The data set and our algorithm is comparable easily.

## Installation
Write Someting...


## Contribution
If you want to contribute to our project, please read [CONTRIBUTING.md](https://github.com/CAU-OSS-2019/team-project-team17_verification_program/blob/master/CONTRIBUTING.md) before contributing.

### Issue
When you have issue, please open your issue [here](https://github.com/CAU-OSS-2019/team-project-team17_verification_program/issues)

### Pull Request
We are developing in 'develop' branch.
1. Fork to your account and modify your changes.
2. Please [pull request](https://github.com/CAU-OSS-2019/team-project-team17_verification_program/pulls) to corresponding branch.


## License
Apache 2.0


## Other Repositories of GameHaeDuo
### Client
https://github.com/CAU-OSS-2019/team-project-team17_client

### Server
https://github.com/CAU-OSS-2019/team-project-team17_server
