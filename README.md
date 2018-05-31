// hello-java
package cn.git.demo;

import java.util.*;

public class ClassDemo1{
  public static void main(String[] args){
    Class<String> clz=String.class;
    System.out.println(clz);
  
    Object o="hi~";
    
    Class<Object> clz2=(Class<Object>) o.getClass();
    System.out.println(clz2);
    
    Class<Date> clz3=(Class<Date>) Class.forName("java.util.Date");
    System.out.ptintln(clz3);
  }
}
