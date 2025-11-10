# Project Template (R)

This git repository is a template that should be used as the default structure for new projects. It was adapted from [NHSE template](https://github.com/nhsengland/nhse-repository-template/tree/main) and [BSOL template](https://github.com/Birmingham-and-Solihull-ICS/BSOLproject) . It won't fit all circumstances perfectly, and you can adapt it to your needs and make a pull request if you want to suggest changes to the template.

The aim of this template is two-fold: firstly to give a common structure for analytical projects to aid
reproducibility, secondly to allow for additional security settings as default to prevent accidental upload of files that should not be committed to Git and GitHub.

## To use this template, please use the following practises:

* Put any data files (if using) in the `data` folder.  This folder is explicitly named in the .gitignore file.  A further layer of security is that all xls, xlsx, csv and pdf files are also explicit ignored in the whole folder as well.  ___If you need to commit one of these files, you must use the `-f` (force) command in `commit`, or specify the file as an exception in the .gitignore but you must be sure there is no identifiable data.__
* Adapt the .gitignore to suit your needs - it will not necessarily cover everything you need.
* Save any documentation or outputs (data tables, visulaisations, presentations, models, documents) which need backing up to a folder on the shared drive (put the folder location in the README). These may often contain sensitive info and saving them to the shared drive means they are backed up, but not pushed to github.
* Change the codeowners file (in .github folder) so you are the codeowner.
* Add a branch protection rule for your main branch and watch the repo so you are made aware of any changes.

### Please also consider the following:
* Linting your code.  This is a formatting process that follows a rule set.  We broadly encourage the tidyverse standard, and recommend the `lintr` package.
* Comment your code to make sure others can follow.
* Consider your naming conventions: we recommend `snake case` where spaces are replaced by underscores and no capitals are use. E.g. `outpatient_referral_data`
* Use the open code checklist to remind yourself of what is appropriate for pushing to GitHub
* If your project is a model, use the model card (based on google documentation), if project is not a model you can delete the model card.

__Please update/replace this README file with one relevant to your project__

# Project Name

### Status
This project is currently work in progress / completed / being maintained / not being maintained

Unless otherwise specified the CODEOWNER has responsibility for maintaining the code and addressing any security concerns.

### About the project
Short description and purpose / objectives of the project

Link to any refereneces / publications

Note: Only public or dummy data are shared in this repository

### Project Structure

* The main code is found in the root of the repo
* Any notes which may be helpful

### Built with
List of R / python versions and packages or if these are captured in a requirements file

### Outputs
If not already described.

### Contributing
Contributions and identification of issues are welcomed. Please raise any security concerns as an issue.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/Feature`)
3. Commit your Changes (`git commit -m 'Add some Feature'`)
4. Push to the Branch (`git push origin feature/Feature`)
5. Open a Pull Request

### License
Unless stated otherwise, the codebase is released under the MIT Licence. This covers both the codebase and any sample code in the documentation.

See LICENSE for more information.
