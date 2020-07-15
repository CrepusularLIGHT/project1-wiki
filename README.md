# Project 1 - Wiki
 Wikipedia-like online encyclopedia

***SCREENCAST:*** https://youtu.be/eZqhbRnmKuQ

**Python files:**
  * _manage.py_
    - main application to run server 
  * **wiki**
    - _\_\_init.py\_\__
    - _asgi.py_
    - _settings.py_
    - _urls.py_
    - _wsgi.py_
   * **encyclopedia**
     - _\_\_init.py\_\__
     - _admin.py_
     - _apps.py_
     - _modles.py_
     - _tests.py_
     - _urls.py_
     - _util.py_
     - _views.py_
    
**HTML files:** (located in folder > encyclopedia/templates/encyclopedia)
  * _layout.html_
    - Basic layout for rest of pages extend
  * _index.html_
    - Main page with list of all entries 
  * _entry.html_
    - Content for an entry
  * _search.html_
    - Shows entries for a search query
  * _create.html_
    - Shows forms to create a new entry/page
  * _edit.html_
    - Shows forms to edit a entry/page
  * _error.html_
    - Displays error for page that doesn't exist
    
**CSS file:** (located in folder > encyclopedia/static/encyclopedia)
  * _style.css_
     
      
### Overview:
Wikipedia like website that consists of entries on various topics. All entries are listed at the homepage (_index.html_). Clicking on an entry will bring you to the entry page, with the url of the ENTRY as: `/wiki/ENTRY`. Going to a page that does not exist will bring the user to an error page saying that the webpage does not exist (_error.html_). A user can create a new page for an entry that is not in the list of entries `/create` (_create.html_), or they can also edit an existing entry `/wiki/ENTRY/edit` (_edit.html_). Users can use markdown to style their entries. A user can search through the list of entries by using the text box in the side pannel `/search/` (_search.html_). 
