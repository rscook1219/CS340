# CS340


### Functionality
This program offers three primary functions. Firstly, it utilizes radial buttons to categorize data according to breed, age, and gender traits for various types of rescue dogs sought by Grazioso Salvare. Upon selecting any radial button, the application executes database queries and presents an updated data frame reflecting the desired criteria. The "Reset" radial button restores the table to its original, unfiltered state. The second function involves mapping and real-time updates. It initially displays a map pinpointing the location of the first entry in the data frame. As users choose rows, the map adjusts the marker to reflect the selected item. The third function generates a dynamic pie chart by sorting the data by breed and producing a chart based on the current data frame (excluding the entire database) showcasing the distribution of animal breeds.


### Dashboard Overview/Reset filters 

 ![image](https://github.com/rscook1219/CS340/assets/117030820/071a3004-bbbe-48ec-908f-c62de74f0755)

![image](https://github.com/rscook1219/CS340/assets/117030820/678c9998-2ad5-43fe-8b17-c717829c6406)




### Water Rescue Filter
 ![image](https://github.com/rscook1219/CS340/assets/117030820/47b64eb7-6fd4-46be-a77b-bf62fee5a20f)
 
 ![image](https://github.com/rscook1219/CS340/assets/117030820/9c887d1f-5c6d-4082-a1a3-fa0bc2eaea70)

 

### Disaster Rescue Filter
![image](https://github.com/rscook1219/CS340/assets/117030820/fd1ae04f-03bd-49b6-aca2-05d4b3afd22e)

![image](https://github.com/rscook1219/CS340/assets/117030820/99a2dae2-1889-4163-81aa-83f98ef0a4a8)


  

### Mountain or Wilderness Rescue Filter
![image](https://github.com/rscook1219/CS340/assets/117030820/701c2dd3-e470-4988-9b40-b1fe83f63885)

![image](https://github.com/rscook1219/CS340/assets/117030820/6293470f-0c1b-4b4e-ab16-39618a0363f5)


 
 

  
### Tools
The tools used are as follows:
- Python – Download Python from this link: https://realpython.com/installing-python/.
-	Jupyter Notebooks - To install follow this link https://jupyter.org/install.
-	MongoDB – Use this link to find download and installation instructions: https://docs.mongodb.com/manual/installation/.
-	Plotly – Plotly needs to be imported to get correct charts for Python. Local copy of it can be found here: https://plotly.com/python/getting-started/
-	Dash – This is used to build web applications. Install dash by following this link: https://pypi.org/project/dash/
-	Pandas – This is used in the web application as well. This is used to create data frames in Python. Install it here: https://pandas.pydata.org/pandas-docs/stable/getting_started/install.html

### Motivation
Mongo was chosen for this program due to its ability to swiftly set up the database using a CSV document and its compatibility with Python. While Python can interact with SQL databases, transitioning between the syntax of SQL and Python can be inconvenient. The querying tools for executing basic CRUD functions in SQL databases tend to be more intricate compared to those in MongoDB when utilized with Python.
The choice of Dash for constructing the dashboard stemmed from its dynamic capabilities. Dash, built on React JavaScript, offers a highly responsive framework. It employs HTML Dash tags to manage outputs to different segments. Subsequently, updates to specified target inputs within the app are processed according to instructions outlined in the Python module.

### Steps Taken
-	Database Configuration: Implemented CRUD operations in Python to interact with MongoDB.
-	Dashboard Creation:
    - Constructed an interactive data table showcasing shelter animal information.
    - Designed filter functionalities catering to Water Rescue, Mountain or Wilderness Rescue, and Disaster Rescue.
    - Integrated widgets for dynamic data visualization, such as a geolocation chart and supplementary chart options.
-	Testing and Deployment:
    - Conducted thorough testing to verify the dashboard's functionality.
    - Locally deployed the dashboard to facilitate user interaction.
    - Generated screenshots illustrating different states of the dashboard for demonstration purposes.

### Challenges
Some of the challenges I faced were the implementation of the dynamic pie chart to display different values according to the filter selected. The next was creating a single function to update the dashboard and map and not create duplicate callback errors. I did not seem to run into too many challenges along the way just small road bumps. 

## Questiuons
1. How do you write programs that are maintainable, readable, and adaptable? Especially consider your work on the CRUD Python module from Project One, which you used to connect the dashboard widgets to the database in Project Two. What were the advantages of working in this way? How else could you use this CRUD Python module in the future?
   - To ensure programs are maintainable, readable, and adaptable, adhering to coding best practices such as meaningful variable names, modularization, and documentation is crucial. Integrating the CRUD Python module in Project Two streamlines connecting dashboard widgets to the database, reducing redundancy and improving code readability. This approach makes future modifications easier and enables reuse of the CRUD module for similar projects with different dashboard interfaces or databases.
2. How do you approach a problem as a computer scientist? Consider how you approached the database or dashboard requirements that Grazioso Salvare requested. How did your approach to this project differ from previous assignments in other courses? What techniques or strategies would you use in the future to create databases to meet other client requests?
   - As a computer scientist, problem-solving involves breaking down tasks, understanding requirements thoroughly, and selecting appropriate tools and technologies. For Grazioso Salvare's database and dashboard requirements, careful planning and integration of technologies like MongoDB, Dash, and Plotly were essential. This project differed from previous assignments by requiring integration of various technologies to create a dynamic dashboard. Agile methodologies, prototyping, and user feedback loops could be employed in the future to meet different client requests for database solutions.
3. What do computer scientists do, and why does it matter? How would your work on this type of project help a company, like Grazioso Salvare, to do their work better?
   - Computer scientists solve problems using computational techniques, algorithms, and software development methodologies, enabling businesses like Grazioso Salvare to streamline operations and make data-driven decisions. Developing tools and systems that facilitate data management, visualization, and analysis, computer scientists play a crucial role in optimizing rescue efforts or resource allocation for different types of missions. By creating dashboards with features like filter functionalities and dynamic visualizations, companies can better understand their data, identify trends, and make informed decisions to improve operations.


