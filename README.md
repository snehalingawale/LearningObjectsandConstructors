# LearningObjectsandConstructors
//Objects and Constructors_Studen and learning loop file

package com.inportia;

public class Student{
	int rollno;
	String fname;
	public Student(){
		
		System.out.println("constructor");
	}
	public Student(int no,String name){
		System.out.println("iam in another constructor");
		rollno=no;
		fname=name;
	
		
	}
    public void displaystudentdata(){
    	System.out.println(rollno);
    	System.out.println(fname);
    	
    	
    	
    }



}
