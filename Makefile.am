

SUBDIRS = chomik font generated generators image scripts sdl_chomik tests


size:
	@find . -name "*.*chomik" -exec cat {} \; | wc
	
generated-code-1:
	@cd generators && $(MAKE) generated-code-1
	
generated-code-2:
	@cd generators && $(MAKE) generated-code-2	

generated-code-correctness:
	@cd generators && $(MAKE) generated-code-correctness
	
	
generated-code: generated-code-1 generated-code-2 generated-code-correctness
