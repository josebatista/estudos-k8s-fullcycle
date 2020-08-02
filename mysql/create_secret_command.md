#Comando para criar o secret no kubernets

kubectl create secret generic mysql-pass --from-literal=password='a1s2d3f4'

mysql-pass => name
password => key
a1s2d3f4 => pass