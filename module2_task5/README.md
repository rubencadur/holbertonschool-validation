# Holberton DevOps Projects


## Prerequisites

Ubuntu 18.04
GNU Make in version 3.81+
Git (command line) in version 2+
Go Hugo v0.84.0
Docker
A text editor or IDE


## Lifecycle

go-lint: Catch errors without the need to compile or execute the application
check: Check syntaxis and links
lint: Staticly analyse
validate: Validate W3C HTML
go-build: Compile the source code of the application to a binary
hugo-build: Generate the website from the markdown and configuration files in the directory dist/
build: Build the project
run: Run the application in background by executing the binary
stop: Stop the application
go-clean: Stop the application. Delete the binary and the log file:
hugo-clean: Cleanup the content of the directory dist/
clean: Cleanup project
post: Create a new blog post whose filename and title come from the environment variables POST_TITLE and POST_NAME
unit-tests: Run unit tests on web server
integration-tests: Run integration tests on web server
test: Ensure that it behaves as expected
help: Show this help usage
