# bindhu
This is first repository
package Strings;

public class stringreversewithoutinbuiltfunction {
	public static void main(String[] args) {
		String str1="bindhupriya chinna";
		String str2="";
		for(int i=str1.length()-1;i>=0;i--) {
			str2=str2+str1.charAt(i);
			
			
		}
		System.out.println(str2);
	}

}
