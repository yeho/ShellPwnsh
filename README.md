# ShellPwnsh
Generador de Backdoor en Golang, usando Reverse Shell en PowerShell, con formato de variables en el codigo para Bypass de AMSI y creando el archivo con pequeño poliformismo.

Para los mas inexpertos, este archivo en Go, te crea un ejecutable (exe) con el cual tienes control remoto de un pc, ademas, es indetectable a los Antivirus y el generador intenta siempre generar el codigo de una manera distinta para la evasion ;)

Testeado en estas plataformas:

<table>
    <tr>
        <th>Operative system</th>
        <th> Version </th>
    </tr>
    <tr>
        <td>Kali Linux</td>
        <td> 2022.1</td>
    </tr>
    <tr>
        <td>Windows 10 Pro</td>
        <td> 21H2</td>
    </tr>
</table>

# Uso Windows:
* `Tener Golang instalado`
* `Ejecutar el binario compilado`
* `o ejecutar el archivo ShellPwnsh.go de source`
* `cd source && go run ShellPwnsh.go`

# Uso Linux:
* `apt update && apt install golang`
* `Ejecuat binario compilado con ./ShellPwnsh`
* `O  ejecutar el archivo ShellPwnsh.go` 
* `cd source && go run ShellPwnsh.go`





