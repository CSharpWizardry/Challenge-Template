# Challenge-Template
Template to the creation of challenges/Katas.  

The template is built using:
* [Visual Studio 2019](https://visualstudio.microsoft.com/)  
* [Sonar Lint](https://www.sonarlint.org/)
* [xUnit.net](https://xunit.net/)
* [SpecFlow - Business Automated Tests on .NET](https://specflow.org/)

## Template Structure
The Template solution is composed of the following projects:
* __CSharpWizardry.Level.Challenges__: Students will develop their code on this project. Some boilerplate code is provided;
* __CSharpWizardry.Level.Challenges.Tests__: Tests that assert the student provided code against expected results;
* __CSharpWizardry.Level.Challenges.Solutions__: Possible solutions to the code challenges;
* __CSharpWizardry.Level.Challenges.Solution.Tests__: Tests that default solutions against expected results;

## How to add a challenge
1. Create a new _Folder_ on the _Solution.Tests_ to store your challanges;
2. Create a new _Feature file_ and add your code scenarios there.
3. Create a new _Steps file_ to implement tests for your scenarios. It should follow the convention: FeatureFileName(Challenge).Steps.cs
4. Implement your tests on the _Steps file_ and your solution on the _Challenges.Solutions project_. Make sure all the tests pass.
5. Create the tests for the _Challenges.Tests project_.
6. Create a folder on the _Challenges project_ with the same name as the FeatureFile.
7. Create the necessary classes and implementation of boilerplate code on the _Challenges_ project (inside the previous created folder).
8. Try the challenge project by implementing the necessary code, making the tests pass and then removing it (the code).
9. DONE! :)

## Ok but how do a Student execute it all?
Please refer to the [General Information](https://github.com/CSharpWizardry/Challenge-Template/blob/master/GeneralInstructions.md) to learn about how to setup environment, code solutions and execute tests.
