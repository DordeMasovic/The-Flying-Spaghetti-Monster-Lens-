all: Dual.class FigDeck.class InputField.class Console.class Misc.class Dialogs.class ErrorMsg.class

Dual.class: Dual.java
	$(JAVAC) Dual.java

Dual.java: Dual.w
	javatangle Dual.w

FigDeck.class: FigDeck.java Figure.class
	$(JAVAC) FigDeck.java

Figure.class: Figure.java FigBase.java Mesh.java
	$(JAVAC) Figure.java

FigDeck.java: FigDeck.w
	javatangle FigDeck.w

Figure.java: Figure.w
	javatangle Figure.w

FigBase.java: FigBase.w
	javatangle FigBase.w

Mesh.java: Mesh.w
	javatangle Mesh.w

ErrorMsg.class: ErrorMsg.java
	$(JAVAC) ErrorMsg.java

ErrorMsg.java: ErrorMsg.w
	javatangle ErrorMsg.w

Dialogs.class: Dialogs.java
	$(JAVAC) Dialogs.java

Dialogs.java: Dialogs.w
	javatangle Dialogs.w

InputField.class: InputField.java
	$(JAVAC) InputField.java

InputField.java: InputField.w
	javatangle InputField.w

Console.class: Console.java
	$(JAVAC) Console.java

Console.java: Console.w
	javatangle Console.w

Misc.class: Misc.java
	$(JAVAC) Misc.java

Misc.java: Misc.w
	javatangle Misc.w

