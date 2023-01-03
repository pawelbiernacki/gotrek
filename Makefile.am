

SUBDIRS = chomik font generated generators image scripts sdl_chomik tests


size:
	@find . -name "*.chomik" -o -name "*.sdl_chomik" -exec cat {} \; | wc
	
generated-code-1:
	@cd generators && $(MAKE) generated-code-1
	
generated-code-2:
	@cd generators && $(MAKE) generated-code-2
	

generated-code: generated-code-1 generated-code-2
