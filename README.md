package aadPack;

import java.util.*;

public class aadTokens
{
   public static void main(String[] args) 
   {
      StringTokenizer st = new StringTokenizer("Come to learn");
      while (st.hasMoreelements())
      {
         SOP("Next element : " + st.nextElement());    
      }
   }
}
