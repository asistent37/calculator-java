Calculator.java, License, Start.java: LOC = 235;

Calculator.java (Cyclomatic Complexity):
Calculator::Operations::Operations - 1; (extremely low risk);
Calculator::Operations::ToString - 1; (extremely low risk);
Calculator::Run - 1; (extremely low risk);
Calculator::evaluateExpression - 12!; (lower risk);
Calculator::Calculate -12!; (lower risk);

Calculator.java (Cognitive Complexity):

Start.java (Cyclomatic Complexity):
Start::main - 3; (extremely low risk);

Start.java (Cognitive Complexity):

Calculator.java (Static analiysis):
Calculator.java - 1 - import - Move this file to a named package;
Calculator.java - 4- Calculator - Add a private constructor to hide the implicit public one;
Calculator.java - 18 - ToString - Rename method "ToString" to prevent any misunderstanding with method "tostring" defined in superclass "java.lang.Object";
Calculator.java - 24 - Run - Rename this method name to match the regular expression;
Calculator.java - 70 - Float.toString - Return this expression instead of assigning it to the temporary variable "tekstResult";
Calculator.java - 74 - Calculate - Rename this method name to match the regular expression;
Calculator.java - 183 - return - Remove this redundant jump;

Start.java (Static analysis):
Start.java - 1 - import - Move this file to a named package;
Start.java - 6 - Expression - Rename this local variable to match the regular expression;
Start.java - 8 - System.out - Replace this use of System.out by a logger;
Start.java - 19 - System.out - Replace this use of System.out by a logger;
