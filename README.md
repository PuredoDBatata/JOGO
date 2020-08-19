correct = 0
questao = 2

print("Welcome to the quiz game!")
print("Responda com 'a' ou 'b'\n")

# ---- question 1 ----
print("1) atacar no inverno?")
print("""a. nop
b. yep
""")
answer = input(">")

if answer == "a":
  correct += 1


  
print("")

# ---- question 2 ----
print("2) usar armas ou espadas")
print("""a. arma de fogo
b. espada""")

answer = input(">")

if answer == "a":
  correct += 1
  
  
print("")

# ---- end ----
score = round(correct/questao*100)
str(score)
print("good")
print("acertou {}%.".format(score))

if score > 50:
    print("ganho")
else:
    print("perdeu")
