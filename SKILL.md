---
name: "iso-29119-software-testing-standards"
description: "Provides ISO/IEC/IEEE 29119 software testing standards guidance. Invoke when user asks about testing concepts, processes, documentation, techniques, or keyword-driven testing."
---

# ISO/IEC/IEEE 29119: Software Testing Standards

This skill provides comprehensive guidance based on the ISO/IEC/IEEE 29119 series of international software testing standards.

## Standards Overview

The ISO/IEC/IEEE 29119 series consists of five parts:
- **Part 1:2013** - Concepts and definitions
- **Part 2:2013** - Test processes
- **Part 3:2013** - Test documentation
- **Part 4:2015** - Test techniques
- **Part 5:2016** - Keyword-driven testing

---

## Part 1: Concepts and Definitions (ISO/IEC/IEEE 29119-1:2013)

## Software Testing Fundamentals

- **Testing**: Process of executing software to find defects or verify requirements
- **Verification**: Confirmation that specified requirements have been fulfilled
- **Validation**: Confirmation that requirements for a specific intended use have been fulfilled
- **Exhaustive Testing**: Testing all possible inputs and preconditions (usually impossible)
- **Testing as Heuristic**: Using experience-based techniques to optimize testing effort

## Risk-Based Testing

Risk-based testing prioritizes testing based on:
- **Risk**: Combination of probability of occurrence and impact
- **Risk Level**: Determined by likelihood × impact
- **Risk Mitigation**: Testing reduces risk by finding defects before release

## Test Sub-processes

1. **Test Objectives**: What testing aims to achieve
2. **Test Item**: Work product being tested
3. **Quality Characteristics**: Functionality, reliability, usability, efficiency, maintainability, portability
4. **Test Basis**: Basis for test design (requirements, specifications)
5. **Retesting**: Verify defects have been fixed
6. **Regression Testing**: Verify changes haven't caused new defects

## Test Practices

- **Requirements-Based Testing**: Derive tests from requirements
- **Model-Based Testing**: Use models to derive tests
- **Mathematical-Based Testing**: Use mathematical techniques
- **Experience-Based Testing**: Use tester knowledge and intuition
- **Scripted Testing**: Pre-defined test procedures
- **Unscripted Testing**: Exploratory, ad-hoc testing

## Testing in Different Lifecycle Models

### Agile Development
- Testing integrated throughout development
- Continuous testing and feedback
- Test-driven development (TDD)
- Acceptance test-driven development (ATDD)
- Behavior-driven development (BDD)

### Sequential (Waterfall) Development
- Distinct phases: requirements, design, implementation, testing, deployment
- Testing at each phase completion
- Formal entry/exit criteria

### Evolutionary Development
- Iterative and incremental
- Continuous refinement based on feedback
- Prototyping and testing cycles

## Test Automation
- Automate repetitive tests
- Increase test coverage
- Improve regression testing efficiency
- Consider automation costs vs. benefits

## Defect Management
- Document defects systematically
- Track defect lifecycle: New → Assigned → Fixed → Verified → Closed
- Analyze defect patterns for process improvement

## Common Terms Reference

| Term | Definition |
|------|------------|
| Defect | Flaw in software that causes incorrect behavior |
| Bug | Common term for defect |
| Error | Human action that produces incorrect result |
| Fault | Manifestation of an error in software |
| Failure | Deviation of software from expected behavior |
| Test Case | Set of inputs, execution conditions, and expected results |
| Test Suite | Collection of test cases |
| Test Script | Automated test procedure |
| Test Data | Data used during test execution |
| Test Environment | Hardware, software, and network configuration for testing |

---

## Part 2: Test Processes (ISO/IEC/IEEE 29119-2:2013)

## Multi-Layer Test Process Model

The standard defines three layers of test processes:
1. **Organizational Test Process** - Organization-wide testing approach
2. **Test Management Processes** - Project-level test management
3. **Dynamic Test Processes** - Actual testing activities

## Organizational Test Process

### Purpose
- Establish organizational testing policies and strategies
- Define testing standards and guidelines
- Provide training and resources
- Monitor and improve testing effectiveness

