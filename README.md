# BDD Example with SpecFlowCalculator
Behavior-Driven Development (BDD) is similar to Test-Driven Development (TDD) in that you don't start from your code (your implementation), you instead start from an external point which is trying to "test" or "drive" the implementation.  In TDD it's your Unit Tests where you define what the Unit should be doing, and in BDD it is the Acceptance Criteria, Feature, or the Scenario - those different meanings.  The advantage of BDD is that anyone can write the Specification of a test in BDD and simnilarly anyone can read & understand it, e.g. Business Analysts (BA) and Product Owners (PO).  Ideally even, those Business people write the Spec, then Developers just write the mapping (code) behind the Spec.  Fundamentally it's the idea that the behavior of The System matches the code and implementation of The System that was defined and agreed-upon before any code-changes even occur - a nice marriage between TDD and Acceptance-Test-Driven Development (ATDD).  From a Domain-Driven Development (DDD) it is diving more into the Domain itself unlike TDD whose focus is on the Unit.  Basically, they're complementary concepts and practices, so they can even be used together well.  In BDD we have a "feature," or feature of your system, and those features satisfied based on Scenarios and you can think of Scenarios as Acceptance Criteria.  They're very similar to using the Given, When, Then approach, making it Human-Readable, in plain English feature or "test," and we drive our Feature with the Test.  

# Instructions for setting up the Code
1. In Visual Studio, create a Class Library project. 
Add these NuGet Packages:
1. SpecFlow
2. Fluent Assertions
3. Microsoft.Net.Test.Sdk

# Instructions following Class Library Project creation
1. Create the Features, Hooks, and a Steps folders, and create a LoggedInDiscount.feature file in the Features folder.  Visual Studio 2022 should automatically detect it as a Specflow file for defining the LoggedInDiscount feature. 
2. 