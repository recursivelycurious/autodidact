.PHONY:	all hello penv diskfree tidy override

FOO ?= $(BAR)

all:
	@printf "available targets:\n"
	@printf "  hello: prints hello world\n"
	@printf "  diskfree: outputs free space on disk.\n"
	@printf "  tidy: remove files matching `*.tmp`"

hello:
	@echo hello world

penv:
	env

diskfree:; df -h /

tidy:
	-rm *.tmp

override:
	@echo "FOO is $(FOO)"
	@echo "BAR is $(BAR)"