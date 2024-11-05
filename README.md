# Go Project Setup

scafolds up a quick simple Go project structure with nothing extra included!

## To Use The Template

```bash
npx git-coppy https://github.com/Hussseinkizz/go-project-setup.git your-project-name
```

Replace your-project-name with the directory name where you want to place the template files or remove it completely to just put into the current directory instead.

## Structure

```bash
your-project-name/
├── bin/                  # Compiled binaries go here (created after build)
├── cmd/
│   └── app/
│       └── main.go       # Main application entry point
├── internals/            # Internal packages (business logic, utilities)
├── tests/                # Test files for unit and integration testing
├── go.mod                # Go module file for dependency management
├── Makefile              # Build, test, and cleanup commands
└── README.md             # Project documentation
```

## That's it

And this is work in progress, so feel free to hit me up <hssnkizz@gmail.com> we dicuss anything you might have or just add it and make a PR!
