## -----------------------------------------------------------------------------
## Make targets to test Ansible deployments locally.
## -----------------------------------------------------------------------------

# Avoid name collisions between targets and files.
.PHONY: help test converge clean all

# A target to format and present all supported targets with their descriptions.
help : Makefile
		@sed -n 's/^##//p' $<

## test: 		Run Molecule test on an existing role.
test:
	molecule test

## converge: 	Build and test an existing role.
converge: 
	molecule converge

## clean: 	Clean up after testing the role.
clean:	
	molecule destroy

## all:		Run the entire molecule cycle (test, converge, and clean).
all: build test clean
