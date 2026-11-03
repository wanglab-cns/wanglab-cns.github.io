
  ![on-push](../../actions/workflows/on-push.yaml/badge.svg)
  ![on-pull-request](../../actions/workflows/on-pull-request.yaml/badge.svg)
  ![on-schedule](../../actions/workflows/on-schedule.yaml/badge.svg)

  # wanglab-cns's Website

  Visit **[wanglab-cns.github.io](https://wanglab-cns.github.io)** 🚀

  ## Running the website locally

  The website is built using [Jekyll](https://jekyllrb.com/) and the [Lab Website Template](https://greene-lab.gitbook.io/lab-website-template-docs). To run the website locally, you need to have Ruby and Bundler installed. Then, you can follow these steps:

  First, clone the repository and navigate to the project directory:

  ```bash
  git clone git@github.com:wanglab-cns/wanglab-cns.github.io.git
  cd wanglab-cns.github.io
  ```

  Please make sure that you have the necessary permissions to access the repository. If you encounter any issues, please contact the repository owner.

  You'll need Ruby and Bundler installed on your system. You can install Bundler by running:

  ```bash
  gem install bundler
  ```

  Then, install the required dependencies. 
  ```bash
  bundle install
  ```

  ## Updating the website

  The website is automatically built and deployed to GitHub Pages whenever changes are pushed to the `main` branch. You can update the website by editing the files in this repository and pushing your changes.

  We recommend using the following workflow for updating the website:

  First, pull the latest changes from the `main` branch to ensure that your local repository is up to date:

  ```bash
  git checkout main
  git pull origin main
  ```

  Create a new branch for your changes.
  ```bash
  git checkout -b feature/<branch-name>
  ```

  Make your changes to the website files, commit them, and push the branch to the remote repository.

  ```bash
  git push origin feature/<branch-name>
  ```

  Finally, create a pull request on GitHub to merge your changes into the `main` branch. Once the pull request is approved and merged, the website will be automatically updated.


  _Built with [Lab Website Template](https://greene-lab.gitbook.io/lab-website-template-docs)_
