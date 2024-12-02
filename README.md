**Exercise 6: Eliminating resource Contention by Suspending the Scheduler**

**Tujuan**

1. Memahami fungsi taskENTER_CRITICAL dan taskEXIT_CRITICAL.
2. menunjukkan cara untuk mengilangkan pengunaan sumber daya secara bersama dengan menghentikan penjadwalan sementara.

**Peralatan**
1. STM32
2. STM32 Cube IDE
3. FreeRTOS
4. Debugger

**Langkah Pengerjaan**
1. Aktifkan FreeRTOS melalui STM32CubeMX.
2. Tambahkan dua Task (Task1 dan Task2). yang mencoba untuk melakukan akses sumber daya secara bersama.
3. Gunakan osDelay() untuk mensimulasikan tugas yang berjalan secara periodik.
4. Amati perbedaan perilaku pada task sebelum dan setelah penggunaan taskENTER_CRITICAL.

**Hasil Percobaan**


https://github.com/user-attachments/assets/136455f5-9425-4595-8875-37e59525b9d3

