# DYNOSOB-talks
A repository that contains presentation slides and posters of the group.

Each member has a corresponding folder named after their initials.

## How to clone the repository

To clone the repository to your computer you need to open a terminal, navigate
to the location you want to the project, and run the following command:

```shell
git clone git@github.com:DYNOSOBs/DYNOSOB-talks.git
```

You can also download the project using the download button on the top right corner.

## How to include slides/poster

To include your presentation slides/poster create a folder in your folder and
use the convention `Type-YY-MM-DD-short-title`, for example
`TK-2021-06-17-cooperation-with-limited-memory-payoffs`. `TK` stands for talk
and `PST` for poster.

In the folder include at least the `pdf` of the slides/poster.
Ideally, include all the files necessary to compile the document.

## How to update the repository using git

Before you start working make sure your copy is up to date. Command:

```shell
git pull origin master
```

Once you changed a file you need to prepare them for a commit using the command `add`:

```shell
git add NG/TK-2021-06-17-cooperation-with-limited-memory-payoffs
```

To commit:

```shell
git commit -m "Your message"
```

or just

```shell
git commit
```

which will open up an editor for you to write your commit.

Once everything is committed push your changes to `GitHub` using the command:

```shell
git push origin main
```