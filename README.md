class Student{
   void Fee(){
      System.out.println("StudentFee=20000");
}
}
Class Student_Name extends Student{
  void Name(){
     System.out.println("Student Name=Jayanti");
  }
}
Class College {
  public Static void main(String args[]){
    Student_Name p=new Student_Name();
    p.Fee();
    p Name();
  }
}

Output:
Student Fee=20000
Student Name=Jayanti
