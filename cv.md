# Emiliya Barkanova

![avatar](https://fatcatart.com/wp-content/uploads/2016/05/Van_Gogh_-_Sunflowers-cat-w.jpg)

## Contacts

- Email: emiliya.barkanova@bk.ru  
- Phone: +79062227083  

## About Me

I am a second-year Software Engineering student at Belarusian–Russian University. I am a beginner in frontend development and I like design and clear interfaces.

I studied in an art school earlier – that helped me to see details and think about how things look and feel.

Now I work as a mathematics tutor assistant in an online school, helping students prepare for the EGE exam. This work helped me to explain difficult things simply and to be patient when teaching.

I want to learn more about web technologies, practice front-end development and build simple projects to show my progress.

## Skills

### Programming Languages
- `Python`
- `C#`
- `C++` (basic)

### Tools & Technologies
- `Multisim`
- `PostgreSQL`
- `Excel`
- `Figma`

### Other Skills
- Algorithmic thinking  
- Mathematical problem-solving  
- Technical research

## Code Example

```python
n, s, f = map(int, input().split())
mas = []
s -= 1
f -= 1
for i in range(n):
    mas.append([int(i) for i in input().split()])
u = [0] * n
v = [999999] * n
v[s] = 0

for i in range(n):
    min = 999999
    ind = 0
    for j in range(n):
        if v[j] < min and u[j] == 0:
            min = v[j]
            ind = j
    for j in range(n):
        if mas[ind][j] > 0:
            if v[ind] + mas[ind][j] < v[j]:
                v[j] = v[ind] + mas[ind][j]
    u[ind] = 1
if v[f] == 999999:
    print(-1)
else:
    print(v[f])
```

---

## Experience

### Mathematics Curator – Online School  
*2024 – Present*

- Assisted students in preparing for the EGE mathematics exam  
- Explained solutions and checked assignments  
- Developed structured approaches to learning  

### Computer Club Staff  
*2023*

- Assisted visitors  
- Helped with basic technical issues  
- Improved communication skills  

## Education

Belarusian–Russian University  
Software Engineering Student  

## English

Level: Pre-Intermediate (A2–B1)
