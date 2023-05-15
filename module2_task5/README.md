# Holberton DevOps Projects


## Prerequisites

Ubuntu 18.04
GNU Make in version 3.81+
Git (command line) in version 2+
Go Hugo v0.84.0
Docker
A text editor or IDE


## Lifecycle

build: Build the project
go-build: Compile the source code of the application to a binary
hugo-build: Generate the website from the markdown and configuration files in the directory dist/
run: Run the application in background by executing the binary
post: Create a new blog post whose filename and title come from the environment variables POST_TITLE and POST_NAME
stop: Stop the application
clean: Cleanup project
hugo-clean: Cleanup the content of the directory dist/
go-clean: Stop the application. Delete the binary and the log file:
check: Check syntaxis and links
go-lint: Catch errors without the need to compile or execute the application
validate: Validate W3C HTML
lint: Staticly analyse the app source code and markdown files
test: Ensure that it behaves as expected
unit-tests: Run unit tests on web server
integration-tests: Run integration tests on web server
help: Show this help usage
