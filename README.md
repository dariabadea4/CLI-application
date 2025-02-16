# CLI Application

Aceasta este o aplicație CLI pentru gestionarea contactelor.

## 📌 Instalare

1. Asigură-te că ai instalat Node.js pe sistemul tău.
2. Clonează acest repository sau descarcă fișierele.
3. Instalează dependențele necesare:
   ```sh
   npm install
🚀 Utilizare
Rulează comenzile de mai jos pentru a gestiona contactele:

🔍 Listarea tuturor contactelor
sh
Copy
Edit
node index.js --action=list
 (https://monosnap.com/file/P3ZrPauLst3v6ix3OSvVki7tjnbEux)
🔎 Obținerea unui contact după ID
sh
Copy
Edit
node index.js --action=get --id=ID_CONTACT
Exemplu:

sh
Copy
Edit
node index.js --action=get --id=w3u1-vPazgsiaJZmQrpnV
(https://monosnap.com/file/KPpsWVjFehMynfreGb4PEiTBLFWx0R)
➕ Adăugarea unui nou contact
sh
Copy
Edit
node index.js --action=add --name="Ana" --email="ana122@gmail.com" --phone="0847489339"
(https://monosnap.com/file/8H7CrR9VHoqoUkvbaQ2uwHekxKRpYJ)
🗑️ Ștergerea unui contact
sh
Copy
Edit
node index.js --action=remove --id=ID_CONTACT 
Exemplu:

sh
Copy
Edit
node index.js --action=remove --id=w3u1-vPazgsiaJZmQrpnV
(https://monosnap.com/file/3tkimmgSzYgKNpVCIcjKoE87mm2sCY)
