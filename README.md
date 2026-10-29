# match_case_problem
Arithmetic Operation Using match case operation
M = int(input("Enter the number one: "))
operator = input("Enter the operator: ")
N = int(input("Enter the number two: "))
calculation = M , operator, N

match calculation:
      case "+":
          print(M + N)
      case "-":
          print(M - N)
      case _:
          print("Invalid")
