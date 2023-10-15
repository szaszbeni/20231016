using System;
using System.Collections.Generic;
using System.ComponentModel;
using System.Data;
using System.Drawing;
using System.Linq;
using System.Text;
using System.Threading.Tasks;
using System.Windows.Forms;

namespace _13.feladat
{
    public partial class Form1 : Form
    {
        public Form1()
        {
            InitializeComponent();
        }

        private void btnszamol_Click(object sender, EventArgs e)
        {
            string szoveg = tbx.Text;
            int szam = 0;

            foreach (char character in szoveg)
            {
                if (char.IsDigit(character))
                {
                    szam++;
                }
            }

            MessageBox.Show("A szövegben található számjegyek száma: " + szam, "Eredmény");
        }

        private void btnkilep_Click(object sender, EventArgs e)
        {
            this.Close();
        }
    }
}
