## 🤖 other resources: week 3

other practice + info on logic & conditionals and other topics this week:
- **🖥️ in-class code:** [floating point approximation, chars/int](https://cpp.sh/?source=%23include+%3Ciostream%3E%0A%23include+%3Ciomanip%3E%0A%23include+%3Cstring%3E%0Ausing+namespace+std%3B%0A%0Aint+main()+%7B%0A%0A++++%2F%2F+defining+some+doubles%0A++++double+x+%3D+0.3%3B%0A++++double+y+%3D+0.1+%2B+0.1+%2B+0.1%3B%0A%0A++++%2F%2F+basic+if%2Felse+statement%0A++++if+(x+%3D%3D+y)+%7B+%2F%2F+notice+operator+has+2+equal+signs%2C+evaluation%0A++++++++cout+%3C%3C+%22THESE+ARE+EQUAL!%22+%3C%3C+endl%3B%0A++++%7D%0A++++else+%7B%0A++++++++cout+%3C%3C+%22THESE+ARE+NOT+EQUAL!!%22+%3C%3C+endl%3B%0A++++%7D%0A++++%2F*+these+are+not+equal%2C+%0A++++due+to+floating+point+approximation+*%2F%0A%0A++++cout+%3C%3C+fixed+%3C%3C+setprecision(20)%3B+%2F%2F+give+me+20+decimal+places+of+precision+to+see+how+x+%26+y+are+different%0A++++cout+%3C%3C+x+%3C%3C+endl%3B%0A++++cout+%3C%3C+y+%3C%3C+endl%3B%0A%0A++++char+letter+%3D+%27a%27%3B+%2F%2F+single+quote!%0A++++string+emoji+%3D+%22%5CU0001FABC%22%3B+%2F%2F+jellyfish%0A%0A++++cout+%3C%3C+letter+%3C%3C+endl%3B+%2F%2F+shows+me+char+letter+%27a%27%0A++++cout+%3C%3C+letter+%2B+1+%3C%3C+endl%3B+%2F%2F+shows+me+int%2C+97+%2B+1+%3D+98%0A++++cout+%3C%3C+static_cast%3Cchar%3E(letter+%2B+2)+%3C%3C+endl%3B+%2F%2F+casts+back+to+char%2C+shows+me+%27c%27%0A++++cout+%3C%3C+emoji+%3C%3C+endl%3B+%2F%2F+shows+me+emoji+from+unicode%0A%0A++++return+0%3B%0A%7D)
- for reference: https://www.asciitable.com/ (ASCII table)
- computerphile (youtube) on  [Floating Point Numbers](https://www.youtube.com/watch?v=PZRI1IfStY0), 9min.
- computerphile (youtube) on [Characters + Unicode](https://www.youtube.com/watch?v=MijmeoH9LT4)
- codeacademy c++, "[Conditionals and Logic](https://www.codecademy.com/courses/learn-c-plus-plus/lessons/cpp-conditionals-and-logic/exercises/introduction)" (free course)
- codeacademy c++ review of "[Conditionals](https://www.codecademy.com/courses/learn-c-plus-plus/lessons/cpp-conditionals-and-logic/exercises/review)"
- harvard cs50 (video) on [Conditional Expressions](https://video.cs50.io/1wsaV5nVC7g) - warning this is in C, but very very similar!
- harvard cs50 (video) on [Logical Operators](https://video.cs50.io/f1xZf4iJDWE) - again this is about C, but very very similar!
- [How Aristotle Created the Computer](https://www.theatlantic.com/technology/archive/2017/03/aristotle-computer/518697/), _Atlantic_ (Dixon, 2017)
- [A Symbolic Analysis of Relay and Switching Circuits](https://www.cs.virginia.edu/~evans/greatworks/shannon38.pdf), Shannon, 1938 - connecting symbolic logic to electric circuitry
- codeacademy c++ quick reference of [`switch` & conditionals](https://www.codecademy.com/resources/docs/cpp/conditionals)
