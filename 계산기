Public Class Form1
    Private Sub Button1_Click(sender As Object, e As EventArgs) Handles Button1.Click
        Dim num1 As Integer
        Dim num2 As Integer
        Dim m As Integer
        Dim i As Integer

        num1 = TextBox1.Text
        num2 = TextBox2.Text

        If CheckBox1.Checked Then
            m = num1 + num2
            TextBox3.Text = m

        ElseIf CheckBox2.Checked Then
            m = num1 - num2
            TextBox3.Text = m

        ElseIf CheckBox3.Checked Then
            m = num1 * num2
            TextBox3.Text = m

        ElseIf CheckBox4.Checked Then
            m = num1 / num2
            TextBox3.Text = m

        ElseIf CheckBox5.Checked Then
            For i = num1 - 1 To 1 Step -1
                num1 = num1 * i
            Next
            TextBox3.Text = num1

        End If

    End Sub
End Class
