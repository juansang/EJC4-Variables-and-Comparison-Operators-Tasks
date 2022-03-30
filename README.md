# EJC4-Variables-and-Comparison-Operators-Tasks

## Task 1
#### Assign a variable with each datatypes covered in theprevious workshop
En en el ejercicio de clase anterior, disponimaos de un booleano False, un String "Primer string" y un entero 3423
```
$BoolanVar=$False
$StringVar = "Primer string"
$IntVar=3423
```
<img width="370" alt="2022-03-30 (34)" src="https://user-images.githubusercontent.com/91699247/160934206-f1d1f260-568f-4e42-939e-ca3ba9a2ab08.png">


## Task 2

#### List all variables currently loaded in to memory
```
Get-Variable
```
<img width="634" alt="2022-03-30 (35)" src="https://user-images.githubusercontent.com/91699247/160934701-a4b61c88-6d83-4e36-8850-2a29a947284e.png">
<img width="668" alt="2022-03-30 (36)" src="https://user-images.githubusercontent.com/91699247/160934706-8bc57174-efd0-42a1-b128-349d818d72ee.png">


## Task 3
#### Multiple two Int variables together
Primero crearemos dos variables que correspondan a los numeros enteros y seguidamente, llevaremos a cabo la multiplicación
```
$IntVar1=30
$IntVar2=120
$IntVar1*$IntVar2
```
<img width="185" alt="2022-03-30 (37)" src="https://user-images.githubusercontent.com/91699247/160935151-b10c8c6f-323d-46e6-b835-fa0d27a4b82d.png">


## Task 4
#### First declare two Int variables. Then divided the first variable by the second and assign the result to a variable named $VariableResult
Primero declaramos las dos variables `` $IntVar3=125 $IntVar4=25`` y posteriormente guardamos el resultado de la division en una nueva variable 
```
$IntVarResultado=$IntVar3/$IntVar4
```
<img width="268" alt="2022-03-30 (38)" src="https://user-images.githubusercontent.com/91699247/160936089-f6a02683-f12f-446b-8cc2-99972cb6aba4.png">


## Task 5
#### Typecast a Variable as a “String” and assign it a value of 5
```
[String]$TypecastVar = 5
```
<img width="220" alt="2022-03-30 (39)" src="https://user-images.githubusercontent.com/91699247/160936423-56d5ed8b-bf7e-448a-9225-04998162ab3e.png">


