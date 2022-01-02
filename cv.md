# Marina Hudkova
====
### My Contact Info
Location: Poland, Gdansk
hudkova.marina@gmail.com
Marina Hudkova(@Marina-teсh-dot) - discord
====
### About Me
I'm ex lawyer.
Now I am going through learning js and other's developers tools. It's not easy, but exciting jorney.
My aim - became high-quality frontend developer.
 * #### My strengths:
    + Diligence
    + Interest to frontend
    + A am learning, and learning, and learning 5 times a week for 4 month...
    + Will of gut
    + Team playing
==== 
### Skills
* HTML
* CSS (SASS/SCSS, BEM)
* Basic JavaScript
* Git
* Gulp
* VsCode
* Figma
====
### Code Examples 
(not the best variant, but the most difficult task for me on 21 december 2021)

    function add(num1, num2) {
  
          let num1New = String(num1).split("");
          let num2New = String(num2).split("");
          let result = [];
          let x = [];
          
          if (num1New.length == num2New.length) {
            for (let i = num2New.length - 1; i >= 0; i--){
                result.unshift((+num1New[i]) + (+num2New[i]));
                }     
          } else if (num1New.length > num2New.length) {
            x = num1New.slice(0, num1New.length - num2New.length).join('');
            num1New = num1New.splice(num1New.length - num2New.length, num1New.length);
            for (let i = num2New.length - 1; i >= 0; i--){
                result.unshift((+num1New[i]) + (+num2New[i]));
                } 
                result.unshift(x);
          } else {
                x = num2New.slice(0, num2New.length - num1New.length).join('');
                num2New = num2New.splice(num2New.length - num1New.length, num2New.length);
            for (let i = num2New.length - 1; i >= 0; i--){
                result.unshift((+num1New[i]) + (+num2New[i]));
                } 
                result.unshift(x);
          }


          return +result.join('');
    }
====
### Education
* Belorassian State University (Lawyer);
* htmlAcademy
* codeAcademy
* youtube frontend chanels
* self education
====
### Languages
* Russian - native speaker
* English - B1 (B2 is in process…)
===