### Key Activities
1. Define organizational test policy
2. Develop organizational test strategy
3. Provide test infrastructure and tools
4. Train testing personnel
5. Monitor and measure testing effectiveness

## Test Management Processes

### 1. Test Planning Process

#### Purpose
- Define test objectives, scope, and approach
- Allocate resources and schedule activities
- Identify risks and mitigation strategies

#### Outcomes
- Test Plan document
- Risk register
- Resource allocation
- Schedule

#### Activities and Tasks
1. Analyze test basis (requirements, specifications)
2. Identify test objectives
3. Define test scope
4. Select test approach and techniques
5. Estimate effort and resources
6. Develop schedule
7. Identify and assess risks
8. Document test plan

### 2. Test Monitoring and Control Process

#### Purpose
- Track testing progress against plan
- Identify deviations and issues
- Take corrective actions
- Report status to stakeholders

#### Outcomes
- Test status reports
- Corrective actions
- Updated plans

#### Activities and Tasks
1. Collect test metrics
2. Compare actual vs. planned progress
3. Identify deviations
4. Analyze root causes
5. Implement corrective actions
6. Report status

### 3. Test Completion Process

#### Purpose
- Summarize testing results
- Archive test assets
- Document lessons learned
- Provide test completion report

#### Outcomes
- Test completion report
- Archived test assets
- Lessons learned documentation

#### Activities and Tasks
1. Verify all test activities completed
2. Analyze test results
3. Document findings
4. Archive test artifacts
5. Prepare completion report
6. Conduct lessons learned session

## Dynamic Test Processes

### 1. Test Design and Implementation Process

#### Purpose
- Design test cases and procedures
- Create test data
- Prepare test environment

#### Outcomes
- Test design specifications
- Test cases
- Test procedures
- Test data

#### Activities and Tasks
1. Identify feature sets
2. Derive test conditions
3. Derive test coverage items
4. Derive test cases
5. Assemble test sets
6. Derive test procedures

### 2. Test Environment Set-up and Maintenance Process

#### Purpose
- Prepare and maintain test environment
- Ensure environment availability
- Configure test tools

#### Outcomes
- Configured test environment
- Environment readiness report

#### Activities and Tasks
1. Identify environment requirements
2. Set up hardware and software
3. Configure network and tools
4. Verify environment readiness
5. Maintain environment

### 3. Test Execution Process

#### Purpose
- Execute test cases
- Record results
- Report incidents

#### Outcomes
- Test execution results
- Incident reports
- Test execution log

#### Activities and Tasks
1. Prepare for test execution
2. Execute test cases
3. Record actual results
4. Compare with expected results
5. Report incidents
6. Log execution events

### 4. Test Incident Reporting Process

#### Purpose
- Document and track incidents
- Communicate issues to stakeholders
- Track resolution

#### Outcomes
- Incident reports
- Incident tracking records

#### Activities and Tasks
1. Identify and document incidents
2. Classify and prioritize incidents
3. Assign incidents for resolution
4. Track incident status
5. Verify resolution

## Process Alignment

This standard aligns with:
- **ISO/IEC 12207:2008** - Software life cycle processes
- **ISO/IEC 15288:2008** - System life cycle processes
- **ISO/IEC 17025:2005** - Testing and calibration laboratories
- **ISO/IEC 25051:2006** - Software product quality requirements

## Test Plan Template Structure

Based on the standard, a test plan should include:
1. Introduction
2. Context of the testing
3. Testing communication
4. Risk register
5. Test strategy
6. Testing activities and estimates
7. Staffing
8. Schedule

---

## Part 3: Test Documentation (ISO/IEC/IEEE 29119-3:2013)

## Documentation Categories

The standard defines documentation at three levels:
1. **Organizational Test Process Documentation** - Organization-wide
2. **Test Management Processes Documentation** - Project management
3. **Dynamic Test Processes Documentation** - Test execution

## Organizational Test Process Documentation

### 1. Test Policy

#### Purpose
- Define organization's testing philosophy and approach
- Establish testing standards and requirements
- Set expectations for testing activities

#### Content Structure
1. **Document Specific Information**
   - Document ID, version, date
   - Author, approver
   - Distribution list

