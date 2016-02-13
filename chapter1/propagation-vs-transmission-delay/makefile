NAME=LineSimApplet

all: $(NAME).class

$(NAME).class: $(NAME).java
	javac $(NAME).java

run: $(NAME).class
	appletviewer $(NAME).html

clean: *.class
	rm -r *.class
