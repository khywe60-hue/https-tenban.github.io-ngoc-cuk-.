from time import sleep

def printLyrics():
lines = [
("Ngọc cuk", 0.0566),
("Ngọc cún", 0.0566),
("Ngọc thối", 0.0566),
("Ngọc kid", 0.0566),
("Ngọc cuto", 0.0566),
("Ngọc gay", 0.0566),
("Ngọc less", 0.0566),
("Ngọc gà", 0.0566),
("Ngọc non", 0.0566),
("Ngọc warui", 0.0566),
("Ngọc bad", 0.0566),
("Ngọc ko xinh", 0.0566),
("Ngọc gì đó", 0.0566),
("Ngọc ........", 0.0566),
("Ngọc mái ngố", 0.039),
("Cảm ơn bạn ngọc đã xem hết mình nấu xói ngọc ", 0.039),
]

for line, delay in lines:
for char in line:
print(char, end="", flush=True)
sleep(delay)
print()

printLyrics()
