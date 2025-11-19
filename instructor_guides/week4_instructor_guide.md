# Week 4 Instructor Guide: Introduction to Data Engineering

## 📚 Course Overview
Week 4 introduces students to data engineering concepts using Python's standard library. Students learn to work with the filesystem, process CSV and JSON data, and build simple data pipelines. This week bridges programming skills to practical data processing applications.

## 🎯 Learning Objectives
By the end of Week 4, students will be able to:
- Navigate and manipulate filesystems using pathlib and os modules
- Read and write CSV files using the csv module
- Work with JSON data for configuration and data exchange
- Build simple ETL (Extract, Transform, Load) pipelines
- Handle file operations safely with proper error management
- Understand data pipeline concepts and best practices

## 🏗️ Session Structure

### Session 1: Individual Data Engineering Foundations (90 minutes)

#### Opening: Data Engineering in the Real World (15 minutes)
- **Industry Context:** Show real data engineering applications
- **Problem-Solving Focus:** "How do we move and transform data?"
- **Preview:** Building data pipelines with pure Python

#### Core Concepts (60 minutes)

1. **Filesystem Operations (20 min)**
   - pathlib vs os: modern vs traditional approaches
   - Creating, navigating, and managing directories
   - File existence checks and path manipulation
   - Activity: Build directory structure for data project
   - Best practice: Use pathlib for new code

2. **CSV Processing Mastery (20 min)**
   - Reading CSV with DictReader (preferred for data work)
   - Writing CSV with DictWriter
   - Handling headers and data types
   - Activity: Process sales data, filter by conditions
   - Error handling: Missing files, malformed data

3. **JSON for Data Exchange (15 min)**
   - JSON structure and Python mapping
   - Reading and writing JSON files
   - Nested data handling
   - Activity: Create configuration files, process API responses
   - Best practice: Validate JSON structure

#### Practice & Integration (15 minutes)
- Combine file operations into simple pipeline
- Process real dataset from start to finish
- Preview collaborative pipeline building

### Session 2: Group Pipeline Development (90 minutes)

#### Collaborative Data Team Structure
- **Data Engineering Team Simulation:** Students work as data team
- **Role Rotation:** Data Extractor, Data Transformer, Data Loader
- **Pipeline Focus:** Build complete ETL process together

#### Group Activities (75 minutes)

1. **ETL Pipeline Challenge (35 min)**
   - Extract data from multiple file formats
   - Transform data using Python data structures
   - Load clean data into new format
   - Each team member handles pipeline stage

2. **Data Quality Workshop (25 min)**
   - Identify and handle data quality issues
   - Build validation checks into pipeline
   - Create data quality reports
   - Share different validation strategies

3. **Pipeline Optimization Competition (15 min)**
   - Teams optimize pipeline for speed/robustness
   - Compare different approaches
   - Discuss trade-offs in pipeline design
   - Best pipeline wins efficiency award

#### Reflection & Connection (15 minutes)
- Compare individual vs collaborative pipeline building
- Connect to upcoming data cleaning topics
- Prepare for Week 5 data validation concepts

## 🧠 Teaching Strategies

### Data Engineering Mindset
1. **Pipeline Thinking:** Break problems into ETL stages
2. **Data Quality First:** Emphasize validation and error handling
3. **Scalability Preview:** Show how small pipelines scale to big data
4. **Real-world Relevance:** Use actual data scenarios

### File Handling Best Practices
1. **Safety First:** Always check file existence
2. **Error Handling:** Comprehensive try/except blocks
3. **Resource Management:** Proper file closing with context managers
4. **Cross-platform:** Use pathlib for compatibility

### Standard Library Focus
1. **No External Dependencies:** Build confidence with built-in tools
2. **Foundation Building:** Understand core concepts before libraries
3. **Troubleshooting:** Easier to debug when you understand internals
4. **Portability:** Code works anywhere Python runs

## 🚨 Common Student Challenges

### File Path Confusion
- **Problem:** Relative vs absolute paths, different operating systems
- **Solution:** Teach pathlib, show path resolution techniques
- **Practice:** Exercises with different path scenarios

### CSV Data Type Issues
- **Problem:** Everything reads as strings from CSV
- **Solution:** Explicit type conversion, validation functions
- **Practice:** Build type conversion utilities

### JSON Structure Complexity
- **Problem:** Nested JSON navigation and modification
- **Solution:** Step-by-step access, intermediate variables
- **Practice:** Work with real API response data

### Pipeline Error Handling
- **Problem:** Pipelines fail silently or crash on bad data
- **Solution:** Comprehensive error handling strategies
- **Practice:** Build robust pipelines with error recovery

## 📋 Assessment & Practice

### Formative Assessment Questions
1. "When would you choose pathlib over os.path?"
2. "How do you handle missing values when reading CSV files?"
3. "What's the difference between csv.reader and csv.DictReader?"
4. "How do you validate JSON data before processing it?"

### Practice Exercises
- **Basic:** Read and write simple CSV and JSON files
- **Intermediate:** Build data transformation pipeline
- **Advanced:** Create robust pipeline with error handling and validation

### Code Review Criteria
- ✅ Proper file handling with context managers
- ✅ Appropriate data structure selection for data processing
- ✅ Comprehensive error handling for file operations
- ✅ Clear separation of ETL pipeline stages
- ✅ Data validation and quality checks

## 🛠️ Technical Requirements

### Sample Data Files
- CSV files with various structures and quality levels
- JSON configuration files and API responses
- Mixed format datasets for realistic scenarios

### Development Environment
- File system access for reading/writing operations
- Text editor with CSV and JSON syntax highlighting
- Command line access for file operations

## 📖 Week Connections

### Building on Previous Weeks
- **Week 1-3:** Use functions and control structures for data processing
- **Data Structures:** Apply lists and dictionaries to file data
- **Error Handling:** Robust file operations with exception handling

### Foundation for Future Weeks
- **Week 5:** Data cleaning builds on file processing skills
- **Week 6:** Data wrangling extends pipeline concepts
- **Week 7+:** All data analysis starts with file loading and processing

### Skills Progression
- File operations enable data ingestion for all future work
- Pipeline thinking applies to all data processing tasks
- Error handling becomes critical for production data systems

## 🔄 Teaching Tips

### Real-world Application
1. **Use Real Data:** Government datasets, sports statistics, weather data
2. **Industry Context:** Show how these skills apply in data engineering jobs
3. **Problem-based Learning:** Start with real problem, build solution
4. **Portfolio Building:** Encourage saving best work for job applications

### Engagement Strategies
- **Data Detective:** Students investigate datasets to find insights
- **Pipeline Race:** Teams compete for fastest/robustest pipeline
- **Error Challenge:** Intentionally break things, then fix them
- **Real Impact:** Show how data engineering affects real decisions

## 📊 Success Metrics

### By End of Week 4, Students Should:
- **Process files confidently:** Read/write CSV and JSON without assistance
- **Build simple pipelines:** Create ETL processes with multiple steps
- **Handle errors gracefully:** Robust file operations with proper error handling
- **Understand data quality:** Identify and address common data issues
- **Work with filesystem:** Navigate and manipulate directories effectively

### Red Flags to Address
- Still struggling with basic file operations
- Not understanding pathlib vs os.path differences
- Unable to separate pipeline stages conceptually
- Missing error handling in file operations
- Confusion about data types when reading files

This guide ensures students develop practical data engineering skills while building confidence in processing real-world data with Python's powerful standard library.