# Run Molecule tests
test: 
	molecule test

# Run Ansible playbook
deploy:
	ansible-playbook ../playbook.yml

# Build and test the role
build: 
	molecule converge

# Clean up after testing the role
clean: 
	molecule destroy

# Run the full test cycle (build, test, and clean)
test-cycle: build test clean
