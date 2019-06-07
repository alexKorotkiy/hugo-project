# Install Hugo

- You need to install Hugo following instructions [https://gohugo.io/getting-started/installing/](https://gohugo.io/getting-started/installing/)

# Run project

- Using the console go to the project directory
- Execute the command: ***hugo server -d***
- Web Server is available at [http://localhost:1313/](http://localhost:1313/) (bind address 127.0.0.1)

# Build project

- To build a project, you must run the command: ***hugo***
- By default, files to upload to the server will be placed in the **"/public"** directory.
It can be changed in the **config.toml** file. Example:
 publishDir = "docs"
