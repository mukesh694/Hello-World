# Hello-world
test repository for git demonstration for learning github practice.
hii everybody, i am new on git hub




Anagram ;-- > a string is said to be anagram of each other if it contains the same characters, 
              only the order of character  in both strings is different.



class Main {
    public static boolean anagram(String str,String str2){
        int st1=str.length();
        int st2=str2.length();
        if(st1 !=st2)
          return false;
          
          Arrays.sort(str);
          Arrays.sort(str2);
          
          for(int i=0;i<st1;i++){
              if(str[i]!=str2[i])
              return false;
          }
          return true;
          
    }    
    
    public static void main(String[] args) {
        
        
     boolean s=anagram("listen","silent");
     
    if(s==true)
       System.out.println("anagram string ");
   else 
       System.out.println("not anagram");
	
        
        
    }
}

======================================================


given array of strings ,write a program to gourp the anagrams  together in java  in java  Leetcode 49

public static List<List<String>> anagram(String [] strs){

List<List<String>> lst=new  ArrayList<>();

HashMap<String ,List<String>> map=new Hashmap<>();










