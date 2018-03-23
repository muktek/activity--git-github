# Activity - Git + Github

For this activity, you are going to practice integrating a git workflow into 2 sample projects **Gallery X** and **Tables for Days**

### Instructions

(1) Setup the directory + download/ install project files

```sh
# (1) navigate to warmups and create directory

cd ~/muktek/warmups
mkdir activity--git-github
cd activity--git-github

# (1) download project files w/ curl
curl https://raw.githubusercontent.com/muktek/activity--git-github/master/github-activity.zip >  github-activity.zip

# (2) Unzip
unzip github-activity.zip
```

(2) Follow the instructions as indicated below.


### Gallery X

1. Create a new gitepo in the `gallery-x` directory.

2. Add to staging and make initial commit.

2. Create a repository on github called _gallery-x_.

3. Connect the remote link to your local repository.

4. Push your the gallery-x directory.

5. Put the following tags in the `<head>` element:

  ```html
  <link rel="stylesheet" href="./css/styles.css"/>

  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  ```

6. Make a new commit with the title 'fixing head tags'  

7. Push the commit to git hub.


### Tables 4 Days

1. Create a new git repo in the `tables-for-days` directory.

2. Add to staging and make initial commit.

2. Create a repository on github called _tables-for-days_.

3. Connect the remote link to your local repository.
  ```
  git remote add origin remote-link-to repo»
  ```

4. Connect the remote link to your local repository.

5. Put the following tags in the `<head>` element:

  ```html
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/skeleton/2.0.4/skeleton.min.css"/>

  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  ```

6. Make a new commit with the title 'adding CSS library'.

7. Push your commit to github.

8. Add a new row in the `<table>`'s `<tbody>` element with the following data. **First:** _Lisa_, **Last:** _Ibarra_, **Score:** _91_.
  - _Note_ the `<tr>` format.

9. Make a new commit with the title 'adding data to table'.

10. Push the commit to github.
