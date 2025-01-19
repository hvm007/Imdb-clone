# IMDb-Clone

## Commands to Start the Application:
- **Run main_app.py**
  - From the terminal: Run `main_app.py`.
  - Activate the virtual environment: `.\venv\Scripts\activate`.

## Operating Systems Supported:
- Windows

## Libraries To Install:
- ttkbootstrap
- pandas
- matplotlib
- fuzzywuzzy
- python-Levenshtein
- tkinter
- random
- datetime
- numpy

## APIs Used:
- **OMDb API**: For movies data retrieval.
- **TMDb API**: For ratings retrieval.

## Features Implemented:
- **Login Page**
- **New Registration Page**
- **Search Bar**
  - Displays user info upon click.
- **Main Page**
  - Shows top 12 movies.
  - Clicking on any movie displays:
    - Plot
    - Director
    - Cast
    - Genre
    - Synopsis
    - Duration
    - IMDb rating
    - Release year
- **Sort Options**
  - Sort by year and genre.
- **Wishlist**
  - Save movies of interest.
  - Wishlist persists across sessions, even after logging out.
- **Line Graphs**
  - Displays rating fluctuations over specific periods: 1st day, 1st month, 3 months, 6 months, and 1 year.
- **Creative Mode**
  - Bar graphs show average IMDb ratings for:
    - Actor
    - Actress
    - Director
    - Genre
- **Report Generation**
  - Compare two movies on various metrics.
  - Generate top 5 movies by genre.
  - Generate top 5 movies by year (user-specified).

## Description of Modules and Classes:
Detailed documentation of all modules and classes is provided in the codebase.

## Work Done by Each Member:

### **Harshvardhan Mishra**
#### Objective:
To manage the user interface (UI) design and implement automation for the IMDb project.

#### Key Features:
1. **User Experience Enhancement:**
   - Designed intuitive and visually appealing UI elements to improve user engagement.
   - Conducted user research and usability testing to identify pain points.
   - Implemented responsive design principles for seamless experiences across devices.
2. **Workflow Streamlining:**
   - Analyzed workflows for inefficiencies and bottlenecks.
   - Automated processes to reduce manual intervention.
   - Created documentation and training materials to support new workflows.
3. **Seamless Integration:**
   - Collaborated with cross-functional teams for smooth process integration.
   - Used APIs and tools to streamline data flow.

#### Value Added:
Resulted in a more efficient and user-friendly application, significantly enhancing user satisfaction.

---

### **Divy Dobariya**
#### Objective:
To automate backend processes and manage user data efficiently, ensuring seamless navigation.

#### Key Features:
1. **Backend Automation and User Data Management:**
   - Automated user data storage and retrieval.
   - Implemented secure, organized management systems using databases or file systems.
   - Enabled dynamic access and updates of user data.
2. **Connecting Pages and Managing Navigation:**
   - Ensured smooth transitions between application pages.
   - Implemented routing mechanisms for efficient navigation.
   - Enhanced user experience with intuitive workflows.

#### Value Added:
Resulted in an efficient, user-friendly application with improved operational efficiency.

---

### **Tejas Kollipara**
#### Objective:
Developed tools to analyze and visualize movie data interactively.

#### Key Features:
1. **Bar Graphs:**
   - Displayed average ratings by genre, actor, actress, and director.
2. **Movie Comparison:**
   - Enabled comparison of two movies on ratings, genre, and other metrics.
3. **Top 5 Movies:**
   - Listed top 5 movies by user-specified year or genre.
4. **Rating Trends:**
   - Used line graphs to track movie rating fluctuations over time.

#### Value Added:
- Simplified complex data visualization.
- Provided interactive tools for personalized analysis.
- Enhanced user insights into movie performance.

---

### **G. Karthikeya**
#### Objective:
To fetch and consolidate detailed movie data using TMDb and OMDb APIs.

#### Work Summary:
1. **API Integration:**
   - Connected to TMDb and OMDb APIs for movie details retrieval.
2. **Data Collected:**
   - Retrieved details such as Director, Plot, Synopsis, Genre, Ratings, Cast, Runtime, Budget, and Collection.
3. **Data Validation:**
   - Ensured accuracy and handled missing fields.
4. **Storage:**
   - Organized data into databases for easy querying and analysis.

#### Value Delivered:
- Centralized, accurate movie data storage.
- Enabled detailed exploration across various metrics.

