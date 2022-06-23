.PHONY: notebook docs
.EXPORT_ALL_VARIABLES:

install: 
	@echo "Installing..."
	poetry install
	poetry run pre-commit install


activate:
	@echo "Activating virtual environment"
	poetry shell

initialize_git:
	git init 


setup: initialize_git install activate
