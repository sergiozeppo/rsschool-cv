# Sergey Tsepodoy

# My Contacts

- **Address:** Republic of Kazakhstan, NKR, Petropavlovsk
- **Phone:** +7 775 2372765
- **E-mail:** [me@sergiozeppo.ru](me@sergiozeppo.ru)
- **LinkedIn:** [sergey-tsepodoy](https://www.linkedin.com/in/sergey-tsepodoy/)
- **GitHub:** [sergiozeppo](https://github.com/sergiozeppo)

# About Me

I'm 33 years old and, might say, I'm following the path of a “reverse switcher”. I studied computer science with a focus on web development (HTML, CSS, php, c++ and JS), so I have some kind of foundation in my head.

But then, immediately after university, fate gave me a job in government agencies, where I worked for many years. Then there was a short period in the field of agricultural analytics (wow!), and after that I worked in a telecommunications company, where I rose to the rank of director of the city branch. 

# Skills

- HTML
- CSS
- JavaScript (ES6+)
- Git, GitHub
- Photoshop, Figma

# Code example

This is my solution for KATA from Codewars. We need to write the function "rndCode" generating random verification code in accordance with the following rules:

1. The code length should be 8.
2. The 1st and 2nd characters should be two uppercase letters. The range is "ABCDEFGHIJKLM".
3. The 3rd-6th characters should be four numbers.
4. The 7th and 8th characters should be two symbols. The range is "~!@#$%^&\*".

> Some valid verification code examples:

```
AB1234#$ MG6145$@ KJ2249@&
CD5678%^ IG7593~% FH8638@&
EF9012!@ GB7047%$ KD7604^%
```

```JavaScript
function rndCode(){
  const char1_2="ABCDEFGHIJKLM";
  const char7_8="~!@#$%^&*";
  let generatedCode='';
  for (let i=0;i<8;i++) {
    if (i<2) {
      generatedCode+=char1_2[~~(char1_2.length*Math.random())];
    } else if (i>=2 && i<6) {
      generatedCode+=~~(9*Math.random());
    } else generatedCode+=char7_8[~~(char7_8.length*Math.random())];
  }
  return generatedCode;
}
console.log(rndCode());
```

# Education

- **M.Kozybayev North Kazakhstan State University, Petropavlovsk**
  - Faculty of IT, Bachelor of Education - IT teacher.
- **Udemy**
  - Jonas Schmedtmann's courses (in progress).
- **RSSchool**
  - JavaScript/Front-end 2023Q4 (in progress).

# Experience

- My thesis was creating a web application for preparing for biology exams. I wrote web application in HTML, CSS, php and JavaScript.

- After University I haven't great experience in programming due to working in another field of activity. I only created blog and website forum.

# Languages

- Russian (native)
- English - B2 according to EPAM English test and efset.org test results.
- Kazakh (basic)
