cara styling dengan tailwindcss
1. install tailwind dengan membuka terminal (tutorial menggunakan terminal langsung dari vs codenya)
   ketik => npm install tailwindcss @tailwindcss/cli
   lalu enter

2. setelah terinstal buat file css lalu ketik di filenya => @import "tailwindcss";
3. setelah mengikuti tutorial no 2 selanjutnya ketik di terminal => npx @tailwindcss/cli -i ./src/input.css -o ./src/output.css --watch
4. setelah file 'output.css' terinstal buat link yang menghubungkan file html dengan 'output.css'
   contoh : (btw bisa aj lngsung di copy lngsung liat hasilnya di live server)
   <!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Document</title>
    <link href="output.css" rel="stylesheet" />
  </head>
  <body>
    <h1 class="text-[blue]">halo</h1>
  </body>
</html>

#btw buat css lanjutan cara styling makenya ad di modul website tailwindnya lngsung cari aj di google 
