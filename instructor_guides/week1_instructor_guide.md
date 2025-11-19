# Week 1 Instructor Guide: Introduction to Python

## 📚 Course Overview
Week 1 serves as the foundation for students transitioning from web development to Python. This week focuses on building confidence with Python syntax, understanding fundamental concepts, and establishing good coding practices from the start.

## 🎯 Learning Objectives
By the end of Week 1, students will be able to:
- Understand and use basic Python data types (strings, integers, floats, booleans)
- Perform arithmetic operations and work with variables
- Write functions that return values (not just print)
- Understand Python's indentation-based syntax
- Compare Python concepts with JavaScript equivalents

## 🏗️ Session Structure

### Session 1: Individual Introduction (90 minutes)
**Target Audience:** One-on-one mentoring session

#### Opening Discussion (15 minutes)
- **Ice Breaker:** "What have you heard about Python?"
- **JavaScript Background Check:** Assess their current programming experience
- **Expectation Setting:** Explain the learning journey ahead

#### Core Concepts Delivery (60 minutes)
1. **Data Types & Variables (20 min)**
   - Live coding: Demonstrate each data type
   - Activity: Students create variables for each type
   - JavaScript parallel: `None` vs `null`, `==` vs `===`

2. **Functions with Return Values (20 min)**
   - Emphasize return over print (Pythonic best practice)
   - Live coding: Build `add()`, `calculate_area()` functions
   - Activity: Students write functions with return values

3. **Indentation Deep Dive (20 min)**
   - Show before/after examples (now in markdown format)
   - Discuss Python vs JavaScript block structure
   - Practice identifying indentation errors

#### Wrap-up & Next Steps (15 minutes)
- Recap key concepts
- Assign practice exercises
- Preview Week 2 topics

### Session 2: Group Collaboration (90 minutes)
**Target Audience:** Small groups (3-4 students)

#### Role-Based Learning Structure
- **Driver:** Writes code (rotates every 15 minutes)
- **Navigator:** Guides the driver (rotates every 15 minutes)  
- **Tester:** Validates output and finds edge cases

#### Enhanced Activities
1. **Categorization Challenge (30 min)**
   - Groups build `categorize_numbers()` function together
   - Each role contributes: Driver codes, Navigator guides, Tester validates
   - Extension: Add list comprehension for advanced students

2. **Divisible-by Challenge (30 min)**
   - Collaborative problem-solving for numbers divisible by 3 and 5
   - Rotate roles halfway through
   - Groups share different solution approaches

3. **Group Reflection (30 min)**
   - Compare individual vs group problem-solving
   - Discuss Python vs JavaScript syntax preferences
   - Plan improvements for next group session

## 🧠 Teaching Strategies

### For Web Developers Transitioning to Python
1. **Bridge Concepts:** Always connect to JavaScript equivalents
2. **Visual Learning:** Use diagrams for indentation hierarchy
3. **Immediate Practice:** Short, frequent coding exercises
4. **Error-Driven Learning:** Intentional mistakes to teach debugging

### Engagement Techniques
- **Live Coding:** Code alongside students, explain thought process
- **Think-Pair-Share:** Individual thinking, partner discussion, group sharing
- **Progressive Disclosure:** Start simple, gradually add complexity
- **Real-World Context:** Show Python's relevance to data and web development

## 🚨 Common Student Challenges

### Indentation Issues
- **Problem:** Students forget to indent or mix tabs/spaces
- **Solution:** Use IDE with visible whitespace, practice with simple examples
- **Prevention:** Start every function with pass statement, then add logic

### Function Return vs Print Confusion
- **Problem:** Students use print instead of return
- **Solution:** Show consequences: can't reuse printed output vs reusable return values
- **Practice:** Convert print-based functions to return-based functions

### Variable Naming Habits
- **Problem:** Bringing JavaScript camelCase to Python
- **Solution:** Emphasize snake_case early, provide naming conventions guide
- **Practice:** Refactor poorly-named variables in examples

## 📋 Assessment & Practice

### Formative Assessment Questions
1. "Why does Python use indentation instead of braces?"
2. "When should you use return vs print in a function?"
3. "How is Python's None different from JavaScript's null?"

### Practice Exercises
- **Basic:** Create variables of each data type and print their types
- **Intermediate:** Write functions that return calculated values
- **Advanced:** Build a simple calculator with multiple functions

### Code Review Criteria
- ✅ Proper snake_case naming
- ✅ Consistent 4-space indentation
- ✅ Functions return values instead of printing
- ✅ Clear variable names (avoid single letters except in loops)

## 🛠️ Technical Setup

### Required Tools
- Python 3.9+ installed
- Jupyter Notebook or JupyterLab
- IDE with Python support (VS Code recommended)

### Pre-Class Setup Checklist
- [ ] Python version verified
- [ ] Jupyter notebooks launch successfully
- [ ] Basic arithmetic operations work
- [ ] Function definitions execute without errors

## 📖 Additional Resources

### For Students
- **Python Tutor:** Visualize code execution step-by-step
- **Real Python:** Beginner-friendly tutorials
- **Python.org Official Tutorial:** Comprehensive reference

### For Instructors
- **PEP 8 Style Guide:** Official Python style conventions
- **Python Enhancement Proposals:** Understanding language evolution
- **Teaching Python:** Pedagogical approaches and common pitfalls

## 🔄 Follow-up & Continuity

### Week 2 Preview
- "Next week we'll build on these basics with data structures"
- "You'll see how lists and dictionaries make data handling powerful"
- "We'll start working with real data files"

### Long-term Connections
- Week 1 concepts appear in every subsequent week
- Function writing becomes more complex over time
- Indentation discipline pays dividends in advanced topics

## 📊 Success Metrics

### By End of Week 1, Students Should:
- **Write 5+ functions** that return values correctly
- **Identify and fix** indentation errors independently
- **Explain** Python vs JavaScript syntax differences
- **Demonstrate** confidence in basic Python operations
- **Collaborate effectively** in group coding sessions

### Red Flags to Watch For
- Consistent indentation errors after multiple corrections
- Unable to distinguish between print and return
- Resistance to Pythonic naming conventions
- Difficulty transitioning from JavaScript mindset

This guide provides the foundation for successful Python learning while respecting students' existing programming knowledge and building bridges between familiar and new concepts.