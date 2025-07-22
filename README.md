# Create a project folder and navigate to it
mkdir handling-missing-data
cd handling-missing-data

# Move the notebook file into this folder
# (Adjust the path if needed)
mv /path/to/handling_missing_data.ipynb .

# Initialize git and push to GitHub
git init
git remote add origin https://github.com/YOUR_USERNAME/handling-missing-data.git
git add .
git commit -m "Initial commit: Added notebook on handling missing data"
git branch -M main
git push -u origin main
