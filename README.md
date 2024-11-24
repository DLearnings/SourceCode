# SourceCode
#1. Program Angka Terbilang
Private Sub Button1_Click(ByVal sender As System.Object, ByVal e As System.EventArgs)
Handles Button1.Click
If TextBox1.Text = 1 Then
MessageBox.Show("Satu", "Terbilang", MessageBoxButtons.OK,
MessageBoxIcon.Information)
End If
If TextBox1.Text = 2 Then
MessageBox.Show("Dua", "Terbilang", MessageBoxButtons.OK,
MessageBoxIcon.Information)
End If
If TextBox1.Text = 3 Then
MessageBox.Show("Tiga", "Terbilang", MessageBoxButtons.OK,
MessageBoxIcon.Information)
End If
If TextBox1.Text = 4 Then
MessageBox.Show("Empat", "Terbilang", MessageBoxButtons.OK,
MessageBoxIcon.Information)
End If
If TextBox1.Text = 5 Then
MessageBox.Show("Lima", "Terbilang", MessageBoxButtons.OK,
MessageBoxIcon.Information)
End If
If TextBox1.Text = 6 Then
MessageBox.Show("Enam", "Terbilang", MessageBoxButtons.OK,
MessageBoxIcon.Information)
End If
If TextBox1.Text = 7 Then
MessageBox.Show("Tujuh", "Terbilang", MessageBoxButtons.OK,
MessageBoxIcon.Information)
End If
If TextBox1.Text = 8 Then
MessageBox.Show("Delapan", "Terbilang", MessageBoxButtons.OK,
MessageBoxIcon.Information)
End If
If TextBox1.Text = 9 Then
MessageBox.Show("Sembilan ", "Terbilang", MessageBoxButtons.OK,
MessageBoxIcon.Information)
End If
If TextBox1.Text = 10 Then
MessageBox.Show("Sepuluh", "Terbilang", MessageBoxButtons.OK,
MessageBoxIcon.Information)
End If
End Sub

#2. Grade
Private Sub Button1_Click(ByVal sender As System.Object, ByVal e As System.EventArgs)
Handles Button1.Click
If TextBox1.Text >= 80 Then
MessageBox.Show("Grade A", "Pesan", MessageBoxButtons.OK,

MessageBoxIcon.Information)
End If
If TextBox1.Text >= 70 And TextBox1.Text < 80 Then
MessageBox.Show("Grade B", "Pesan", MessageBoxButtons.OK,

MessageBoxIcon.Information)
End If
If TextBox1.Text >= 50 And TextBox1.Text < 70 Then
MessageBox.Show("Grade C", "Pesan", MessageBoxButtons.OK,

MessageBoxIcon.Information)
End If
If TextBox1.Text >= 0 And TextBox1.Text < 50 Then
MessageBox.Show("Grade D", "Pesan", MessageBoxButtons.OK,

MessageBoxIcon.Information)
End If
End Sub

#3. Password Sederhana
Private Sub Button1_Click(ByVal sender As System.Object, ByVal e As System.EventArgs)
Handles Button1.Click
If TextBox1.Text = "Nobi" And TextBox2.Text = "Permana" Then
Form2.Show()
Else
MessageBox.Show("Password Anda Salah", "Pemberitahuan", MessageBoxButtons.OK,
MessageBoxIcon.Information)
End If
End Sub
#Setelah itu klik 2 kali button keluar dan masukan kode sebaagai berikut :
Private Sub Button2_Click(ByVal sender As System.Object, ByVal e As
System.EventArgs) Handles Button2.Click
End
End Sub
