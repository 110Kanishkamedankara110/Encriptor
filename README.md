# Encriptor
Encriptor based on enigma machine that i build using java
Add Library To your Project



import com.pixbin.encript.Decriptor;
import com.pixbin.encript.Encriptor;

class Test {

    public static void main(String[] args) {
        Encriptor e=new Encriptor();
        Decriptor de=new Decriptor();
        System.out.println(e.encriptString("Hi Im Kanishka"));
        
        
        
        System.out.println(de.decriptString("Mh/aW,rfx,k<&!"));
       
    }

}


