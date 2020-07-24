# Bash React CLI

A simple wrapper around create-react-app to adjust the app to my workflow by adding **redux** , **react router** , **Sass**, **Axios**, **typescript** and a specific folder structure.\
you also have commands to add class or functional components. use `brc` command to get started.

**Opinionated !!**\
this script was created to fit my own workflow and is highly opinionanted ... feel free to fork it !

## Dependencies
nodejs\
yarn\
gnu sed

## Options
`init <project name>` : start a new project with a specific configuration\
`gc <component name>` : generate class component with a sass stylesheet\
`gf <component name>` : generate class component with a sass stylesheet\

## Files
**brc :** The script itself which will be copied to your */usr/bin* directory\
**install :** You need to use `sudo` because it adds the script to */usr/bin* directory to be globally available in the CLI\
**uninstall :** Same story. It simply deletes the script from your */usr/bin* directory
