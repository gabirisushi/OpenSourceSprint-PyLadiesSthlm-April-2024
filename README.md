
# Python Open Source Sprints

## Workshop description
Did you know that open-source software contributes trillions of dollars to the global economy? According to a recent report, the value of open source is staggering -- a whopping $8.8 trillion when considering all indirect benefits!

But here's the catch: while open source creates immense value, the individuals and communities behind it often struggle to receive the support they need. That's why at PyLadies Stockholm, we're passionate about empowering open-source contributors and building sustainable models for the future.

Join us at our upcoming event at the end of the month, where we'll dive deep into the world of open-source contributions. Let's explore how we can support and reward those who make open source thrive, while also fostering innovation and collaboration.

## What are Python Open Source Sprints?
Open-source software, like Python and its various libraries, is created by a collaboration of numerous programmers. People like you dedicate their time to enhancing these tools by adding to documentation, running tests, fixing bugs, and introducing new features. This workshop offers you a fantastic chance to actively participate in improving the Python library you rely on, with guidance along the way.

## Can I participate if I have never contributed to open source?
Sure! If you have some experience with Python, no matter which area of application (e.g. data analysis, web development, machine learning, etc...) you're invited to join us. The workshop will be led by mentors from PyLadies Stockholm and Theodora Tech, who will provide guidance throughout the event.

## Requirements
- GitHub account
- Laptop/Computer

## Open Source Projects
* [scikit-learn](https://scikit-learn.org/stable/) - machine learning in Python
* [transformers](https://huggingface.co/docs/transformers/en/index) - state-of-the-art Machine Learning for Pytorch, TensorFlow, and JAX
* [pandas](https://pandas.pydata.org/) - flexible and powerful data analysis/manipulation library for Python
* [numpy](https://numpy.org/) - the fundamental package for scientific computing with Python
* [dbt-core](https://www.getdbt.com/product/what-is-dbt) - dbt enables data analysts and engineers to transform their data using the same practices that software engineers use to build applications
* [FastAPI](https://fastapi.tiangolo.com/) - high performance, easy to learn, fast to code, ready for production

## Usage
1. Fork the desired project
* Fork the repository (It will duplicate the project in your GitHub account. This lets you modify the code without impacting the original repository.)
* If the forking is successful, it will create a new repo under your account.

2. Clone the project
* You need to clone your forked repo to your local machine to develop the project.
* Run the clone command in your local environment: `git clone <link to repo>`

3. Create a new branch
* Create a new branch to carry out your development. Navigate to the local folder of the cloned repository and use the git checkout command to create a new branch `git checkout -b new-user-contribution`

4. Develop, Stage, and Commit
* In the new branch, you can use your favourite IDE, Text Editor, or any tools to make the necessary changes to the source code.
* Then you need to stage these changes and commit the changes to the repository. Use the "git add ." to add the modified files and then the "git commit" command to commit the changes.

`git add <.\Contributors.md>`
`git commit -m “<Add XYZ to Contributors List>”`

5. Push changes
* The changes you've committed are currently only in your local environment. To update the forked GitHub repository in your account, use the **git push** command.
* The process from **git add**, **git commit** to **git push** is consistent across all development environments and is the standard method for submitting changes to any git repository.

6. Pull request
* If pushing is successful, you should see a message indicating the new push with the "Compare and pull request" button when visiting the GitHub repository. 
* It will generate a pull request targeting the original repository, merging changes from your fork's "new-user-contribution" branch into its master branch.
* It's generally a good practice to leave a comment indicating the changes or the reason for the pull request.
* Click on the "Create pull request" button to create the request. It will navigate the user to the newly created pull request in the original repository.

**If you followed all those steps, you have successfully contributed your changes to an open-source project. However, your changes are still not accepted and merged to the original repository. Your changes need to be first verified by the repository maintainers. They will only be merged into the repository after the maintainers approve the request.** 

## More resources!
* [How to collaborate in Open Source Projects](https://www.pontikis.net/blog/how-to-collaborate-on-github-open-source-projects)
* [Contributing to Open Source as a non-programmer](https://github.com/szabgab/awesome-for-non-programmers)
* [Friendly Open Source Projects for Newbies](https://www.firsttimersonly.com/)


## Credits
This workshop was set up by @pyladiessthlm and [magigarbi](https://github.com/gabirisushi)
