# Day-3-Task

1. For the given JSON iterate over all for loops (for, for in, for of, forEach)

FOR LOOP:
const cars = ["BMW", "Volvo", "Saab", "Ford", "Fiat", "Audi"];

let text = "";
for (let i = 0; i < cars.length; i++) {
  text += cars[i] + "<br>";}
  
output:
BMW
Volvo
Saab
Ford
Fiat
Audi

FOR IN:
const person = {fname:"John", lname:"Doe", age:25}; 

let txt = "";
for (let x in person) {
  txt += person[x] + " ";
}

output:
John Doe 25

FOR OF:
let language = "JavaScript";

let text = "";
for (let x of language) {
  text += x + "<br>";
}

output:
J
a
v
a
S
c
r
i
p
t


2. Create your own resume data in JSON format?
let myResume={
    "basics": {
      "name": "MISHAM CHRIST SHAMED J",
      "email": "mishamshibin@gamil.com",
      "phone": 9000090000,
      "degree": "MBA",
      "location": {
        "address": "15/16 Sainath Enclave ShenoyNagar",
        "postalCode": 629802,
        "city": "kanyakumari",
        "state": "Tamilnadu",
        "country": "India"
      },
    "work": [
      {
        "company": "elshadai tech solution",
        "position": "IT admin",
        "startDate": "2020-jan",
        "endDate": "2021-dec",
        "summary": "i am the IT ADMIN to execute various task and gaining lots of experience",
      },
    ],
    "education": [
      {
        "institution": "hindusthan college of arts and science",
        "department": "mba",
        "studyType": "fulltime",
        "batch start year": 2017,
        "batch end year": 2019,
        "gpa": 7.2,
      }
    ],
    "skills": [
      {
        "name": "javascript",
        "level": "beginer",
      }
    ],
    "languages": [
      {
        "language": "Tamil,Enlish",
      }
    ],
    "interests": [
      {
        "name": "script writter,Rider,",
      }
    ]
  }
  console.log(myResume);
  
  
  
