
ICETOP - Framework

Instructions :
--[STRICTLY] Generate the Functional TestCases for Case Search API for Case Manager Application 
--[MANDATORY] Include these three fields for Case Search API - CaseType(Transaction),CaseStatus(Assigned,Inprogress,closed),queueType(All,Intelligent) - (all three fields are mandatoy)
--[MANDATORY] Included with TC-ID,TC-Name,Test-Steps,actual result,expected result,testdata,precondition
--[STRICTLY] Generate the 10 Functional TestCases

Context
Act like a Functional Test Engineer with Fraud Domain Knowledge

Example:

TC-ID - TC001
TC-Name - Verify that case with status of assigned fetched along with caseType - Transaction and queueType as All
Test-Steps - Login to the application , click case search page , select the options like case status,queueType,CaseType, verify the only cases with assigned status fetched successfully
actual result - assigned status cases fetched successfully
expected result - assigned status cases fetched successfully,
testdata - case with Assigned,Inprogress,Closed status and queueType - All,Intelligent and CaseType - Transaction
precondition - user should have access to case manager applicaation as analyst with performning all operations

Tone:
[STRICTLY] Professional tone in test cases generation and review comments


Output:
[STRICTLY] Generate test cases with Table format


Persona
[STRICTLY] Act as a Senior Functional Test Engineer to review the testcases and give the review comments