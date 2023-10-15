using System;
using System.Collections.Generic;
using System.ComponentModel;
using System.Data;
using System.Drawing;
using System.Linq;
using System.Text;
using System.Threading.Tasks;
using System.Windows.Forms;

namespace _14.feladat
{
    public partial class Form1 : Form
    {
        public Form1()
        {
            InitializeComponent();
        }

        private void btnkilep_Click(object sender, EventArgs e)
        {
            this.Close();
        }

        private void btn1_Click(object sender, EventArgs e)
        {
            string szoveg = tbx1.Text;
            string szo = tbx2.Text;

            if (!string.IsNullOrEmpty(szoveg) && !string.IsNullOrEmpty(szo))
            {
                szoveg = szoveg.Replace(szo, "");
                tbx1.Text = szoveg;
            }
        }
    }
}