2. **Introduction**
   - Purpose and scope
   - References to related documents
   - Definitions and abbreviations

3. **Test Policy Statements**
   - Testing objectives
   - Testing principles
   - Testing standards
   - Testing independence
   - Test completion criteria

### 2. Organizational Test Strategy

#### Purpose
- Define organization-wide testing approach
- Establish reusable test practices
- Guide project-level test planning

#### Content Structure
1. **Document Specific Information**
2. **Introduction**
3. **Project-wide Organizational Test Strategy Statements**
   - Test levels (unit, integration, system, acceptance)
   - Test types (functional, non-functional)
   - Test techniques to be used
   - Test environment requirements
   - Test automation approach

4. **Test Sub-process-specific Organizational Test Strategy Statements**
   - For each test level/type
   - Entry and exit criteria
   - Required documentation

## Test Management Processes Documentation

### 1. Test Plan

#### Purpose
- Document project-specific test approach
- Define test objectives, scope, and schedule
- Allocate resources and identify risks

#### Content Structure
1. **Document Specific Information**
   - Project name, test item
   - Version, date, author
   - Approval history

2. **Introduction**
   - Purpose and scope
   - References
   - Definitions

3. **Context of the Testing**
   - Test items
   - Features to be tested
   - Features not to be tested
   - Test items relationship

4. **Testing Communication**
   - Stakeholder identification
   - Communication channels
   - Reporting frequency

5. **Risk Register**
   - Identified risks
   - Risk analysis
   - Mitigation strategies

6. **Test Strategy**
   - Test levels
   - Test types
   - Test techniques
   - Test environment
   - Entry/exit criteria

7. **Testing Activities and Estimates**
   - Test activities
   - Effort estimates
   - Dependencies

8. **Staffing**
   - Roles and responsibilities
   - Required skills
   - Training needs

9. **Schedule**
   - Key milestones
   - Test phases
   - Resource allocation

### 2. Test Status Report

#### Purpose
- Report current test status to stakeholders
- Highlight progress and issues
- Support decision making

#### Content Structure
1. **Document Specific Information**
2. **Introduction**
3. **Test Status**
   - Period covered
   - Test activities completed
   - Test results summary
   - Incidents and defects
   - Risks and issues
   - Deviations from plan

### 3. Test Completion Report

#### Purpose
- Summarize test results and findings
- Document test activities performed
- Provide recommendations

#### Content Structure
1. **Document Specific Information**
2. **Introduction**
3. **Testing Performed**
   - Test activities completed
   - Test items tested
   - Test environment used

4. **Test Results Summary**
   - Tests executed vs. planned
   - Pass/fail statistics
   - Defects found and fixed
   - Outstanding issues

5. **Evaluation**
   - Quality assessment
   - Risk assessment
   - Recommendations

## Dynamic Test Processes Documentation

### 1. Test Design Specification

#### Purpose
- Document test conditions and coverage items
- Basis for test case derivation

#### Content Structure
1. **Document Specific Information**
2. **Introduction**
3. **Feature Sets**
4. **Test Conditions**

### 2. Test Case Specification

#### Purpose
- Define individual test cases
- Specify inputs, expected results, and conditions

#### Content Structure
1. **Document Specific Information**
2. **Introduction**
3. **Test Coverage Items**
4. **Test Cases**
   - Test case ID
   - Test objective
   - Preconditions
   - Test steps
   - Expected results
   - Actual results (to be filled)
   - Status (to be filled)

### 3. Test Procedure Specification

#### Purpose
- Define ordered sequence of test cases
- Specify execution instructions

#### Content Structure
1. **Document Specific Information**
2. **Introduction**
3. **Test Sets**
4. **Test Procedures**
   - Procedure ID
   - Objective
   - Test cases included
   - Execution order
   - Special instructions

### 4. Test Data Requirements

#### Purpose
- Specify data needed for testing
- Ensure data availability

#### Content Structure
1. **Document Specific Information**
2. **Introduction**
3. **Detailed Test Data Requirements**
   - Data elements
   - Data sources
   - Data constraints
   - Data privacy requirements

