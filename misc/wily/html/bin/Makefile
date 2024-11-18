SHELL=/bin/sh

html  = h1 h2 h3 h4 h5 h6 title pre cite code em kbd samp strong var tt dfn
html1 = bold italic underline

install:
	- for file in $(html) ; do \
		rm -f $$file ; \
		ln -s html $$file ; \
	done

	- for file in $(html1) ; do \
		rm -f $$file ; \
		ln -s html1 $$file ; \
	done

clean:
	rm -f $(html) $(html1)
