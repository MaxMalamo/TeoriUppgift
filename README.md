Problem:
-----------------
- input1 och 2 tog inte in nummer utan text.(string input1, string input2). Jag fixade det så här (int input1 = Convert.ToInt32(Console.ReadLine());). input1 och 2 är nu nummer och när man skriver in någåt så konverteras det til nummer.
- Räkningarnas variabler var också text(string) istället för nummer(int). Jag fixade dem också.
- Funktionerna hade också string istället för int så jag böt ut t.ex: static string Add(string num1, string num2) till: static int Add(int num1, int num2):
  