### 5. Test Environment Requirements

#### Purpose
- Specify environment needs for testing
- Ensure environment readiness

#### Content Structure
1. **Document Specific Information**
2. **Introduction**
3. **Detailed Test Environment Requirements**
   - Hardware requirements
   - Software requirements
   - Network requirements
   - Tools requirements

### 6. Test Data Readiness Report

#### Purpose
- Report status of test data preparation
- Identify data issues

#### Content Structure
1. **Document Specific Information**
2. **Introduction**
3. **Test Data Status**
   - Data preparation progress
   - Data quality issues
   - Outstanding data needs

### 7. Test Environment Readiness Report

#### Purpose
- Report status of test environment preparation
- Identify environment issues

#### Content Structure
1. **Document Specific Information**
2. **Introduction**
3. **Test Environment Readiness**
   - Environment setup status
   - Configuration issues
   - Availability schedule

### 8. Actual Results

#### Purpose
- Record actual test execution results
- Compare with expected results

### 9. Test Result

#### Purpose
- Document outcome of test execution
- Record pass/fail status

### 10. Test Execution Log

#### Purpose
- Log test execution events
- Provide audit trail

#### Content Structure
1. **Document Specific Information**
2. **Introduction**
3. **Events**
   - Timestamp
   - Event description
   - Actor
   - Outcome

### 11. Incident Report

#### Purpose
- Document test incidents
- Track incident resolution

#### Content Structure
1. **Document Specific Information**
2. **Introduction**
3. **Incident Details**
   - Incident ID
   - Related test case
   - Incident description
   - Severity
   - Priority
   - Steps to reproduce
   - Expected behavior
   - Actual behavior
   - Environment details
   - Attachments
   - Resolution status

---

## Part 4: Test Techniques (ISO/IEC/IEEE 29119-4:2015)

## Test Design Techniques Overview

The standard categorizes test design techniques into three groups:
1. **Specification-Based Techniques** (Black-box)
2. **Structure-Based Techniques** (White-box)
3. **Experience-Based Techniques**

## Specification-Based Test Design Techniques

### 1. Equivalence Partitioning

#### Purpose
- Reduce test cases by dividing input data into partitions
- Assume all values in a partition behave similarly

#### Process
1. Identify input conditions
2. Divide each input into valid and invalid partitions
3. Select one representative value from each partition
4. Design test cases to cover each partition

#### Example
For age input (valid range 18-65):
- Invalid: < 18
- Valid: 18-65
- Invalid: > 65

Test values: 10, 30, 70

### 2. Boundary Value Analysis

#### Purpose
- Test at boundaries of equivalence partitions
- Defects often occur at boundaries

#### Process
1. Identify boundaries from equivalence partitions
2. Select values at, just below, and just above boundaries
3. Design test cases for boundary values

#### Example
For age input (valid range 18-65):
- Lower boundary: 17, 18, 19
- Upper boundary: 64, 65, 66

### 3. Combinatorial Test Design

#### Purpose
- Systematically test combinations of inputs
- Reduce combinations while maintaining coverage

#### Types
- **Pairwise Testing**: Test all pairs of input values
- **t-way Testing**: Test all t-way combinations
- **Orthogonal Arrays**: Use mathematical arrays for coverage
- **All Combinations**: Test every possible combination

#### Process
1. Identify input parameters and their values
2. Select combination strategy
3. Generate combination set
4. Create test cases from combinations

### 4. Decision Table Testing

#### Purpose
- Test complex business rules and conditions
- Ensure all condition combinations are tested

#### Process
1. Identify conditions (inputs)
2. Identify actions (outputs)
3. Create table with all condition combinations
4. Determine actions for each combination
5. Create test cases for each column

#### Example
| Conditions | Rule 1 | Rule 2 | Rule 3 | Rule 4 |
|------------|--------|--------|--------|--------|
| Age >= 18 | Y | Y | N | N |
| Has License | Y | N | Y | N |
| **Actions** | | | | |
| Allow Drive | X | | | |
| Deny | | X | X | X |

### 5. Cause-Effect Graphing

