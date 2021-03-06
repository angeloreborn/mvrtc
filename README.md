# Model View Realtime Controller Framework
## Introduction 
MVRTC is a web framework built on .NET 5 aiming to provide a rich and dynamic real time experience for users and developers. 

## Features and support
The list of intended `features` and `support` for the framework

**Backend**
- CS to TS transcompilation support for models and controllers
- Designed for distributed event-driven architecture
- MVC templating engine
- Integrated api support for controllers

**Frontend**
- React as Typescript (Standard)
- React Router Dom (Standard)
- CS to TS transcompilation support for views with model binding

**General**
- E2E Encyrpted 
- Realtime experience
- Hot reload for frontend
- Real Time Socket manager
- Cache hydration 
- Single session only

# CLI Documentation
## MIT Licence Agreement
On first launch, user is required to accept the MIT liscence agreement.
## Command Interface 
### Directory Navigation 

| Command | Description |
| --- | --- |
| `cd [DIRECTORY]` | Changes the target working directory.
| `cdd [FOLDER]` | Moves into folder within the working directory .
| `cdu` | Moves 1 layer up directory tree.
| `d save [NAME]` | Saves working directory by name.
| `d load [NAME]` | Opens available working directory. (Pipes using `cd`).
| `d clear [Name]` | Clears saved working directory.
| `d list` | Lists files and folders in working directory.
| `d list folders` | Lists folders in working directory.
| `d list files` | Lists files in working directory.
| `d search [name]` | Searches directory for files or folders 



### Project Creation 
- `create project [PROJECT_NAME] [OPTIONS]` - Creates a project 
#### Create Project Options 
- `-styling [CSS/SCSS/CSLINT]` - Sets styling template.
- `-output [DIRECTORY]` - Build project in specified directory.
### Project Maintanance
- `project list` - Lists created projects.
- `project [NAME]` - Lists details of existing project.
- `project select [NAME]` - Marks project as active. (Automount)
#### Selected Project Commands
- `commit [MESSAGE]` - Starts version control commit
- `revert` - Reverts to older version. (Requires version history) 
- `delete` - Deletes project
- `rename [NAME]` - Renames project

### Project Mounting
- `mount all` - Mounts all unmounted projects
- `unmount all` - Unmounts all projects
- `mount [NAME]` - Mounts specific project
- `remount` - Remounts all mounted projects

# Transcompilation 
## Creating models
Transcompilation model support 
- Nested
- Inherited 

# Templating Engine

# E2E Encyrption 

# Realtime Socket Manager

# Cache Hydration 

# Single Session Only 


