# LineOne

LineOne adalah proyek yang menggunakan Tailwind CSS untuk membangun file CSS final dan mengoptimalkan CSS saat pengembangan. Proyek ini mencakup dua skrip utama: `build` dan `dev`.

## Deskripsi

Proyek ini menggunakan Tailwind CSS untuk menghasilkan file CSS. Ada dua mode utama:

- **Build**: Menghasilkan file CSS final yang telah dioptimalkan untuk produksi.
- **Dev**: Menghasilkan file CSS yang terus diperbarui setiap kali ada perubahan selama pengembangan.

Dengan mendefinisikan perintah di dalam `scripts` pada file `package.json`, Anda bisa menjalankan perintah `npx tailwindcss -i ./src/input.css -o ./src/output.css --watch` atau `npx tailwindcss -i ./src/input.css -o ./src/output.css` secara singkat hanya dengan:

- **`npm run dev`**: Untuk menjalankan mode pengembangan (`--watch`), di mana Tailwind CSS akan terus memantau perubahan dan memperbarui file `output.css` secara otomatis.
- **`npm run build`**: Untuk menjalankan build satu kali yang menghasilkan file CSS final yang siap untuk produksi.

Dengan kata lain, Anda tidak perlu mengetik perintah lengkapnya setiap kali. Menjalankan `npm run dev` atau `npm run build` akan otomatis menjalankan baris yang sesuai dalam `package.json`. Ini memudahkan dan mempercepat proses pengembangan dan build.
