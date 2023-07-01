# AdvancedArithmTest
Advanced Arithmetic Test: Perform the calculation on a variable of the square root of an Integer.
Visual Basic 2005.NET
Imports System.Math
Public Class Form1

    Private Sub Button1_Click(ByVal sender As System.Object, ByVal e As System.EventArgs) Handles Button1.Click

        Dim Resultado As Double
        Resultado = Sqrt(625)
        TextBox1.Text = Resultado
    End Sub
End Class
