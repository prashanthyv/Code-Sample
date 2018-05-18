# Code-Sample
While writing the code samples it's good to go by these principles (unless we can find better)
- When in Doubt on the level of detail we need to explain - Assume the user is new to Azure and new to Key Vault
    We could sure have links to explain topics in further detail but all important topics should be explained on the main page. 
    For example (Intro to Key Vault should explain Service Principal in base detail and we should have a link to explain it in further detail)
- The samples / quickstarts should work / have instructions on how to get it to work on Windows / Linux and Mac OS
- We should not favor Windows centric worlds
- Every sample should be such that user can finish the sample by reading a single web page + code editor. 

# Project Name
(short, 1-3 sentenced, description of the project)
This project allows you to do 
- Create a key vault (As an example)
- 

### Prerequisites

(ideally very short, if any)
- OS
- Software Libraries required (Specific versions if need to be specified)

### Installation
(Explain how to install the pre reqs - this is not mandatory. Use your judgement)
- npm install [package name]
- nuget install
- ...

### Quickstart
(Add steps to get up and running quickly)
1. git clone [repository clone url]
2. cd [respository name]
3. npm start / flask run

### What does this code do?
- In here paste the lines of code that we want users to focus on (As an example below)

This piece of code starts the app and prints a message
```
static void Main(string[] args)
{
    Console.WriteLine("Get Secure with Azure Key Vault!");
}
```
- Next if we need to point the users to different section of code (in a different file) we still have the code copy here and explain what it does
- This section should feel like a story where we explain 
  - What concepts we want users to understand?
  - What sections of code we want users to focus on?
  - As a result Best practices that we want users to follow

## Resources
(Any additional resources that we want users to read)
- Link to Azure Key Vault 
- Link to Azure Key Vault Roadmap