#### Purpose
- Analyze relationships between causes and effects
- Derive test cases from cause-effect relationships

#### Process
1. Identify causes (inputs) and effects (outputs)
2. Draw cause-effect graph showing relationships
3. Convert to decision table
4. Derive test cases

### 6. State Transition Testing

#### Purpose
- Test systems with distinct states and transitions
- Verify valid and invalid state transitions

#### Process
1. Identify states
2. Identify events that cause transitions
3. Draw state transition diagram
4. Create test cases to cover transitions

#### Example
States: Idle, Processing, Complete, Error
Transitions:
- Idle → Processing (on Start)
- Processing → Complete (on Success)
- Processing → Error (on Failure)
- Error → Idle (on Reset)

### 7. Scenario Testing

#### Purpose
- Test end-to-end user scenarios
- Validate complete workflows

#### Process
1. Identify user roles and goals
2. Define main success scenario
3. Identify alternative flows
4. Identify exception flows
5. Create test cases for each scenario

### 8. Random Testing

#### Purpose
- Generate test cases randomly
- Find unexpected defects

#### Process
1. Define input domain
2. Generate random inputs
3. Execute and evaluate
4. Analyze results

## Structure-Based Test Design Techniques

### 1. Statement Testing

#### Purpose
- Execute every statement in code
- Basic level of code coverage

#### Coverage Metric
- Statement Coverage = (Statements executed / Total statements) × 100%

#### Process
1. Identify all statements
2. Design test cases to execute each
3. Measure coverage

### 2. Branch Testing

#### Purpose
- Execute every branch (decision outcome)
- More thorough than statement testing

#### Coverage Metric
- Branch Coverage = (Branches executed / Total branches) × 100%

#### Process
1. Identify all decision points
2. Design test cases for True/False outcomes
3. Measure coverage

### 3. Decision Testing

#### Purpose
- Test all possible outcomes of decisions
- Each decision has True/False outcome

#### Coverage Metric
- Decision Coverage = (Decisions evaluated / Total decisions) × 100%

### 4. Branch Condition Testing

#### Purpose
- Test each condition in a decision
- More granular than decision testing

#### Process
1. Identify conditions within decisions
2. Test each condition for True/False
3. Measure condition coverage

### 5. Branch Condition Combination Testing

#### Purpose
- Test all combinations of conditions within decisions
- Most thorough decision-based testing

#### Coverage Metric
- Condition Combination Coverage = (Combinations tested / Total combinations) × 100%

### 6. Modified Condition/Decision Coverage (MC/DC)

#### Purpose
- Each condition independently affects decision outcome
- Required for safety-critical systems (e.g., aviation)

#### Process
1. For each condition, find test pairs where:
   - Only that condition changes
   - Decision outcome changes
2. Verify independence

### 7. Data Flow Testing

#### Purpose
- Test paths of data definitions and uses
- Find data flow anomalies

#### Types
- **All-DU-Paths**: All definition-use paths
- **All-Uses**: All uses of definitions
- **All-Definitions**: All definitions

#### Process
1. Identify variable definitions
2. Identify variable uses
3. Trace definition-use paths
4. Design test cases to cover paths

## Experience-Based Test Design Techniques

### 1. Error Guessing

#### Purpose
- Use experience to anticipate defects
- Supplement systematic techniques

#### Process
1. Review historical defect data
2. Identify common error patterns
3. Create test cases for likely errors
4. Focus on high-risk areas

#### Common Error Patterns
- Division by zero
- Null/empty inputs
- Boundary violations
- Off-by-one errors
- Data type mismatches
- Concurrency issues

### 2. Exploratory Testing

#### Purpose
- Simultaneously learn, design, and test
- Find defects missed by scripted testing

#### Process
1. Define test charter (mission)
2. Time-box testing session
3. Design and execute tests simultaneously
4. Document findings
5. Debrief and plan next session

### 3. Checklist-Based Testing

#### Purpose
- Use predefined checklists
- Ensure consistent coverage

#### Process
1. Create/maintain checklist
2. Execute tests following checklist
3. Update checklist based on findings

## Test Coverage Measurement

