# Organization Naming Conventions  

To maintain consistency across our repositories, files, and other assets, we follow a set of standardized naming conventions. These guidelines help ensure clarity, readability, and ease of use across projects.  

## Repository Names  

- **Use lowercase letters**  
- **Separate words with hyphens (`-`) instead of underscores (`_`)**  
- **Avoid special characters** (except `-`)  
- **Keep names concise and descriptive**  

**Why hyphens instead of underscores?**  
- Hyphens improve readability in URLs (`github.com/org/repo-name` vs. `github.com/org/repo_name`).  
- Underscores can be hidden when links are underlined.  
- Many command-line tools and package names use hyphens (e.g., `django-rest-framework`).  

### Examples  

✅ `fastapi-service`  
✅ `data-pipeline`  
❌ `fastapi_service` (avoid underscores)  
❌ `DataPipeline` (avoid camel case)  

## Python Module and Package Names  

- **Use lowercase letters**  
- **Use underscores (`_`) instead of hyphens (`-`)**  
- **Avoid special characters**  

📌 Python modules must follow this rule because hyphens are not allowed in importable module names.  

### Examples  

✅ `data_processing.py`  
✅ `my_project/utils.py`  
❌ `data-processing.py` (invalid module name)  

## Branch Names  

- **Use lowercase letters**  
- **Use hyphens (`-`) to separate words**  
- **Include a ticket number when applicable**  

### Examples  

✅ `feature/add-api-authentication`  
✅ `bugfix/fix-database-timeout`  
❌ `feature_add_api_authentication` (avoid underscores)  

## File and Directory Names  

- **Use lowercase letters**  
- **Use hyphens (`-`) for general files and directories**  
- **Use underscores (`_`) for Python modules**  
- **Use uppercase letters and/or underscores in special situations**
  - Follow  conventions when they are obvious; e.g. adding a file to a directory where all files are uppercase
  - A good example this file in the *.github* repository!

### Examples  

✅ `deployment-scripts/` (directory)  
✅ `database-migrations/` (directory)  
✅ `config_loader.py` (Python module)  
❌ `DeploymentScripts/` (avoid capital letters)  

## Environment Variables  

- **Use uppercase letters**  
- **Separate words with underscores (`_`)**  

### Examples  

✅ `DATABASE_URL`  
✅ `API_SECRET_KEY`  
❌ `database-url` (hyphens are not valid in env variables)  

---  

By following these conventions, we maintain consistency and make collaboration across projects easier. If you have suggestions or exceptions to propose, please open a discussion in this repository.  
