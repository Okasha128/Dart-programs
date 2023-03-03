# Dart-programs 
# Object oriented Programming
void main(){

 
var obj = new class1();
  obj.name = 'Shan';
  print(obj.name);
  
}


class class1{
  var name = "Ali";
  fun1(){
    print('Hello');
    
  }
 
  }
  #  Default Constructor (it calls whenever you create an object)
  void main(){
 var obj1 = class1();
     obj1.fun1();
 

}


class class1{
  class1(){
   print('Hello'); 
  }
   fun1(){
    print("I'm Okasha");
  }
  
  
  # Parameter Constructor
  }
  void main(){
 var obj1 = class1("Hamza");
  obj1.fun1();
 

}


class class1{
  var name;
  class1(this.name){
    
  }
   fun1(){
    print("I am "+name);
  }
  }
 
 
 
 
 void main(){
/// var obj1 = class1();
 var obj1 = class1.myConstructor('Okasha');
  obj1.fun1();
  
 

}

# Named Constructor
class class1{
  var name;
  class1.myConstructor(name){
    this.name = name;
  }
   fun1(){
       print('Hello '+name);
   }
  }
