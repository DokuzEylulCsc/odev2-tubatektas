
//tuba tektas 2018280042

/*bu bir roma rakamları dönüştürme ödevidiir.
resource https://www.youtube.com/watch?v=Omwh5981X2c,
https://www.geeksforgeeks.org/converting-roman-numerals-decimal-lying-1-3999/

*/
private voit butan1_click(object sender)
{
    string rs=textbox1.text;
    int sayı = 0, k1 = 0, k2, k3
    for(int i = 0; i < rs.lenght; i++)
    {
    
    
    k2=k1;
    switch(rs[i])
    {
    case "I": k1=1; break;
    case "V": k1=5; break;
    case "X": K1=10; break;
    case "L": k1=50; break;
    case "C": k1=100; break;
    case "D": k1=500; break;
    case "M": k1=1000; break;
   
    
    
    }
    if(k1>k2)
    {
    
            k3=-2*k2;
    
  }
  else
  {   
            k3=0;
  }
   
   sayı=sayı+ k1+ k3;
   
   
   
   }
textBox2.text=sayı.ToString();

}
