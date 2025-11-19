# Week 2 Instructor Guide: Data Structures and File Handling

## 📚 Course Overview
Week 2 introduces students to Python's powerful data structures (lists, dictionaries, tuples, sets) and file handling capabilities. This week bridges from basic syntax to practical data manipulation, preparing students for data engineering concepts.

## 🎯 Learning Objectives
By the end of Week 2, students will be able to:
- Create and manipulate lists, dictionaries, tuples, and sets
- Understand when to use each data structure
- Read from and write to text files using Python
- Handle basic file operations and error scenarios
- Combine data structures for complex data representation

## 🏗️ Session Structure

### Session 1: Individual Data Structures Deep Dive (90 minutes)

#### Opening: Data Structure Comparison (15 minutes)
- **JavaScript Bridge:** Compare Python lists to JavaScript arrays
- **Real-world Example:** Show how different data structures solve different problems
- **Preview:** "These structures become the foundation for all data work"

#### Core Concepts (60 minutes)

1. **Lists - The Workhorse (20 min)**
   - Creation, indexing, slicing, methods
   - Live coding: Build and manipulate lists
   - Activity: Students create lists of different data types
   - JavaScript parallel: `append()` vs `push()`, `len()` vs `length`

2. **Dictionaries - Key-Value Power (20 min)**
   - Creation, access, modification, iteration
   - Live coding: Build user profiles, count occurrences
   - Activity: Create address book with nested dictionaries
   - JavaScript parallel: Similar to objects but different syntax

3. **Tuples and Sets - Specialized Tools (15 min)**
   - When immutability matters (tuples)
   - When uniqueness matters (sets)
   - Activity: Convert between data structures

4. **File Handling - Data Persistence (5 min)**
   - Basic file operations with context managers
   - Error handling introduction
   - Activity: Save and load data structures to files

#### Practice & Wrap-up (15 minutes)
- Guided practice combining multiple structures
- Preview next session's group activities
- Assign file manipulation homework

### Session 2: Group Data Manipulation (90 minutes)

#### Collaborative Problem Solving Structure
- **Data Team Simulation:** Students work as data analysts
- **Role Rotation:** Data Collector, Data Processor, Data Reporter
- **Real Dataset:** Work with actual CSV or JSON data

#### Group Activities (75 minutes)

1. **Data Structure Olympics (25 min)**
   - Teams compete to solve data manipulation challenges fastest
   - Examples: Find duplicates, group by category, filter conditions
   - Rotate roles every challenge

2. **File Processing Pipeline (25 min)**
   - Read messy data from file
   - Clean and transform using data structures
   - Write cleaned data to new file
   - Each team member handles different file format

3. **Data Structure Design Challenge (25 min)**
   - Given a real-world scenario, design optimal data structure
   - Teams present and defend their choices
   - Peer review and optimization suggestions

#### Reflection & Connection (15 minutes)
- Compare individual vs group approaches
- Connect to upcoming data engineering topics
- Plan improvements for next week

## 🧠 Teaching Strategies

### Data Structure Selection Guidance
1. **Decision Tree Approach:** Provide clear criteria for choosing structures
2. **Performance Preview:** Briefly mention efficiency considerations
3. **Real-world Mapping:** Connect to database concepts they'll see later

### File Handling Best Practices
1. **Context Manager Emphasis:** Always use `with open()`
2. **Error Handling:** Introduce try/except for file operations
3. **Path Safety:** Use `pathlib` for cross-platform compatibility

### JavaScript Transition Support
- **Array vs List:** Show method name differences
- **Object vs Dict:** Highlight syntax and method differences
- **No Direct Equivalent:** Explain tuples and sets as Python advantages

## 🚨 Common Student Challenges

### Data Structure Confusion
- **Problem:** Choosing wrong structure for the task
- **Solution:** Provide decision framework, practice scenarios
- **Prevention:** Emphasize use cases, not just syntax

### File Path Issues
- **Problem:** Files not found, permission errors
- **Solution:** Teach path debugging, use absolute vs relative paths
- **Prevention:** Always check file existence, use try/except

### Nested Structure Complexity
- **Problem:** Accessing deeply nested data
- **Solution:** Break down step-by-step, use intermediate variables
- **Practice:** Gradually increase nesting complexity

## 📋 Assessment & Practice

### Formative Assessment Questions
1. "When would you choose a set over a list?"
2. "How do you safely handle file operations in Python?"
3. "What's the difference between a tuple and a list?"

### Practice Exercises
- **Basic:** Create and manipulate each data structure type
- **Intermediate:** Build nested structures for real-world data
- **Advanced:** Design optimal structure for complex dataset

### Code Review Criteria
- ✅ Appropriate data structure selection
- ✅ Proper file handling with context managers
- ✅ Clear variable names indicating structure contents
- ✅ Efficient use of built-in methods

## 🛠️ Technical Requirements

### File Setup
- Sample data files (CSV, JSON, TXT)
- Directory structure for file operations practice
- Messy data files for cleaning exercises

### Development Environment
- Text editor with Python syntax highlighting
- File system access for reading/writing operations
- Jupyter notebooks for interactive exploration

## 📖 Week Connections

### Foundation for Future Weeks
- **Week 3:** Functions will manipulate these data structures
- **Week 4:** File operations become data pipelines
- **Week 5:** Data cleaning uses these structures extensively
- **Week 6+:** All data analysis builds on these foundations

### Skills Progression
- Week 1: Basic syntax → Week 2: Data manipulation → Week 3: Advanced functions
- Each week adds complexity while reinforcing previous concepts

## 🔄 Teaching Tips

### Making It Stick
1. **Spaced Repetition:** Reference Week 1 concepts frequently
2. **Incremental Complexity:** Add one new concept at a time
3. **Practical Application:** Always show real-world usefulness
4. **Peer Learning:** Encourage students to explain to each other

### Engagement Strategies
- **Gamification:** Turn exercises into competitions
- **Storytelling:** Frame problems as real data challenges
- **Immediate Feedback:** Use Jupyter's instant execution
- **Collaboration:** Mix individual and group work

## 📊 Success Metrics

### By End of Week 2, Students Should:
- **Manipulate confidently:** Create, modify, and access all data structures
- **Choose appropriately:** Select optimal structure for given problem
- **Handle files safely:** Read/write files with proper error handling
- **Work collaboratively:** Contribute effectively in group data tasks
- **Connect concepts:** Link data structures to real-world data problems

### Red Flags to Address
- Confusion between list and dictionary syntax
- Using print instead of return in data manipulation functions
- Ignoring file existence checks before operations
- Difficulty accessing nested data structures
- Choosing inappropriate data structures for tasks

This guide ensures students build solid foundations in data manipulation while maintaining engagement through practical, collaborative learning experiences.