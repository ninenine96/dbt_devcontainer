# Dev Container for using DBT locally
#### This dev container is comprised of all the dependencies and requirements pre-installed so you can quickly get started with DBT.

# Steps to use:
1. Install the Dev Containers extension on your VSCode 
	`ms-vscode-remote.remote-containers`

2. Clone the repository to your local system
	`git clone https://github.com/ninenine96/dbt_devcontainer.git`

3. Run docker desktop

4. Open the folder in VSCode, it should prompt you to reopen the folder in a dev container. If it doesn't then press F1 and just type 'reopen folder in a dev container'.
5. Edit the profile in .dbt/profile.yml and add your credentials.
6. Run the following command
`cp .dbt/profile.yml /home/vscode/.dbt/profile.yml`
7. You can create a dbt_project.yml file and start creating your models.