# JavaScript-Object-statement
  <script>
   var student1={
       Name:"Mansur",
       Age: 50,
       Result:4.5,
       Lang:"English, Bangali, Hindi"
   }
      document.write(student1.Lang); 
      </script>
      //another
      <script>
          //how to create an ibject
          //how to print the value property an object
          //adding a constructor
   var student1={
       Name:"Mansur",
       Age: 50,
       Result:4.5,
       Lang:"English, Bangali, Hindi"
   }
   var student1={
       Name:"Towfique",
       Age: 12,
       Result:4.25,
       Lang:"English, Bangali"
   }
   var student1={
       Name:"Sumon",
       Age: 30,
       Result:4.00,
       Lang:"English, Bangali, Arabic"
   }
      document.write(student1.Lang); 
      </script>
      //another
        //how to create an ibject
          //how to print the value property an object
          //adding a constructor
          //adding a function inside a constructor
          function Student(Name,Age,Result,Lang){
              this.Name= Name;
              this.Age= Age;
              this.Result= Result;
              this.Lang=Lang;
          }
          var student1= new Student("Mansur",50,4.5,"English, Bangali, Hindi");
          var student2= new Student("Towfique",12,4.25,"English, Bangali, Hindi");
          var student3= new Student("Sumon",30,4.15,"English, Bangali, Hindi");
        document.write(student1.Name+"<br>");
        document.write(student1.Age+"<br>");
        document.write(student1.Result+"<br>");
        document.write(student1.Lang);
     </script>
      //adding a function inside a constructor
          function Student(Name,Age,Result,Lang){
              this.Name= Name;
              this.Age= Age;
              this.Result= Result;
              this.Lang=Lang;

              this.display= function(){
                document.write(yhis.Name+"<br>");
        document.write(this.Age+"<br>");
        document.write(this.Result+"<br>");
        document.write(this.Lang);
              }
          }
          var student1= new Student("Mansur",50,4.5,"English, Bangali, Hindi");
          var student2= new Student("Towfique",12,4.25,"English, Bangali, Hindi");
          var student3= new Student("Sumon",30,4.15,"English, Bangali, Hindi");
       
     </script>