### Specification-Based Coverage
- Equivalence Partition Coverage
- Boundary Value Coverage
- Decision Table Coverage
- State Transition Coverage

### Structure-Based Coverage
- Statement Coverage
- Branch Coverage
- Decision Coverage
- Condition Coverage
- MC/DC Coverage
- Data Flow Coverage

### Experience-Based Coverage
- Error Guessing Coverage (qualitative)

## Technique Selection Guide

| Scenario | Recommended Techniques |
|----------|----------------------|
| Requirements-based | Equivalence Partitioning, Boundary Value, Decision Table |
| Complex business rules | Decision Table, Cause-Effect Graphing |
| State-based systems | State Transition Testing |
| User workflows | Scenario Testing |
| Code coverage goals | Statement, Branch, MC/DC |
| Safety-critical | MC/DC, All Combinations |
| Quick testing | Error Guessing, Exploratory |
| API testing | Equivalence Partitioning, Boundary Value, Pairwise |

---

## Part 5: Keyword-Driven Testing (ISO/IEC/IEEE 29119-5:2016)

## Keyword-Driven Testing Overview

### What is Keyword-Driven Testing?
- Test automation approach using keywords (actions) to define tests
- Separates test logic from test implementation
- Enables non-technical users to create automated tests
- Promotes reusability and maintainability

### Benefits
- **For Test Automation**: Reusable keywords, easier maintenance, reduced duplication
- **For Manual Testing**: Clear test steps, consistent execution, training aid
- **For Organizations**: Knowledge capture, cross-team collaboration, ROI improvement

## Layers in Keyword-Driven Testing

### 1. Domain Layer
- High-level keywords representing business actions
- Business-focused, technology-independent
- Example: `Login`, `Create Order`, `Verify Balance`

### 2. Test Interface Layer
- Mid-level keywords for test actions
- Maps domain keywords to implementation
- Example: `Enter Text`, `Click Button`, `Verify Text`

### 3. Implementation Layer
- Low-level keywords for technical actions
- Interacts with application under test
- Example: `Send Keys`, `Click Element`, `Get Text`

## Types of Keywords

### 1. Simple Keywords
- Single action or verification
- Cannot be decomposed further
- Example: `Click`, `Verify`, `Enter`

### 2. Composite Keywords
- Combine multiple simple keywords
- Represent higher-level actions
- Example: `Login` = `Enter Username` + `Enter Password` + `Click Login Button`

### 3. Navigation/Interaction Keywords (Input)
- Perform actions on application
- Navigate, input data, trigger events
- Example: `Click`, `Enter`, `Select`, `Navigate`

### 4. Verification Keywords (Output)
- Verify expected results
- Check application state
- Example: `Verify Text`, `Verify Element Present`, `Verify Value`

## Keywords and Data

### Data-Driven Testing
- Separate test data from test logic
- Same keyword sequence with different data
- Enables data-driven execution

### Data Sources
- Spreadsheets (Excel, CSV)
- Databases
- XML/JSON files
- Test management tools

## Application of Keyword-Driven Testing

### Identifying Keywords
1. Analyze application under test
2. Identify common actions and verifications
3. Define keyword hierarchy (domain → interface → implementation)
4. Document keyword specifications

### Composing Test Cases
1. Select domain keywords for test scenario
2. Add necessary data parameters
3. Sequence keywords logically
4. Include verification points

### Modularity and Refactoring
- Break complex tests into reusable keywords
- Maintain keyword library
- Update keywords when application changes
- Version control keyword definitions

### Integration with Test Design Process

#### TD1: Identify Feature Sets
- Group related functionality
- Define feature scope for keywords

#### TD2: Derive Test Conditions
- Identify what to test
- Define preconditions and postconditions

#### TD3: Derive Test Coverage Items
- Determine coverage requirements
- Map to keyword verifications

#### TD4: Derive Test Cases
- Create keyword sequences
- Add data parameters

#### TD5: Assemble Test Sets
- Group related test cases
- Define execution order

#### TD6: Derive Test Procedures
- Document execution steps
- Include setup and teardown

## Keyword-Driven Testing Frameworks

### Framework Components

