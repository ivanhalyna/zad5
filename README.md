<!DOCTYPE html>
<html lang="pl-PL">
<head>
    <meta charset="utf-8">
    <title>Ivan Halyna</title>
    <script language="JavaScript">
                function WinOpen_z1()
        {
            window.open("zadanie1_haly.html","okienko_z4","toolbar=no,directories=no,menubar=no,height=900,width=900,top=100,left=400");
        }
                function WinOpen_z2()
        {
            window.open("zadanie2_haly.html","okienko_z4","toolbar=no,directories=no,menubar=no,height=900,width=900,top=100,left=400");
        }
                function WinOpen_z3()
        {
            window.open("zadanie3_hal.html","okienko_z4","toolbar=no,directories=no,menubar=no,height=900,width=900,top=100,left=400");
        }
        function WinOpen_z4()
        {
            window.open("z4_hal.html","okienko_z4","toolbar=no,directories=no,menubar=no,height=900,width=900,top=100,left=400");
        }
         function WinOpen_z5()
        {
            window.open("z5_hal.html","okienko_z4","toolbar=no,directories=no,menubar=no,height=900,width=900,top=100,left=400");
        }
       

        function okno_zamknij()
        {
            window.close()
        }
    </script>
</head>
<body>
    <p align="left">
        <font color="red" size="7" face="Arial">Skielet zaliczeniowy JavaScript, wykonal: Ivan Halyna 3F</font>
    </p>

    <p style="font-size:2cm;">Ivan Halyna</p>

    <form>
        <input type="button" name="zadanie4" value="zadanie1-Halyna" onclick="WinOpen_z1(' ')">
        <input type="button" name="zadanie4" value="zadanie2-Halyna" onclick="WinOpen_z2(' ')">
        <input type="button" name="zadanie4" value="zadanie3-Halyna" onclick="WinOpen_z3(' ')">
        <input type="button" name="zadanie4" value="zadanie4-Halyna" onclick="WinOpen_z4(' ')">
        <input type="button" name="zadanie5" value="zadanie5-Halyna" onclick="WinOpen_z5(' ')">
        <br><br>
        <input type="button" value="zamknij okno" onclick="okno_zamknij()" />
    </form>
</body>
</html>
