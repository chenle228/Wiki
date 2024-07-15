# Project Wiki

🎉 **Welcome to Project Wiki!** 🎉

Wikipedia is a free online encyclopedia featuring entries on various topics. This project aims to create a similar platform where each entry is stored using Markdown, a lightweight markup language, for easier writing and editing. The Markdown content is converted to HTML for web display.


## Features 🌟 

1. **Entry Page** 
   - View encyclopedia entries by visiting /wiki/TITLE.
   - If the entry doesn't exist, an error page is shown.

2. **Index Page** 
   - Lists all encyclopedia entries.
   - Click on an entry name to view its content.

3. **Search** 
   - Search for entries by name.
   - Matching entries redirect to the entry page, while partial matches show a search results page.

4. **New Page** 
   - Create new encyclopedia entries with a title and Markdown content.
   - Duplicate titles show an error message.
    
5. **Edit Page** 
   - Edit existing entries with pre-populated content in a textarea.
  
6. **Random Page** 
   - View a random encyclopedia entry.
    
3. **Markdown to HTML Conversion** 
   - Convert Markdown content to HTML for display using the python-markdown2 package.


## Tech Stack 🛠️

- **Django**: Web framework used for development.
- **Markdown**: Markup language for writing entries.
- **HTML/CSS**: Frontend technologies for rendering pages.

## Getting Started 🚀

1. **Download the Project**
   - Clone the repository: `git clone https://github.com/yourusername/project-search.git`

2. **Navigate to the project directory and install required packages**
   - cd wiki
   - pip install -r requirements.txt

3. **Run the Django development server**
   - python manage.py runserver

4. **Visit the application**
   - Open your web browser and go to http://127.0.0.1:8000.

