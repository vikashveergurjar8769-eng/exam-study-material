# 📖 SOFTWARE ENGINEERING + SDLC (System Development Life Cycle)
## Complete Deep Study Material

---

## 🎯 Topic Overview

**Importance in Exam:** ⭐⭐⭐⭐⭐ (HIGHEST PRIORITY)
- **Expected Questions:** 15-20
- **Question Types:** MCQ, Short Answer, Scenario-based
- **Weightage:** 40% of Software Engineering portion

---

## 📚 TABLE OF CONTENTS

1. [Introduction to SDLC](#introduction)
2. [SDLC Models](#models)
3. [SDLC Phases](#phases)
4. [Types of Maintenance](#maintenance)
5. [Software Testing](#testing)
6. [Important Concepts](#concepts)
7. [Exam Questions Bank](#questions)

---

## <a name="introduction"></a>
## 1️⃣ INTRODUCTION TO SDLC

### **What is SDLC?**
SDLC (System Development Life Cycle) is a **structured process** that defines the steps involved in designing, developing, testing, and deploying software.

### **Key Objectives:**
- ✅ Provide a framework for software development
- ✅ Ensure quality of software
- ✅ Reduce costs and time
- ✅ Improve reliability and maintainability
- ✅ Provide systematic approach

### **SDLC Characteristics:**
| Characteristic | Description |
|---|---|
| **Systematic** | Follows planned steps |
| **Structured** | Clear phases and activities |
| **Documented** | All phases have deliverables |
| **Controlled** | Quality checks at each phase |
| **Measurable** | Progress can be tracked |

---

## <a name="models"></a>
## 2️⃣ SDLC MODELS

### **A. WATERFALL MODEL** 🌊

**Definition:** Sequential model where each phase must be completed before next phase begins.

**Flow:**
```
Requirements → Design → Implementation → Testing → Deployment → Maintenance
```

**Characteristics:**
- ✅ Linear and sequential
- ✅ Each phase has specific deliverables
- ✅ High documentation
- ✅ Changes are expensive
- ✅ Easy to manage

**Phases:**
1. **Requirements** - Gather what system should do
2. **Design** - How to build the system
3. **Implementation** - Actual coding
4. **Testing** - Find and fix bugs
5. **Deployment** - Release to production
6. **Maintenance** - Support and updates

**Advantages:**
- ✅ Simple and easy to understand
- ✅ Works well for small projects
- ✅ Clear documentation
- ✅ Easy to estimate time and cost
- ✅ Good for hardware integration

**Disadvantages:**
- ❌ Not flexible for changes
- ❌ Late testing (bugs found late)
- ❌ Not suitable for complex projects
- ❌ Working software comes late
- ❌ Risk of project failure if requirements wrong

**Best For:**
- Projects with **well-defined, stable requirements**
- **No expected changes**
- Regulatory/compliance projects
- Hardware-software integration

---

### **B. AGILE MODEL** 🚀

**Definition:** Iterative model focusing on flexibility, customer feedback, and rapid development.

**Flow:**
```
Planning → Design → Development → Testing → Review → Repeat
(Sprint cycle: 1-4 weeks)
```

**Characteristics:**
- ✅ Iterative and incremental
- ✅ Flexible and adaptive
- ✅ Customer involvement throughout
- ✅ Regular feedback
- ✅ Minimal documentation
- ✅ Continuous delivery

**Sprint Cycle:**
1. **Sprint Planning** (2-4 weeks)
2. **Daily Standups** (15 mins daily)
3. **Development & Testing**
4. **Sprint Review** (Demo to client)
5. **Sprint Retrospective** (Improve process)

**Advantages:**
- ✅ Highly flexible for changes
- ✅ Early and continuous feedback
- ✅ Working software frequently
- ✅ Risk identified early
- ✅ Good team collaboration
- ✅ Quick to market

**Disadvantages:**
- ❌ Less documentation
- ❌ Requires experienced team
- ❌ Hard to predict final cost
- ❌ Difficult for large teams
- ❌ Requires constant client involvement

**Best For:**
- Projects with **changing requirements**
- **Dynamic environments**
- Innovation-focused projects
- Web/Mobile applications
- Startups

**Agile Frameworks:**
- **Scrum** - Most popular (sprints, roles, ceremonies)
- **Kanban** - Continuous flow model
- **XP (Extreme Programming)** - Technical practices
- **Lean** - Eliminate waste

---

### **C. RAD MODEL (Rapid Application Development)** ⚡

**Definition:** Speed-focused model using visual tools and prototyping for quick development.

**Flow:**
```
Requirements → Design with prototyping → Development → Testing → Deployment
(Time-boxed: 60-90 days)
```

**Characteristics:**
- ✅ Time-boxed iterations
- ✅ Visual development tools
- ✅ Frequent prototyping
- ✅ Quick iterations
- ✅ User involvement
- ✅ Focus on speed

**Phases:**
1. **Business Modeling** - Understand business
2. **Data Modeling** - Design data structures
3. **Process Modeling** - Define processes
4. **Application Generation** - Visual tools, code generation
5. **Testing & Turnover** - Quick testing, deploy

**Advantages:**
- ✅ Very fast development
- ✅ Early working prototype
- ✅ User sees progress early
- ✅ Reduces development time
- ✅ Flexibility within time-box

**Disadvantages:**
- ❌ Requires experienced developers
- ❌ Expensive tools needed
- ❌ Not for long-term projects
- ❌ Scalability issues
- ❌ Integration challenges

**Best For:**
- **Quick time-to-market projects**
- Projects with **known requirements** but need speed
- **Business applications**
- **GUI-intensive applications**

---

### **D. SPIRAL MODEL** 🌀

**Definition:** Combines iterative and waterfall approaches with risk assessment at each cycle.

**Flow:**
```
Planning → Risk Analysis → Engineering → Evaluation → Repeat (Spiral)
```

**Characteristics:**
- ✅ Risk-driven approach
- ✅ Multiple iterations
- ✅ Combines waterfall + iterative
- ✅ Risk assessment at each cycle
- ✅ High documentation
- ✅ Expensive

**Spiral Quadrants:**
1. **Objective Setting** - Define goals, requirements
2. **Risk Analysis** - Identify and analyze risks
3. **Engineering** - Build and test
4. **Evaluation** - Review and plan next cycle

**Advantages:**
- ✅ Excellent risk management
- ✅ Early risk identification
- ✅ Flexible for changes
- ✅ Good for complex projects
- ✅ Multiple reviews

**Disadvantages:**
- ❌ Very expensive
- ❌ Complex to implement
- ❌ Requires risk expertise
- ❌ Long development time
- ❌ Difficult to manage

**Best For:**
- **Large, complex projects**
- **High-risk projects**
- **Mission-critical systems**
- **When cost is not primary concern**
- **Long-term projects**

---

### **E. PROTOTYPING MODEL** 🎨

**Definition:** Build a working prototype first to understand requirements better.

**Flow:**
```
Requirements → Build Prototype → User Feedback → Refine → Final Development → Testing → Deployment
```

**Characteristics:**
- ✅ Build prototype early
- ✅ User feedback driven
- ✅ Quick feedback cycle
- ✅ Reduces misunderstandings
- ✅ Evolutionary approach

**Advantages:**
- ✅ Clarifies unclear requirements
- ✅ Early user feedback
- ✅ Reduces development risk
- ✅ Identifies issues early
- ✅ Better user understanding

**Disadvantages:**
- ❌ May lead to poorly designed system
- ❌ Users may expect final product early
- ❌ Extra costs
- ❌ May not follow best practices
- ❌ Prototype may be abandoned

**Best For:**
- **Unclear or evolving requirements**
- **User interface heavy projects**
- **When requirements not well-defined**

---

### **F. V-MODEL (Verification & Validation)** ✅

**Definition:** Extension of Waterfall with testing at each phase.

**Flow:**
```
Requirements ↔ Acceptance Testing
    ↓           ↑
Design ↔ System Testing
    ↓           ↑
Implementation ↔ Integration Testing
    ↓           ↑
Unit Testing ↔ Unit Testing
```

**Characteristics:**
- ✅ Each phase has corresponding test phase
- ✅ Early testing
- ✅ Quality assurance throughout
- ✅ Clear documentation

**Advantages:**
- ✅ Defects caught early
- ✅ High quality
- ✅ Easy to track progress
- ✅ Good documentation

**Disadvantages:**
- ❌ Not flexible
- ❌ High cost
- ❌ Late product delivery

---

## <a name="phases"></a>
## 3️⃣ SDLC PHASES & DELIVERABLES

### **Phase 1: PLANNING** 📋

**Objectives:**
- Define project scope
- Estimate resources
- Calculate costs
- Assess feasibility
- Plan timeline

**Activities:**
- Project scope definition
- Resource allocation
- Risk assessment
- Budget planning
- Schedule creation

**Deliverables:**
- ✅ Project Plan
- ✅ Resource Plan
- ✅ Cost Estimation Report
- ✅ Feasibility Study Report
- ✅ Timeline/Gantt Chart
- ✅ Risk Assessment Report

**Tools Used:**
- MS Project
- JIRA
- Resource management tools

---

### **Phase 2: REQUIREMENTS ANALYSIS** 📝

**Objectives:**
- Understand what system should do
- Document all requirements
- Clarify user needs
- Get stakeholder approval

**Activities:**
- Requirement gathering
- Stakeholder interviews
- Requirement documentation
- Requirement analysis
- Approval process

**Deliverables:**
- ✅ **SRS (Software Requirements Specification)** - MOST IMPORTANT
- ✅ Use Cases
- ✅ Data Flow Diagrams (DFD)
- ✅ Requirements Traceability Matrix (RTM)
- ✅ Data Dictionary

**DFD Example:**
```
User → [Validate Input] → Database → [Process] → Output
```

**SRS Content:**
- Functional requirements
- Non-functional requirements
- System requirements
- Constraints
- Assumptions

---

### **Phase 3: DESIGN** 🎨

**Objectives:**
- Design system architecture
- Plan database structure
- Design user interface
- Plan implementation approach

**Activities:**
- System architecture design
- Database design
- UI/UX design
- API design
- Technology selection

**Deliverables:**
- ✅ System Architecture Document
- ✅ Database Schema/ER Diagram
- ✅ UI Mockups/Wireframes
- ✅ Design Document (HLD - High Level Design)
- ✅ Design Document (LLD - Low Level Design)
- ✅ API Specifications

**Design Levels:**
1. **HLD (High-Level Design)** - System overview, modules
2. **LLD (Low-Level Design)** - Detailed module design

---

### **Phase 4: IMPLEMENTATION (DEVELOPMENT)** 💻

**Objectives:**
- Write actual code
- Build system components
- Follow coding standards
- Create documentation

**Activities:**
- Code development
- Code review
- Version control
- Unit testing (basic)
- Documentation

**Deliverables:**
- ✅ Source Code
- ✅ Code Documentation
- ✅ Build/Compiled Software
- ✅ Code Comments
- ✅ Technical Documentation

**Best Practices:**
- Follow coding standards
- Use version control (Git)
- Peer code review
- Document code properly

---

### **Phase 5: TESTING** 🧪

**Objectives:**
- Find and fix bugs
- Ensure quality
- Validate requirements
- Ensure performance

**Activities:**
- Test planning
- Test case creation
- Test execution
- Bug reporting
- Bug fixing
- Regression testing

**Deliverables:**
- ✅ Test Plan
- ✅ Test Cases
- ✅ Test Summary Report
- ✅ Bug Reports
- ✅ Test Coverage Report

**Testing Types:**

| Type | Focus | Level | Who |
|------|-------|-------|-----|
| **Unit Testing** | Individual functions | Component | Developers |
| **Integration Testing** | Module interactions | Module | QA |
| **System Testing** | Complete system | System | QA |
| **UAT/Acceptance** | User requirements | User | End Users |
| **Performance** | Speed, load | System | QA |
| **Security** | Vulnerabilities | System | Security Team |

**Testing Pyramid:**
```
        △ UAT (10%)
       △ △ System Testing (20%)
      △ △ △ Integration (30%)
     △ △ △ △ Unit (40%)
```

---

### **Phase 6: DEPLOYMENT** 🚀

**Objectives:**
- Release to production
- Install on user systems
- Train users
- Go-live support

**Activities:**
- Deployment planning
- Production setup
- Data migration
- User training
- Go-live
- Support

**Deliverables:**
- ✅ Deployment Plan
- ✅ Release Notes
- ✅ User Training Materials
- ✅ Installation Guide
- ✅ System Administration Guide
- ✅ Support Documentation

**Deployment Strategies:**
- **Big Bang** - All at once (risky)
- **Phased** - Gradual rollout (safe)
- **Parallel** - Old and new systems together (expensive)
- **Pilot** - Test with small group first (safe)

---

### **Phase 7: MAINTENANCE** 🔧

**Objectives:**
- Support users
- Fix issues
- Improve system
- Handle changes

**Activities:**
- User support
- Bug fixes
- Performance optimization
- Feature enhancements
- System updates

**Deliverables:**
- ✅ Support documentation
- ✅ Maintenance logs
- ✅ Patches and updates
- ✅ Change documentation

---

## <a name="maintenance"></a>
## 4️⃣ TYPES OF MAINTENANCE

### **A. CORRECTIVE MAINTENANCE** 🐛

**Definition:** Fix bugs and errors found in production system.

**Focus:** Problems that exist in current system

**Examples:**
- System crashes → Fix cause of crash
- Security vulnerabilities → Patch security hole
- Data corruption → Fix data corruption
- Logic errors → Correct wrong calculations

**Characteristics:**
- ✅ Fix existing bugs
- ✅ Emergency fixes sometimes
- ✅ Reactive (response to issues)
- ✅ Unplanned
- ✅ Usually high priority

**Cost:** Low to Medium
**Timeline:** Immediate to Short-term

---

### **B. ADAPTIVE MAINTENANCE** 🔄

**Definition:** Modify system to adapt to new environment changes.

**Focus:** Environmental changes (not system changes)

**Examples:**
- New Operating System released → Adapt software
- New database version → Update compatibility
- Regulatory requirement change → Adapt system
- Hardware upgrade → Optimize for new hardware
- Platform migration → Port to new platform

**Characteristics:**
- ✅ Adapt to environment
- ✅ No new features
- ✅ Planned
- ✅ System logic unchanged
- ✅ Compliance-driven

**Cost:** Medium
**Timeline:** Short to Medium-term

---

### **C. PERFECTIVE MAINTENANCE** ✨

**Definition:** Improve system performance, appearance, or add new features.

**Focus:** Enhancements and improvements

**Examples:**
- Add new features (user request) → User wants new functionality
- Improve UI design → Better user experience
- Optimize code performance → Faster execution
- Improve documentation → Better maintainability
- Refactor code → Better code quality

**Characteristics:**
- ✅ User-driven improvements
- ✅ Add value to system
- ✅ Planned
- ✅ May add new features
- ✅ Quality improvement

**Cost:** Medium to High
**Timeline:** Medium-term

---

### **D. PREVENTIVE MAINTENANCE** 🛡️

**Definition:** Improve system to prevent future problems.

**Focus:** Preventing issues before they occur

**Examples:**
- Code refactoring → Prevent future bugs
- Documentation updates → Prevent knowledge loss
- Performance optimization → Prevent slowdown
- Database indexing → Prevent performance issues
- Security audit → Prevent security breaches
- Technology upgrade → Stay current

**Characteristics:**
- ✅ Proactive approach
- ✅ Long-term benefits
- ✅ Planned
- ✅ Cost-effective
- ✅ Quality improvement

**Cost:** Low (upfront)
**Timeline:** Long-term

---

## **Maintenance Comparison Table:**

| Type | Focus | Trigger | Cost | Timeline | Nature |
|------|-------|---------|------|----------|--------|
| **Corrective** | Fix bugs | Problem occurs | Low-Med | Immediate | Reactive |
| **Adaptive** | Adapt to environment | Environment changes | Med | Short-Med | Planned |
| **Perfective** | Improve/enhance | User requests | Med-High | Medium | Planned |
| **Preventive** | Prevent problems | Improvement plan | Low | Long-term | Proactive |

---

## <a name="testing"></a>
## 5️⃣ SOFTWARE TESTING (Deep Dive)

### **What is Software Testing?**
Process of executing a program with intent of finding errors.

### **Testing Levels:**

**1. UNIT TESTING** 🧩
- **Who:** Developers
- **What:** Individual functions/methods
- **Tools:** JUnit, NUnit, pytest
- **Scope:** Single component
- **Cost:** Low
- **When:** During development

**Example:**
```
Test function: calculateTotal(price, quantity, tax)
Expected: 110 (100*1 + 10 tax)
Actual: 110 ✅
```

---

**2. INTEGRATION TESTING** 🔗
- **Who:** QA Team
- **What:** Module interactions
- **Scope:** Multiple components together
- **Tools:** Postman, SoapUI
- **Cost:** Medium
- **When:** After unit testing

**Example:**
```
Test: UI → Database → API → Server
Check if data flows correctly between modules
```

---

**3. SYSTEM TESTING** 🎯
- **Who:** QA Team
- **What:** Complete system
- **Scope:** End-to-end
- **Tools:** Selenium, QTP
- **Cost:** High
- **When:** After integration testing

**Examples:**
- Functional testing
- Performance testing
- Security testing
- Usability testing
- Compatibility testing

---

**4. UAT/ACCEPTANCE TESTING** ✅ (IMPORTANT)
- **Who:** End Users/Clients
- **What:** Real-world scenarios
- **Scope:** User requirements
- **Tools:** Manual testing
- **Cost:** High
- **When:** Before deployment

**Components:**
- ✅ **Usability Testing** - User-friendly? ← ACCEPTED AS ACCEPTANCE TESTING
- ✅ **Business Logic Validation** - Does it work as required?
- ✅ **End-to-End Workflow Testing** - Complete process works?
- ✅ **User Acceptance Criteria** - Meets requirements?

---

### **Testing Types by Approach:**

**1. BLACK BOX TESTING** 🔲
- Test without knowing internal code
- Input → Output only
- User perspective
- Examples: Functional, UAT testing

**2. WHITE BOX TESTING** 🔳
- Test with knowledge of code
- Test internal logic
- Developer perspective
- Examples: Unit testing, Code coverage

**3. GRAY BOX TESTING** ⚫
- Partial knowledge of code
- Mix of black and white
- Integration level

---

## <a name="concepts"></a>
## 6️⃣ IMPORTANT CONCEPTS & CONNECTIONS

### **A. MODULAR DESIGN** 🧩

**What is it?** Breaking system into independent modules.

**Key Terms:**

**1. COUPLING** 🔗
- **Definition:** Strength of connection/dependency BETWEEN modules
- **Low Coupling** ✅ GOOD - Modules independent
- **High Coupling** ❌ BAD - Modules dependent
- **Goal:** Minimize coupling
- **Benefit:** Easy to change, test, reuse

**Example:**
```
Low Coupling:
Module A ──┐
           ├─→ Interface ──→ Module C
Module B ──┘
(Modules don't directly depend on each other)

High Coupling:
Module A ──→ calls ──→ Module B ──→ calls ──→ Module C
(Changes in C affect B, B affects A)
```

**Types of Coupling (Worst to Best):**
1. **Content Coupling** - Direct access to internal data
2. **Common Coupling** - Shared global data
3. **Control Coupling** - Pass control flags
4. **Stamp Coupling** - Pass data structures
5. **Data Coupling** - Pass only data ✅ BEST

---

**2. COHESION** 🎯
- **Definition:** How well elements WITHIN a module relate
- **High Cohesion** ✅ GOOD - Related functions together
- **Low Cohesion** ❌ BAD - Unrelated functions mixed
- **Goal:** Maximize cohesion
- **Benefit:** Easy to understand, maintain

**Example:**
```
High Cohesion:
Module: PaymentProcessing
├─ validateCard()
├─ processPayment()
├─ generateReceipt()
└─ updateBalance()
(All payment-related)

Low Cohesion:
Module: Utils
├─ calculateTax()
├─ sendEmail()
├─ drawCircle()
└─ encryptPassword()
(Unrelated functions)
```

**Cohesion Types (Worst to Best):**
1. **Coincidental** - No relationship
2. **Logical** - Similar type functions
3. **Temporal** - Execute at same time
4. **Procedural** - Follow sequence
5. **Communicational** - Same data
6. **Sequential** - Output of one is input of another ✅ GOOD
7. **Functional** - Single responsibility ✅ BEST

---

**COUPLING vs COHESION:**
```
┌─────────────────────────────────────────┐
│          Module A                       │
├─────────────────────────────────────────┤
│ High Cohesion: Related functions        │ ← Internal unity
│ - func1()                               │
│ - func2()                               │
│ - func3()                               │
└────────────┬──────────────────────────┬─┘
             │                          │
          Low Coupling (Independent)   │
             │                          │
          Module B                   Module C
```

---

### **B. DFD (DATA FLOW DIAGRAM)** 📊

**What is it?** Graphical representation showing data flow through system.

**Type:** **Flow Model** ✅

**Components:**
1. **Process (Circle)** - Transforms data
2. **Data Store (Double line)** - Stores data (database, file)
3. **External Entity (Rectangle)** - Outside source/destination
4. **Data Flow (Arrow)** - Movement of data

**DFD Levels:**
- **Level 0 (Context)** - Entire system as one process
- **Level 1** - Main processes
- **Level 2+** - Detailed sub-processes

**Example DFD:**
```
┌─────────┐
│  User   │ External Entity
└────┬────┘
     │ Username/Password
     ▼
  ●─────────●  Process: Validate Login
  │         │
  └────┬────┘
       │ User ID
       ▼
  [Auth DB]  Data Store
  
  If valid:
  ┌──────────────┐
  │   Redirect   │ Process
  │  to Dashboard│
  └──────────────┘
```

**DFD is:** Flow Model ✅ (NOT Class, Scenario, or Behavioral)

---

### **C. ER MODEL (Entity-Relationship)** 🗂️

**What is it?** Shows entities, attributes, and relationships.

**Components:**
- **Entity** - Real-world object (Student, Course)
- **Attribute** - Property of entity (Name, ID)
- **Relationship** - Connection between entities (Enrolls)

**Cardinality Notations:**
- **1:1** - One-to-One (Student has one ID Card)
- **1:N** - One-to-Many (Teacher has many Students)
- **M:N** - Many-to-Many (Students take many Courses)

---

## <a name="questions"></a>
## 7️⃣ EXAM QUESTIONS BANK

### **QUESTION 1: SDLC Models**

**Q: Which model is best suited for projects with well-defined requirements and no expected changes?**

**A: Waterfall Model** ✅

**Explanation:**
- Waterfall is sequential and rigid
- Best when requirements are fixed
- Not suitable for changes
- High documentation
- Clear phases

**Why others are wrong:**
- Agile: For changing requirements
- RAD: For speed, not stability
- Spiral: For high-risk complex projects
- Prototyping: For unclear requirements

---

### **QUESTION 2: Maintenance Types**

**Q: Which of the following is NOT a reason for corrective maintenance?**
- (A) System errors detected by users
- (B) User requests for additional features ✅
- (C) System crashes due to software bugs
- (D) Security vulnerabilities discovered

**A: (B) User requests for additional features** ✅

**Explanation:**
- Corrective = Fix existing bugs/errors
- User requests for features = Adaptive/Perfective (enhancement)
- NOT corrective maintenance

---

### **QUESTION 3: Testing Levels**

**Q: Which of the following is a normal acceptance testing?**
- (A) Data Flow testing
- (B) Alpha testing
- (C) Security testing
- (D) Usability testing ✅

**A: (D) Usability testing** ✅

**Explanation:**
- UAT/Acceptance testing includes usability testing
- Users validate if system is user-friendly
- Part of acceptance criteria
- Other options are specialized testing types

---

### **QUESTION 4: DFD Model Type**

**Q: Data Flow Diagram (DFD) is a -**
- (A) Flow model ✅
- (B) Class model
- (C) Scenario-based model
- (D) Behavioral model

**A: (A) Flow model** ✅

**Explanation:**
- DFD shows data flow through system
- It's called Flow Model
- Class model = UML Class Diagram
- Scenario model = Use Case Diagram
- Behavioral model = State/Activity Diagram

---

### **QUESTION 5: Coupling Definition**

**Q: What does "Coupling" indicate in modular design?**
- (A) The strength of connection between modules ✅
- (B) The relationship between system hardware
- (C) The documentation process of modules
- (D) The cohesion of a module

**A: (A) The strength of connection between modules** ✅

**Explanation:**
- Coupling = Dependencies BETWEEN modules
- Low coupling = Good (modules independent)
- Cohesion ≠ Coupling (different concepts)
- Hardware relationship ≠ Software coupling

---

### **QUESTION 6: SDLC Phase Mapping**

**Q: Select the correct mapping of system phase with deliverables:**
- (A) Analysis: Data Model, Process Models, Use Cases ✅
- (B) Implementation: Program Design, Hardware specs
- (C) Design: Test Plan, Programs, Migration Plan
- (D) Planning: Test Plan, Program Design, Support Plan

**A: (A) Analysis: Data Model, Process Models, Use Cases** ✅

**Explanation:**

| Phase | Correct Deliverables |
|-------|---------------------|
| **Analysis** | SRS, Data Model, Process Models, Use Cases, DFD |
| **Design** | Design Doc, Database Schema, UI Mockups |
| **Implementation** | Source Code, Built Software |
| **Testing** | Test Plan, Test Cases, Bug Reports |
| **Deployment** | Deployment Plan, Release Notes |
| **Maintenance** | Support Plan, Patches |

---

### **QUESTION 7: Agile vs Waterfall**

**Q: Which statement is TRUE about Agile model?**
- (A) It's rigid and sequential
- (B) Changes are expensive
- (C) It allows flexibility and continuous feedback ✅
- (D) It requires minimal customer involvement

**A: (C) It allows flexibility and continuous feedback** ✅

**Explanation:**
- Agile: Flexible, iterative, customer-involved
- Waterfall: Rigid, sequential, changes expensive
- Agile: Frequent releases, daily standups
- Waterfall: Complete after each phase

---

### **QUESTION 8: V-Model**

**Q: In V-Model, what corresponds to Design phase?**
- (A) Unit Testing
- (B) System Testing ✅
- (C) Integration Testing
- (D) Acceptance Testing

**A: (B) System Testing** ✅

**Explanation:**
```
V-Model Mapping:
Requirements ─────↔───── Acceptance Testing
Design ───────────↔───── System Testing
Implementation ───↔───── Integration Testing
Unit Code ────────↔───── Unit Testing
```

---

### **QUESTION 9: Spiral Model**

**Q: Spiral model is best for which type of project?**
- (A) Small projects with clear requirements
- (B) Large, complex, high-risk projects ✅
- (C) Quick development projects
- (D) Projects with unclear requirements

**A: (B) Large, complex, high-risk projects** ✅

**Explanation:**
- Spiral: Risk-driven approach
- Multiple iterations with risk assessment
- Expensive but effective
- Best for mission-critical systems

---

### **QUESTION 10: RAD Model**

**Q: RAD model is characterized by:**
- (A) Sequential development
- (B) Time-boxed iterations and visual tools ✅
- (C) High documentation
- (D) Long development cycles

**A: (B) Time-boxed iterations and visual tools** ✅

**Explanation:**
- RAD: Rapid Application Development
- Time-boxed (60-90 days)
- Visual development tools
- Quick iterations
- Speed-focused

---

### **QUESTION 11: SRS (Software Requirements Specification)**

**Q: What is the primary purpose of SRS?**
- (A) Define system architecture
- (B) Document all requirements in detail ✅
- (C) Create user interface design
- (D) Develop test cases

**A: (B) Document all requirements in detail** ✅

**Explanation:**
- SRS = Software Requirements Specification
- Output of Requirements Analysis phase
- Contains: Functional requirements, Non-functional, Constraints
- Used as contract between client and developer
- Basis for design and testing

---

### **QUESTION 12: Prototyping Model**

**Q: When is Prototyping model most suitable?**
- (A) When requirements are very clear
- (B) When requirements are unclear/evolving ✅
- (C) When time and cost are critical
- (D) When system is mission-critical

**A: (B) When requirements are unclear/evolving** ✅

**Explanation:**
- Prototyping: Build working model first
- Get user feedback early
- Clarify unclear requirements
- Reduces misunderstandings
- Evolutionary approach

---

### **QUESTION 13: Cohesion vs Coupling**

**Q: Which statement about good modular design is TRUE?**
- (A) High coupling and Low cohesion
- (B) Low coupling and High cohesion ✅
- (C) High coupling and High cohesion
- (D) Low coupling and Low cohesion

**A: (B) Low coupling and High cohesion** ✅

**Explanation:**
- **Low Coupling** ✅ GOOD - Modules independent
- **High Cohesion** ✅ GOOD - Related functions together
- **Low Cohesion** ❌ BAD - Unrelated functions mixed
- **High Coupling** ❌ BAD - Modules dependent

**Goal in Good Design:**
```
LOW COUPLING + HIGH COHESION = BEST DESIGN
```

---

### **QUESTION 14: Testing Pyramid**

**Q: In the Testing Pyramid, which level has maximum number of tests?**
- (A) Unit Testing ✅
- (B) Integration Testing
- (C) System Testing
- (D) Acceptance Testing

**A: (A) Unit Testing** ✅

**Explanation:**
```
Testing Pyramid (from bottom to top):
       △ UAT (10%)
      △ △ System (20%)
     △ △ △ Integration (30%)
    △ △ △ △ Unit (40%) ← MAXIMUM
    
Maximum unit tests because:
- Easiest to write
- Fastest to execute
- Lowest cost
- Most numerous
```

---

### **QUESTION 15: Deployment Strategies**

**Q: Which deployment strategy is safest but most expensive?**
- (A) Big Bang
- (B) Phased
- (C) Parallel ✅
- (D) Pilot

**A: (C) Parallel** ✅

**Explanation:**

| Strategy | Safety | Cost | Time | Usage |
|----------|--------|------|------|-------|
| **Big Bang** | Risky | Low | Fast | Small systems |
| **Phased** | Safe | Medium | Medium | Most systems |
| **Parallel** | Safest | HIGH ⭐ | Slow | Critical systems |
| **Pilot** | Safe | Medium | Slow | New technology |

- Parallel: Old + New system running together
- Safest: Can rollback immediately
- Most expensive: Double resources

---

### **QUESTION 16: Code Review**

**Q: In which SDLC phase is Code Review typically done?**
- (A) Requirements phase
- (B) Design phase
- (C) Implementation/Development phase ✅
- (D) Testing phase

**A: (C) Implementation/Development phase** ✅

**Explanation:**
- Code review: Part of quality assurance
- Done during development
- Peer review of code
- Catches bugs early
- Improves code quality

---

### **QUESTION 17: Change Management**

**Q: Which SDLC model handles changes most efficiently?**
- (A) Waterfall
- (B) Agile ✅
- (C) Spiral
- (D) V-Model

**A: (B) Agile** ✅

**Explanation:**
- Agile: Built for changes
- Flexible iterations
- Regular feedback
- Can incorporate changes in next sprint
- Waterfall: Changes are expensive

---

### **QUESTION 18: Risk Assessment**

**Q: Which SDLC model emphasizes risk assessment at each cycle?**
- (A) Waterfall
- (B) Agile
- (C) Spiral ✅
- (D) Prototyping

**A: (C) Spiral** ✅

**Explanation:**
- Spiral Model: Risk-driven approach
- 4 quadrants: Objective, Risk Analysis, Engineering, Evaluation
- Risk assessment at EACH spiral
- Best for high-risk projects
- Most expensive model

---

### **QUESTION 19: Functional vs Non-Functional Requirements**

**Q: Which is a Non-Functional requirement?**
- (A) User can login with username and password
- (B) System should respond within 2 seconds ✅
- (C) System can generate monthly reports
- (D) User can update profile information

**A: (B) System should respond within 2 seconds** ✅

**Explanation:**

| Functional Requirements | Non-Functional Requirements |
|----------------------|--------------------------|
| WHAT system does | HOW system performs |
| Login functionality | Response time |
| Generate reports | Scalability |
| Update data | Security |
| Search features | Usability |
| | Performance |
| | Reliability |

---

### **QUESTION 20: Quality Assurance vs Quality Control**

**Q: What is the difference between QA and QC?**
- (A) QA is testing, QC is bug fixing
- (B) QA is process-oriented, QC is product-oriented ✅
- (C) QA is expensive, QC is cheap
- (D) QA is before development, QC is after

**A: (B) QA is process-oriented, QC is product-oriented** ✅

**Explanation:**

| QA (Quality Assurance) | QC (Quality Control) |
|----------------------|----------------------|
| **Focus:** Process | Focus: Product |
| **When:** Before and During | When: After |
| **Activity:** Plan, Review, Audit | Activity: Test, Inspect |
| **Goal:** Prevent defects | Goal: Find defects |
| **Proactive** | Reactive |

---

## 📋 KEY FORMULAS & FACTS

### **SDLC Models Quick Reference:**

```
WATERFALL: Requirements → Design → Dev → Test → Deploy → Maintain
├─ Best for: Well-defined, stable requirements
├─ Changes: Expensive
└─ Documentation: High

AGILE: Sprint Planning → Dev → Test → Review → Retrospective (Repeat)
├─ Best for: Changing requirements
├─ Changes: Cheap (flexible)
└─ Documentation: Minimal

RAD: Requirements → Visual Design → Dev → Test (60-90 days)
├─ Best for: Speed
├─ Tools: Visual development
└─ Cost: High upfront

SPIRAL: Plan → Risk Analysis → Engineering → Evaluation (Repeat)
├─ Best for: High-risk, complex projects
├─ Iterations: Multiple with risk assessment
└─ Cost: Very high

PROTOTYPING: Req → Prototype → Feedback → Refine → Final Dev
├─ Best for: Unclear requirements
├─ User involvement: High
└─ Goal: Clarify requirements

V-MODEL:
├─ Req ↔ Acceptance Testing
├─ Design ↔ System Testing
├─ Code ↔ Integration Testing
└─ Units ↔ Unit Testing
```

---

## 💡 COMMON MISTAKES TO AVOID

❌ **MISTAKE 1:** Confusing Corrective with Adaptive Maintenance
- ✅ **FIX:** Corrective = Fix bugs | Adaptive = Environment change

❌ **MISTAKE 2:** Thinking DFD is Behavioral Model
- ✅ **FIX:** DFD is Flow Model | Behavioral = State Diagram

❌ **MISTAKE 3:** Mixing Coupling and Cohesion
- ✅ **FIX:** Coupling = Between modules | Cohesion = Within module

❌ **MISTAKE 4:** UAT includes all testing types
- ✅ **FIX:** UAT specifically includes Usability & User acceptance testing

❌ **MISTAKE 5:** Agile has high documentation
- ✅ **FIX:** Agile has MINIMAL documentation (Waterfall has high)

---

## 🎓 STUDY TIPS

1. **Create comparison tables** - Makes differences clear
2. **Draw diagrams** - DFD, V-Model, SDLC flow
3. **Memorize model characteristics** - When to use which
4. **Connect to real projects** - Think of examples
5. **Practice mapping questions** - Phase to deliverables

---

## ✅ REVISION CHECKLIST

Before exam, ensure you can answer:

- [ ] What are 7 SDLC phases and their deliverables?
- [ ] Difference between Waterfall and Agile?
- [ ] When to use Spiral vs Prototyping?
- [ ] What is SRS and why important?
- [ ] Types of maintenance and examples?
- [ ] Coupling vs Cohesion?
- [ ] DFD components and levels?
- [ ] Testing levels and who does them?
- [ ] What is UAT and its components?
- [ ] V-Model mapping?

---

**Next Topic:** Data Structures & Algorithms 📊

*Good Luck with your exam! 🚀*
