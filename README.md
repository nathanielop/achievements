# achievements
A collection of shell scripts to achieve 100% of API-accessible Github achievements

## Prerequisites
- `gh` Github CLI Installed
- `gh auth login` Must be ran and completed successfully

## Instructions

### Setup

In order to run the scripts this repository provides, one must first setup a local version of this repository. In order to do this, one should first fork [the main repository](https://github.com/nathanielop/achievements) on github.

After forking the repository, go into your terminal and run the following series of commands.

```
mkdir achievements
cd achievements
git init
git remote add origin git@github.com:[YOUR USERNAME HERE]/achievements.git
```

| Warning: The commands above rely on your git already being setup with your github account, if you haven't done this already then follow the guide [here](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/about-ssh) |
| --- |

### Running Achievement Scripts

Gain any individual achievement by running the name of that achievement directly;

#### Example
`bash pullshark`

Or, to gain all achievements, simply run `bash all`

| Warning: This process can take upwards of several hours in order to not result in a rate limit from the API. It is recommended to let this script run in the background. |
| --- |