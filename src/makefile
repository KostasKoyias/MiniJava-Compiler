all: 
	java -jar ../jtb132di.jar minijava.jj 
	java -jar ../javacc5.jar minijava-jtb.jj 
	rm -rf ../build
	mkdir ../build
	javac Main.java -d ../build -Xlint:unchecked

clean:
	rm -rf ../build/* *Parse* syntaxtree visitor *Token* minijava-jtb.jj JavaCharStream.java *.class out*