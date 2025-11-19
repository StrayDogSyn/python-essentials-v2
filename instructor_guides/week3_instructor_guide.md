# Week 3 Instructor Guide: More Python Skills

## 📚 Course Overview
Week 3 expands students' Python capabilities with control flow (if/else, loops), comprehensive error handling, and advanced function concepts. This week transforms students from basic syntax users to confident Python programmers capable of solving complex problems.

## 🎯 Learning Objectives
By the end of Week 3, students will be able to:
- Master control flow with if/elif/else statements and loops
- Implement comprehensive error handling with try/except/finally
- Write functions with multiple parameters and return values
- Understand scope and work with global/local variables
- Use list comprehensions and generator expressions
- Apply Pythonic idioms and best practices

## 🏗️ Session Structure

### Session 1: Individual Skill Development (90 minutes)

#### Opening: Control Flow Foundations (15 minutes)
- **JavaScript Bridge:** Compare Python control flow to JavaScript
- **Problem-Solving Focus:** "How do we make programs make decisions?"
- **Preview:** Advanced function concepts and error handling

#### Core Concepts (60 minutes)

1. **Control Flow Mastery (25 min)**
   - If/elif/else chains with complex conditions
   - For loops with range(), enumerate(), zip()
   - While loops and break/continue statements
   - Activity: Build number guessing game with loops
   - JavaScript parallel: Similar concepts, different syntax

2. **Error Handling Excellence (20 min)**
   - Try/except/finally structure
   - Specific exception types vs generic catches
   - Raising exceptions with meaningful messages
   - Activity: Build robust input validation functions
   - Best practice: Never use bare except clauses

3. **Advanced Functions (15 min)**
   - Multiple parameters and default values
   - Returning multiple values with tuples
   - Scope: local vs global variables
   - Activity: Build data processing functions

#### Practice & Integration (15 minutes)
- Combine control flow with error handling
- Refactor previous week's functions with new skills
- Preview group problem-solving session

### Session 2: Group Problem Solving (90 minutes)

#### Collaborative Challenge Structure
- **Software Team Simulation:** Students work as development team
- **Role Rotation:** Problem Solver, Code Reviewer, Tester
- **Complexity Scaling:** Start simple, build to sophisticated solutions

#### Group Activities (75 minutes)

1. **Control Flow Challenge Series (30 min)**
   - Pattern recognition with nested loops
   - Data filtering with complex conditions
   - Algorithm implementation (sorting, searching)
   - Each team member leads different approach

2. **Error Handling Workshop (25 min)**
   - Given buggy code, teams add proper error handling
   - Create custom exceptions for domain-specific errors
   - Build robust file processing with error recovery
   - Share different error handling strategies

3. **Function Design Competition (20 min)**
   - Teams design functions for complex requirements
   - Emphasize readability, efficiency, and error handling
   - Peer review and optimization suggestions
   - Best function wins class vote

#### Reflection & Connection (15 minutes)
- Compare individual vs collaborative problem-solving
- Connect to data processing applications
- Prepare for Week 4 data engineering concepts

## 🧠 Teaching Strategies

### Control Flow Teaching Approach
1. **Visual Flowcharts:** Show program execution visually
2. **Step-by-Step Execution:** Use debugger or print statements
3. **Common Pattern Recognition:** Identify recurring control flow patterns
4. **Real-world Analogy:** Traffic lights, decision trees, recipes

### Error Handling Philosophy
1. **Fail Fast, Fail Loud:** Teach proper exception raising
2. **Specific over General:** Catch specific exceptions when possible
3. **Graceful Degradation:** Programs should fail gracefully
4. **User-Friendly Messages:** Error messages should help users

### Advanced Function Concepts
1. **Function Composition:** Build complex functions from simple ones
2. **Single Responsibility:** Each function should do one thing well
3. **Documentation:** Clear docstrings and comments
4. **Testing:** Write simple tests for functions

## 🚨 Common Student Challenges

### Loop Complexity
- **Problem:** Nested loops and complex iteration patterns
- **Solution:** Break down into smaller steps, use diagrams
- **Practice:** Start with single loops, gradually add complexity

### Exception Handling Confusion
- **Problem:** When to catch vs when to raise exceptions
- **Solution:** Clear guidelines and decision frameworks
- **Practice:** Lots of examples with different scenarios

### Scope Understanding
- **Problem:** Global vs local variable confusion
- **Solution:** Visual scope diagrams, explicit examples
- **Prevention:** Encourage local variables, minimize globals

### List Comprehension Complexity
- **Problem:** Nested comprehensions and conditional logic
- **Solution:** Start simple, build complexity gradually
- **Practice:** Convert loops to comprehensions step by step

## 📋 Assessment & Practice

### Formative Assessment Questions
1. "When would you use a for loop vs a while loop?"
2. "What's the difference between except Exception and except ValueError?"
3. "How do you return multiple values from a function?"
4. "When should you use a list comprehension vs a regular loop?"

### Practice Exercises
- **Basic:** Write loops for common patterns (counting, summing, filtering)
- **Intermediate:** Add error handling to existing functions
- **Advanced:** Build complex functions with multiple parameters and error cases

### Code Review Criteria
- ✅ Proper exception handling (specific exceptions, not bare except)
- ✅ Clear control flow with appropriate loop choices
- ✅ Functions have single responsibility and clear names
- ✅ No unnecessary global variables
- ✅ List comprehensions used appropriately

## 🛠️ Technical Requirements

### Development Environment
- Python debugger access (pdb or IDE debugger)
- Code coverage tools for testing practice
- Error tracking and logging capabilities

### Practice Data
- Sample datasets for processing exercises
- Files with intentional errors for error handling practice
- Complex nested data structures for manipulation

## 📖 Week Connections

### Building on Previous Weeks
- **Week 1-2:** Functions now use control flow and error handling
- **Data Structures:** Manipulated with loops and conditions
- **File Operations:** Enhanced with error handling

### Foundation for Future Weeks
- **Week 4:** Data pipelines use these control structures
- **Week 5:** Data cleaning uses error handling extensively
- **Week 6+:** All data analysis builds on these programming skills

### Skills Progression
- Control flow enables complex data processing logic
- Error handling makes programs robust and professional
- Advanced functions enable code reuse and modularity

## 🔄 Teaching Tips

### Making It Stick
1. **Spiral Learning:** Revisit concepts in new contexts
2. **Incremental Complexity:** Build from simple to complex
3. **Real-world Application:** Show practical uses immediately
4. **Peer Teaching:** Students explain concepts to each other

### Engagement Strategies
- **Gamification:** Programming challenges and competitions
- **Story Problems:** Frame exercises as real scenarios
- **Immediate Feedback:** Use automated testing when possible
- **Collaboration:** Mix individual and pair programming

## 📊 Success Metrics

### By End of Week 3, Students Should:
- **Write complex control flow:** Nested loops, conditional chains
- **Handle errors gracefully:** Try/except with appropriate exceptions
- **Build sophisticated functions:** Multiple parameters, return values
- **Use Pythonic constructs:** List comprehensions, proper idioms
- **Solve multi-step problems:** Break complex problems into functions

### Red Flags to Address
- Still struggling with basic loop syntax
- Using print for debugging instead of proper error handling
- Writing functions that are too long or do too many things
- Not understanding when to use different loop types
- Confusion about variable scope and global/local distinctions

This guide ensures students develop robust programming skills that will serve them throughout the course and their careers, with particular emphasis on writing clean, error-resistant code suitable for data processing applications.