info = '''This is a code to simulate collatz conjecture.
Enter 0 or anything other than positive numbers to kill this program.
'''

def collatz(n):
  assert type(n) == int
  assert n > 0
  if n % 2 == 0:
    n = int(n/2)
  elif n != 1:
    n = int((n*3+1)/2)
  else:
    return 1
  return n

while True:
  print(info)
  n = int(input("Enter an interger (a poistive number): "))
  try:
    while n != 1:
      n = collatz(n)
      print(n)
    print("=== Simulation End ===\n")
  except:
    print(f'Invalid input: {n}\nProgram has been shut down')
    break