#### 1. Keyword-Driven Editor
- Create and edit keyword sequences
- Visual test design interface
- Syntax highlighting and validation

#### 2. Decomposer
- Parse keyword sequences
- Map keywords to implementations
- Handle parameter substitution

#### 3. Data Sequencer
- Manage test data
- Iterate through data sets
- Handle data variations

#### 4. Manual Test Assistant
- Guide manual testers through keyword steps
- Display instructions and expected results
- Capture manual test results

#### 5. Tool Bridge
- Connect to external tools
- Integrate with test management
- Support multiple automation tools

#### 6. Test Execution Environment
- Runtime for keyword execution
- Handle test execution flow
- Manage test state

#### 7. Execution Engine
- Execute keyword actions
- Interact with application
- Report execution results

#### 8. Keyword Library
- Repository of available keywords
- Keyword documentation
- Version control

#### 9. Data Storage
- Store test data
- Manage data sets
- Handle data access

#### 10. Script Repository
- Store keyword sequences
- Version control
- Reuse and share tests

### Framework Attributes

#### Basic Attributes
- General framework information
- Supported keyword types
- Data format support

#### Advanced Attributes
- Parallel execution support
- Distributed testing
- Reporting capabilities
- Integration APIs

## Data Interchange

### Standard Formats
- XML for keyword definitions
- CSV/Excel for test data
- JSON for configuration

### Interoperability
- Export/import keyword sequences
- Share between frameworks
- Version control integration

## Roles and Tasks

### Domain Expert
- Define domain keywords
- Specify business actions
- Validate keyword coverage

### Test Designer
- Compose test cases using keywords
- Define test data
- Design test scenarios

### Test Automation Expert
- Implement keyword libraries
- Maintain framework
- Optimize performance

## Getting Started with Keyword-Driven Testing

### Step 1: Assess Readiness
- Evaluate current test automation maturity
- Identify suitable pilot project
- Define success criteria

### Step 2: Design Keyword Architecture
- Define keyword layers
- Establish naming conventions
- Design keyword hierarchy

### Step 3: Build Initial Keywords
- Start with high-frequency actions
- Implement core verifications
- Test keyword implementations

### Step 4: Create Test Cases
- Convert existing manual tests
- Create new keyword-based tests
- Validate test execution

### Step 5: Expand and Optimize
- Add more keywords
- Refactor and optimize
- Train team members

## Example: Basic Keywords for GUI Testing

### Navigation Keywords
```
Navigate to <url>
Click <element>
Double Click <element>
Right Click <element>
Drag <source> to <target>
Scroll <direction> <amount>
```

### Input Keywords
```
Enter <text> in <field>
Select <value> from <dropdown>
Check <checkbox>
Select <radio button>
Upload <file> to <field>
```

### Verification Keywords
```
Verify Text <expected> in <element>
Verify Element <element> is <visible|hidden>
Verify Value <expected> in <field>
Verify Page Title is <expected>
Verify URL contains <text>
```

### Wait Keywords
```
Wait for <element> to be <visible>
Wait <seconds> seconds
Wait for <text> to appear
Wait for page to load
```

## Example: Domain-Level Keywords

### Login Keywords
```
Login with credentials <username> <password>
Logout
Verify login successful
Verify login failed with message <expected>
```

### Shopping Cart Keywords
```
Add <product> to cart
Remove <product> from cart
Update quantity of <product> to <quantity>
Verify cart total is <amount>
Proceed to checkout
```

### Order Keywords
```
Create order with items <items>
Verify order confirmation number
Cancel order <order number>
Verify order status is <status>
```

## Best Practices

1. **Keep keywords simple and focused**
2. **Use consistent naming conventions**
3. **Document all keywords thoroughly**
4. **Version control keyword definitions**
5. **Review and refactor regularly**
6. **Involve domain experts in keyword design**
7. **Measure ROI and effectiveness**

---

## Usage Guidelines

When applying this skill:
1. Identify the testing concept, process, documentation, or technique being discussed
2. Provide definitions and explanations based on the standard
3. Give practical examples where applicable
4. Reference related concepts for comprehensive understanding
5. Adapt to project context as needed (tailored conformance supported)
