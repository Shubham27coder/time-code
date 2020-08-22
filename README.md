# time-code
import java.io.*;
class conversion
public static void main (String args[]) throw IOException
{
BufferReadred in=new Bufferreadred (new InputStreamReader (System.in));
int val, hr, min,sec;
System.out.println("enter the value of second");
val= Integer.parseInt(in.readLine());
hr= val/3600;
min=(val%3600)/60;
sec=(val%3600)560;
System.out.print.ln("value of hour"+hr);
System.out.print.ln("value of min"+min);
System.out.print.ln("value of second"+sec);
}
}
