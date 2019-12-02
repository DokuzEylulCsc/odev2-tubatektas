using System;
using System.Collections.Generic;
using System.ComponentModel;
using System.Data;
using System.Drawing;
using System.Linq;
using System.Text;
using System.Threading.Tasks;
using System.Windows.Forms;

namespace ödev2
{
    public partial class Form1 : Form
    {
        public Form1()
        {
            InitializeComponent();
      
}

//tuba tektas 2018280042

/*bu bir roma rakamları dönüştürme ödevidiir.
resource https://www.youtube.com/watch?v=Omwh5981X2c,
https://www.geeksforgeeks.org/converting-roman-numerals-decimal-lying-1-3999/

*/
private void butan1_click(object sender, EventsArgs e)
{
    string rs=textbox1.Text;
    
    int sayi = 0, k1 = 0, k2, k3;
    
    for(int i = 0; i < rs.Lenght; i++)
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
    if (k1>k2)
    {
    
            k3 = -2 * k2;
    
  }
    else
  {   
            k3 = 0;
  }
   
   sayi = sayi + k1 + k3;
   
   
   
   }
   textBox2.Text= sayİ.ToString();

}
