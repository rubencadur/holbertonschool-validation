build:  ## Generate the website from the markdown and configuration files in the directory dist/ 
	@hugo

clean:  ## Cleanup the content of the directory dist/
	@rm -Rf dist/

post:   ## Create a new blog post whose filename and title come from the environment variables POST_TITLE and POST_NAME
	@rm -Rf content/posts/$(POST_NAME).md
	@hugo new posts/$(POST_NAME).md
	@sed -i 's/title:.*/title: $(POST_TITLE)/' content/posts/$(POST_NAME).md
	@sed -i 's/draft:.*/draft: "false"/' content/posts/$(POST_NAME).md

help:   ## Show this help usage
	@cat Makefile | grep "##" | tr -d "##" | head -n -1
