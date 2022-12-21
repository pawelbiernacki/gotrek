

SUBDIRS = chomik font generated generators image scripts sdl_chomik tests


size:
	@find . -name "*.chomik" -o -name "*.sdl_chomik" -exec cat {} \; | wc
	
generated-code:
	@cd generators && $(MAKE) generated-code
