```ts
class Person{
    name:string
 
    speak():void{
        console.log(this.name+" can speak.")
    }
}
 
class Student extends Person{
    // variables
    rollnumber:number
 
    // constructors
    constructor(rollnumber:number, name1:string){
        super(); // calling Parent's constructor
        this.rollnumber = rollnumber
        this.name = name1
    }
 
    // functions
    displayInformation():void{
        console.log("Name : "+this.name+", Roll Number : "+this.rollnumber)
    }
}
 
var student1 = new Student(2, "Rohit")
var student2 = new Student(4, "Kohli")
 
// accessing variables
console.log("Student 1 name is : "+student1.name)
console.log("Student 2 roll number is : "+student2.rollnumber)
 
console.log("\n---Student 1---")
// calling functions
student1.displayInformation()
// calling funciton of parent class
student1.speak()
 
console.log("\n---Student 2---")
student2.displayInformation()
student2.speak()
```
